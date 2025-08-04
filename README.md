<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Satheesh M | 3D GitHub Profile</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      height: 100vh;
      background: linear-gradient(to right, #1e1e2f, #232347);
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      overflow: hidden;
    }
    .container {
      perspective: 1000px;
    }
    .card {
      width: 400px;
      height: 500px;
      background: #ffffff10;
      border-radius: 20px;
      backdrop-filter: blur(10px);
      box-shadow: 0 20px 50px rgba(0, 0, 0, 0.3);
      color: white;
      padding: 2rem;
      transform-style: preserve-3d;
      transform: rotateY(0deg) rotateX(0deg);
      transition: transform 0.2s ease-out;
    }
    .card:hover {
      animation: float 6s ease-in-out infinite;
    }
    @keyframes float {
      0%, 100% {
        transform: rotateY(0deg) rotateX(0deg);
      }
      50% {
        transform: rotateY(15deg) rotateX(10deg);
      }
    }
    h1 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }
    h2 {
      font-size: 1.2rem;
      color: #aaa;
      margin-bottom: 2rem;
    }
    ul {
      list-style: none;
      margin-bottom: 2rem;
    }
    ul li {
      margin-bottom: 0.5rem;
    }
    a {
      color: #00ffee;
      text-decoration: none;
    }
    .btn {
      display: inline-block;
      padding: 0.5rem 1rem;
      background: #00ffee;
      color: #111;
      border-radius: 10px;
      text-decoration: none;
      margin-top: 1rem;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <h1>Hi 👋, I'm Satheesh M</h1>
      <h2>Frontend & Mobile App Developer from India</h2>
      <ul>
        <li>🔭 Working on <a href="https://github.com/MSatheesh0/healthapp">Holistic Harmony</a></li>
        <li>🌱 Learning Flutter, Firebase, Supabase</li>
        <li>👯 Collaborating on ML healthcare projects</li>
        <li>📫 Email: <a href="mailto:satheesh2005satheesh@gmail.com">satheesh2005satheesh@gmail.com</a></li>
        <li>🔗 <a href="https://linkedin.com/in/m-satheesh-968090258">LinkedIn</a></li>
        <li>💻 <a href="https://satheesh-portfolio.firebaseapp.com">Portfolio</a></li>
      </ul>
      <a href="https://www.buymeacoffee.com/satheeshm" class="btn">☕ Buy me a coffee</a>
    </div>
  </div>
</body>
</html>
