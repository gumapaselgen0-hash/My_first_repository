<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GitHub Code Information</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      background: #0d1117;
      color: #f0f6fc;
      line-height: 1.6;
    }

    .container {
      width: 90%;
      max-width: 1200px;
      margin: auto;
    }

    header {
      padding: 70px 0 40px;
      text-align: center;
    }

    .github-icon {
      font-size: 70px;
      margin-bottom: 15px;
    }

    h1 {
      font-size: 64px;
      margin-bottom: 10px;
    }

    .tagline {
      color: #8b949e;
      font-size: 24px;
    }

    .intro {
      max-width: 700px;
      margin: 20px auto;
      color: #8b949e;
      font-size: 18px;
    }

    .content {
      display: grid;
      grid-template-columns: 1.5fr 1fr;
      gap: 35px;
      align-items: center;
    }

    /* Code Window */
    .code-window {
      background: #161b22;
      border: 1px solid #30363d;
      border-radius: 14px;
      overflow: hidden;
      box-shadow: 0 15px 40px rgba(0,0,0,.3);
    }

    .repo-header {
      padding: 18px 22px;
      border-bottom: 1px solid #30363d;
      color: #c9d1d9;
    }

    .file-name {
      padding: 15px 22px;
      border-bottom: 1px solid #30363d;
      font-weight: bold;
    }

    pre {
      padding: 25px;
      overflow-x: auto;
      color: #c9d1d9;
      font-size: 15px;
    }

    .keyword {
      color: #ff7b72;
    }

    .function {
      color: #d2a8ff;
    }

    .string {
      color: #a5d6ff;
    }

    .comment {
      color: #8b949e;
    }

    .repo-footer {
      padding: 15px 22px;
      border-top: 1px solid #30363d;
      color: #8b949e;
    }

    /* Features */
    .features {
      display: flex;
      flex-direction: column;
      gap: 20px;
    }

    .feature {
      display: flex;
      gap: 18px;
      align-items: center;
      padding: 18px;
      border-radius: 12px;
      background: #161b22;
      border: 1px solid #30363d;
    }

    .icon {
      width: 55px;
      height: 55px;
      border-radius: 12px;
      display: grid;
      place-items: center;
      font-size: 25px;
      background: #238636;
    }

    .feature h3 {
      margin-bottom: 4px;
    }

    .feature p {
      color: #8b949e;
      font-size: 14px;
    }

    /* Statistics */
    .stats {
      margin: 60px 0;
      padding: 25px;
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
      text-align: center;
      border-top: 1px solid #30363d;
      border-bottom: 1px solid #30363d;
    }

    .stat h2 {
      font-size: 32px;
    }

    .stat p {
      color: #8b949e;
    }

    @media (max-width: 800px) {
      h1 {
        font-size: 44px;
      }

      .content {
        grid-template-columns: 1fr;
      }

      .stats {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>

<body>

  <div class="container">

    <header>
      <div class="github-icon">◉</div>
      <h1>GitHub</h1>
      <div class="tagline">Build software together.</div>

      <p class="intro">
        GitHub is a platform where developers can host,
        review, manage, and collaborate on code.
      </p>
    </header>

    <section class="content">

      <!-- Code -->
      <div class="code-window">

        <div class="repo-header">
          👤 username / <strong>hello-world</strong>
        </div>

        <div class="file-name">
          📄 app.py
        </div>

        <pre><code><span class="comment"># A simple Python program</span>

<span class="keyword">def</span> <span class="function">greet</span>(name):
    <span class="keyword">return</span> <span class="string">f"Hello, {name}!"</span>

<span class="keyword">if</span> __name__ == <span class="string">"__main__"</span>:
    user = input(<span class="string">"What's your name? "</span>)
    print(greet(user))</code></pre>

        <div class="repo-footer">
          ✓ Add simple greeting program
          &nbsp; • &nbsp; 2 days ago
        </div>

      </div>

      <!-- Features -->
      <div class="features">

        <div class="feature">
          <div class="icon">⑂</div>
          <div>
            <h3>Version Control</h3>
            <p>Track changes and manage your code with Git.</p>
          </div>
        </div>

        <div class="feature">
          <div class="icon">👥</div>
          <div>
            <h3>Collaboration</h3>
            <p>Review code, discuss ideas, and work together.</p>
          </div>
        </div>

        <div class="feature">
          <div class="icon">🛡</div>
          <div>
            <h3>Security</h3>
            <p>Protect your projects with built-in security tools.</p>
          </div>
        </div>

        <div class="feature">
          <div class="icon">☁</div>
          <div>
            <h3>Open Source</h3>
            <p>Discover and contribute to projects worldwide.</p>
          </div>
        </div>

      </div>

    </section>

    <section class="stats">

      <div class="stat">
        <h2>100M+</h2>
        <p>Developers</p>
      </div>

      <div class="stat">
        <h2>420M+</h2>
        <p>Repositories</p>
      </div>

      <div class="stat">
        <h2>3M+</h2>
        <p>Organizations</p>
      </div>

    </section>

  </div>

</body>
</html>
