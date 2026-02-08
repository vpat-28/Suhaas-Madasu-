<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Suhaas Madasu — Portfolio</title>
  
  <!-- Font Awesome for Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com">

  <style>
    :root {
      --bg: #071028;
      --card: #111827;
      --accent: #7dd3fc;
      --muted: #94a3b8;
      --text: #e6eef8;
      font-family: system-ui, -apple-system, sans-serif;
    }
    body { 
      margin: 0; 
      background: var(--bg); 
      color: var(--text);
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
      padding: 40px 20px;
    }
    .container { max-width: 600px; width: 100%; text-align: center; }
    h1 { color: var(--accent); font-size: 2.5rem; margin-bottom: 10px; }
    p { color: var(--muted); line-height: 1.6; }
    
    /* Social Icons Styling */
    .social-links { margin: 30px 0; display: flex; gap: 25px; justify-content: center; }
    .social-links a { color: var(--text); font-size: 1.8rem; transition: 0.3s; }
    .social-links a:hover { color: var(--accent); transform: translateY(-3px); }

    /* Form Styling */
    form { background: var(--card); padding: 30px; border-radius: 12px; text-align: left; margin-top: 40px; border: 1px solid #1e293b; }
    label { display: block; margin-bottom: 8px; color: var(--accent); font-weight: bold; }
    input, textarea { 
      width: 100%; padding: 12px; margin-bottom: 20px; border-radius: 6px; 
      border: 1px solid #334155; background: #0f172a; color: white; box-sizing: border-box;
    }
    button { 
      width: 100%; padding: 12px; background: var(--accent); color: #071028; 
      border: none; border-radius: 6px; font-weight: bold; cursor: pointer; transition: 0.2s;
    }
    button:hover { opacity: 0.9; transform: scale(1.02); }
  </style>
</head>
<body>

  <div class="container">
    <h1>Suhaas Madasu</h1>
    <p>Welcome to my personal portfolio. I am building this site using AI and GitHub Pages.</p>

    <!-- Social Links -->
    <div class="social-links">
      <a href="https://linkedin.com" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
      <a href="https://github.com" target="_blank"><i class="fa-brands fa-github"></i></a>
      <a href="https://twitter.com" target="_blank"><i class="fa-brands fa-x-twitter"></i></a>
    </div>

    <!-- Contact Form -->
    <form action="https://formspree.io" method="POST">
      <label>Email Address</label>
      <input type="email" name="email" placeholder="email@example.com" required>
      
      <label>Message</label>
      <textarea name="message" rows="4" placeholder="How can I help you?" required></textarea>
      
      <button type="submit">Send Message</button>
    </form>
  </div>

</body>
</html>
