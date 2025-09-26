<div class="container">
  <div class="hero">
    <div class="hero-content">
      <h1 class="hero-title">
        <span class="gradient-text">oiuv</span>
      </h1>
      <p class="hero-subtitle">个人项目导航</p>
    </div>
  </div>

  <div class="nav-grid">
    <div class="nav-card">
      <div class="card-bg">
        <div class="card-icon">🎮</div>
      </div>
      <div class="card-content">
        <h2>Mud Game</h2>
        <p>经典的文字游戏世界，体验纯粹的RPG冒险</p>
        <div class="card-features">
          <span class="feature-tag">文字游戏</span>
          <span class="feature-tag">角色扮演</span>
        </div>
        <a href="https://mud.ren" class="nav-btn" target="_blank">
          <span class="btn-text">访问网站</span>
          <span class="btn-arrow">→</span>
        </a>
      </div>
    </div>

    <div class="nav-card">
      <div class="card-bg">
        <div class="card-icon">🌿</div>
      </div>
      <div class="card-content">
        <h2>Game Ivy</h2>
        <p>游戏开发与创意分享平台，探索无限可能</p>
        <div class="card-features">
          <span class="feature-tag">游戏开发</span>
          <span class="feature-tag">创意分享</span>
        </div>
        <a href="https://gameivy.com" class="nav-btn" target="_blank">
          <span class="btn-text">访问网站</span>
          <span class="btn-arrow">→</span>
        </a>
      </div>
    </div>
  </div>

  <div class="floating-shapes">
    <div class="shape shape-1"></div>
    <div class="shape shape-2"></div>
    <div class="shape shape-3"></div>
  </div>

  <div class="footer">
    <p>© 2024 oiuv | 用心创造每一个项目</p>
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
  position: relative;
  overflow-x: hidden;
}

.container {
  width: 100%;
  max-width: 1400px;
  padding: 2rem 4rem;
  position: relative;
  z-index: 1;
}

.hero {
  text-align: center;
  margin-bottom: 4rem;
}

.hero-title {
  font-size: 5rem;
  font-weight: 800;
  margin-bottom: 1rem;
  letter-spacing: -0.02em;
}

.gradient-text {
  background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 50%, #e9ecef 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  filter: drop-shadow(0 4px 20px rgba(0,0,0,0.3));
}

.hero-subtitle {
  font-size: 1.5rem;
  color: rgba(255,255,255,0.95);
  font-weight: 300;
  letter-spacing: 0.05em;
}

.nav-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 3rem;
  margin-bottom: 4rem;
  max-width: 1200px;
  margin-left: auto;
  margin-right: auto;
}

.nav-card {
  background: rgba(255,255,255,0.95);
  border-radius: 24px;
  overflow: hidden;
  box-shadow: 0 25px 50px rgba(0,0,0,0.15);
  transition: all 0.4s cubic-bezier(0.25, 0.8, 0.25, 1);
  backdrop-filter: blur(10px);
  border: 1px solid rgba(255,255,255,0.2);
  position: relative;
}

.nav-card:hover {
  transform: translateY(-12px) scale(1.02);
  box-shadow: 0 35px 70px rgba(0,0,0,0.2);
}

.card-bg {
  height: 140px;
  background: linear-gradient(135deg, rgba(102,126,234,0.1) 0%, rgba(118,75,162,0.1) 100%);
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}

.card-bg::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: linear-gradient(135deg, rgba(102,126,234,0.2) 0%, rgba(118,75,162,0.2) 100%);
  opacity: 0;
  transition: opacity 0.3s ease;
}

.nav-card:hover .card-bg::before {
  opacity: 1;
}

.card-icon {
  font-size: 5rem;
  filter: drop-shadow(0 8px 16px rgba(0,0,0,0.15));
  transition: transform 0.3s ease;
}

.nav-card:hover .card-icon {
  transform: scale(1.1) rotate(5deg);
}

.card-content {
  padding: 2.5rem;
  text-align: center;
}

.nav-card h2 {
  font-size: 2.2rem;
  font-weight: 700;
  margin-bottom: 1rem;
  color: #2c3e50;
  letter-spacing: -0.01em;
}

.nav-card p {
  font-size: 1.2rem;
  color: #5a6c7d;
  margin-bottom: 1.5rem;
  line-height: 1.6;
  font-weight: 400;
}

.card-features {
  display: flex;
  gap: 0.8rem;
  justify-content: center;
  margin-bottom: 2rem;
  flex-wrap: wrap;
}

.feature-tag {
  background: linear-gradient(135deg, rgba(102,126,234,0.1) 0%, rgba(118,75,162,0.1) 100%);
  color: #667eea;
  padding: 0.4rem 1rem;
  border-radius: 20px;
  font-size: 0.85rem;
  font-weight: 500;
  border: 1px solid rgba(102,126,234,0.2);
}

.nav-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 14px 32px;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  text-decoration: none;
  border-radius: 28px;
  font-weight: 600;
  font-size: 1rem;
  transition: all 0.3s ease;
  border: none;
  cursor: pointer;
  position: relative;
  overflow: hidden;
}

.nav-btn::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
  transition: left 0.5s;
}

.nav-btn:hover::before {
  left: 100%;
}

.nav-btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 12px 24px rgba(102, 126, 234, 0.4);
}

.btn-arrow {
  transition: transform 0.3s ease;
}

.nav-btn:hover .btn-arrow {
  transform: translateX(4px);
}

.floating-shapes {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  z-index: 0;
}

.shape {
  position: absolute;
  border-radius: 50%;
  background: rgba(255,255,255,0.1);
  animation: float 6s ease-in-out infinite;
}

.shape-1 {
  width: 80px;
  height: 80px;
  top: 20%;
  left: 10%;
  animation-delay: 0s;
}

.shape-2 {
  width: 120px;
  height: 120px;
  top: 60%;
  right: 10%;
  animation-delay: 2s;
}

.shape-3 {
  width: 60px;
  height: 60px;
  bottom: 20%;
  left: 20%;
  animation-delay: 4s;
}

@keyframes float {
  0%, 100% {
    transform: translateY(0px) rotate(0deg);
  }
  50% {
    transform: translateY(-20px) rotate(180deg);
  }
}

.footer {
  text-align: center;
  color: rgba(255,255,255,0.8);
  font-size: 1rem;
  margin-top: 2rem;
}

@media (max-width: 1200px) {
  .container {
    padding: 2rem 3rem;
  }

  .hero-title {
    font-size: 4rem;
  }

  .nav-grid {
    gap: 2rem;
  }
}

@media (max-width: 768px) {
  .container {
    padding: 1.5rem 2rem;
  }

  .hero-title {
    font-size: 3rem;
  }

  .hero-subtitle {
    font-size: 1.2rem;
  }

  .nav-grid {
    grid-template-columns: 1fr;
    gap: 2rem;
  }

  .nav-card {
    margin: 0 1rem;
  }

  .card-content {
    padding: 2rem;
  }

  .nav-card h2 {
    font-size: 1.8rem;
  }

  .nav-card p {
    font-size: 1.1rem;
  }

  .card-icon {
    font-size: 4rem;
  }
}

@media (max-width: 480px) {
  .container {
    padding: 1rem;
  }

  .hero-title {
    font-size: 2.5rem;
  }

  .nav-card {
    margin: 0 0.5rem;
  }
}
</style>
