某些项目由于其元素的样式而自动居中。

你可以使用 `xcenter` 和 `ycenter` 类将其他元素水平和垂直居中。

![三个块。 第一个块的文本水平居中，第二个块的文本垂直居中，第三个块的文本水平和垂直居中。](images/center-text.png)


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
