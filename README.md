<h1 align= "center"> МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</h1>
<p align= "center">Лабораторная работа №5 - JS</p>
<p align= "right">Выполнил: Андреев Д.В.</p>
<p align="center">г. Южно-Сахалинск <br> 2023 год</p>
<h2 style="text-align: center">Введение</h2>
<p align="justify">JavaScript — это язык программирования, который используют для написания frontend- и backend-частей сайтов, а также мобильных приложений. Часто в текстах и обучающих материалах название языка сокращают до JS. Это язык программирования высокого уровня, то есть код на нем понятный и хорошо читается.<br>JS поддерживают все популярные браузеры. Во frontend-части сайтов язык используют для создания интерактива (анимаций, всплывающих форм, автозаполнения), так как он связан с HTML и CSS и может ими манипулировать. В backend-части с языком JavaScript работают на платформе Node.js. С ее помощью, например, разрабатывают серверные веб-приложения и подключают библиотеки. В поисковике Google на JavaScript работает строка автозаполнения, а Netflix, Uber, eBay используют его в своем backend. Уже 6 лет JS — самый популярный язык среди разработчиков по версии GitHub.</p>
<h2 style="text-align: center">Цели и задачи</h2>
<ol align="justify">
    <li>
        Создал переменную str="hdfgv" и по индексам нужных символов вывел их в абзац с id="1". 
    </li>
    <li>
        Чтобы найти количество секунд в часе, нужно умножить количество минут в часе на количество секунд в минуте, т.е. 60 * 60.
    </li>
    <li>
        Заменяем все операции с num на упрощенные операторы +=, -=, *=, /=, ++, --. И выводим число num через метод alert().
    </li>
    <li>
        Присвоили значение num = 3 и вывели с помощью метода alert.
    </li>
    <li>
        Создали переменные a = 10 и b = 2. Для отображения результатов четырех арифметических операций над переменными a и b создал соответствующие абзацы. 
    </li>
    <li>
        Создал переменные c = 15 и d = 2, и присвоил их результат сложения переменной result= c + d.
    </li>
    <li>
        Создал переменные a=10, b=2, c=5 и получил результат 17.
    </li>
    <li>
        Создал переменные. Выполнил операции. Получил результат 14
    </li>
    <li>
        Создал переменные hour, day, mounth. Высчитал по формулам hour = 60*60; day = 24 * hour; mounth = 31 * day;.
    </li>
    <li>
        Для решения задачи, я использовал переменную типа Date. Создал текущую дату и с помощью методов вытащил количество часов, минут и секунд. Вывел в абзац конкатенировав по соответствующему фомрату.
    </li>
    <li>
        Для возведения в степень используется оператор "**".
    </li>
    <li>
        Для решения этой задачи я использовал метод forEach, который перебирает каждый элемент массива и выполняет заданную функцию. Заместо вычисляемой функции я использую лямбда-выражение, которое проверяет четность вводимого элемента, и если он четный, то суммирует его квадратный корень с указанием суммы, если нет, то к сумме прибавлялся 0.
    </li>
    <li>
        При сложении 1.15 и 2.30 должно получится 3.45 . Но JavaScript выводит близкое к этому числу - 3.4499999999999997. Связано это с внутренним устройством представления вещественных чисел.
    </li>
    <li>
        При написании следующего кода <code>let x = 5; alert(x++); </code> будет выведено число 5, т.к. x++ выполняется после завершения оператора.
    </li>
    <li>
        <code>[ ] + false - null + true</code> будет равно Nan (NotANumer - не число).
    </li>
    <li>
       При написании кода <code>let y = 1; let x = y = 2; console.log(x);</code> будет выведено число 2. Причем при выводе y также получил число 2.
    </li>
    <li>
        <code>[ ] + 1 + 2</code> в результате получим строку "12".
    </li>
    <li>
        Создал переменные и провел над ними ряд операций. Их результат занес в соответствующие абзацы.
    </li>
    <li>
        Проинициализировал указанные переменные и вычислил площадь по формуле height * width.
    </li>
    <li>
        Проинициализировал указанные переменные и вычислил объем по формуле <code>3.14 * (dC / 2)**2 * heightC</code>.
    </li>
    <li>
        Проинициализировал указанные переменные и вычислил переплату по кридиту по формуле <code>S * years * ( p - 1)</code>.
    </li>
    <li>
        Str типа строка, num типа целового числа, flag логического типа и txt типа строка.
    </li>
    <li>
        Противоположное число получим, если исходное умножим на -1.
    </li>
