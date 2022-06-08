Some items will automatically be centered because of the style for their element. 

You can use the `xcenter` and `ycenter` classes to center other elements horizontally and vertically. 

![Three blocks with text centered only horizontally, only vertically and both.](images/center-text.png)


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
