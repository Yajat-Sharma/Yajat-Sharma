
<style>
@import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&family=JetBrains+Mono:wght@300;400;500&display=swap');
*{box-sizing:border-box;margin:0;padding:0;}
.rw{font-family:'Space Grotesk',sans-serif;color:var(--color-text-primary);max-width:680px;padding:8px 0 24px;}
.mono{font-family:'JetBrains Mono',monospace;}
.acc{color:#F5C842;}
.acc2{color:#5DCAA5;}
.dim{color:var(--color-text-secondary);}
.hero{padding:28px 0 20px;border-bottom:0.5px solid var(--color-border-tertiary);}
.hero-top{display:flex;align-items:flex-start;justify-content:space-between;gap:16px;}
.hero-left{}
.status-dot{display:inline-block;width:7px;height:7px;border-radius:50%;background:#5DCAA5;margin-right:7px;vertical-align:2px;}
.status-line{font-family:'JetBrains Mono',monospace;font-size:11px;color:var(--color-text-tertiary);margin-bottom:10px;}
.name{font-size:38px;font-weight:700;letter-spacing:-1px;line-height:1.05;margin-bottom:6px;}
.tagline{font-size:13px;font-family:'JetBrains Mono',monospace;color:var(--color-text-secondary);line-height:1.6;max-width:380px;margin-bottom:14px;}
.badge-row{display:flex;flex-wrap:wrap;gap:6px;}
.badge{font-family:'JetBrains Mono',monospace;font-size:10px;padding:3px 10px;border-radius:4px;border:0.5px solid var(--color-border-secondary);color:var(--color-text-secondary);}
.badge.y{border-color:#854F0B;color:#F5C842;background:#412402;}
.badge.g{border-color:#0F6E56;color:#5DCAA5;background:#04342C;}
.badge.p{border-color:#534AB7;color:#AFA9EC;background:#26215C;}
.hero-right{flex-shrink:0;}
.avatar{width:72px;height:72px;border-radius:12px;background:#1a1a2e;border:1px solid var(--color-border-secondary);display:flex;align-items:center;justify-content:center;font-size:26px;font-weight:700;color:#F5C842;font-family:'Space Grotesk',sans-serif;letter-spacing:-1px;}
.sec{margin-top:22px;}
.sec-head{display:flex;align-items:center;gap:10px;margin-bottom:12px;}
.sec-head .label{font-family:'JetBrains Mono',monospace;font-size:10px;font-weight:500;letter-spacing:0.13em;text-transform:uppercase;color:var(--color-text-tertiary);white-space:nowrap;}
.sec-head::after{content:'';flex:1;height:0.5px;background:var(--color-border-tertiary);}
.about-box{background:var(--color-background-secondary);border-radius:10px;padding:16px 20px;border-left:2px solid #F5C842;border-top:0.5px solid var(--color-border-tertiary);border-right:0.5px solid var(--color-border-tertiary);border-bottom:0.5px solid var(--color-border-tertiary);border-top-left-radius:0;border-bottom-left-radius:0;}
.about-box p{font-size:13px;font-family:'JetBrains Mono',monospace;color:var(--color-text-secondary);line-height:1.8;}
.about-box strong{color:var(--color-text-primary);}
.project-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;}
.pc{background:var(--color-background-secondary);border-radius:10px;border:0.5px solid var(--color-border-tertiary);padding:16px 18px;transition:border-color 0.2s;}
.pc:hover{border-color:var(--color-border-secondary);}
.pc-top{display:flex;align-items:flex-start;justify-content:space-between;margin-bottom:6px;}
.pc-title{font-size:14px;font-weight:600;color:var(--color-text-primary);}
.pc-live{font-family:'JetBrains Mono',monospace;font-size:9px;padding:2px 7px;border-radius:3px;background:#04342C;color:#5DCAA5;border:0.5px solid #0F6E56;}
.pc-desc{font-family:'JetBrains Mono',monospace;font-size:11px;color:var(--color-text-secondary);line-height:1.6;margin-bottom:10px;}
.pc-tags{display:flex;flex-wrap:wrap;gap:4px;}
.pt{font-family:'JetBrains Mono',monospace;font-size:9px;padding:2px 7px;border-radius:3px;background:var(--color-background-primary);border:0.5px solid var(--color-border-tertiary);color:var(--color-text-tertiary);}
.stack-section{}
.stack-group{margin-bottom:14px;}
.sg-label{font-family:'JetBrains Mono',monospace;font-size:10px;color:var(--color-text-tertiary);margin-bottom:6px;display:flex;align-items:center;gap:6px;}
.sg-label::before{content:'›';color:#F5C842;}
.pill-row{display:flex;flex-wrap:wrap;gap:5px;}
.pill{font-family:'JetBrains Mono',monospace;font-size:11px;padding:4px 12px;border-radius:5px;background:var(--color-background-secondary);border:0.5px solid var(--color-border-tertiary);color:var(--color-text-secondary);}
.pill.core{background:#412402;color:#F5C842;border-color:#854F0B;}
.pill.tool{background:#26215C;color:#AFA9EC;border-color:#534AB7;}
.interest-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;}
.int-card{background:var(--color-background-secondary);border-radius:8px;border:0.5px solid var(--color-border-tertiary);padding:12px 14px;text-align:center;}
.int-icon{font-size:18px;margin-bottom:5px;}
.int-label{font-family:'JetBrains Mono',monospace;font-size:10px;color:var(--color-text-secondary);}
.stats-note{background:var(--color-background-secondary);border-radius:10px;border:0.5px solid var(--color-border-tertiary);padding:14px 18px;}
.stats-note p{font-family:'JetBrains Mono',monospace;font-size:11px;color:var(--color-text-tertiary);margin-bottom:8px;}
.stats-note code{font-family:'JetBrains Mono',monospace;font-size:10px;color:var(--color-text-secondary);display:block;line-height:2.2;}
.connect-row{display:flex;gap:8px;flex-wrap:wrap;}
.cb{display:inline-flex;align-items:center;gap:7px;font-family:'JetBrains Mono',monospace;font-size:11px;padding:8px 16px;border-radius:7px;border:0.5px solid var(--color-border-secondary);background:var(--color-background-secondary);color:var(--color-text-primary);text-decoration:none;cursor:pointer;}
.cb:hover{border-color:#F5C842;color:#F5C842;}
.cb i{font-size:15px;}
.footer{margin-top:24px;padding-top:16px;border-top:0.5px solid var(--color-border-tertiary);display:flex;align-items:center;justify-content:space-between;}
.footer-left{font-family:'JetBrains Mono',monospace;font-size:10px;color:var(--color-text-tertiary);}
.footer-right{display:flex;gap:14px;}
.flink{font-family:'JetBrains Mono',monospace;font-size:10px;color:var(--color-text-tertiary);}
</style>

<div class="rw">
  <h2 style="position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0,0,0,0)">Yajat Sharma — GitHub Profile README</h2>

  <div class="hero">
    <div class="hero-top">
      <div class="hero-left">
        <p class="status-line mono"><span class="status-dot"></span>available for internships &amp; collabs</p>
        <h1 class="name">Yajat <span class="acc">Sharma</span></h1>
        <p class="tagline">Full-Stack Engineer &amp; aspiring Data Scientist.<br>Building India-scale products from <span class="acc">Mumbai</span> 📍</p>
        <div class="badge-row">
          <span class="badge y">📍 Mumbai, India</span>
          <span class="badge g">2nd Year · Engineering</span>
          <span class="badge p">Open to Internships</span>
          <span class="badge">Building in Public</span>
        </div>
      </div>
      <div class="hero-right">
        <div class="avatar">YS</div>
      </div>
    </div>
  </div>

  <div class="sec">
    <div class="sec-head"><span class="label">whoami</span></div>
    <div class="about-box">
      <p>I build <strong>production-grade full-stack apps</strong> and <strong>multi-agent AI pipelines</strong>. My focus is India-scale problems — hyperlocal services, ed-tech, and automation tools that actually work at ground level. I care deeply about clean architecture, real-world impact, and shipping things people use.<br><br>Currently exploring data engineering as a career path — obsessed with pipelines, evidence fusion, and turning messy data into decisions.</p>
    </div>
  </div>

  <div class="sec">
    <div class="sec-head"><span class="label">currently shipping</span></div>
    <div class="project-grid">
      <div class="pc">
        <div class="pc-top">
          <span class="pc-title">LocalServices</span>
          <span class="pc-live">WIP</span>
        </div>
        <p class="pc-desc">Hyperlocal home-services booking platform for Maharashtra. Three-role system — customers, providers, admins. Real-time chat + live tracking.</p>
        <div class="pc-tags">
          <span class="pt">Next.js 15</span><span class="pt">PostgreSQL</span><span class="pt">Socket.io</span><span class="pt">Firebase</span><span class="pt">Prisma</span>
        </div>
      </div>
      <div class="pc">
        <div class="pc-top">
          <span class="pc-title">AI Exam Predictor</span>
          <span class="pc-live">WIP</span>
        </div>
        <p class="pc-desc">Multi-agent n8n pipeline predicting Mumbai University exam topics. 4 parallel research agents + evidence fusion. Weighted confidence scoring.</p>
        <div class="pc-tags">
          <span class="pt">Llama 3.3 70B</span><span class="pt">n8n</span><span class="pt">Groq</span><span class="pt">RAG</span>
        </div>
      </div>
    </div>
  </div>

  <div class="sec">
    <div class="sec-head"><span class="label">tech stack</span></div>
    <div class="stack-section">
      <div class="stack-group">
        <p class="sg-label">languages</p>
        <div class="pill-row">
          <span class="pill core">Python</span>
          <span class="pill core">JavaScript</span>
          <span class="pill core">C++</span>
          <span class="pill">HTML / CSS</span>
          <span class="pill">Bash</span>
        </div>
      </div>
      <div class="stack-group">
        <p class="sg-label">frontend &amp; backend</p>
        <div class="pill-row">
          <span class="pill core">Next.js 15</span>
          <span class="pill core">React 19</span>
          <span class="pill">Tailwind CSS</span>
          <span class="pill">Node.js</span>
          <span class="pill">FastAPI</span>
          <span class="pill">Express</span>
          <span class="pill">Prisma</span>
        </div>
      </div>
      <div class="stack-group">
        <p class="sg-label">data &amp; infra</p>
        <div class="pill-row">
          <span class="pill">PostgreSQL</span>
          <span class="pill">MongoDB</span>
          <span class="pill">Docker</span>
          <span class="pill">Firebase</span>
          <span class="pill">Groq API</span>
          <span class="pill">Cloudinary</span>
        </div>
      </div>
      <div class="stack-group">
        <p class="sg-label">tools &amp; automation</p>
        <div class="pill-row">
          <span class="pill tool">n8n</span>
          <span class="pill tool">Git</span>
          <span class="pill tool">GitHub</span>
          <span class="pill tool">Postman</span>
          <span class="pill tool">Figma</span>
          <span class="pill tool">VS Code</span>
          <span class="pill tool">OBS Studio</span>
        </div>
      </div>
    </div>
  </div>

  <div class="sec">
    <div class="sec-head"><span class="label">currently learning</span></div>
    <div class="interest-grid">
      <div class="int-card"><div class="int-icon">⚙️</div><p class="int-label">DSA &amp; Algorithms</p></div>
      <div class="int-card"><div class="int-icon">🧠</div><p class="int-label">Multi-Agent AI</p></div>
      <div class="int-card"><div class="int-icon">📊</div><p class="int-label">Data Engineering</p></div>
      <div class="int-card"><div class="int-icon">🏗️</div><p class="int-label">System Design</p></div>
      <div class="int-card"><div class="int-icon">📐</div><p class="int-label">Graph Theory</p></div>
      <div class="int-card"><div class="int-icon">🚀</div><p class="int-label">CI/CD &amp; DevOps</p></div>
    </div>
  </div>

  <div class="sec">
    <div class="sec-head"><span class="label">github stats</span></div>
    <div class="stats-note">
      <p>↳ paste these into your README.md — they render as live widgets</p>
      <code>
        ![stats](https://github-readme-stats.vercel.app/api?username=Yajat-Sharma&theme=tokyonight&hide_border=true&show_icons=true&bg_color=0d1117&title_color=F5C842&icon_color=5DCAA5)<br>
        ![langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Yajat-Sharma&theme=tokyonight&hide_border=true&layout=compact&bg_color=0d1117&title_color=F5C842)<br>
        ![streak](https://streak-stats.demolab.com?user=Yajat-Sharma&theme=tokyonight&hide_border=true&background=0d1117&ring=F5C842&fire=5DCAA5&currStreakLabel=F5C842)
      </code>
    </div>
  </div>

  <div class="sec">
    <div class="sec-head"><span class="label">connect</span></div>
    <div class="connect-row">
      <a class="cb" href="https://linkedin.com/in/yajat-sharma2006" target="_blank"><i class="ti ti-brand-linkedin" aria-hidden="true"></i>LinkedIn</a>
      <a class="cb" href="mailto:yajats@gmail.com"><i class="ti ti-mail" aria-hidden="true"></i>Email</a>
      <a class="cb" href="https://github.com/Yajat-Sharma" target="_blank"><i class="ti ti-brand-github" aria-hidden="true"></i>GitHub</a>
    </div>
  </div>

  <div class="footer">
    <span class="footer-left mono">// open to internships · data science · full-stack · building cool stuff</span>
  </div>
</div>
