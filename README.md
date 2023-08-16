
<!DOCTYPE html>
<html>
<meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Shippori+Antique:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet">

  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script>
  <script src="https://unpkg.com/typeit@8.7.0/dist/index.umd.js"></script>
  <script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script>
  
<head>
<title>Selamat Ultahhh</title>
<meta name="description" content="S.id/heihbd">
</head>

<style>
:root {
--tombol-bg: rgba(0, 0, 0, .4); 
--tombol-teks: #fff;
--tombol-bingkai: #fff;
--bingkai: 8px;
--bingkai-kiri: 1.3px solid var(--tombol-bingkai);
--bingkai-kanan: 1.3px solid var(--tombol-bingkai);
--gaya-font: 'Shippori Antique', sans-serif;
--gaya-font2: 'Dancing Script', sans-serif;
}
@keyframes fanim {0% {background-position: 0% 0%;}25% {background-position: 100% 100%;} 50% {background-position: 0% 100%;} 75% {background-position: 50% 50%;} 100% {background-position: 0% 0%;}}
body{background-color:#000;font-family:var(--gaya-font);padding: 20px 25px;-webkit-user-select: none; -ms-user-select: none; user-select: none;} a{text-decoration:none;}
body::before{content:"\00A9  Rayys | PalingIT";color:white;opacity:.05;font-size:10px;position:fixed;bottom:25px;right:25px;z-index:2}
#bodyblur{opacity:0;position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.3);transition:all 1s ease;} 
#wallpaper{width:100%;height:100%;transform: scale(2);transition:all 1.3s ease;}
#beneranblur{position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.3);-webkit-backdrop-filter:blur(0px); backdrop-filter:blur(0px);transition:all 3s ease;}

@keyframes jj{0%  {transform: scale(1.1);} 50% {transform: scale(1.2);} 100% {transform: scale(1.1);}}
@keyframes rts{from {transform:scale(.1);} to {transform:scale(1);}}
@keyframes rto{from {transform:scale(1);} to {transform:scale(1.1);}}
@keyframes aniopa{0% {transform: scale(1);} 50% {transform: scale(.75);} 100% {transform: scale(1);}}
@keyframes rtf{from {transform: rotate(0deg);} to {transform: rotate(360deg);}} @keyframes rt{from {transform: scale(.9);/* transform: rotate(-5deg); */} to {transform: scale(1);/* transform: rotate(5deg); */}}
@keyframes kont{0%  {left:-1px; top:-3px;} 50% {left:1px; top:3px;} 100% {left:-1px; top:-3px;}}

blockquote{position:absolute;opacity:0;visibility:hidden;margin-top:100px;background:var(--tombol-bg);box-shadow: rgba(255,255,255, 0.3) 0px 7px 29px 0px;transform: scale(.1);transition:all 1s ease;margin-top:120px;margin-left:0;margin-right:0;color:var(--tombol-teks);text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);}
blockquote{width:400px;border-radius:10px;text-align:center;line-height:1.3em;padding:20px;}
blockquote::before{content:attr(data-text);opacity:.7;font-family: sans-serif;position:absolute;left:8px;top:8px;min-width:15px;font-size:16px;text-align:center}
blockquote::after{content: "";position: absolute;border: 1px solid #fff;border-radius:10px;top: -8px;bottom: -8px;left: -8px;right: -8px;}
blockquote p{font-size:16px;font-weight:700;line-height:1.4em;transition:all .5s ease;}
blockquote > .gaya2{font-size:15px;font-weight:400}
blockquote > #pesan3{position: absolute;opacity:0;transform: scale(.1);transition:all .7s ease;}
blockquote > #pesan5, blockquote > #pesan8{margin-top:25px}
blockquote p:not(#opsL, #kalimat, #pesan3, .gaya2){display:none;}
blockquote > #opsL{text-align:right;font-size:11px;font-weight:400;line-height:0;margin-top:24px;color:white;opacity:0;transition:all .2s ease;}

#Tombol{position:relative;opacity:0;margin:0;display:flex;align-items:left;list-style:none;transform: scale(.1);transition:all 1s ease;}
#Tombol a{cursor:pointer;display:inline-flex;align-items:center; margin:0;margin:12px 0 12px 0;transition:all .2s ease;padding:10px;outline:0;border: 1px solid #fefefeba;border-radius:10px;line-height:15px;background:rgba(0,0,0,.5);color:var(--tombol-teks);font-size:12px;font-weight:700;white-space:nowrap;overflow:hidden;box-shadow: rgba(255,255,255, 0.3) 0px 7px 29px 0px;z-index:1} 
#Bn{margin:12px 0 12px 12px !important;}
#Bn2{position:absolute;opacity:0;width:0}

#Content{animation-name:none;animation-duration: 3s;animation-iteration-count: infinite;position:relative;opacity:0;margin-top:50px;width:100%;height:180px;transition:all .7s ease;}
#Content > *{display:flex;align-items:center;text-align:center;justify-content:center;margin-top:1px;}
.kumpulanstiker > img{display:none;background: rgba(255, 255, 255, 0.5);box-shadow: 0 4px 30px rgba(255,255,255, 0.3);backdrop-filter: blur(5px);-webkit-backdrop-filter: blur(5px);border: 1px solid rgba(255, 255, 255, 0.3);border-radius: 50%;padding:10px;width:100px;height:100px;margin:20px 0;}
#fotostiker{opacity:.1;transition:all 1.2s ease;transform: scale(.1);}
.halo{font-size:18px !important;position:relative;margin:15px 0 20px 0} 
.halo.gaya2{font-family:var(--gaya-font2);font-size:24px !important;margin-top:20px !important;}
.halo.sty3{position:absolute !important;font-size:14px !important;font-weight:400 !important;margin:30px 20px !important;}

#fotolove img{transition:all .5s ease;width:75px;height:75px;padding:0;background:none}
#kadoIn img{display:inline-flex;background:none;width:130px;height:130px;transition:all .3s ease;} 
#ket, #kot, .halo{text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);font-size:17px;font-weight:700;color:white}
#ket, #kot{margin-top:25px !important;font-weight:400;}
#kadoIn img:hover{transform:scale(.9);}
#kot a{font-size:13px;color:white;text-decoration:underline}
#kot{padding:10px;}

#kolombaru{position:absolute;opacity:0;display:flex;transform:scale(.1);transition:all 1s ease;align-items:center;text-align:center;justify-content:center;z-index:1;}
#kolombaru > li{margin:8px;padding:0;list-style-type: none;}
#kolombaru li{opacity:.8;display:flex;font-size:30px}
#kolombaru li:hover{opacity:.5;transform: scale(1.15);transition:all .3s ease;}

.kolomrange{padding:0;background:none;position:relative;z-index:1;display:none;transition:all 1s ease;align-items:center;}
.kolomrange .inirange{width:100%;height:40px;margin-right:15px;display:flex;align-items:center;text-align:center;justify-content:center;}
.kolomrange .inirange input{height:10px;width:100%;-webkit-appearance:none;outline:none;background:#f2f2f2;border-radius:25px;box-shadow:inset 0px 0px 4px rgba(0,0,0,0.2);}
.kolomrange .inirange input::-webkit-slider-thumb{-webkit-appearance:none;appearance:none;width:20px;height:20px;border-radius:50%;border:3px solid #006FFF;background:white;transition:all .2s ease;}
.kolomrange .inirange input::-webkit-slider-thumb:hover{border:5px solid #006FFF;}
.kolomrange .inivalue{color:white;font-size:20px}

.swal2-modal > *{font-size:16px;}
.swal2-title,.swal2-html-container{line-height:1.3em;font-size:17px;font-weight:700;text-align:center;padding:15px 30px 0 30px;}
.swal2-timer-progress-bar-container > *{opacity:.7;background:#00B6FF;margin:0 2px}
.swal2-modal{background:#EAEAEA;box-shadow: 0 4px 30px rgba(255,255,255, 0.3);backdrop-filter: blur(2px);-webkit-backdrop-filter: blur(2px);border: 1px solid rgba(255, 255, 255, 0.3);border-radius: 8px;max-width:330px;top:-60px;}
.swal2-styled.swal2-confirm, .swal2-styled.swal2-cancel{position: relative;background-color: #4839eb;color: #fff;border-radius:18px;z-index: 1;transition: all 0.2s;}

.fa-snowflake {opacity:.3;color:white;font-size: 20px;position: absolute;animation:  heartMove linear 1;top: -10vh;z-index: 0;}
@keyframes heartMove {0%{transform: translateY(-10vh) ;} 100%{transform: translateY(100vh) ;}}
.sembunyi, #pesanditolak > *, #kado2, #kado3{display:none !important}
</style>
<body>
	
   <!-- Ganti Audio di sini -->
   <audio src="https://feeldreams.github.io/djikhlas.mp3" id="linkmp3" class="sembunyi"></audio>
   
   <div id="bodyblur">
     <!-- Wallpaper --><img src="awan.jpg" id="wallpaper"/><div id="beneranblur"></div>
   </div>
   
   <div id='Content'>

     <div id="kadoIn">
       <!-- Tombol Surat --><img src="https://feeldreams.github.io/kadoin.png"/>
     </div>
     <p id="ket">Klik Kadonya!</p>
     <p id="kot"><a href="https://bit.ly/htmlfeeldream"></a></p>

     <div class="kumpulanstiker">
         <!-- Stiker untuk Konten -->
         <img src="https://feeldreams.github.io/bunga.gif" id="fotostiker"/>
         <img src="https://feeldreams.github.io/pusn.gif" id="fotostiker1"/>
         <img src="https://feeldreams.github.io/pandacoklat.gif" id="fotostiker2"/>
         <img src="https://feeldreams.github.io/cilukba.gif" id="fotostiker3"/>
         <img src="https://feeldreams.github.io/pandakuning.gif" id="fotostiker4"/>
         <img src="https://feeldreams.github.io/emawh.gif" id="fotostiker5"/>
         
         <img src="https://feeldreams.github.io/pandacoklat.gif" id="fotostiker6"/>
     </div>
     
     <p id="halo" class="halo"></p>
     
     <div><blockquote id='bq'>
       <p id="kalimat">X-4 mau ngasih sesuatuu nihh 🤣❤️</p>
       <p id="kalimatt">Kamu tau ini hari apaa?️?</p>

       <p id="pesan1">Klik Pesann di Bawah! 😆❤️</p>
       <div id="kolombaru">
         <li id="lv4" style="width:35px;height:35px;margin-left:-10px;">📩</li>
       </div>

       <p id="pesan2">Tunggu bentarr yee... 👉👈</p>
       <!-- Pesan -->
       <p id="pesan3">Ciee..yang Hari Ini Ultah 🤣❤️</p>
       <p id="pesan4">Happy Birthday yaa, </p>
       <p id="pesan5" class="gaya2">Semoga panjang umur, sehat selaluu </p>
       <p id="pesan6" class="gaya2">Makin deket sama Tuhan dan Orang tua 😆❤️</p>
       <p id="pesan7" class="gaya2">Sehat selalu ya! ✨</p>

       <p id="pesan8" class="gaya2">Canda wkwwk :v</p>
       <p id="pesan9" class="gaya2">Oh iya, semoga di hari spesialmu ini kamu bisa menjadi pribadi yang lebih baik yaa.. 😍❤️</p>
       <p id="pesan10" class="gaya2">Happy Level Up Day!! 🥳</p>

       <!-- Tombol Lanjut -->
       <p id="opsL">Klik untuk Lanjut</p>
     </blockquote></div>

     <!-- Tombol Kirim Pesan -->
     <div id="Tombol"><a id="By">&#128140; Lanjut</a></div>

     <!-- Pesan Tambahan -->
     <p id="katatambahan" class="sembunyi">Kalau mau, tanyaa bendahara kelas kitaa<br>Wkwkwkwk 😜</p>
     
     <!-- Pesan Ditolak -->
     <div id="pesanditolak">
       <img id="stikerditolak" src="https://feeldreams.github.io/weee.gif"/>
       <p id="kataditolak">Yaudah kalo gamau mh 😜</p>
     </div>

   </div>

<!-- Jangan Edit Bagian Ini --><script>
  const body = document.querySelector("body");const swalst = Swal.mixin({timer: 2300, allowOutsideClick: false, showConfirmButton: false, timerProgressBar: true, imageHeight: 90,}); audio = new Audio('' + linkmp3.src); ftganti=0;fungsi=0;fungsiAwal=0;deffotostiker=fotostiker.src;function berjatuhan() {const heart = document.createElement("div"); heart.className = "fas fa-snowflake"; heart.style.left = (Math.random() * 90)+"vw"; heart.style.animationDuration = (Math.random()*3)+2+"s"; body.appendChild(heart);} setInterval(function name(params) {var heartArr = document.querySelectorAll(".fa-snowflake"); if (heartArr.length > 100) {heartArr[0].remove()}},100);Content.style = "opacity:1;margin-top:16vh"; const swals = Swal.mixin({allowOutsideClick: false, cancelButtonColor: '#FF0040', imageHeight: 80,}); 
  function tunjukkan(){document.getElementById("sticky-ad").style = "bottom: 0px";}
  function hilangkan() {document.getElementById("sticky-ad").style = "bottom: -130px";}

  document.getElementById("kadoIn").onclick = function() {if(fungsiAwal==0){audio.play();fungsiAwal=1;kot.style="display:none";kadoIn.style="transition:all .8s ease;transform:scale(10);opacity:0";wallpaper.style="transform: scale(1.5);";ket.style="display:none";setTimeout(initengahan,300);setTimeout(inipesan,500)}}
  
  async function inipesan(){
    nama = "Michael"  
    hurufdepan = nama.charAt(0);
    nama = hurufdepan.toUpperCase() + nama.slice(1);
    window.nama = nama;
    vketikhalo="Hai, " + nama + " ✨";
    mulainama();
    
  }

  function initengahan(){
    kadoIn.style="display:none";ket.style="display:none";
    Content.style = "opacity:1;margin-top:0";
    wallpaper.style="transform: scale(1.5);";
  }
  
  async function mulainama() {
    bodyblur.style="opacity:.9";
    wallpaper.style="transform: scale(1);";
    fotostiker.style="display:inline-flex;";setTimeout(ftmuncul,200);
    setTimeout(kethalo,500);
  }
  
  function ftmuncul(){
    if(ftganti==0){fotostiker.src = deffotostiker;}
    if(ftganti==1){fotostiker.src = fotostiker1.src;}
    if(ftganti==2){fotostiker.src = fotostiker2.src;}
    if(ftganti==3){fotostiker.src = fotostiker3.src;}
    if(ftganti==4){fotostiker.src = fotostiker4.src;}
    if(ftganti==5){fotostiker.src = fotostiker5.src;}
    
    fotostiker.style="display:inline-flex;opacity:1;transform:scale(1)";
  }
  function fthilang(){fotostiker.style="display:inline-flex;opacity:0;transition:all .7s ease;transform:scale(.1)";}
  function jjfoto(){fotostiker.style.animation="rto .8s infinite alternate";}
  
  function bqmuncul(){bq.style = "position:relative;opacity:1;visibility:visible;transform: scale(1);margin-top:0";mulaiketik1();}
  function bqhilang(){wallpaper.style="transform: scale(2);";bodyblur.style="opacity:.3";bq.style = "position:relative;transition:all .7s ease;";}
  function kethalo(){new TypeIt("#halo", {strings: ["" + vketikhalo], startDelay: 50, speed: 40, waitUntilVisible: true, afterComplete: function(){halo.innerHTML = vketikhalo;setTimeout(bqmuncul,200);},}).go();}

  function tombol(){wallpaper.style="transform: scale(1);";Tombol.style="opacity:1;transform: scale(1);";if(fungsi==2){By.innerHTML="&#128140; Balas"}}
  document.getElementById("By").onclick = function() {if(fungsi==1){Tombol.style="";fthilang();fungsi=0;pertanyaan();} if(fungsi==2){Tombol.style="";menuju();}}
  
  const waktuSekarang = new Date().getHours();let ucapan;
  if(waktuSekarang < 10){ucapan = "Selamat Pagi, ";} 
  else if(waktuSekarang < 16){ucapan = "Selamat Siang, ";}
  else if(waktuSekarang < 19){ucapan = "Selamat Sore, ";}
  else{ucapan = "Selamat Malam, ";}

  vketik1=kalimat.innerHTML;kalimat.innerHTML = "";
  function mulaiketik1(){
  new TypeIt("#kalimat", {
  strings: ["" + vketik1], startDelay: 400, speed: 20, cursor: false, deleteSpeed: 20, breakLines: false, waitUntilVisible: true, lifelike: true,
  afterComplete: function(){
    aktiopsL();tunjukkan();
  },}).go();
  }
  
  vketikk=kalimatt.innerHTML;kalimatt.innerHTML = "";
  function mulaiketik11(){
  new TypeIt("#kalimatt", {
  strings: ["" + vketikk], startDelay: 400, speed: 20, cursor: false, deleteSpeed: 20, breakLines: false, waitUntilVisible: true, lifelike: true,
  afterComplete: function(){
    aktiopsL();tunjukkan();
  },}).go();
  }
  
  opsLclick=0;opsLcheck=0;defopsL=opsL.innerHTML;
  document.getElementById("bq").onclick = function() {
    if(opsLclick==1){
      if(opsLcheck==1){setTimeout(aktipesan1,400);fthilang();ftganti=1;setTimeout(ftmuncul,300);}
      if(opsLcheck==2){mulaiketik3();}
      if(opsLcheck==3){mulaiketik4();}
      if(opsLcheck==4){mulaiketik5();}
      if(opsLcheck==5){kethalo2();}
      otomatis();opsL.style.opacity="0";opsLclick=0;
    }
  }
  function aktiopsL(){opsL.innerHTML=defopsL;opsL.style.opacity=".8";opsLclick=1;opsLcheck+=1;}
  function gantiopsL(){opsL.innerHTML="[ Klik beberapa LOVE-nya ]";opsL.style.opacity=".8";}
  function otomatis(){pesan3.style="transition:none";pesan8.style="display:none";kalimat.style="opacity:0";if(otoaktipesan==0){setTimeout(otolanj,400)}}
  function otolanj(){kalimat.style="opacity:1";}

  function aktipesan1(){kalimat.innerHTML=pesan1.innerHTML;kolombaru.style="position:relative;opacity:1;transform:scale(1);";}
  vketik2=pesan2.innerHTML;
  function aktipesan2(){
  wallpaper.style="transform: scale(1.5);";
  kolombaru.style="";kalimat.innerHTML="";
  new TypeIt("#kalimat", {
  strings: ["" + vketik2], startDelay: 20, speed: 40, cursor: true, deleteSpeed: 50, breakLines: false, waitUntilVisible: true, lifelike: true,
  afterComplete: function(){
    setTimeout(aktipesan3,500);
  },}).go();
  }
  vketik3=pesan3.innerHTML;pesan3.innerHTML="";
  function aktipesan3(){
  kalimat.style="display:none";
  pesan3.style="position:relative;opacity:1;transform: scale(1)";
  wallpaper.style="transform: scale(1)";
  fthilang();ftganti=2;setTimeout(ftmuncul,300);
  new TypeIt("#pesan3", {
  strings: ["" + vketik3], startDelay: 1, speed: 45, cursor: true, waitUntilVisible: true, lifelike: true,
  afterComplete: function(){
    pesan3.innerHTML=vketik3;setTimeout(otomatis,600);setTimeout(aktipesan4,1010);
  },}).go();
  }
  function aktipesan4(){
    wallpaper.style="transform: scale(1.5);";kalimat.innerHTML=pesan4.innerHTML + nama + " 🥳";kalimat.style="transform:scale(1.2)";setTimeout(aktipesan5,1000);
  }
  vketik5=pesan5.innerHTML;pesan5.innerHTML="";
  function aktipesan5(){
  fthilang();ftganti=3;setTimeout(ftmuncul,300);
  wallpaper.style="transform: scale(1);";
  new TypeIt("#pesan5", {
  strings: ["" + vketik5], startDelay: 1, speed: 52, cursor: true, waitUntilVisible: true, lifelike: true,
  afterComplete: function(){
    pesan5.innerHTML=vketik5 + " ><";setTimeout(aktipesan6,800);
  },}).go();
  }
  vketik6=pesan6.innerHTML;pesan6.innerHTML="";
  function aktipesan6(){
  wallpaper.style="transform: scale(1.5);";
  new TypeIt("#pesan6", {
  strings: ["" + vketik6], startDelay: 1, speed: 52, cursor: true, waitUntilVisible: true, lifelike: true,
  afterComplete: function(){
    pesan6.innerHTML=vketik6;setTimeout(aktipesan7,800);
  },}).go();
  }
  vketik7=pesan7.innerHTML;pesan7.innerHTML="";
  function aktipesan7(){
  fthilang();ftganti=1;setTimeout(ftmuncul,300);
  wallpaper.style="transform: scale(1);";
  new TypeIt("#pesan7", {
  strings: ["" + vketik7], startDelay: 1, speed: 52, cursor: true, waitUntilVisible: true, lifelike: true,
  afterComplete: function(){
    pesan7.innerHTML=vketik7;fungsi=1;setTimeout(tombol,400);
  },}).go();
  }
  //Pemisah
  vketik81=pesan8.innerHTML;pesan8.innerHTML="";
  vketik9=pesan9.innerHTML;pesan9.innerHTML="";
  vketik10=pesan10.innerHTML;pesan10.innerHTML="";
  function aktipesan8(){
  pesan5.style="display:none";pesan6.style="display:none";pesan7.style="display:none";pesan8.style="";
  wallpaper.style="transform: scale(1);";
  ftganti=4;ftmuncul();
  new TypeIt("#pesan8", {
  strings: ["" + vketik8, "" + vketik9], startDelay: 20, speed: 45, cursor: true, deleteSpeed: 30, breakLines: false, waitUntilVisible: true, lifelike: true,
  afterComplete: function(){
    pesan8.innerHTML=vketik9;setTimeout(otomatis,1300);setTimeout(aktipesan10,1710);
  },}).go();
  }
  function aktipesan10(){
    wallpaper.style="transform: scale(1.5);";
    fthilang();ftganti=5;setTimeout(ftmuncul,300);
    otoaktipesan=1;otomatis();setTimeout(toaktipesan,300);
    setInterval(berjatuhan,400);
    fungsi=2;setTimeout(tombol,2000);
  }
  var otoaktipesan=0;
  function toaktipesan(){kalimat.innerHTML=vketik10;kalimat.style="transform:scale(1);font-size:24px;font-family:var(--gaya-font2)";}

    document.getElementById("lv4").onclick = function() {lv4.style="opacity:0";slov+=1;this.onclick=null;checkslov();}
  var slov=3;function checkslov() {if(slov==4){kolombaru.style="position:relative;transform:scale(1)";otomatis();setTimeout(aktipesan2,400);}}
  
  async function pertanyaan(){var { isConfirmed: prtanya } = await swals.fire({title: nama + ' ' + tanya, imageUrl: '' + fotostiker6.src, showCancelButton: true, confirmButtonText: '' + tompositif, cancelButtonText: '' + tomnegatif,});
    if(prtanya){
  await swalst.fire({html: '' + katatambahan.innerHTML, timer: 3000, imageUrl: '' + stikerditolak.src,});
      vketik8=vketik81;aktipesan8();
    } else {
	await swalst.fire({html: '' + kataditolak.innerHTML, timer: 3000, imageUrl: '' + stikerditolak.src,});
      vketik8="";aktipesan8();
    }
    }

  //Variable Pertanyaan Akhir
  var tanya = 'Mau Kado Gak Nih? 😶❤️';
  var opstanya = 'Ayo jawab 😆';
  var tompositif = 'Mau';
  var tomnegatif = 'Engga';
    
    async function menuju(){pesanwhatsapp = "Makasii udah ngucapin " + nama + " ultah ><";await swals.fire('OK!', 'Kirim jawabannya ke WhatsApp aku, ya!', 'success');window.location = "https://api.whatsapp.com/send?phone=&text=" + pesanwhatsapp;}
</script>
</body>
</html>
