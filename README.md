<div align="center">
  <!-- Interactive Running Cat -->
  <div id="cat-container" style="position:relative; height:120px; width:100%; max-width:800px; overflow:hidden; margin:20px auto; background:linear-gradient(transparent,#0D1117); border-radius:12px;">
    <div id="cat" style="position:absolute; font-size:60px; cursor:pointer; transition:transform 0.3s; left:10%; animation:run 4s linear infinite;">
      🐈
    </div>
  </div>

  <script>
    const cat = document.getElementById('cat');
    let direction = 1;
    let pos = 10;
    
    function animateCat() {
      pos += direction * 2;
      if (pos >= 85 || pos <= 5) direction *= -1;
      cat.style.left = pos + '%';
      cat.style.transform = `scaleX(${direction})`;
    }
    
    setInterval(animateCat, 50);
    
    // Interactive: Click to jump!
    cat.addEventListener('click', () => {
      cat.style.transform = `scaleX(${direction}) scaleY(0.6) translateY(-30px)`;
      setTimeout(() => {
        cat.style.transform = `scaleX(${direction})`;
      }, 300);
    });
  </script>

  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=38&duration=2500&pause=600&color=00FFAA&center=true&vCenter=true&width=800&lines=👋+Hello+World!;I'm+Rakibul+Hasan;Senior+Full-Stack+Developer;197+Commits+in+June+2026;Crafting+Scalable+Web+Magic+%F0%9F%9A%80" alt="Typing Animation" />
  
  <br>
  
  <img height="220" src="https://github-readme-stats.vercel.app/api?username=rbkhan007&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=00FFAA&icon_color=FF00AA&text_color=FFFFFF" />
  <img height="220" src="https://github-readme-streak-stats.herokuapp.com/?user=rbkhan007&theme=radical&hide_border=true&background=0D1117&stroke=00FFAA&ring=FF00AA&fire=00FFAA" />
</div>

---

<div align="center">
  <h2>🚀 About Me</h2>
</div>

**Senior Full-Stack Engineer** from Dhaka, Bangladesh.  
I build **production-ready**, high-performance web applications. Passionate about clean code, real-time systems, performance optimization, and **bug fixing**.

- 🔥 **June 2026 Momentum**: **197 commits** across 5 repositories
- 🔧 Strong focus on **bug fixing, optimization & rapid delivery**
- 💼 Open to **full-time Senior Full-Stack roles**

---

<div align="center">
  <h2>🛠️ Tech Arsenal</h2>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Next.js-000000?logo=next.js&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwind-css&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=for-the-badge" />
</div>

---

<div align="center">
  <h2>📊 Skills Progress</h2>
</div>

<div align="center">

**Next.js**  
<div style="background:#333; height:12px; border-radius:10px; width:100%; max-width:500px; margin:8px auto;">
  <div style="background:linear-gradient(90deg,#00FFAA,#00CC88); height:12px; border-radius:10px; width:95%;"></div>
</div>
95%

**TypeScript**  
<div style="background:#333; height:12px; border-radius:10px; width:100%; max-width:500px; margin:8px auto;">
  <div style="background:linear-gradient(90deg,#00FFAA,#00CC88); height:12px; border-radius:10px; width:90%;"></div>
</div>
90%

**Tailwind CSS**  
<div style="background:#333; height:12px; border-radius:10px; width:100%; max-width:500px; margin:8px auto;">
  <div style="background:linear-gradient(90deg,#00FFAA,#00CC88); height:12px; border-radius:10px; width:98%;"></div>
</div>
98%

**Supabase + PostgreSQL**  
<div style="background:#333; height:12px; border-radius:10px; width:100%; max-width:500px; margin:8px auto;">
  <div style="background:linear-gradient(90deg,#00FFAA,#00CC88); height:12px; border-radius:10px; width:92%;"></div>
</div>
92%

**Prisma ORM**  
<div style="background:#333; height:12px; border-radius:10px; width:100%; max-width:500px; margin:8px auto;">
  <div style="background:linear-gradient(90deg,#00FFAA,#00CC88); height:12px; border-radius:10px; width:88%;"></div>
</div>
88%

**Bug Fixing & Optimization**  
<div style="background:#333; height:12px; border-radius:10px; width:100%; max-width:500px; margin:8px auto;">
  <div style="background:linear-gradient(90deg,#FF00AA,#CC0088); height:12px; border-radius:10px; width:97%;"></div>
</div>
97%

</div>

---

<div align="center">
  <h2>🔥 June 2026 Activity Highlights</h2>
</div>

- **197 Commits** in 5 repositories
- Heavy focus on **bug fixing**, feature development & performance

**Top Repos**:
- [Nexus-Crypto-Ventory](https://github.com/rbkhan007/Nexus-Crypto-Ventory) — 74 commits
- [Rag-Optimized-F-Commerce-SAAS](https://github.com/rbkhan007/Rag-Optimized-F-Commerce-SAAS) — 54 commits
- [VeloCommerce-AI](https://github.com/rbkhan007/VeloCommerce-AI) — 40 commits

![Contribution Graph](https://github-readme-activity-graph.vercel.app/graph?username=rbkhan007&theme=radical&hide_border=true&bg_color=0D1117&color=00FFAA)

---

<div align="center">
  <h2>🌟 Featured Projects</h2>
</div>

<table align="center" style="width:100%; max-width:800px;">
  <tr>
    <td align="center"><a href="https://velo-commerce-ai.vercel.app/"><strong>VeloCommerce AI</strong></a><br>AI-Powered E-commerce</td>
    <td align="center"><a href="https://nexus-crypto-ventory.vercel.app/"><strong>Nexus Crypto Ventory</strong></a><br>Crypto Portfolio Tool</td>
    <td align="center"><a href="https://rhasan-dev-bd-com.vercel.app/"><strong>Rhasan Portfolio</strong></a><br>Modern Showcase</td>
  </tr>
</table>

---

<div align="center">
  <h2>📬 Let's Connect</h2>
</div>

<div align="center">
  <a href="https://rhasan-dev-bd-com.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-FF00AA?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/your-linkedin-profile/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://twitter.com/Rakibulhas35269">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" />
  </a>
</div>

<br>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=rbkhan007&label=Profile%20Views&color=00FFAA&style=for-the-badge" />
</div>

---

*Made with ❤️, ☕ & consistent commits in Dhaka, Bangladesh*  
**"Clean code + Relentless bug fixing = Exceptional products"** 🐈‍⬛
