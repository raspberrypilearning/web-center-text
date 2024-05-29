Certains éléments sont automatiquement centrés en raison du style de leur élément.

Tu peux utiliser les classes `xcenter` et `ycenter` pour centrer les autres éléments horizontalement et verticalement.

![Trois blocs. Le premier bloc a du texte centré horizontalement, le deuxième bloc a du texte centré verticalement et le troisième bloc a du texte centré horizontalement et verticalement.](images/center-text.png)


--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<section class="wrap">
  <div class="tertiary xcenter  tile">
    <p>Lorem ipsum</p>
  </div>
  <div class="secondary ycenter tile">
    <p>Lorem ipsum</p>
  </div>
  <div class="tertiary xcenter ycenter tile">
     <p>Lorem ipsum</p>
  </div>
</section>

--- /code ---
