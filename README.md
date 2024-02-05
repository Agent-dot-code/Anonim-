html>
<head>
<title>Minggo.co.id</title>
<link href="style.css" rel="stylesheet" type="text/css" />
<link href="js/js-image-slider.css" rel="stylesheet" type="text/css" />
<script src="js/js-image-slider.js" type="text/javascript"></script>
<link rel="stylesheet" href="http://fonts.googleapis.com/css?family=Bitter:400,700">
<link href="generic.css" rel="stylesheet" type="text/css" />
<link href="http://ajax.googleapis.com/ajax/libs/jqueryui/1.8/themes/base/jquery-ui.css" rel="stylesheet" type="text/css"/>
  <script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.6.2/jquery.min.js"></script>
  <script src="http://ajax.googleapis.com/ajax/libs/jqueryui/1.8/jquery-ui.min.js"></script>
  <link rel="stylesheet" media="screen" href="calendar.css"  />
  <script>
  $(document).ready(function() {
    $("#datepicker").datepicker();
  });
    $(document).ready(function() {
    $("#datepicker2").datepicker();
  });
  </script>
  <link href="select2.css" rel="stylesheet"/>
    <script src="jquery-1.8.0.min.js"></script>
    <script src="select2.js"></script>
    <script>
        $(document).ready(function() {
            $("#states").select2();   
        });
    </script>
</head>
<body>
<div class="konten">
<div class="Menu">
<ul id="pilihan">
<li id="log"><img src="ing/lokec.PNG" style="width:28px"></li>
<a href=""><li id="home">HOME</li></a>
<a href=""><li id="shop">SHOP</li></a>
<a href=""><li id="land">MINGGO LAND</li></a>
<a href=""><li id="about">ABOUT US</li></a>
</ul>
</div>

<div class="tengah">

<div class="banner_back">
<div class="slider2">
 <div id="sliderFrame">
        <div id="slider">
            <a href="#" target="_blank">
                <img src="ing/koki.jpg" style="width:100%" alt="Selamat Datang di Minggo.co.id" />
            </a>
            <img src="ing/kok.png" style="width:100%" alt="" />
            <img src="ing/ko.png" style="width:100%" alt="" />
            <img src="ing/koki.jpg" style="width:100%" alt="" />
            <img src="ing/kok.png" style="width:100%" />
        </div>
    </div>
</div>

<div class="tiket">
<div id="tab">
<h3>Hotel</h3>
</div>
<div id="judul">
<h1>Cari Hotel Termurah Jawa Barat Disini</h1>
</div>
<table id="tiket_tab">
 <tr>
 <form action="proses.php" name="form_tiket">
  <td id="carip">
   <div>
   <h2>1. Pilih Tujuan Wisata</h2>
   <p>Tempat Wisata, daerah, nama hotel</p>
   <select style="width:100%" id="states">
               <optgroup label="Pantai">
                   <option value="AK">Pangandaran</option>
                   <option value="HI">Santolo</option>
       <option value="AK">Sayang Heulang</option>
                   <option value="HI">Manalusu</option>
       <option value="AK">Rancabuaya</option>
               </optgroup>
               <optgroup label="Pegunungan">
                   <option value="CA">Cikurai</option>
                   <option value="NV">Papandayan</option>
                   <option value="OR">Ciremai</option>
                   <option value="WA">Guntur</option>
               </optgroup>
               <optgroup label="Danau">
                   <option value="AZ">Situ Bagendit</option>
                   <option value="CO">Cangkuang</option>
                   <option value="ID">Talaga Bodas</option>
                   <option value="MT">Kawah Putih</option><option value="NE">Nebraska</option>
               </optgroup>
              </select>
   </div>
  </td>
  <td style="width:30%">
   <div>
   <h2>2. Tentukan Waktu Menginap</h2>
   <p>Check In</p>
   <input type="text" id="datepicker" name="waktu_datang" placeholder="01/06/2015">
   <p>Berapa Lama?</p>
   <input type="text" name="waktu" placeholder="2 Hari">
   <p>Check Out</p>
   <input type="text" id="datepicker2" name="waktu_akhir" placeholder="01/08/2015">
   </div>
  </td>
  <td style="width:10%">
   <div>
   <h2>3. Mulai Pencarian</h2>
   <input type="submit" name="submit" value="Cari">
   </div>
  </td>
 </form>
 </tr>
</table>
</div>
</div>

<div class="profil">
<h1>Mengapa pilih Kami? Ini alasannya </h1>
<table id="tab_profil">
<tr id="tab_ul">
<td>
<img src="ing/logos.png" style="width: 80px;">
</td>
<td>
<h3>Judul 1</h3>
<span>dwkahdbkw jndkjan wkjdkjaw nkdjnakjw ndkad jdkwkad</span>
</td>
</tr>

<tr id="tab_ul">
<td>
<img src="ing/logos.png" style="width: 80px;">
</td>
<td>
<td>
<h3>Judul 2</h3>
<span>dwkahdbkw jndkjan wkjdkjaw nkdjnakjw ndkad jdkwkad</span>
</td>
</tr>

<tr id="tab_ul">
<td>
<img src="ing/logos.png" style="width: 80px;">
</td>
<td>
<h3>Judul 3</h3>
<span>dwkahdbkw jndkjan wkjdkjaw nkdjnakjw ndkad jdkwkad</span>
</td>
</tr>

</table>
</div>

<div class="profil2">
<table id="tab_profil2" style="width:100%;height: 65px;">

<tr id="tab_ul2" style="width: 65%;padding-left: 10px;padding-top: 15px;">
<td>
<h2>Dapatkan informasi terbaru harga tiket promo melalui email Anda.</h2>
</td>
</tr>

<tr id="tab_ul2">
<td>
<input type="text" name="email" placeholder="Masukkan Email" style="background: white;width: 240px;height: 40px;border: 1px solid #FFF;color: #545454;"/>
<input type="submit" name="submit" value="Kirim" style="background:rgb(102, 102, 102)"/>

</td>
</tr>
</table>
</div>

<div class="maindiv">
<div class="sidebar1">
<h2>on Facebook</h2>
<iframe src="//www.facebook.com/plugins/likebox.php?href=https%3A%2F%2Fwww.facebook.com%2Fgapuraofficial&amp;width=320&amp;height=258&amp;colorscheme=light&amp;show_faces=true&amp;header=false&amp;stream=false&amp;show_border=true&amp;appId=1500968830142627" scrolling="no" frameborder="0" style="border:none; overflow:hidden; width:320px; height:258px;" allowTransparency="true"></iframe>
<br/>
<br/>
<h2>on Twitter</h2>
<br/>
<a href="https://twitter.com/gapuratv" class="twitter-follow-button" data-show-count="false" data-size="large" data-dnt="true">Follow @gapuratv</a>
<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+'://platform.twitter.com/widgets.js';fjs.parentNode.insertBefore(js,fjs);}}(document, 'script', 'twitter-wjs');</script>
</div>

<div class="kalender" style="float: right;width: 60%;">
<form method="post">
<table border="0" cellpadding="2" cellspacing="2">
  <tr>
    <td colspan="3" align="left" valign="middle"><?php
//Draw Calendar
function draw_calendar($month,$year){

 // Draw table for Calendar 
 $calendar = '<table cellpadding="0" cellspacing="0" class="calendar">';
