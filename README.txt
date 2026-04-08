<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Paisley Lifestyle</title>
  <meta name="description" content="Paisley Lifestyle — an expression of elegance and intention." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <button class="mobile-toggle" type="button" aria-label="Toggle navigation" aria-expanded="false" data-mobile-toggle><span></span></button>
      <div class="nav-shell" data-nav-shell>
        <div class="nav-shell-inner">
          <nav class="nav-group" aria-label="Primary left navigation">
            <a class="nav-link active" href="index.html">Home</a>
            <a class="nav-link" href="experience.html">Experience</a>
            <a class="nav-link" href="co-create.html">Co-Create</a>
          </nav>
          <nav class="nav-group right" aria-label="Primary right navigation">
            <a class="nav-link" href="story.html">The Story</a>
            <a class="nav-link" href="contact.html">Contact</a>
          </nav>
        </div>
      </div>
      <a class="brand-lockup" href="index.html" aria-label="Paisley Lifestyle home">
        <span class="brand-mark"><img src="assets/mainlogo.pngholder.svg" alt="Paisley Lifestyle logo" /></span>
        <span class="brand-type"><span class="top">Paisley</span><span class="bottom">Lifestyle</span></span>
      </a>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container hero-content">
        <div class="hero-logo"><img src="assets/mainlogo.pngholder.svg" alt="Paisley Lifestyle logo" /></div>
        <h1 class="hero-title gold-gradient">Paisley</h1>
        <div class="hero-subtitle gold-gradient">Lifestyle</div>
        <p class="hero-tagline">An expression of elegance and intention.</p>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container footer-inner">
      <div>Paisley Lifestyle</div>
      <div>Curated gatherings with warmth, beauty, and intention.</div>
    </div>
  </footer>
  <script src="script.js"></script>
</body>
</html>
