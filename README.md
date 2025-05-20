<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ankit Meena | Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #000;
      font-family: 'Segoe UI', sans-serif;
      color: #fff;
      overflow-x: hidden;
    }
    .container {
      text-align: center;
      padding: 50px 20px;
    }
    h1 {
      font-size: 3em;
      color: #fff;
      text-shadow: 0 0 10px red;
      animation: glow 2s ease-in-out infinite alternate;
    }
    @keyframes glow {
      from { text-shadow: 0 0 10px red; }
      to { text-shadow: 0 0 20px #ff0000, 0 0 30px red; }
    }
    p.bio {
      font-size: 1.2em;
      color: #eee;
      margin-bottom: 30px;
      text-shadow: 0 0 5px #ff0000;
    }
    .social-links {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 20px;
    }
    .link {
      background: #111;
      border: 1px solid red;
      border-radius: 10px;
      padding: 15px 30px;
      color: white;
      font-size: 1.2em;
      text-decoration: none;
      display: flex;
      align-items: center;
      gap: 15px;
      transition: 0.3s;
      box-shadow: 0 0 10px red;
    }
    .link:hover {
      background: #222;
      transform: scale(1.05);
      box-shadow: 0 0 20px red;
      color: #ff4c4c;
    }
    .link i {
      font-size: 1.5em;
      animation: pulse 2s infinite;
    }
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.2); }
      100% { transform: scale(1); }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Ankit Meena</h1>
    <p class="bio">BTech persuing | AI Explorer | Gmail: ankitmeenag3@gmail.com</p>
    <div class="social-links">
      <a class="link" href="https://youtube.com/@aisamosawala?si=JYOh-xVk469nEoQZ" target="_blank">
        <i class="fab fa-youtube"></i> YouTube Channel
      </a>
      <a class="link" href="https://www.instagram.com/_ankit_meena._/profilecard/?igsh=ZDY5bDE2MnBreTU0" target="_blank">
        <i class="fab fa-instagram"></i> Instagram
      </a>
      <a class="link" href="https://www.linkedin.com/in/ankit-meena-215850285?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank">
        <i class="fab fa-linkedin"></i> LinkedIn
      </a>
      <a class="link" href="https://www.snapchat.com/add/ankit_meena142?share_id=ukOhtshoimk&locale=en-US" target="_blank">
        <i class="fab fa-snapchat"></i> Snapchat
      </a>
    </div>
  </div>
</body>
</html>