</ol>

<h2 style="text-align: center">Вывод</h2>
<p>
Я исппользуя JavaScript решил поставленные задачи. Цели и задачи выполнены. 
<!DOCTYPE html>
<html> 
<head> 
    <link rel="stylesheet" href="index.css">
<title>DZAGOLOVKI</title>
</head>
<style>
body {
        background-image: url('qwe.jpg'); 
        background-repeat: no-repeat;
		text-align:center;
      }
</style>
   <div class="su" ><img src="qw.gif"  width="180" height="110"></div>
   <div class="sus" ><img src="qw1.gif"  width="200" height="110"></div>
   <div class="menu" >
 <ul >
<a href="#"> </a>
<a href="#"> </a>
</ul>

</div>
<hr>
 <div class="heading">
 <!--1-->
<script> 
var str = 'hdfgv';
document.write(str[0]); 
document.write(str[1]); 
document.write(str[4]); 
</script><br>
 <!--2-->
<script> 
alert(60 * 60);
</script>
 <!--3-->
<script> 
  var num = 1;
num += 12;
num -= 14;
num *= 5;
num /= 7;
num++;
num--;
alert(num);
  </script>
   <!--4-->
  <script> 
  var num  = 3;
  alert(num);
    </script>
    
     <!--5-->
    <script> 
      var a  = 10;
      var b  = 2;
      alert(a+b);
      alert(a-b);
      alert(a/b);
      alert(a*b);
        </script>
  <!--6-->
  <script> 
    var c  = 15;
    var d  = 2;
    result = c + d;
    alert(result);
    </script>
      <!--7-->
  <script> 
   var a  = 10;
    var b  = 2;
    var c  = 5;
   alert(a+b+c);
    </script>  
    <!--8-->
  <script> 
    var a  = 17;
    var b  = 10;
    c=a-b;
    var d=7;
    result=c+d;
    alert(result);
    </script>
      <!--9-->
  <script> 
    alert(60*60);
    alert(60*60*24);
    alert( 60*60*24*30);
    </script>
          <!--10-->
  <script> 
    var has  = 16;
    var min  = 25;
    var sec  = 15;
    document.write(has +':'+ min +':'+ sec);
    </script>
        <!--11-->
  <br><script> 
    var a = 16;
    document.write(a*a);
    </script>
       <!--12-->
        <!--reduce перебирает значения массива-->
  <br><script> 
 document.write(  [1, 2, 3, 4, 5, 6, 7,8,9,10].filter(n => n % 2 == 0).reduce( (sum, n) => sum + n**0.5, 0 ));
    </script>
       <!--13-->
     <br><script> 
      var a = 1.15;
      var b = 2.30;
      c=a+b;
      document.write(c);
      </script>
          <!--14-->
     <script> 
      let X = 5;
      alert(X++);
      alert(X);
     </script>
 <!--15-->
 <br><script> 
   document.write([ ] + false - null + true);
 </script>
 <!--16-->
 <script> 
 let y=1;
 let x=y=2;
 console.log(x);
  </script>
   <!--17-->
 <br><script> 
document.write([ ] + 1 + 2);
</script>
   <!--18-->
   <br><script> 
   let a6=5%3;
 let a7=3%5;
 let a8=5+'3';
 let a9='5'-3;
 let a10=75+'кг';
    document.write(a6,'  ',a7,'  ',a8,'  ',a9,'  ',a10);
    </script>
<!--19-->
<br><script> 
  let height =23;
let width=10;
s = height*width;
   document.write(s);
   </script>
  <!--20-->
  <br><script> 
    let heightC =10;
  let dC=4;
  v = height*Math.PI*(2**2);
     document.write(v);
     </script>
  <!--21-->
  <br><script> 
    let S =2000000;
  let P=0.1;
  let years=5;
  perepl = S*P*years;
     document.write(perepl);
     </script>
       <!--22-->
  <br><script> 
    let str ="Привет";
  let num=123;
  let flag=true;
  let txt="true";
     console.log(typeof(str,num,flag,txt));
     </script>
           <!--23-->
  <br><script> 
    let qq =213214;
document.write(-qq);
     </script>

</div>
</body>

</html> 
</p>
