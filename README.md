# youtube_embed_mobile_web
use youtube iframe embed in mobile web (RWD)

    <html>
      <head>
        <style>
        body {
          margin: 0;
        }
        .video-container {
          position: relative;
          padding-bottom: 56.25%;
          padding-top: 30px; height: 0; overflow: hidden;
        }

        .video-container iframe {
          position: absolute;
          top: 0;
          left: 0;
          width: 100%;
          height: 100%;
        }
        </style>
      </head>
      <body>
        <div class="video-container">
          <iframe width="640" height="360" src="https://www.youtube.com/embed/z9Ul9ccDOqE?playsinline=1&controls=0&rel=0" frameborder="0" allowfullscreen></iframe>
        </div>
      </body>
    </html>
