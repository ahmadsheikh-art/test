<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mahmood Ahmad - Coder | YouTuber | Muslim</title>
  <style>
    /* Background video styles */
    #bg-video {
      position: fixed;
      right: 0;
      bottom: 0;
      min-width: 100%;
      min-height: 100%;
      z-index: -1;
      object-fit: cover;
      filter: brightness(1.5); /* optional dark overlay */
    }

    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      color: white;
      height: 100vh;
      overflow: hidden;
    }

    .overlay {
      background-color: rgba(0, 0, 0, 0.7);
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      overflow-y: auto;
      display: flex;
      flex-direction: column;
      justify-content: flex-start;
      align-items: center;
      text-align: center;
      padding-top: 50px;
    }

    .container {
      max-width: 800px;
      padding: 30px;
    }

    .logo {
      max-width: 150px;
      height: auto;
      margin-bottom: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.4);
    }

    h1 {
      font-size: 3em;
      margin-bottom: 10px;
      text-shadow: 2px 2px 5px #000;
    }

    .title {
      font-size: 1.5em;
      margin-bottom: 30px;
      text-shadow: 1px 1px 3px #000;
    }

    .social-links {
      margin-top: 30px;
    }

    .social-link {
      display: inline-block;
      margin: 10px 15px;
      padding: 12px 25px;
      background-color: #ff2d20;
      color: white;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
      transition: all 0.3s ease;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
    }

    .social-link:hover {
      background-color: #ff4d40;
      transform: translateY(-3px);
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4);
    }

    .social-link.instagram {
      background-color: #E1306C;
    }

    .social-link.instagram:hover {
      background-color: #F56040;
    }

    .social-icon {
      margin-right: 8px;
      font-size: 1.2em;
    }

    .play-button {
      margin-top: 20px;
      padding: 12px 25px;
      background-color: #28a745;
      color: white;
      border: none;
      border-radius: 30px;
      font-weight: bold;
      cursor: pointer;
      transition: background-color 0.3s ease;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
    }

    .play-button:hover {
      background-color: #218838;
    }

    .videos {
      margin-top: 40px;
    }

    .video-wrapper {
      margin: 20px 0;
    }

    video {
      width: 100%;
      max-width: 600px;
      height: 340px;
      border-radius: 15px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.5);
    }
  </style>

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
</head>
<body>

 <style>
  body{
    background-image: url("0478cf6f0c07bb570303ad5be333044f.jpg");
  }
 </style>

  <!-- Audio Element -->
  <audio id="bg-music" autoplay loop>
    <source src="my life .mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>

  <div class="overlay">
    <div class="container">

      <!-- Logo Image -->
      <img src="
      hy.jpeg" alt="Mahmood Ahmad Logo" class="logo">

      <h1>Mahmood Ahmad</h1>
      <div class="title">Coder • YouTuber • Muslim</div>

      <button class="play-button" onclick="playMusic()">
        <i class="fas fa-play"></i> Play Background Music
      </button>

      <div class="social-links">
        <a href="https://www.instagram.com/ur_ahmadsheikh1/" class="social-link instagram" target="_blank">
          <i class="fab fa-instagram social-icon"></i>Instagram
        </a>
        <a href="https://heylink.me/ahmadsheikh" class="social-link" target="_blank">
          <i class="fas fa-link social-icon"></i>All Socials & Giveaways
        </a>
      </div>

      
    </div>
  </div>

  <script>
    function playMusic() {
      const audio = document.getElementById('bg-music');
      audio.play().catch(error => {
        console.log("Playback error:", error);
      });
    }
  </script>
</body>
</html>
