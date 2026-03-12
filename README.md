<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Scripture Sanctuary</title>
  <meta name="description" content="Scripture Sanctuary is a peaceful immersive reading experience for Meta Quest, designed for Scripture reading, reflection, and devotion in a calm virtual setting." />
  <style>
    :root {
      --bg: #f5f1e8;
      --card: #fffdf8;
      --text: #2b251c;
      --muted: #6b6255;
      --accent: #7a5c2e;
      --accent-light: #e8dcc7;
      --border: #d9ccb6;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: Georgia, "Times New Roman", serif;
      background: linear-gradient(to bottom, #f8f4ec, #efe6d7);
      color: var(--text);
      line-height: 1.7;
    }

    .container {
      max-width: 960px;
      margin: 0 auto;
      padding: 24px;
    }

    .hero {
      text-align: center;
      padding: 64px 24px 40px;
    }

    .hero h1 {
      font-size: 3rem;
      margin: 0 0 12px;
      color: var(--accent);
    }

    .hero p {
      max-width: 760px;
      margin: 0 auto;
      font-size: 1.15rem;
      color: var(--muted);
    }

    .card {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 32px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.06);
      margin-bottom: 24px;
    }

    h2 {
      color: var(--accent);
      margin-top: 0;
      margin-bottom: 16px;
      font-size: 1.75rem;
    }

    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 16px;
      margin-top: 20px;
    }

    .feature {
      background: var(--bg);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 18px;
    }

    .feature h3 {
      margin-top: 0;
      margin-bottom: 8px;
      font-size: 1.05rem;
      color: var(--accent);
    }

    .feature p {
      margin: 0;
      color: var(--muted);
      font-size: 0.97rem;
    }

    .meta {
      font-size: 0.98rem;
      color: var(--muted);
    }

    .links {
      margin-top: 20px;
    }

    .button {
      display: inline-block;
      text-decoration: none;
      background: var(--accent);
      color: #fff;
      padding: 12px 18px;
      border-radius: 10px;
      margin-right: 12px;
      margin-bottom: 12px;
      font-weight: bold;
    }

    .button.secondary {
      background: transparent;
      color: var(--accent);
      border: 1px solid var(--accent);
    }

    footer {
      text-align: center;
      color: var(--muted);
      padding: 20px 24px 40px;
      font-size: 0.95rem;
    }

    a {
      color: var(--accent);
    }

    @media (max-width: 640px) {
      .hero {
        padding-top: 40px;
      }

      .hero h1 {
        font-size: 2.2rem;
      }

      .card {
        padding: 22px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <section class="hero">
      <h1>Scripture Sanctuary</h1>
      <p>
        A peaceful immersive reading experience for Meta Quest, designed for Scripture reading,
        reflection, and devotion in a calm virtual setting.
      </p>
    </section>

    <section class="card">
      <h2>About the App</h2>
      <p>
        <strong>Scripture Sanctuary</strong> transforms Bible reading into a calm and immersive
        experience on <strong>Meta Quest</strong>. Enter a peaceful virtual setting designed for
        quiet reading, reflection, and devotion, while keeping the experience simple, comfortable,
        and easy to use.
      </p>
      <p>
        Read <strong>Scripture</strong> and other devotional texts in a clean, focused reading
        interface built for VR. Save your place automatically, create <strong>bookmarks</strong>,
        and return to passages whenever you want. Controller-based interaction makes it easy to
        navigate books, chapters, and saved locations.
      </p>
      <p>
        <strong>Scripture Sanctuary</strong> also supports <strong>passthrough</strong>, allowing
        you to blend your reading experience with your real surroundings when desired. Whether you
        want full immersion or a more grounded mixed-reality experience, the app is designed to
        help you slow down, focus, and spend meaningful time in the text.
      </p>
    </section>

    <section class="card">
      <h2>Features</h2>
      <div class="features">
        <div class="feature">
          <h3>Immersive Reading Environment</h3>
          <p>Experience Scripture in a peaceful virtual space designed for focus and reflection.</p>
        </div>

        <div class="feature">
          <h3>Passthrough Support</h3>
          <p>Blend the reading experience with your real surroundings for a comfortable mixed-reality option.</p>
        </div>

        <div class="feature">
          <h3>Bookmarks</h3>
          <p>Save meaningful passages and return to them easily whenever you like.</p>
        </div>

        <div class="feature">
          <h3>Reading Progress Saving</h3>
          <p>Your place is saved locally on your device so you can continue where you left off.</p>
        </div>

        <div class="feature">
          <h3>Comfortable Navigation</h3>
          <p>Use intuitive controller-based navigation to move through books, chapters, and saved places.</p>
        </div>

        <div class="feature">
          <h3>Calm Devotional Atmosphere</h3>
          <p>Built to support quiet reading, prayerful reflection, and focused devotional time.</p>
        </div>
      </div>
    </section>

    <section class="card">
      <h2>Developer Information</h2>
      <p class="meta"><strong>Developer:</strong> Bicentennial Software</p>
      <p class="meta"><strong>Contact:</strong> <a href="mailto:your-email@example.com">your-email@example.com</a></p>

      <div class="links">
        <a class="button" href="privacy-policy.html">View Privacy Policy</a>
      </div>
    </section>
  </div>

  <footer>
    &copy; 2026 Bicentennial Software. All rights reserved.
  </footer>
</body>
</html>
