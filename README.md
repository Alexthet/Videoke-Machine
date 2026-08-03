<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset=UTF-8">
  <meta name="viewport" content="width-device-width, intial-scale 1.0">
  <title>Hybrid Megavision - MIDI & Custome BGV edition</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  
  <div class="video-background" id="lobby-bgv">
    <video autoplay muted loop playsinline id="bg-video-element">
      <source id="video-source" src="bgv/defult.mp4" type="video/mp4"
    </video>
      <div class="video-overlay-tint"></div>
  </div>   

    <div class="megavision-screen">
      <div class="select-song-text">SELECT SONG</div>
      <div class="digits-display" id="digits">00000</div>
      <div class="song-marquee-text" id="marquee-text">READY TO SING...INSERT COIN</div>
    </div>
    
    <script src="https://cdn.jsdelivr.net/npm/@tonaljs/tonal/browser/tonaljs.min.js"></script>
    <script src="https://cdn.jsdelivr.net/gh/rism-ch/midi-player-js@master/browser/midi-player-js"></script>
    <script src="https://cdn.jsdelivr.net/gh/danigb/soundfont-player@master/dist/soundfont-player. min.js"></script>
    
    <script src="script.js"></script>
    
 </body>
 <html> 