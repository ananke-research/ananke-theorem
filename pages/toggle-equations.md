---
layout: default
title: Toggle Equations (Buttons)
permalink: /pages/toggle-equations/
---

<h2>Toggle equations with buttons</h2>

<div class="toggle-widget">

  <div class="toggle-buttons" role="tablist" aria-label="Equation sets">
    <button type="button" class="toggle-btn active" data-target="eq1" aria-controls="eq1" aria-selected="true">Set 1</button>
    <button type="button" class="toggle-btn" data-target="eq2" aria-controls="eq2" aria-selected="false">Set 2</button>
    <button type="button" class="toggle-btn" data-target="eq3" aria-controls="eq3" aria-selected="false">Set 3</button>
  </div>

  <div id="eq1" class="toggle-section active" role="tabpanel" aria-labelledby="eq1">
    <p>Energy–mass equivalence:</p>
    $$E = mc^2$$
  </div>

  <div id="eq2" class="toggle-section" role="tabpanel" aria-labelledby="eq2">
    <p>Maxwell (Gauss law):</p>
    $$
    \nabla\cdot\mathbf{E} = \frac{\rho}{\varepsilon_0}
    $$
  </div>

  <div id="eq3" class="toggle-section" role="tabpanel" aria-labelledby="eq3">
    <p>Einstein–Hilbert action:</p>
    $$
    S = \int d^4x \sqrt{-g}\, \left(\frac{1}{2\kappa}R + \mathcal{L}_\text{matter}\right)
    $$
  </div>

</div>

<script>
(function () {
  var buttons = document.querySelectorAll('.toggle-btn');
  function deactivateAll() {
    document.querySelectorAll('.toggle-btn').forEach(function(b){
      b.classList.remove('active');
      b.setAttribute('aria-selected','false');
    });
    document.querySelectorAll('.toggle-section').forEach(function(s){
      s.classList.remove('active');
    });
  }
  buttons.forEach(function(btn){
    btn.addEventListener('click', function(){
      var targetId = btn.getAttribute('data-target');
      var target = document.getElementById(targetId);
      if (!target) return;
      deactivateAll();
      btn.classList.add('active');
      btn.setAttribute('aria-selected','true');
      target.classList.add('active');

      if (typeof renderMathInElement === 'function') {
        try {
          renderMathInElement(target, {
            delimiters: [
              { left: "$$", right: "$$", display: true },
              { left: "$", right: "$", display: false },
              { left: "\\(", right: "\\)", display: false },
              { left: "\\[", right: "\\]", display: true }
            ],
            throwOnError: false
          });
        } catch (e) {
          console.warn('KaTeX render error:', e);
        }
      }
    });
  });
})();
</script>
