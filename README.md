<h1 align= "center"> МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</h1>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<p align= "center">Лабораторная работа №6 - CSS</p><br><br><br><br><br><br><br><br>
<p align= "right">Выполнил: Андреев Д.В.</p><br><br><br><br><br><br><br><br>
<p align="center">г. Южно-Сахалинск <br> 2023 год</p><br><br><br><br><br><br><br><br>
<h2 style="text-align: center">Введение</h2>
<p align="justify">CSS используется создателями веб-страниц для задания цветов, шрифтов, стилей, расположения отдельных блоков и других аспектов представления внешнего вида этих веб-страниц. Основной целью разработки CSS является ограждение и отделение описания логической структуры веб-страницы (которое производится с помощью HTML или других языков разметки) от описания внешнего вида этой веб-страницы (которое теперь производится с помощью формального языка CSS). Такое разделение может увеличить доступность документа, предоставить большую гибкость и возможность управления его представлением, а также уменьшить сложность и повторяемость в структурном содержимом.
Кроме того, CSS позволяет представлять один и тот же документ в различных стилях или методах вывода, таких как экранное представление, печатное представление, чтение голосом (специальным голосовым браузером или программой чтения с экрана) или при выводе устройствами</p>
<h2 style="text-align: center">Цели и задачи</h2>
<ol align="justify">
    <li>
      Повторить по образцу, то есть сделать такой же макет используя материалы из архива lab7.zip
    </li>
    <br>  <br>  <br>  <br>  <br> 
<!-- Этот код создает абзац
<p>
<html> 
<head> 
    <link rel="stylesheet" href="index.css">
<title>Главная</title>
</head>
<body>
	<header>
		<div class="glava">
			<div class="logo">
				<a href="index.html">Elysa4t</a>
			</div>
			<div class="navigation">
				<ul class="menu">
					<li><a href="#" class="active">Home</a></li>
					<li><a href="#">Archives</a></li>
					<li><a href="#">Gallery</a></li>
					<li><a href="#">About</a></li>
					<li><a href="#">Contact</a></li>
				</ul>
			</div>
		</div>
	</header>


<div class="photo">
		
   <div class="banner-block container">
      <div class="image">
         <img src="banner-image.jpg">
      </div>
      <div class="text">
         <h2>Magna sed phasellus consequat lorem ipsum dolor</h2>
      </div>
   </div>
   
</div>

<div class="centr">
   <div class="containers">
      <section>
         <div class="info">
            <p>Posted by  Someone
            on April 14, 2012</p>
         </div>
         <h2 id="zz">Lorem ipsum sed veroeros amet</h2>
         <div class="image2">
            <img src="pics01.jpg">
         </div>
         <div class="text2">
            <p>Nam vestibulum hendrerit orci, sed pharetra elit elementum in. Donec in eros sed odio varius tempus. Vestibulum quis quam et velit rutrum ornare nec a massa. Curabitur malesuada ullamcorper nunc in suscipit. Donec semper venenatis dui sed facilisis. Morbi congue facilisis ante in feugiat. Mauris consectetur magna eu enim sagittis et bibendum lacus imperdiet. Maecenas semper massa ac odio ornare sodales. Nunc rhoncus vulputate nisi sed malesuada. Fusce ac mauris dui, id luctus ligula. Integer hendrerit.</p>
         </div>
         <div class="comments2">
            <p>Posted in  News, Design,Other</p>
            <p>235 Comments</p>
         </div>
      </section>
      <aside>
         <div class="sprava"></div>
            <div class="info2">
               <p>About Elysa4t</p>
            </div>
            <div class="textsp">
               <p>Mauris consectetur magna eu enim sagittis et bibendum lacus imperdiet. Maecenas semper massa amet et odio mauris dui, id luctus amet ligula.
               </p>
            </div>
            <div class="info2"><p>Recent Post</p></div>
            <div class="textsp">
               <p>Mauris consectetur magna eu enim sagittis et bibendum lacus imperdiet. Maecenas semper massa amet et odio mauris dui, id luctus amet ligula.
               </p>
            </div>
            <div class="info2"><p>Something Else</p></div>
            <div class="textsp">
               <p>Mauris consectetur magna eu enim sagittis et bibendum lacus imperdiet. Maecenas semper massa amet et odio mauris dui, id luctus amet ligula.</p>
            </div>

       
      </aside>
   </div>
</div>



<div class="blocki">
	
   <div class="container">
      
      <div class="stolb">
         <h3>Just another widget</h3>
         <p>Mauris consectetur magna tempus enim sagittis et bibendum lacus et imperdiet. Maecenas semper et massa amet et odio mauris dui, id luctus amet ligula.</p>
      </div>
      <div class="stolb">
         <h3>Just another widget</h3>
         <p>Mauris consectetur magna tempus enim sagittis et bibendum lacus et imperdiet. Maecenas semper et massa amet et odio mauris dui, id luctus amet ligula.</p>
      </div>
      <div class="stolb">
         <h3>Just another widget</h3>
         <p>Mauris consectetur magna tempus enim sagittis et bibendum lacus et imperdiet. Maecenas semper et massa amet et odio mauris dui, id luctus amet ligula.</p>
      </div>
      
   </div>
</div>

<footer>
   <div class="footer-info container">
      <p> Андреев Дмитрий</p>
   </div> 
</footer>


</body>

</html> 
</p>
 ->

<h2 style="text-align: center">Вывод</h2>
	CSS используется создателями веб-страниц для задания цветов, шрифтов, стилей, расположения отдельных блоков и других аспектов представления внешнего вида этих веб-страниц. Основной целью разработки CSS является ограждение и отделение описания логической структуры веб-страницы (которое производится с помощью HTML или других языков разметки) от описания внешнего вида этой веб-страницы 
Основной целью разработки CSS является ограждение и отделение описания логической структуры веб-страницы
Я исппользуя CSS решил поставленные задачи. Цели и задачи выполнены. 
