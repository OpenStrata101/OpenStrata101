<style>
  .neon { color: #6495ED; text-shadow: 0 0 5px #6495ED, 0 0 10px #6495ED; }
  .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(120px, 1fr)); gap: 15px; }
  .card { background: rgba(255,255,255,0.05); padding: 20px; border-radius: 10px; transition: transform 0.3s; }
  .card:hover { transform: translateY(-5px); }
  .icon { filter: drop-shadow(0 0 5px #6495ED); }
  .stat { background: rgba(255,255,255,0.03); border-radius: 10px; padding: 15px; }
</style>

<div align="center" style="background: #0D1117; color: white; padding: 30px; min-height: 100vh;">
  <!-- Banner -->
  <img src="https://i.postimg.cc/NjJxbP6H/20250220-143912.png" width="100%" style="border-radius: 10px;">
  
  <!-- Greeting -->
  <h1 class="neon">Rakib 🌌</h1>
  <p style="color: #6495ED;">Cross-dimensional developer</p>

  <!-- Quick Stats -->
  <div class="grid" style="max-width: 800px; margin: 30px auto;">
    <div class="stat">
      <img src="https://komarev.com/ghpvc/?username=OpenStrata101&color=blueviolet&style=flat-square" width="100%">
    </div>
    <div class="stat">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=OpenStrata101&theme=dark&background=0D1117" width="100%">
    </div>
  </div>

  <!-- Skills Matrix -->
  <h2 class="neon">Skill Nodes</h2>
  <div class="grid" style="max-width: 1000px; margin: 30px auto;">
    <div class="card">
      <img class="icon" src="https://skillicons.dev/icons?i=c" height="40">
      <p>Systems Programming</p>
    </div>
    <div class="card">
      <img class="icon" src="https://skillicons.dev/icons?i=dart,flutter" height="40">
      <p>Cross-platform</p>
    </div>
    <div class="card">
      <img class="icon" src="https://skillicons.dev/icons?i=linux,arch" height="40">
      <p>Linux Wizardry</p>
    </div>
    <div class="card">
      <img class="icon" src="https://skillicons.dev/icons?i=git,vscode" height="40">
      <p>DevOps Tools</p>
    </div>
    <div class="card">
      <img class="icon" src="https://skillicons.dev/icons?i=figma" height="40">
      <p>UI/UX Design</p>
    </div>
  </div>

  <!-- Connect -->
  <h2 class="neon">Portals</h2>
  <div class="grid" style="max-width: 400px; margin: 30px auto;">
    <a href="https://github.com/OpenStrata101" class="card">
      <img src="https://skillicons.dev/icons?i=github" height="40">
    </a>
    <a href="#" class="card">
      <img src="https://skillicons.dev/icons?i=gitlab" height="40">
    </a>
    <a href="#" class="card">
      <img src="https://skillicons.dev/icons?i=instagram" height="40">
    </a>
  </div>

  <!-- Footer -->
  <div style="position: fixed; bottom: 20px; width: 100%;">
    <p class="neon" style="font-size: 12px;">⚡ Powered by starlight</p>
  </div>
</div>
