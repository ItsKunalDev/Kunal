#!/bin/bash

# === Customize Your Details ===
NAME="Kunal Dev"
USERNAME="your-github-username"       # change this
TAGLINE="🚀 Final Year CSE | MERN Stack Enthusiast | GATE Aspirant | Problem Solver"
EMAIL="your.email@example.com"
LINKEDIN="https://linkedin.com/in/your-linkedin"
PORTFOLIO="https://your-portfolio.com"

# === Create README.md ===
cat <<EOF > README.md
<h1 align="center">Hi there 👋, I'm $NAME</h1>
<h3 align="center">$TAGLINE</h3>

<p align="center">
  <a href="$LINKEDIN">
    <img src="https://img.shields.io/badge/LinkedIn-blue?logo=linkedin&style=for-the-badge" />
  </a>
  <a href="mailto:$EMAIL">
    <img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white&style=for-the-badge" />
  </a>
  <a href="$PORTFOLIO">
    <img src="https://img.shields.io/badge/Portfolio-000000?logo=github&style=for-the-badge" />
  </a>
</p>

---

🧑‍💻 **About Me:**

- 🎓 Final year B.Tech CSE student at VIT Bhopal  
- 💡 I love building front-end experiences using the MERN stack  
- 🧠 Always exploring Data Structures, Algorithms, and competitive programming  
- 🎯 Currently preparing for GATE 2025  
- 🌱 Learning TypeScript & System Design  

---

🛠️ **Tech Stack & Tools:**

<p align="left">
  <img src="https://img.shields.io/badge/C++-00599C?logo=c%2B%2B&logoColor=white&style=flat-square" />
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat-square" />
  <img src="https://img.shields.io/badge/Java-007396?logo=java&logoColor=white&style=flat-square" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white&style=flat-square" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white&style=flat-square" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat-square" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white&style=flat-square" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white&style=flat-square" />
  <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white&style=flat-square" />
</p>

---

📈 **GitHub Stats:**

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=$USERNAME&show_icons=true&theme=tokyonight" alt="stats" />
  <br>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=$USERNAME&theme=tokyonight" alt="streak" />
  <br>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=$USERNAME&layout=compact&theme=tokyonight" alt="languages" />
</p>

---

🧠 **Fun Fact:**
> I'm not a magician, but I can turn *coffee ☕* into *code 💻*.

---

⭐️ *Thanks for stopping by! Feel free to connect with me.*

EOF

echo "🔥 Creative README.md generated successfully!"
