Sommige items zijn automatisch gecentreerd vanwege de style voor hun element.

Je kunt de `xcenter` en `ycenter` classes gebruiken om andere elementen horizontaal en verticaal te centreren.

![Drie blokken. Het eerste blok heeft tekst horizontaal gecentreerd, het tweede blok heeft tekst verticaal gecentreerd en het derde blok heeft tekst horizontaal en verticaal gecentreerd.](images/center-text.png)


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
