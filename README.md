```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Cinematic Studio</title>

  <style>
    body {
      margin: 0;
      background: radial-gradient(ellipse at top, #292044 0%, #101018 65%);
      color: white;
      font-family: Arial, sans-serif;
      text-align: center;
    }

    header {
      padding: 60px 20px;
    }

    h1 {
      font-size: 42px;
      letter-spacing: 3px;
      text-shadow: 0 0 12px rgba(160, 100, 255, 0.5);
    }

    p {
      color: #c6c6d0;
      line-height: 1.7;
    }

    a {
      display: inline-block;
      margin: 12px;
      padding: 12px 20px;
      background: #8055ff;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      box-shadow: 0 0 15px rgba(128, 85, 255, 0.25);
    }

    a:hover {
      background: #9b79ff;
      box-shadow: 0 0 22px rgba(155, 121, 255, 0.6);
    }

    section {
      padding: 30px 20px;
    }

    .film-card {
      max-width: 600px;
      margin: 30px auto;
      padding: 25px;
      background: #191923;
      border: 1px solid #8055ff;
      border-radius: 12px;
      box-shadow: 0 0 25px rgba(128, 85, 255, 0.25);
      box-sizing: border-box;
      animation: fadeIn 1.2s ease-out;
    }

    .film-card img {
      width: 100%;
      max-width: 500px;
      height: auto;
      display: block;
      margin: auto;
      border-radius: 8px;
    }

    .image-link {
      display: block;
      padding: 0;
      background: none;
      box-shadow: none;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(15px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @media (max-width: 600px) {
      h1 {
        font-size: 30px;
      }

      header {
        padding: 40px 15px;
      }
    }
  </style>
</head>

<body>
  <header>
    <h1>MY CINEMATIC STUDIO</h1>
    <p>Creating cinematic worlds with AI.</p>

    <p>FOLLOW MY WORK</p>

    <a href="https://www.facebook.com/profile.php?id=61595801547247"
       target="_blank" rel="noopener noreferrer">Facebook</a>

    <a href="https://www.tiktok.com/@cindy.cano62"
       target="_blank" rel="noopener noreferrer">TikTok</a>

    <a href="https://www.instagram.com/anzklhy00011/"
       target="_blank" rel="noopener noreferrer">Instagram</a>

    <p>
      <a href="#work">View My Work</a>
      <a href="mailto:your-email@example.com">Contact Me</a>
    </p>
  </header>

  <section id="work">
    <h2>My AI Films</h2>
    <p>Explore my cinematic AI videos and visual stories.</p>

    <div class="film-card">
      <a class="image-link"
         href="https://www.facebook.com/share/r/1B3dCjaze2/"
         target="_blank" rel="noopener noreferrer">
        <img src="ai-film.jpg"
             alt="Preview of my first cinematic AI film">
      </a>

      <h3>My First AI Film</h3>
      <p>An original cinematic creation made with AI.</p>

      <a href="https://www.facebook.com/share/r/1B3dCjaze2/"
         target="_blank" rel="noopener noreferrer">
        ▶ Watch My First Video on Facebook
      </a>
    </div>

    <div class="film-card">
      <h3>My Second AI Film</h3>
      <p>Another original cinematic creation made with AI.</p>

      <a href="https://www.facebook.com/share/r/1JzzmpH2eV/"
         target="_blank" rel="noopener noreferrer">
        ▶ Watch My Second Video on Facebook
      </a>
    </div>
  </section>

  <section>
    <h2>Work With Me</h2>
    <p>Interested in a cinematic video? Get in touch.</p>
  </section>
</body>
</html>
```
