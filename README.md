<script>
<canvas id="matrix"></canvas>

<style>
  body {
    margin: 0;
    overflow: hidden;
    background: black;
  }
  canvas {
    display: block;
  }
</style>

<script>
  const canvas = document.getElementById("matrix");
  const ctx = canvas.getContext("2d");
  canvas.width = window.innerWidth;
  canvas.height = window.innerHeight;
  const letters = "01";
  const matrix = [];
  for (let i = 0; i < canvas.width / 10; i++) {
    matrix[i] = Math.random() * canvas.height;
  }

  function draw() {
    ctx.fillStyle = "rgba(0, 0, 0, 0.05)";
    ctx.fillRect(0, 0, canvas.width, canvas.height);
    ctx.fillStyle = "#0F0";
    ctx.font = "15px monospace";
    for (let i = 0; i < matrix.length; i++) {
      const text = letters.charAt(Math.floor(Math.random() * letters.length));
      ctx.fillText(text, i * 10, matrix[i]);
      matrix[i] += 15;
      if (matrix[i] > canvas.height && Math.random() > 0.95) {
        matrix[i] = 0;
      }
    }
  }
  setInterval(draw, 50);
</script>





🌟 **About Me:**
- 🎯 Aspiring Python developer, passionate about technology and innovation.
- 🌱 Currently learning Python and exploring the world of programming.
- 💡 Interests include: cryptocurrency, computer technologies, cryptography, and philosophy.

---

🛠 **Skills:**
- Languages: Python (currently learning)
- Interests: Blockchain, Cryptography, AI, and Philosophy.

---

📈 **GitHub Stats:**

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=N23eos&show_icons=true&theme=radical)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=N23eos&layout=compact&theme=radical)

---

🚀 **Projects:**
- *Coming soon!* Stay tuned for my upcoming repositories and projects.

---

📫 **How to Reach Me:**
- [Telegram](https://t.me/N23eo)
- [Twitter](https://twitter.com/N23eo_n)
