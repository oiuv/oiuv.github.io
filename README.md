<div class="container">
  <div class="header">
    <h1>oiuv</h1>
    <p>个人项目导航</p>
  </div>

  <div class="nav-grid">
    <div class="nav-card">
      <div class="card-icon">🎮</div>
      <h2>Mud Game</h2>
      <p>经典的文字游戏世界</p>
      <a href="https://mud.ren" class="nav-btn" target="_blank">访问网站</a>
    </div>

    <div class="nav-card">
      <div class="card-icon">🌿</div>
      <h2>Game Ivy</h2>
      <p>游戏开发与创意分享</p>
      <a href="https://gameivy.com" class="nav-btn" target="_blank">访问网站</a>
    </div>
  </div>

  <div class="footer">
    <p>© 2024 oiuv</p>
  </div>
</div>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #333;
}

.container {
  width: 100%;
  max-width: 1200px;
  padding: 2rem;
}

.header {
  text-align: center;
  margin-bottom: 3rem;
}

.header h1 {
  font-size: 3rem;
  font-weight: 700;
  color: white;
  margin-bottom: 0.5rem;
  text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
}

.header p {
  font-size: 1.2rem;
  color: rgba(255,255,255,0.9);
  font-weight: 300;
}

.nav-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-bottom: 3rem;
}

.nav-card {
  background: white;
  border-radius: 20px;
  padding: 2.5rem;
  text-align: center;
  box-shadow: 0 20px 40px rgba(0,0,0,0.1);
  transition: all 0.3s ease;
  border: 1px solid rgba(255,255,255,0.2);
}

.nav-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 30px 60px rgba(0,0,0,0.15);
}

.card-icon {
  font-size: 4rem;
  margin-bottom: 1rem;
  filter: drop-shadow(2px 2px 4px rgba(0,0,0,0.1));
}

.nav-card h2 {
  font-size: 1.8rem;
  font-weight: 600;
  margin-bottom: 1rem;
  color: #333;
}

.nav-card p {
  font-size: 1.1rem;
  color: #666;
  margin-bottom: 2rem;
  line-height: 1.6;
}

.nav-btn {
  display: inline-block;
  padding: 12px 30px;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  text-decoration: none;
  border-radius: 25px;
  font-weight: 500;
  font-size: 1rem;
  transition: all 0.3s ease;
  border: none;
  cursor: pointer;
}

.nav-btn:hover {
  transform: scale(1.05);
  box-shadow: 0 10px 20px rgba(102, 126, 234, 0.3);
}

.footer {
  text-align: center;
  color: rgba(255,255,255,0.8);
  font-size: 0.9rem;
}

@media (max-width: 768px) {
  .container {
    padding: 1rem;
  }

  .header h1 {
    font-size: 2.5rem;
  }

  .nav-grid {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }

  .nav-card {
    padding: 2rem;
  }

  .card-icon {
    font-size: 3rem;
  }
}
</style>
