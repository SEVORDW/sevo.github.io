# sevo.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SEVORDW | YouTube Channel</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: #0f0f0f;
      color: #ffffff;
    }
    header {
      padding: 60px 20px;
      text-align: center;
      background: linear-gradient(135deg, #ff0000, #900000);
    }
    header h1 {
      font-size: 3rem;
      margin: 0;
    }
    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 24px;
      background: #ffffff;
      color: #000000;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
      transition: transform 0.2s, box-shadow 0.2s;
    }
    .btn:hover {
      transform: translateY(-2px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.3);
    }
    section {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      text-align: center;
      margin-bottom: 30px;
    }
    .video {
      position: relative;
      padding-bottom: 56.25%;
      height: 0;
      overflow: hidden;
      border-radius: 16px;
    }
    .video iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      border: none;
    }
    footer {
      text-align: center;
      padding: 30px 20px;
      background: #080808;
      opacity: 0.8;
    }
  </style>
</head>
<body>

  <header>
    <h1>SEVORDW</h1>
    <p>Official website of the YouTube channel</p>
    <a class="btn" href="https://www.youtube.com/@SEVORDW" target="_blank">Subscribe on YouTube</a>
  </header>

  <section>
    <h2>Latest Featured Video</h2>
    <div class="video">
      <iframe
        src="https://www.youtube.com/embed/nu82IRrngdg"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
      </iframe>
    </div>
  </section>

  <section>
    <h2>More Videos</h2>
    <div class="video">
      <!-- Shows latest uploads from the channel automatically -->
      <iframe
        src="https://www.youtube.com/embed?channel=SEVORDW"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
      </iframe>
    </div>
  </section>

  <section>
    <h2>About the Channel</h2>
    <p style="text-align:center; max-width:700px; margin:auto; line-height:1.6;">
      Welcome to <strong>SEVORDW</strong>! This is the official website for the channel.
      Here you’ll find the latest videos, updates, and content. Subscribe on YouTube
      so you don’t miss new uploads.
    </p>
  </section>

  <footer>
    <p>© 2025 SEVORDW • All rights reserved</p>
  </footer>

</body>
</html>
