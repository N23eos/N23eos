<svg width="500" height="300" viewBox="0 0 500 300" xmlns="http://www.w3.org/2000/svg">
    <!-- Monitor -->
    <rect x="100" y="50" width="300" height="200" fill="black" stroke="gray" stroke-width="5"/>
    <rect x="110" y="60" width="280" height="180" fill="#222"/>
    
    <!-- Animated Code -->
    <text id="codeText" x="120" y="80" font-family="monospace" font-size="16" fill="lime">
        > Initializing...
    </text>
    
    <!-- Stand -->
    <rect x="210" y="250" width="80" height="10" fill="gray"/>
    <rect x="230" y="260" width="40" height="10" fill="gray"/>
    
    <!-- Animation -->
    <script>
        <![CDATA[
        let lines = [
            "> Booting system...",
            "> Loading repositories...",
            "> Fetching commits...",
            "> Deploying...",
            "> Hello, GitHub!"
        ];
        let index = 0;
        function updateText() {
            let textElement = document.getElementById("codeText");
            textElement.textContent = lines[index];
            index = (index + 1) % lines.length;
            setTimeout(updateText, 1500);
        }
        updateText();
        ]]>
    </script>
</svg>




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
