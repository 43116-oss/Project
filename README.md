<!DOCTYPE html>
<html lang="th">
<head>
<title>work10 html layout</title>
<meta charset="utf-8">
<style>
*{
        box-sizing:border-box
        padding:0;
        margin:0;
}
.container{
        width:1024px;
        margin:0 auto;
}

header{
        background-image:url(images/english.jpg);
        height:256px;
}
nav{
        background-color:#FFFFB5C2;
        flex:1;
}
article{
        background-color:#FFE5EC;
        padding:10px;
        flex:3;
}
footer{
        background-color:#D7EFEF;
        padding:25px;
        text-align:center;
        color:#5B506C;
}
section{
        display:flex;
}
a:link{
         color:#D4EEF1;
         text-decoration:none;
         background-color:#FEFFDA;
         display:block;
         width:100%;
         padding:10px;
}
a:visited{
         color:pink;
}
a:hover{
         color:B8E2F2;
         background-color:#8291E8;
}
a:active{
         color:D4F0F0;
}

</style>


</head>
<body>
<div class="container">
<header></header>
<section>
<nav>
<ul style="list-style-type:none">
<li><a href="index.html">SOME</a></li>
<li><a href="page2.html">ANY</a><li>
<li><a href="page3.html">HAVE</a><li>
<li><a href="page4.html">HAS</a><li>
<li><a href="page5.html">VERB TO BE</a><li>
</ul>
</nav>
<article>
<h1>SOME</h1>
<img src="images/some.jpg">
<p><b>SOME :  ใช้กับ ประโยคบอกเล่า / ร้องขอ / เชิญชวน</b></p>
<br>EX: 1:There is some water in the bottle.</br>
<br>2 : Can i have some sugar?</br>
<br>3 : Would you like some cake?</br>
</article>
</section>
<footer>
<p>จัดทำโดยนายธีรภัทร​ บุญนพ ชั้น​ ม.6/3 เลขที่ 21 <br>โรงเรียนรัตนราษฎร์บำรุง</p>
</footer>
</div>
</body>
</html>
