<h1 align="center">
  <span style="display: inline-block; animation: bounce 2s infinite;">👋</span> 
  Hey there, I'm <span class="gradient-text">Ayush Raj</span>
</h1>

<p align="center" style="font-size: 1.2em;">
  <span class="typing-animation">🚀 Aspiring </span>
  <strong class="pulse-animation">AI/ML Engineer</strong> 
  • <span class="typing-animation" style="animation-delay: 0.5s;">💻 Tech Explorer</span> 
  • <span class="typing-animation" style="animation-delay: 1s;">🔍 Curious Mind</span>
</p>

---

### 🧠 <span class="section-title">Who Am I?</span>

<div class="floating-card">
  <ul style="list-style-type: none; padding-left: 20px;">
    <li>🤖 <span class="highlight">Machine Learning enthusiast</span> turning ideas into intelligent systems</li>
    <li>🔭 Currently <span class="highlight">learning and building</span> practical ML models</li>
    <li>🌱 Always <span class="highlight">leveling up</span> my skills through hands-on projects</li>
    <li>💬 Love to <span class="highlight">connect</span> with like-minded folks and exchange ideas</li>
    <li>📫 Reach out on <a href="https://www.linkedin.com/in/ayushraj1104" class="social-link">LinkedIn</a></li>
  </ul>
</div>

---

### 🚀 <span class="section-title">Tech Stack & Tools</span>

<div class="tech-stack">
  <div class="tech-icon" title="Python"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" class="rotate"/></div>
  <div class="tech-icon" title="C"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" class="float"/></div>
  <div class="tech-icon" title="C++"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" class="rotate"/></div>
  <div class="tech-icon" title="MySQL"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" class="float"/></div>
  <div class="tech-icon" title="Flask"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" class="rotate"/></div>
  <div class="tech-icon" title="NumPy"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" class="float"/></div>
  <div class="tech-icon" title="Pandas"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" class="rotate"/></div>
  <div class="tech-icon" title="Matplotlib"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" class="float"/></div>
  <div class="tech-icon" title="Scikit-learn"><img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" class="rotate"/></div>
</div>

---

<style>
  /* Animation Keyframes */
  @keyframes bounce {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-10px); }
  }
  
  @keyframes typing {
    from { width: 0 }
    to { width: 100% }
  }
  
  @keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.05); }
    100% { transform: scale(1); }
  }
  
  @keyframes float {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-5px); }
  }
  
  @keyframes rotate {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
  }
  
  @keyframes gradient {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  
  /* Styling Classes */
  .gradient-text {
    background: linear-gradient(90deg, #00b894, #00cec9, #0984e3);
    background-size: 200% auto;
    color: #0000;
    background-clip: text;
    -webkit-background-clip: text;
    animation: gradient 3s linear infinite;
    font-weight: bold;
  }
  
  .typing-animation {
    display: inline-block;
    overflow: hidden;
    white-space: nowrap;
    animation: typing 3.5s steps(40, end);
  }
  
  .pulse-animation {
    display: inline-block;
    animation: pulse 2s infinite;
  }
  
  .floating-card {
    background: rgba(255, 255, 255, 0.1);
    backdrop-filter: blur(5px);
    border-radius: 15px;
    padding: 20px;
    margin: 10px 0;
    transition: transform 0.3s;
  }
  
  .floating-card:hover {
    transform: translateY(-5px);
  }
  
  .highlight {
    background: linear-gradient(90deg, #00b894, #00cec9);
    background-size: 200% auto;
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
    font-weight: bold;
  }
  
  .social-link {
    color: #00b894;
    text-decoration: none;
    font-weight: bold;
    position: relative;
  }
  
  .social-link::after {
    content: '';
    position: absolute;
    width: 100%;
    height: 2px;
    bottom: 0;
    left: 0;
    background: #00b894;
    transform: scaleX(0);
    transition: transform 0.3s;
  }
  
  .social-link:hover::after {
    transform: scaleX(1);
  }
  
  .tech-stack {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 20px;
  }
  
  .tech-icon {
    transition: all 0.3s;
  }
  
  .tech-icon:hover {
    transform: scale(1.2);
  }
  
  .rotate {
    animation: rotate 10s linear infinite;
  }
  
  .float {
    animation: float 3s ease-in-out infinite;
  }
  
  .section-title {
    background: linear-gradient(90deg, #00b894, #00cec9);
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
    font-weight: bold;
  }
</style>
