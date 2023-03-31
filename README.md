<h1 align= "center"> МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</h1>
<p align= "center">Лабораторная работа №6 - CSS</p>
<p align= "right">Выполнил: Андреев Д.В.</p>
<p align="center">г. Южно-Сахалинск <br> 2023 год</p>
<h2 style="text-align: center">Введение</h2>
<p align="justify">CSS используется создателями веб-страниц для задания цветов, шрифтов, стилей, расположения отдельных блоков и других аспектов представления внешнего вида этих веб-страниц. Основной целью разработки CSS является ограждение и отделение описания логической структуры веб-страницы (которое производится с помощью HTML или других языков разметки) от описания внешнего вида этой веб-страницы (которое теперь производится с помощью формального языка CSS). Такое разделение может увеличить доступность документа, предоставить большую гибкость и возможность управления его представлением, а также уменьшить сложность и повторяемость в структурном содержимом.
Кроме того, CSS позволяет представлять один и тот же документ в различных стилях или методах вывода, таких как экранное представление, печатное представление, чтение голосом (специальным голосовым браузером или программой чтения с экрана) или при выводе устройствами</p>
<h2 style="text-align: center">Цели и задачи</h2>
<ol align="justify">
    <li>
       Придумайте селектор, который выберет абзацы <p> внутри дивов <div>.
    </li>
    <li>
        Придумайте селектор, который выберет все <h2> внутри дивов <div>.
    </li>
    <li>
       Придумайте селектор, который выберет все абзацы <p> из элемента с id=test.
    </li>
    <li>
       Придумайте селектор, который выберет все <h2> из элемента с id=test.
    </li>
    <li>
       Выберите все элементы с классом bbb. 
    </li>
    <li>
       Выберите все элементы с классом bbb из элемента с id=test.
    </li>
    <li>
       Выберите все абзацы <p> с классом bbb.
    </li>
    <li>
        Выберите все <h2> с классом bbb.
    </li>
    <li>
       9.	Выберите все абзацы <p> с классом bbb из элемента с id=test.
    </li>
    <li>
        10.	Выберите все элементы с классом bbb и элементы с классом xxx одновременно.
    </li>
    <li>
       11.	Выберите все абзацы <p> с классом bbb и <h2> с классом xxx одновременно.
    </li>
    <li>
       12.	Выберите все абзацы <p> с классом bbb из id=test и все абзацы <p> с классом xxx из id=test одновременно.
    </li>
    <li>
       13.	Выберите все элементы из класса fff.
    </li>
    <li>
        14.	Выберите все абзацы <p> из класса fff.
    </li>
    <li>
        15.	Выберите все абзацы <p> с классом fff.
    </li>
    <li>
       16.	Выберите все элементы с классом bbb из класса fff.
    </li>
    <li>
       17.	Выберите все <h2> с классом bbb из класса fff.
    </li>
    <li>
        18.	Сделайте селектор, который выберет все ссылки из id=test, с состояния link и visited сделайте неподчеркнутыми и красными, а состояние hover - подчеркнутым и голубым.
    </li>
    <li>
        Сделайте селектор, который выберет все ссылки с классом www, состояния link и visited сделайте подчеркнутыми и голубыми, а состояние hover - неподчеркнутым.
    </li>
    <li>
        20.	 Сделайте селектор, который выберет все ссылки из id=test с классом www. Цвета состояний выберите самостоятельно.
    </li>
    <li>
        Сделайте селектор, который выберет все ссылки из class=eee с классом www. Цвета состояний выберите самостоятельно.
    </li>
    <li>
        22.	Повторите страницы по данному по образцу:
    </li>
   
</ol>

<h2 style="text-align: center">Вывод</h2>

Я исппользуя JavaScript решил поставленные задачи. Цели и задачи выполнены. 

<p>
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
