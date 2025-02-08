# 🌌 Welcome to My Universe! 🚀

## Hi 👋! I'm Ismail, a Front-End Developer specializing in Angular and modern web technologies.

---

### 🪐 About Me
Passionate about building interactive and visually stunning web applications. I love exploring the latest technologies and bringing ideas to life with beautiful UI/UX.

---

### 🌍 Skills
<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="50" alt="HTML5"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="50" alt="CSS3"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="50" alt="JavaScript"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="50" alt="TypeScript"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angular/angular-original.svg" height="50" alt="Angular"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" height="50" alt="Bootstrap"/>
</div>

---

### 🛰️ Projects
- 🚀 **[Project Name]** - A futuristic web app inspired by space exploration.
- 🌌 **[Project Name]** - A dynamic, interactive UI with planetary animations.

---

### ✨ Animated Solar System (Real 3D Planets!)
<div align="center">
  <canvas id="solar-system"></canvas>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
  <script>
    const scene = new THREE.Scene();
    const camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
    const renderer = new THREE.WebGLRenderer({ alpha: true });
    renderer.setSize(300, 300);
    document.getElementById("solar-system").appendChild(renderer.domElement);
    
    const geometry = new THREE.SphereGeometry(2, 32, 32);
    const material = new THREE.MeshBasicMaterial({ map: new THREE.TextureLoader().load('https://upload.wikimedia.org/wikipedia/commons/9/97/The_Earth_seen_from_Apollo_17.jpg') });
    const planet = new THREE.Mesh(geometry, material);
    scene.add(planet);
    
    camera.position.z = 5;
    
    function animate() {
      requestAnimationFrame(animate);
      planet.rotation.y += 0.01;
      renderer.render(scene, camera);
    }
    animate();
  </script>
</div>

---

### 💊 GitHub Stats
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=IsmailAshraf111&show_icons=true&theme=dracula" height="150" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=IsmailAshraf111&theme=dracula" height="150" alt="GitHub Streak" />
</div>

---

### 🌠 Let's Connect!
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/ismailashraf111/)
[![Twitter](https://img.shields.io/badge/Twitter-Follow-blue?style=flat&logo=twitter)](https://twitter.com/ismailashraf111)

---

*🚀 Keep looking up at the stars and keep coding! 💻✨*
