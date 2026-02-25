<div align="center">
  <!-- Your avatar with futuristic neon + glitch wrapper -->
  <div style="
    position: relative;
    width: 180px;
    height: 180px;
    margin: 20px auto;
    border-radius: 50%;
    overflow: hidden;
    box-shadow: 
      0 0 20px #00f0ff,
      0 0 40px #ff00aa,
      inset 0 0 30px rgba(0, 240, 255, 0.4);
    border: 3px solid #00f0ff;
    animation: pulse 4s infinite alternate, glitch-border 6s infinite;
  ">
    <img 
      src="https://avatars.githubusercontent.com/u/104215351?v=4" 
      alt="SaHor Avatar" 
      width="180" 
      height="180"
      style="width:100%; height:100%; object-fit: cover;"
    />
    <!-- Optional overlay glitch/scanline effect -->
    <div style="
      position: absolute;
      inset: 0;
      background: linear-gradient(
        transparent 0%,
        rgba(255,0,170,0.08) 50%,
        transparent 100%
      );
      pointer-events: none;
      animation: scanline 8s linear infinite;
    "></div>
  </div>

  <h1 style="
    font-size: 3.5em;
    background: linear-gradient(90deg, #00f0ff, #ff00aa, #39ff14);
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    text-shadow: 0 0 15px #00f0ff;
    font-family: 'Courier New', monospace;
    letter-spacing: 5px;
    animation: glitch 5s infinite;
  ">
    SAHOR — SISHIR DEVKOTA
  </h1>

  <p style="font-size: 1.5em; color: #00ffcc; text-shadow: 0 0 10px #00ffcc;">
    <span style="color:#ff00aa;">AI</span> Architect • 
    <span style="color:#ffff00;">Trading Intelligence</span> Engineer • 
    <span style="color:#39ff14;">Automation Futurist</span>
  </p>
</div>

<!-- Add these keyframes to your <style> block (or keep the previous ones) -->
<style>
  @keyframes pulse {
    0% { box-shadow: 0 0 20px #00f0ff, 0 0 40px #ff00aa; }
    100% { box-shadow: 0 0 40px #00f0ff, 0 0 80px #ff00aa; }
  }
  @keyframes scanline {
    0% { transform: translateY(-100%); }
    100% { transform: translateY(100%); }
  }
  @keyframes glitch-border {
    0%, 100% { border-color: #00f0ff; }
    20% { border-color: #ff00aa; }
    40% { border-color: #39ff14; }
    60% { border-color: #ffff00; }
  }
</style>
