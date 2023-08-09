 # **Гайд по шаблону для посадочных страниц**


**Шаблон основан на сетке Bootstrap**

C [документацией по Bootstrap](https://bootstrap-5.ru/docs/5.3/layout/grid/) можно ознакомиться на официальном сайте. 

Шаблон можно найти по [ссылке](https://github.com/valikkirov/wso/blob/main/Template.html)

<br>

----

<br>

>В начале необходимо загрузить все необходимые графические элементы на сайт при помощи менеджера изображений. Название картинок необходимо писать на латинице. Откройте отдельно какой нибудь редактор кода и собирайте блоки там. Если собираете код в редакторе OpenCart, не забывайте постоянно сохраняться. Можно использовать сервис https://codepen.io.

<br>

*1. Для того чтобы начать собирать посадочную страницу, необходимо вставить стили. В шаблоне начало и конец стилей помечены комментариями:*

        <!-- Начало стилей -->

        <!-- Конец стилей -->

<br>

> Для удобства в шаблоне закоментированы все блоки

<br>

Копируем код, который находится между комментариями и всавляем редактор OpenCart переключившись на вкладку "Исходный код".

![](img/Screen_redactor.png)

Вставляем код

![](img/Screen_redactor_code.png)

Не забываем сохраняться.

<br>

---

<br>

*2. Для удобства шаблон разбит на блоки. В заисимости от дизайна и структуры, вставляются необходимые блоки. Блоки можно вставлять из гайда, они представлены в виде кода или из самого шаблона.* 

2.1. Баннер картинка на всю ширину.

    <!-- Блок баннер картинка на всю ширину. -->
    <div class="row">
        <div class="col-md-12">
            <div class="land-banner-img">
            <img src="https://gdr.one/simg/1200x300">
            </div>
        </div>
    </div>
    <!-- Конец блока -->

<br>

>Коды блоков вставляем после <span style="color: red">кода стилей</span>

<br>

Для того чтобы подставить свою картинку, в строке 

        <img src="https://gdr.one/simg/1200x300">

Между ковычками <span style="color: red">""</span> прописываем адрес нужной картинки. Например: https://product-wso.ru/image/catalog/img/img-design/text.png 


Просмотр работу блока в live режиме в Codepen: https://codepen.io/qbqgigys-the-looper/pen/rNQKGOL

<br>

>Минимальная рекомендованная длина картинки 1000px

<br>

---

<br>

2.2. Отступ между блоками. Вставляется код, который создает пустое место между блоками. Вставляем необходимое количество, чтобы получить заданыый отступ.

    <div class="row">
        <div class="col-md-12"><p>&nbsp;</p></div>
    </div>

<br>

---

<br>

2.3. Текстовый блок на всю ширину.

    <div class="row">
    <div class="col-md-12">
        <div class="land-banner-text">
        <p class="text-block">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Impedit      enim ipsa recusandae tempora illum, fuga aperiam quidem atque      dignissimos numquam dolorum nihil, quo a dolores doloremque suscipit     architecto molestiae quisquam.
            Doloribus blanditiis nam eum perferendis, doloremque incidunt hic?     Repellendus et, nulla quos fuga debitis velit maiores? Hic     perferendis inventore aliquid alias ipsum, cupiditate blanditiis  dolores, maiores, qui soluta doloremque similique.
        </p>
        </div>
    </div>
    </div>

Заменяем "рыбный" текст между `<p class="text-block">` и `</p>`

<br>

---

<br>

2.4. Блок из 2-х строк, 3-х колонок, в которых идет кликабельная картинка и текст. Всего 6 колонок.

Просмотр блока в live режиме в Codepen: https://codepen.io/qbqgigys-the-looper/pen/mdQYOXo



     <!-- Блок из 2-х строк, 3-х колонок, в которых идет кликабельная картинка и текст.  -->

     <div class="row">

        <!-- Начало 1 колонки -->
        <div class="col-md-4 col-sm-6">
            <a href="#" class="land-block-category-img_text">
            <img src="https://gdr.one/simg/700x700">
            <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi vero minus blanditiis ad voluptates adipisci consequuntur nobis neque eos eaque fugiat dicta ab, aperiam reiciendis officiis qui, illo harum nam.
            </p>
            </a>
        </div>
        <!-- Конец колонки -->

        <!-- Начало 2 колонки -->
        <div class="col-md-4 col-sm-6">
            <a href="#" class="land-block-category-img_text">
            <img src="https://gdr.one/simg/700x700">
            <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Saepe asperiores nihil commodi reprehenderit id. Provident ullam rerum fugit temporibus eligendi necessitatibus possimus voluptas nihil molestias expedita? Aspernatur nam dignissimos delectus.
            </p>
            </a>
        </div>
        <!-- Конец колонки -->
    
        <!-- Начало 3 колонки -->
        <div class="col-md-4 col-sm-6">
            <a href="#" class="land-block-category-img_text">
            <img src="https://gdr.one/simg/700x700">
            <p>
             Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere expedita ut suscipit consequuntur alias quo, non nemo odio eius delectus deleniti earum quibusdam ipsa rem, maiores commodi, iure officia totam!
            </p>
            </a>
        </div>
        <!-- Конец колонки -->
    
        <!-- Начало 4 колонки -->
        <div class="col-md-4 col-sm-6">
            <a href="#" class="land-block-category-img_text">
            <img src="https://gdr.one/simg/700x700">
             <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nihil aliquid mollitia quas velit quaerat placeat debitis earum nisi quae aperiam nulla perspiciatis nesciunt amet laudantium eveniet, consequatur eius. Quisquam, beatae?
             </p>
            </a>
         </div>
         <!-- Конец колонки -->
    
        <!-- Начало 5 колонки -->
        <div class="col-md-4 col-sm-6">
            <a href="#" class="land-block-category-img_text">
            <img src="https://gdr.one/simg/700x700">
            <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur tempore excepturi amet odio voluptates! Ipsum nulla, dolor reprehenderit, officia repudiandae, quibusdam rerum maxime est atque ullam mollitia earum natus quae!
            </p>
            </a>
        </div>
        <!-- Конец колонки -->
    
        <!-- Начало 6 колонки -->
        <div class="col-md-4 col-sm-6">
            <a href="#" class="land-block-category-img_text">
            <img src="https://gdr.one/simg/700x700">
            <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid enim sed voluptatibus sunt, ex velit eos aut quo voluptatem quibusdam fugit dolor sequi expedita impedit consequuntur voluptates porro. Ratione, delectus.
            </p>
            </a>
         </div>
         <!-- Конец колонки -->
    
    </div>
    <!-- Конец блока -->


Колонки разбиты для удобства, чтобы понимать где начинается и заканчивается колонка. Редактирование колонки:

- Чтобы задать ссылку на другой ресурс в каждой колонке в `<a href="#"` меняем <span style="color: red">#</span> на адресс сылки. 
Например:  `<a href="https://github.com"`

<br>

- Адресс картинки задаем в строке `<img src="https://gdr.one/simg/700x700">` между <span style="color: red">" "</span>.

<br>


- Текст меняем между тегами `<p>` и `</p>`

<br>


>Минимальная рекомендованная длина картинки 700px. 

>Чтобы добавить дополнительные колонки, необходимо внутри блока скопировать код колонки и вставить его после последней колонки. Соответственно, чтобы убрать колонки, нужно удалить код колонки. Чтобы не ошибиться каждая колонка закоментирована. 

>При добавлении или удалении колонок структура блока не меняется. Он будет состоять из 3 колонок, но будет меняться количество строк.

<br>

---

<br>

2.5. Блок из 2-х строк, 3-х колонок. Текст и картинка некликабельны. Всего 6 колонок.

```
<!-- Блок из 2-х строк, 3-х колонок. Текст и картинка некликабельны -->
<div class="row">

  <!-- Начало 1 колонки -->
  <div class="col-md-4 col-sm-6">
    <div class="land-block-category-img_text">
    <img src="https://gdr.one/simg/700x700">
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi vero minus blanditiis ad voluptates adipisci consequuntur nobis neque eos eaque fugiat dicta ab, aperiam reiciendis officiis qui, illo harum nam.
    </p>
  </div>
  </div>
  <!-- Конец колонки -->
    
  <!-- Начало 2 колонки -->
  <div class="col-md-4 col-sm-6">
    <div class="land-block-category-img_text">
    <img src="https://gdr.one/simg/700x700">
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Saepe asperiores nihil commodi reprehenderit id. Provident ullam rerum fugit temporibus eligendi necessitatibus possimus voluptas nihil molestias expedita? Aspernatur nam dignissimos delectus.
    </p>
  </div>
  </div>
  <!-- Конец колонки -->
    
  <!-- Начало 3 колонки -->
  <div class="col-md-4 col-sm-6">
    <div class="land-block-category-img_text">
    <img src="https://gdr.one/simg/700x700">
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere expedita ut suscipit consequuntur alias quo, non nemo odio eius delectus deleniti earum quibusdam ipsa rem, maiores commodi, iure officia totam!
    </p>
  </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 4 колонки -->
  <div class="col-md-4 col-sm-6">
    <div class="land-block-category-img_text">
    <img src="https://gdr.one/simg/700x700">
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere expedita ut suscipit consequuntur alias quo, non nemo odio eius delectus deleniti earum quibusdam ipsa rem, maiores commodi, iure officia totam!
    </p>
  </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 5 колонки -->
  <div class="col-md-4 col-sm-6">
    <div class="land-block-category-img_text">
    <img src="https://gdr.one/simg/700x700">
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere expedita ut suscipit consequuntur alias quo, non nemo odio eius delectus deleniti earum quibusdam ipsa rem, maiores commodi, iure officia totam!
    </p>
  </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 6 колонки -->
  <div class="col-md-4 col-sm-6">
    <div class="land-block-category-img_text">
    <img src="https://gdr.one/simg/700x700">
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere expedita ut suscipit consequuntur alias quo, non nemo odio eius delectus deleniti earum quibusdam ipsa rem, maiores commodi, iure officia totam!
    </p>
  </div>
  </div>
  <!-- Конец колонки -->
 
</div>
<!-- Конец блока -->

```

Редактирование колонки:

- Адресс картинки задаем в строке `<img src="https://gdr.one/simg/700x700">` между <span style="color: red">" "</span>.

<br>


- Текст меняем между тегами `<p>` и `</p>`

<br>


>Минимальная рекомендованная длина картинки 700px. 

>Чтобы добавить дополнительные колонки, необходимо внутри блока скопировать код колонки и вставить его после последней колонки. Соответственно, чтобы убрать колонки, нужно удалить код колонки. Чтобы не ошибиться каждая колонка закоментирована. 

>При добавлении или удалении колонок структура блока не меняется. Он будет состоять из 3 колонок, но будет меняться количество строк.

<br>

---

<br>

2.6. Блок из 2-х строк, 4-х колонок. Текст и картинка некликабельны. Всего 8 колонок.

```
<!-- Блок из 2-х строк, 4-х колонок. Текст и картинка некликабельны -->
<div class="row">
  
  <!-- Начало 1 колонки -->
  <div class="col-md-3 col-sm-6">
    <div class="land-block-category-img_text">
    <img src="https://gdr.one/simg/500x500">
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi vero minus blanditiis ad voluptates adipisci consequuntur nobis neque eos eaque fugiat dicta ab, aperiam reiciendis officiis qui, illo harum nam.
    </p>
  </div>
  </div>
  <!-- Конец колонки -->
    
  <!-- Начало 2 колонки -->
  <div class="col-md-3 col-sm-6">
    <div class="land-block-category-img_text">
    <img src="https://gdr.one/simg/500x500">
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Saepe asperiores nihil commodi reprehenderit id. Provident ullam rerum fugit temporibus eligendi necessitatibus possimus voluptas nihil molestias expedita? Aspernatur nam dignissimos delectus.
    </p>
  </div>
  </div>
  <!-- Конец колонки -->
    
  <!-- Начало 3 колонки -->
  <div class="col-md-3 col-sm-6">
    <div class="land-block-category-img_text">
    <img src="https://gdr.one/simg/500x500">
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere expedita ut suscipit consequuntur alias quo, non nemo odio eius delectus deleniti earum quibusdam ipsa rem, maiores commodi, iure officia totam!
    </p>
  </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 4 колонки -->
  <div class="col-md-3 col-sm-6">
    <div class="land-block-category-img_text">
    <img src="https://gdr.one/simg/500x500">
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere expedita ut suscipit consequuntur alias quo, non nemo odio eius delectus deleniti earum quibusdam ipsa rem, maiores commodi, iure officia totam!
    </p>
  </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 5 колонки -->
  <div class="col-md-3 col-sm-6">
    <div class="land-block-category-img_text">
    <img src="https://gdr.one/simg/500x500">
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi vero minus blanditiis ad voluptates adipisci consequuntur nobis neque eos eaque fugiat dicta ab, aperiam reiciendis officiis qui, illo harum nam.
    </p>
  </div>
  </div>
  <!-- Конец колонки -->
    
  <!-- Начало 6 колонки -->
  <div class="col-md-3 col-sm-6">
    <div class="land-block-category-img_text">
    <img src="https://gdr.one/simg/500x500">
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Saepe asperiores nihil commodi reprehenderit id. Provident ullam rerum fugit temporibus eligendi necessitatibus possimus voluptas nihil molestias expedita? Aspernatur nam dignissimos delectus.
    </p>
  </div>
  </div>
  <!-- Конец колонки -->
    
  <!-- Начало 7 колонки -->
  <div class="col-md-3 col-sm-6">
    <div class="land-block-category-img_text">
    <img src="https://gdr.one/simg/500x500">
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere expedita ut suscipit consequuntur alias quo, non nemo odio eius delectus deleniti earum quibusdam ipsa rem, maiores commodi, iure officia totam!
    </p>
  </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 8 колонки -->
  <div class="col-md-3 col-sm-6">
    <div class="land-block-category-img_text">
    <img src="https://gdr.one/simg/500x500">
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere expedita ut suscipit consequuntur alias quo, non nemo odio eius delectus deleniti earum quibusdam ipsa rem, maiores commodi, iure officia totam!
    </p>
  </div>
  </div>
  <!-- Конец колонки -->
  
</div>
<!-- Конец блока -->

```

<br>

Редактирование колонки:

- Адресс картинки задаем в строке `<img src="https://gdr.one/simg/500x500">` между <span style="color: red">" "</span>.

<br>


- Текст меняем между тегами `<p>` и `</p>`

<br>


>Минимальная рекомендованная длина картинки 500px. 

>Чтобы добавить дополнительные колонки, необходимо внутри блока скопировать код колонки и вставить его после последней колонки. Соответственно, чтобы убрать колонки, нужно удалить код колонки. Чтобы не ошибиться каждая колонка закоментирована. 

>При добавлении или удалении колонок структура блока не меняется. Он будет состоять из 4 колонок, но будет меняться количество строк.

<br>

---

<br>

2.7. Блок с заголовоком H2.


```
<!-- Блок с заголовоком H2 -->>
<div class="row">
  <div class="col-md-12">
    <h2 class="h2-block">Заголовок</h2>
  </div>
</div>
<!-- Конец блока -->

```

Заменяем текст "Заголовок" внутри тегов `<h2 class="h2-block">` и `</h2>`


<br>

---

<br>

2.8. Блок из 2-х строк, 3-х колонок. Картинки и заголовки H4. Всего 6 колонок.

```
<!-- Блок из 2-х строк, 3-х колонок. Картинки и заголовки H4. -->
<div class="row">

  <!-- Начало 1 колонки -->
  <div class="col-md-4 col-sm-6">
    <div class="land-block-ico">
      <img src="https://gdr.one/simg/700x700">
      <h4>Lorem ipsum dolor sit amet</h4>
    </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 2 колонки -->
  <div class="col-md-4 col-sm-6">
    <div class="land-block-ico">
      <img src="https://gdr.one/simg/700x700">
       <h4>Lorem ipsum dolor sit amet</h4>
    </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 3 колонки -->  
  <div class="col-md-4 col-sm-6">
    <div class="land-block-ico">
      <img src="https://gdr.one/simg/700x700" >
      <h4>Lorem ipsum dolor sit amet</h4>
    </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 4 колонки -->
  <div class="col-md-4 col-sm-6">
    <div class="land-block-ico">
      <img src="https://gdr.one/simg/700x700" >
      <h4>Lorem ipsum dolor sit amet</h4>
    </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 5 колонки -->
  <div class="col-md-4 col-sm-6">
    <div class="land-block-ico">
      <img src="https://gdr.one/simg/700x700" >
      <h4>Lorem ipsum dolor sit amet</h4>
    </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 6 колонки -->
  <div class="col-md-4 col-sm-6">
    <div class="land-block-ico">
      <img src="https://gdr.one/simg/700x700" >
      <h4>Lorem ipsum dolor sit amet</h4>
    </div>
  </div>
  <!-- Конец колонки -->

</div>
<!-- Конец блока -->

```

Редактирование колонки:

- Адресс картинки задаем в строке `<img src="https://gdr.one/simg/700x700">` между <span style="color: red">" "</span>.

<br>


- Заголовок меняем между тегами `<h4>` и `</h4>`

<br>


>Минимальная рекомендованная длина картинки 700px. 

>Чтобы добавить дополнительные колонки, необходимо внутри блока скопировать код колонки и вставить его после последней колонки. Соответственно, чтобы убрать колонки, нужно удалить код колонки. Чтобы не ошибиться каждая колонка закоментирована. 

>При добавлении или удалении колонок структура блока не меняется. Он будет состоять из 3 колонок, но будет меняться количество строк.

<br>

---

<br>

2.8. Блок из 2-х строк, 4-х колонок с картинками. Всего 8 колонок.

Просмотр блока в live режиме в Codepen: https://codepen.io/qbqgigys-the-looper/pen/LYXoWmx

```
<!-- Блок из 2-х строк, 4-х колонок с картинками. -->
<div class="row">

  <!-- Начало 1 колонки -->
  <div class="col-md-3 col-sm-6">
    <div class="land-block-category-img">
      <img src="https://gdr.one/simg/500x500">
    </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 2 колонки -->
  <div class="col-md-3 col-sm-6">
    <div class="land-block-category-img">
      <img src="https://gdr.one/simg/500x500">
    </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 3 колонки -->
  <div class="col-md-3 col-sm-6">
    <div class="land-block-category-img">
      <img src="https://gdr.one/simg/500x500">
    </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 4 колонки -->
  <div class="col-md-3 col-sm-6">
    <div class="land-block-category-img">
      <img src="https://gdr.one/simg/500x500">
    </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 5 колонки -->
  <div class="col-md-3 col-sm-6">
    <div class="land-block-category-img">
      <img src="https://gdr.one/simg/500x500">
    </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 6 колонки -->
  <div class="col-md-3 col-sm-6">
    <div class="land-block-category-img">
      <img src="https://gdr.one/simg/500x500">
    </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 7 колонки -->
  <div class="col-md-3 col-sm-6">
    <div class="land-block-category-img">
      <img src="https://gdr.one/simg/500x500">
    </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 8 колонки -->
  <div class="col-md-3 col-sm-6">
    <div class="land-block-category-img">
      <img src="https://gdr.one/simg/500x500">
    </div>
  </div>
  <!-- Конец колонки -->
  
</div>
<!-- Конец блока -->

```

Редактирование колонки:

- Адресс картинки задаем в строке `<img src="https://gdr.one/simg/500x500">` между <span style="color: red">" "</span>.

<br>

>Минимальная рекомендованная длина картинки 500px. 

>Чтобы добавить дополнительные колонки, необходимо внутри блока скопировать код колонки и вставить его после последней колонки. Соответственно, чтобы убрать колонки, нужно удалить код колонки. Чтобы не ошибиться каждая колонка закоментирована. 

>При добавлении или удалении колонок структура блока не меняется. Он будет состоять из 4 колонок, но будет меняться количество строк.

<br>

---

<br>

2.9. Блок из 2-х строк, 3-х колонок с картинками. Всего 6 колонок.

```

<!-- Блок из 2-х строк, 3-х колонок с картинками. -->
<div class="row">

  <!-- Начало 1 колонки -->
  <div class="col-md-4 col-sm-6">
    <div class="land-block-category-img">
      <img src="https://gdr.one/simg/700x700">
    </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 2 колонки -->
  <div class="col-md-4 col-sm-6">
    <div class="land-block-category-img">
      <img src="https://gdr.one/simg/700x700">
    </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 3 колонки -->
  <div class="col-md-4 col-sm-6">
    <div class="land-block-category-img">
      <img src="https://gdr.one/simg/700x700">
    </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 4 колонки -->
  <div class="col-md-4 col-sm-6">
    <div class="land-block-category-img">
      <img src="https://gdr.one/simg/700x700">
    </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 5 колонки -->
  <div class="col-md-4 col-sm-6">
    <div class="land-block-category-img">
      <img src="https://gdr.one/simg/700x700">
    </div>
  </div>
  <!-- Конец колонки -->

  <!-- Начало 6 колонки -->
  <div class="col-md-4 col-sm-6">
    <div class="land-block-category-img">
      <img src="https://gdr.one/simg/700x700">
    </div>
  </div>
  <!-- Конец колонки -->
  
</div>
<!-- Конец блока -->

```

Редактирование колонки:

- Адресс картинки задаем в строке `<img src="https://gdr.one/simg/700x700">` между <span style="color: red">" "</span>.

<br>

>Минимальная рекомендованная длина картинки 700px. 

>Чтобы добавить дополнительные колонки, необходимо внутри блока скопировать код колонки и вставить его после последней колонки. Соответственно, чтобы убрать колонки, нужно удалить код колонки. Чтобы не ошибиться каждая колонка закоментирована. 

>При добавлении или удалении колонок структура блока не меняется. Он будет состоять из 3 колонок, но будет меняться количество строк.


<br>

---

<br>

2.10. Блок из 3 колонок контакты.

```

<!-- Блок из 3 колонок контакты -->
<div class="row">
   
  <!-- Колонка адрес -->
  <div class="col-md-4">
    <div class="land-block-ico-contact">
      <div class="col-md-12">
        <img src="https://gdr.one/simg/500x500">
      </div>
        <p>
          Город, улица, дом
        </p>
    </div>
  </div>
  <!-- Конец колонки -->

  <!-- Колонка e-mail -->
  <div class="col-md-4">
    <div class="land-block-ico-contact">
      <div class="col-md-12">
        <img src="https://gdr.one/simg/500x500">
      </div>
        <a href="mailto:info@somemail.ru">
          info@somemail.ru
        </a>
    </div>
  </div>
  <!-- Конец колонки -->
    
  <!-- Колонка телефон -->
  <div class="col-md-4">
    <div class="land-block-ico-contact">
      <div class="col-md-12">
        <img src="https://gdr.one/simg/500x500">
      </div>
        <a href="tel:+ 0 (000) 000-00-00">
          + 0 (000) 000-00-00
        </a>
    </div>
   </div>
   <!-- Конец колонки -->
    
</div>
<!-- Конец блока -->

```

- Адресс картинки задаем в строке `<img src="https://gdr.one/simg/500x500">` между <span style="color: red">" "</span>.

- Адрес меняем в сточке  `<p>Город, улица, дом</p>`

- Адресс электронной почты правим в 2-х местах: 
    
    - в `<a href="mailto:info@somemail.ru">`  после <span style="color: red">mailto:</span>

    - между тегами `<a href="mailto:info@somemail.ru">` и `</a>`

- Телефон правим в 2-х местах: 
    
    - в `<a href="tel:+ 0 (000) 000-00-00">`  после <span style="color: red">tel:</span>

    - между тегами `<a href="tel:+ 0 (000) 000-00-00">` и `</a>`

<br>

>Минимальная рекомендованная длина картинки 500px. 

<br>
<hr>
<br>

2.11. Блок из 2-х колонок. Слева картинка. Справа заголовок и текст.

```
<!-- Блок из 2-х колонок. Слева картинка. Справа заголовок и текст -->
<div class="row">

  <div class="land-article">
    <div class="row">
    <div class="col-sm-6">
      <img src="https://gdr.one/simg/900x600">
    </div>

    <div class="col-sm-6">
      <h3 style="text-align:left" class="h3-block">Заголовок</h3>
      <p class="text-block">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia totam deleniti, deserunt corporis aspernatur pariatur, repudiandae labore obcaecati quod eligendi quia modi praesentium ratione nam recusandae blanditiis doloribus reprehenderit iusto?
        Consequuntur minus possimus molestiae temporibus voluptatibus consequatur tenetur, nostrum dolores repudiandae dicta earum libero ullam, velit excepturi. Laboriosam hic ipsa reprehenderit quidem. Consequuntur eum asperiores ipsa ex sapiente quos ipsam?
        Non impedit excepturi labore quod, blanditiis tempora minus cum eum magnam perspiciatis dolorum maxime, debitis ratione consequatur asperiores neque quas molestias nam necessitatibus architecto, voluptates eligendi! Nam deleniti a soluta!
      </p>
    </div>
    </div>
  </div>   
   
</div>
<!-- Конец блока -->

```

- Адресс картинки задаем в строке `<img src="https://gdr.one/simg/900x600">` между <span style="color: red">" "</span>.

<br>


- Заголовок меняем между тегами `<h3 style="text-align:left" class="h3-block">` и `</h3>`

- "Рыбный текст" меняем между тегами `<p class="text-block">` и `</p>`

<br>

>Минимальная рекомендованная длина картинки 900px.

>У заголовка выравниване по левому краю. Если необходимо поменять выравнивание, то в строке `<h3 style="text-align:left" class="h3-block">` 
меняем `"text-align:left"` на `"text-align:center"` (для выравнивания по центру) <br>
и на `"text-align:right"` (для выравнивания по правому краю)

<br>
---
<br>

2.12. Блок из 2-х колонок. Слева заголовок и текст. Справа картинка.

Просмотр блока в live режиме в Codepen: https://codepen.io/qbqgigys-the-looper/pen/ZEmRXbQ

```

<!-- Блок из 2-х колонок. Слева заголовок и текст. Справа картинка -->
<div class="row">

  <div class="land-article">
    <div class="row">
    <div class="col-sm-6">
      <h3 style="text-align:left" class="h3-block">Заголовок</h3>
      <p class="text-block">
        Consequuntur minus possimus molestiae temporibus voluptatibus consequatur tenetur, nostrum dolores repudiandae dicta earum libero ullam, velit excepturi. Laboriosam hic ipsa reprehenderit quidem. Consequuntur eum asperiores ipsa ex sapiente quos ipsam?
        Non impedit excepturi labore quod, blanditiis tempora minus cum eum magnam perspiciatis dolorum maxime, debitis ratione consequatur asperiores neque quas molestias nam necessitatibus architecto, voluptates eligendi! Nam deleniti a soluta!
      </p>
    </div>

    <div class="col-sm-6">
      <img src="https://gdr.one/simg/900x600">
    </div>
    </div>
  </div> 

</div>
<!-- Конец блока -->

```

- Адресс картинки задаем в строке `<img src="https://gdr.one/simg/900x600">` между <span style="color: red">" "</span>.

<br>


- Заголовок меняем между тегами `<h3 style="text-align:left" class="h3-block">` и `</h3>`

- "Рыбный текст" меняем между тегами `<p class="text-block">` и `</p>`

<br>

>Минимальная рекомендованная длина картинки 900px.

>У заголовка выравниване по левому краю. Если необходимо поменять выравнивание, то в строке `<h3 style="text-align:left" class="h3-block">` 
меняем `"text-align:left"` на `"text-align:center"` (для выравнивания по центру) <br>
и на `"text-align:right"` (для выравнивания по правому краю)

<br>
---
<br>

2.13. Блок кнопка.

```

<!-- Блок кнопка -->
<div class="row">
  <div class="col-md-12">
    <a href="#" class="land-button">
      <img src="https://gdr.one/simg/800x130">
    </a>
  </div>
</div>
<!-- Конец блока -->

```

- Адресс картинки задаем в строке `<img src="https://gdr.one/simg/800x130">` между <span style="color: red">" "</span>.

<br>


- Ссылку вписываеи в `<a href="#" class="land-button">` вместо <span style="color: red">#</span> между <span style="color: red">" "</span>.

>При создании картинки для кнопки необходимо учитывать, что картинка в итоге будет иметь размер 50%. <br>
В шаблоне используется 800х130 px

>Кнопку желательно вставлять внутри в колонку перед закрывающемся `</div>` колонки

<br>
---

<br>

*3. Если необходимо установить акцентный цвет для заголовков и для ссылок при наведении, необходимо в стилях в самом начале найти:*

```
:root {
  --accent-color: #000;
}
```
Необходимо заменить код цвета `#000` на свой.