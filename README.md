<div align="center">

<!-- START TERMINAL HEADER -->
<svg width="100%" height="200" viewBox="0 0 1000 200" xmlns="http://www.w3.org/2000/svg" style="max-width: 1000px; margin: 0 auto; display: block;">
  <defs>
    <linearGradient id="headerGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color: #1a1b2e; stop-opacity: 1" />
      <stop offset="50%" style="stop-color: #16161e; stop-opacity: 1" />
      <stop offset="100%" style="stop-color: #1a1b2e; stop-opacity: 1" />
    </linearGradient>
    <linearGradient id="accentGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color: #7aa2f7" />
      <stop offset="50%" style="stop-color: #bb9af7" />
      <stop offset="100%" style="stop-color: #73daca" />
    </linearGradient>
    <linearGradient id="lineGlow" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color: #7aa2f7; stop-opacity: 0" />
      <stop offset="50%" style="stop-color: #7aa2f7; stop-opacity: 0.6" />
      <stop offset="100%" style="stop-color: #7aa2f7; stop-opacity: 0" />
    </linearGradient>
  </defs>
  
  <!-- Terminal window frame -->
  <rect x="0" y="0" width="1000" height="200" rx="12" fill="url(#headerGrad)" stroke="#30363d" stroke-width="1.5"/>
  
  <!-- Title bar -->
  <rect x="0" y="0" width="1000" height="36" rx="12" fill="#16161e"/>
  <rect x="0" y="24" width="1000" height="12" fill="#16161e"/>
  
  <!-- Window controls -->
  <circle cx="22" cy="18" r="6" fill="#f7768e">
    <animate attributeName="opacity" values="0.7;1;0.7" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="44" cy="18" r="6" fill="#e0af68">
    <animate attributeName="opacity" values="0.7;1;0.7" dur="2s" begin="0.3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="66" cy="18" r="6" fill="#73daca">
    <animate attributeName="opacity" values="0.7;1;0.7" dur="2s" begin="0.6s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Title text -->
  <text x="500" y="24" text-anchor="middle" font-family="'Courier New', monospace" font-size="12" fill="#565f89">darshan@gen-ai-engineer:~/profile</text>
  
  <!-- Glowing line under terminal header -->
  <rect x="100" y="38" width="800" height="1.5" rx="1" fill="url(#lineGlow)">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="3s" repeatCount="indefinite"/>
  </rect>
  
  <!-- Prompt line 1 -->
  <text x="24" y="70" font-family="'Courier New', monospace" font-size="18" fill="#73daca" font-weight="bold">┌──(</text>
  <text x="65" y="70" font-family="'Courier New', monospace" font-size="18" fill="#7aa2f7" font-weight="bold">darshan</text>
  <text x="130" y="70" font-family="'Courier New', monospace" font-size="18" fill="#565f89">@</text>
  <text x="145" y="70" font-family="'Courier New', monospace" font-size="18" fill="#bb9af7" font-weight="bold">gen-ai-engineer</text>
  <text x="280" y="70" font-family="'Courier New', monospace" font-size="18" fill="#73daca" font-weight="bold">)</text>
  <text x="296" y="70" font-family="'Courier New', monospace" font-size="18" fill="#73daca" font-weight="bold">─</text>
  <text x="310" y="70" font-family="'Courier New', monospace" font-size="18" fill="#73daca" font-weight="bold">(</text>
  <text x="326" y="70" font-family="'Courier New', monospace" font-size="18" fill="#e0af68">~</text>
  <text x="342" y="70" font-family="'Courier New', monospace" font-size="18" fill="#73daca" font-weight="bold">)</text>
  
  <!-- Prompt line 2 -->
  <text x="24" y="105" font-family="'Courier New', monospace" font-size="18" fill="#73daca" font-weight="bold">└──[</text>
  <text x="80" y="105" font-family="'Courier New', monospace" font-size="18" fill="#7aa2f7">07-09-2026 12:00:00</text>
  <text x="280" y="105" font-family="'Courier New', monospace" font-size="18" fill="#73daca" font-weight="bold">]</text>
  <text x="296" y="105" font-family="'Courier New', monospace" font-size="18" fill="#73daca" font-weight="bold">━━━</text>
  <text x="335" y="105" font-family="'Courier New', monospace" font-size="18" fill="#73daca" font-weight="bold">▶</text>
  
  <!-- Blinking cursor -->
  <text x="355" y="105" font-family="'Courier New', monospace" font-size="18" fill="#73daca">
    ./build-intelligence.sh
    <animate attributeName="opacity" values="1;1;0;0" dur="2.5s" repeatCount="indefinite" keyTimes="0;0.7;0.72;1"/>
  </text>
  
  <!-- Output line (appears with delay) -->
  <text x="24" y="140" font-family="'Courier New', monospace" font-size="14" fill="#565f89">
    <animate attributeName="opacity" values="0;1" dur="0.5s" begin="2s" fill="freeze"/>
    [INFO] Initializing Darshan V S — Python / Gen AI Engineer
  </text>
  
  <!-- Output line 2 -->
  <text x="24" y="165" font-family="'Courier New', monospace" font-size="14" fill="#565f89">
    <animate attributeName="opacity" values="0;1" dur="0.5s" begin="3.5s" fill="freeze"/>
    [INFO] Architecting agentic AI systems · RAG pipelines · LLM-powered applications
  </text>
  
  <!-- Success badge -->
  <text x="24" y="190" font-family="'Courier New', monospace" font-size="14" fill="#73daca">
    <animate attributeName="opacity" values="0;1" dur="0.3s" begin="5s" fill="freeze"/>
    ✅ System ready — 3 production projects · 2 hackathons · 8+ tech stacks mastered
  </text>
</svg>
<!-- END TERMINAL HEADER -->

<br>

<!-- VISITOR COUNTER & SOCIAL PROOF BAR -->
<a href="https://github.com/Darshanvs0730">
  <img src="https://komarev.com/ghpvc/?username=Darshanvs0730&label=PROFILE+VISITS&color=7aa2f7&style=for-the-badge" alt="Profile Views" />
</a>
<a href="https://github.com/Darshanvs0730?tab=followers">
  <img src="https://img.shields.io/github/followers/Darshanvs0730?label=FOLLOWERS&style=for-the-badge&color=bb9af7&logo=github" alt="GitHub Followers" />
</a>
<a href="https://github.com/Darshanvs0730?tab=stars">
  <img src="https://img.shields.io/github/stars/Darshanvs0730?label=STARS&style=for-the-badge&color=e0af68&logo=star" alt="GitHub Stars" />
</a>
<a href="https://linkedin.com/in/Darshan-V-S">
  <img src="https://img.shields.io/badge/LINKEDIN-Let%27s%20Connect-7aa2f7?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="mailto:darshansunkanur999@gmail.com">
  <img src="https://img.shields.io/badge/EMAIL-Get%20In%20Touch-f7768e?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>

</div>

<br>

<!-- ===== ABOUT ME ===== -->
<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Laptop.png" width="32" />
  <b style="font-size: 22px; color: #7aa2f7; font-family: 'Courier New', monospace;">$ cat /proc/darshan/about</b>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Laptop.png" width="32" />
</div>

<br>

<!-- ABOUT ME SECTION -->
<table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td width="50%" valign="top" style="padding-right: 15px;">
      
<!-- Terminal Card -->
<svg width="100%" height="auto" viewBox="0 0 480 280" xmlns="http://www.w3.org/2000/svg" style="max-width: 480px;">
  <rect x="0" y="0" width="480" height="280" rx="10" fill="#161b22" stroke="#30363d" stroke-width="1"/>
  <rect x="0" y="0" width="480" height="28" rx="10" fill="#161b22"/>
  <rect x="0" y="18" width="480" height="10" fill="#161b22"/>
  <circle cx="14" cy="14" r="4.5" fill="#f7768e"/>
  <circle cx="28" cy="14" r="4.5" fill="#e0af68"/>
  <circle cx="42" cy="14" r="4.5" fill="#73daca"/>
  <text x="240" y="19" text-anchor="middle" font-family="sans-serif" font-size="10" fill="#565f89">about.sh</text>
  
  <text x="16" y="55" font-family="'Courier New', monospace" font-size="13" fill="#7aa2f7" font-weight="bold">darshan@gen-ai</text>
  <text x="140" y="55" font-family="'Courier New', monospace" font-size="13" fill="#565f89">:</text>
  <text x="148" y="55" font-family="'Courier New', monospace" font-size="13" fill="#73daca">~</text>
  <text x="160" y="55" font-family="'Courier New', monospace" font-size="13" fill="#565f89">$</text>
  <text x="176" y="55" font-family="'Courier New', monospace" font-size="13" fill="#c0caf5">cat about.txt</text>
  
  <text x="16" y="85" font-family="'Courier New', monospace" font-size="13" fill="#73daca">╔══════════════════════════════════════════╗</text>
  <text x="16" y="105" font-family="'Courier New', monospace" font-size="13" fill="#73daca">║</text>
  <text x="24" y="105" font-family="'Courier New', monospace" font-size="13" fill="#c0caf5">Name  : Darshan V S</text>
  <text x="400" y="105" font-family="'Courier New', monospace" font-size="13" fill="#73daca">║</text>
  <text x="16" y="125" font-family="'Courier New', monospace" font-size="13" fill="#73daca">║</text>
  <text x="24" y="125" font-family="'Courier New', monospace" font-size="13" fill="#c0caf5">Role  : Python / Gen AI Engineer</text>
  <text x="400" y="125" font-family="'Courier New', monospace" font-size="13" fill="#73daca">║</text>
  <text x="16" y="145" font-family="'Courier New', monospace" font-size="13" fill="#73daca">║</text>
  <text x="24" y="145" font-family="'Courier New', monospace" font-size="13" fill="#c0caf5">Motto : Architecting intelligence,</text>
  <text x="400" y="145" font-family="'Courier New', monospace" font-size="13" fill="#73daca">║</text>
  <text x="16" y="165" font-family="'Courier New', monospace" font-size="13" fill="#73daca">║</text>
  <text x="24" y="165" font-family="'Courier New', monospace" font-size="13" fill="#c0caf5">       one agent at a time.</text>
  <text x="400" y="165" font-family="'Courier New', monospace" font-size="13" fill="#73daca">║</text>
  <text x="16" y="185" font-family="'Courier New', monospace" font-size="13" fill="#73daca">╚══════════════════════════════════════════╝</text>

  <text x="16" y="220" font-family="'Courier New', monospace" font-size="12" fill="#565f89"># Education:</text>
  <text x="16" y="240" font-family="'Courier New', monospace" font-size="13" fill="#e0af68">  B.E. Computer Science & Engineering</text>
  <text x="16" y="260" font-family="'Courier New', monospace" font-size="12" fill="#565f89">  Jain College of Engineering · CGPA: 8.39 · 2022–2026</text>
</svg>

    </td>
    <td width="50%" valign="top" style="padding-left: 15px;">
      
<!-- Professional Philosophy Card -->
<svg width="100%" height="auto" viewBox="0 0 480 280" xmlns="http://www.w3.org/2000/svg" style="max-width: 480px;">
  <rect x="0" y="0" width="480" height="280" rx="10" fill="#161b22" stroke="#30363d" stroke-width="1"/>
  <rect x="0" y="0" width="480" height="28" rx="10" fill="#161b22"/>
  <rect x="0" y="18" width="480" height="10" fill="#161b22"/>
  <circle cx="14" cy="14" r="4.5" fill="#f7768e"/>
  <circle cx="28" cy="14" r="4.5" fill="#e0af68"/>
  <circle cx="42" cy="14" r="4.5" fill="#73daca"/>
  <text x="240" y="19" text-anchor="middle" font-family="sans-serif" font-size="10" fill="#565f89">philosophy.md</text>
  
  <text x="16" y="55" font-family="'Courier New', monospace" font-size="12" fill="#565f89"># Engineering Philosophy</text>
  
  <text x="16" y="80" font-family="'Courier New', monospace" font-size="12" fill="#c0caf5">I architect complex agentic AI systems, RAG pipelines,</text>
  <text x="16" y="100" font-family="'Courier New', monospace" font-size="12" fill="#c0caf5">and LLM-integrated REST APIs using prompt-engineered</text>
  <text x="16" y="120" font-family="'Courier New', monospace" font-size="12" fill="#c0caf5">workflows with FastAPI, LangChain, and LangGraph.</text>
  
  <text x="16" y="150" font-family="'Courier New', monospace" font-size="12" fill="#565f89"># What drives me:</text>
  
  <!-- Bullet points with animated checkmarks -->
  <text x="20" y="175" font-family="'Courier New', monospace" font-size="12" fill="#73daca">✦</text>
  <text x="35" y="175" font-family="'Courier New', monospace" font-size="12" fill="#c0caf5">Shipping production-grade applications — fast</text>
  
  <text x="20" y="195" font-family="'Courier New', monospace" font-size="12" fill="#73daca">✦</text>
  <text x="35" y="195" font-family="'Courier New', monospace" font-size="12" fill="#c0caf5">Turning AI prototypes into deployed, tested systems</text>
  
  <text x="20" y="215" font-family="'Courier New', monospace" font-size="12" fill="#73daca">✦</text>
  <text x="35" y="215" font-family="'Courier New', monospace" font-size="12" fill="#c0caf5">Building at the intersection of LLMs + systems design</text>
  
  <text x="20" y="235" font-family="'Courier New', monospace" font-size="12" fill="#73daca">✦</text>
  <text x="35" y="235" font-family="'Courier New', monospace" font-size="12" fill="#c0caf5">Leveraging AI-accelerated dev for the 10× advantage</text>
  
  <text x="20" y="255" font-family="'Courier New', monospace" font-size="12" fill="#73daca">✦</text>
  <text x="35" y="255" font-family="'Courier New', monospace" font-size="12" fill="#c0caf5">From multi-step LLM orchestration → full-stack SaaS</text>
</svg>

    </td>
  </tr>
</table>

<br>

<!-- ===== ENGINEERING VELOCITY / QUICK STATS ===== -->
<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bar%20Chart.png" width="28" />
  <b style="font-size: 22px; color: #bb9af7; font-family: 'Courier New', monospace;">$ ./engineering--velocity --metrics</b>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bar%20Chart.png" width="28" />
</div>

<br>

<!-- STAT CARDS -->
<table align="center" border="0" cellspacing="10" cellpadding="0" width="100%">
  <tr>
    <td align="center" width="20%">
      <svg width="180" height="100" viewBox="0 0 180 100" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <linearGradient id="g1" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" style="stop-color: #7aa2f7; stop-opacity: 0.15"/>
            <stop offset="100%" style="stop-color: #7aa2f7; stop-opacity: 0.05"/>
          </linearGradient>
        </defs>
        <rect x="0" y="0" width="180" height="100" rx="10" fill="url(#g1)" stroke="#7aa2f7" stroke-width="1" stroke-opacity="0.3"/>
        <text x="90" y="35" text-anchor="middle" font-family="'Courier New', monospace" font-size="28" font-weight="bold" fill="#7aa2f7">3</text>
        <text x="90" y="52" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#7aa2f7" font-weight="bold">PRODUCTION</text>
        <text x="90" y="67" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#7aa2f7" font-weight="bold">PROJECTS</text>
        <text x="90" y="85" text-anchor="middle" font-family="'Courier New', monospace" font-size="9" fill="#565f89">Shipped to production</text>
      </svg>
    </td>
    <td align="center" width="20%">
      <svg width="180" height="100" viewBox="0 0 180 100" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <linearGradient id="g2" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" style="stop-color: #bb9af7; stop-opacity: 0.15"/>
            <stop offset="100%" style="stop-color: #bb9af7; stop-opacity: 0.05"/>
          </linearGradient>
        </defs>
        <rect x="0" y="0" width="180" height="100" rx="10" fill="url(#g2)" stroke="#bb9af7" stroke-width="1" stroke-opacity="0.3"/>
        <text x="90" y="35" text-anchor="middle" font-family="'Courier New', monospace" font-size="28" font-weight="bold" fill="#bb9af7">2</text>
        <text x="90" y="52" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#bb9af7" font-weight="bold">HACKATHON</text>
        <text x="90" y="67" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#bb9af7" font-weight="bold">WINS</text>
        <text x="90" y="85" text-anchor="middle" font-family="'Courier New', monospace" font-size="9" fill="#565f89">Sole backend · 48hr builds</text>
      </svg>
    </td>
    <td align="center" width="20%">
      <svg width="180" height="100" viewBox="0 0 180 100" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <linearGradient id="g3" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" style="stop-color: #73daca; stop-opacity: 0.15"/>
            <stop offset="100%" style="stop-color: #73daca; stop-opacity: 0.05"/>
          </linearGradient>
        </defs>
        <rect x="0" y="0" width="180" height="100" rx="10" fill="url(#g3)" stroke="#73daca" stroke-width="1" stroke-opacity="0.3"/>
        <text x="90" y="35" text-anchor="middle" font-family="'Courier New', monospace" font-size="28" font-weight="bold" fill="#73daca">8+</text>
        <text x="90" y="52" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#73daca" font-weight="bold">TECH STACK</text>
        <text x="90" y="67" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#73daca" font-weight="bold">MASTERED</text>
        <text x="90" y="85" text-anchor="middle" font-family="'Courier New', monospace" font-size="9" fill="#565f89">Gen AI · Backend · Cloud · Web</text>
      </svg>
    </td>
    <td align="center" width="20%">
      <svg width="180" height="100" viewBox="0 0 180 100" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <linearGradient id="g4" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" style="stop-color: #e0af68; stop-opacity: 0.15"/>
            <stop offset="100%" style="stop-color: #e0af68; stop-opacity: 0.05"/>
          </linearGradient>
        </defs>
        <rect x="0" y="0" width="180" height="100" rx="10" fill="url(#g4)" stroke="#e0af68" stroke-width="1" stroke-opacity="0.3"/>
        <text x="90" y="35" text-anchor="middle" font-family="'Courier New', monospace" font-size="28" font-weight="bold" fill="#e0af68">3</text>
        <text x="90" y="52" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#e0af68" font-weight="bold">TEAM</text>
        <text x="90" y="67" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#e0af68" font-weight="bold">LEADS</text>
        <text x="90" y="85" text-anchor="middle" font-family="'Courier New', monospace" font-size="9" fill="#565f89">Cross-functional leadership</text>
      </svg>
    </td>
    <td align="center" width="20%">
      <svg width="180" height="100" viewBox="0 0 180 100" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <linearGradient id="g5" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" style="stop-color: #f7768e; stop-opacity: 0.15"/>
            <stop offset="100%" style="stop-color: #f7768e; stop-opacity: 0.05"/>
          </linearGradient>
        </defs>
        <rect x="0" y="0" width="180" height="100" rx="10" fill="url(#g5)" stroke="#f7768e" stroke-width="1" stroke-opacity="0.3"/>
        <text x="90" y="35" text-anchor="middle" font-family="'Courier New', monospace" font-size="28" font-weight="bold" fill="#f7768e">2</text>
        <text x="90" y="52" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#f7768e" font-weight="bold">INDUSTRY</text>
        <text x="90" y="67" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#f7768e" font-weight="bold">TRAININGS</text>
        <text x="90" y="85" text-anchor="middle" font-family="'Courier New', monospace" font-size="9" fill="#565f89">HCL Tech · Agile certified</text>
      </svg>
    </td>
  </tr>
</table>

<br>

<!-- ===== FEATURED PROJECTS ===== -->
<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" width="28" />
  <b style="font-size: 22px; color: #73daca; font-family: 'Courier New', monospace;">$ ls -la /projects/featured/</b>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" width="28" />
</div>

<br>

<!-- PROJECT CARDS -->
<table width="100%" border="0" cellspacing="10" cellpadding="0">
  <tr valign="top">
    <!-- Project 1: ComplianceAI -->
    <td width="33.33%">
      <svg width="100%" height="auto" viewBox="0 0 320 420" xmlns="http://www.w3.org/2000/svg" style="max-width: 320px;">
        <defs>
          <linearGradient id="cardGrad1" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" style="stop-color: #1a1b2e; stop-opacity: 1"/>
            <stop offset="100%" style="stop-color: #16161e; stop-opacity: 1"/>
          </linearGradient>
          <linearGradient id="borderGrad1" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" style="stop-color: #7aa2f7"/>
            <stop offset="100%" style="stop-color: #73daca"/>
          </linearGradient>
        </defs>
        <!-- Card border with gradient animation -->
        <rect x="0" y="0" width="320" height="420" rx="12" fill="none" stroke="url(#borderGrad1)" stroke-width="2" stroke-opacity="0.6">
          <animate attributeName="stroke-opacity" values="0.4;0.8;0.4" dur="4s" repeatCount="indefinite"/>
        </rect>
        <!-- Card background -->
        <rect x="2" y="2" width="316" height="416" rx="11" fill="url(#cardGrad1)"/>
        
        <!-- Status indicator -->
        <circle cx="18" cy="18" r="4" fill="#73daca">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="2s" repeatCount="indefinite"/>
        </circle>
        <text x="28" y="22" font-family="'Courier New', monospace" font-size="9" fill="#73daca">PRODUCTION</text>
        
        <!-- Project icon -->
        <text x="160" y="52" text-anchor="middle" font-size="28">🛡️</text>
        
        <!-- Title -->
        <text x="160" y="80" text-anchor="middle" font-family="'Courier New', monospace" font-size="16" font-weight="bold" fill="#7aa2f7">ComplianceAI</text>
        
        <!-- Tagline -->
        <text x="160" y="98" text-anchor="middle" font-family="sans-serif" font-size="10" fill="#565f89">AI Compliance Verification Platform</text>
        
        <line x1="20" y1="110" x2="300" y2="110" stroke="#30363d" stroke-width="0.5"/>
        
        <!-- Key metrics -->
        <text x="20" y="135" font-family="'Courier New', monospace" font-size="9" fill="#bb9af7" font-weight="bold">>_ engine.log</text>
        
        <text x="20" y="155" font-family="'Courier New', monospace" font-size="9" fill="#73daca">✦</text>
        <text x="32" y="155" font-family="sans-serif" font-size="9" fill="#c0caf5">101 routes discovered</text>
        
        <text x="20" y="172" font-family="'Courier New', monospace" font-size="9" fill="#73daca">✦</text>
        <text x="32" y="172" font-family="sans-serif" font-size="9" fill="#c0caf5">695 UI elements extracted</text>
        
        <text x="20" y="189" font-family="'Courier New', monospace" font-size="9" fill="#73daca">✦</text>
        <text x="32" y="189" font-family="sans-serif" font-size="9" fill="#c0caf5">59% resolved without LLM</text>
        
        <text x="20" y="206" font-family="'Courier New', monospace" font-size="9" fill="#73daca">✦</text>
        <text x="32" y="206" font-family="sans-serif" font-size="9" fill="#c0caf5">50%+ inference cost reduction</text>
        
        <text x="20" y="223" font-family="'Courier New', monospace" font-size="9" fill="#73daca">✦</text>
        <text x="32" y="223" font-family="sans-serif" font-size="9" fill="#c0caf5">100% screenshot validation</text>
        
        <line x1="20" y1="235" x2="300" y2="235" stroke="#30363d" stroke-width="0.5"/>
        
        <!-- Tech stack -->
        <text x="20" y="255" font-family="'Courier New', monospace" font-size="9" fill="#bb9af7" font-weight="bold">>_ stack.config</text>
        
        <!-- Tech chips -->
        <rect x="20" y="265" width="70" height="18" rx="9" fill="#7aa2f7" fill-opacity="0.15"/>
        <text x="55" y="278" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#7aa2f7" font-weight="bold">FastAPI</text>
        
        <rect x="95" y="265" width="70" height="18" rx="9" fill="#73daca" fill-opacity="0.15"/>
        <text x="130" y="278" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#73daca" font-weight="bold">LangChain</text>
        
        <rect x="170" y="265" width="70" height="18" rx="9" fill="#bb9af7" fill-opacity="0.15"/>
        <text x="205" y="278" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#bb9af7" font-weight="bold">Playwright</text>
        
        <rect x="20" y="288" width="70" height="18" rx="9" fill="#e0af68" fill-opacity="0.15"/>
        <text x="55" y="301" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#e0af68" font-weight="bold">Groq LLM</text>
        
        <rect x="95" y="288" width="70" height="18" rx="9" fill="#f7768e" fill-opacity="0.15"/>
        <text x="130" y="301" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#f7768e" font-weight="bold">Docker</text>
        
        <rect x="170" y="288" width="70" height="18" rx="9" fill="#7aa2f7" fill-opacity="0.15"/>
        <text x="205" y="301" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#7aa2f7" font-weight="bold">AWS</text>
        
        <line x1="20" y1="318" x2="300" y2="318" stroke="#30363d" stroke-width="0.5"/>
        
        <!-- Architecture -->
        <text x="20" y="338" font-family="'Courier New', monospace" font-size="9" fill="#bb9af7" font-weight="bold">>_ architecture</text>
        <text x="20" y="358" font-family="sans-serif" font-size="9" fill="#565f89">Three-gate verification cascade:</text>
        <text x="20" y="375" font-family="sans-serif" font-size="9" fill="#565f89">Exact Match → Semantic Similarity</text>
        <text x="20" y="392" font-family="sans-serif" font-size="9" fill="#565f89">→ LLM RAG Reasoning</text>
        
        <!-- ATS keyword highlights -->
        <text x="20" y="415" font-family="'Courier New', monospace" font-size="8" fill="#e0af68">#ats: Python, FastAPI, LangChain, AWS, Docker, RAG, CI/CD, Playwright</text>
      </svg>
    </td>
    
    <!-- Project 2: JobPilot -->
    <td width="33.33%">
      <svg width="100%" height="auto" viewBox="0 0 320 420" xmlns="http://www.w3.org/2000/svg" style="max-width: 320px;">
        <defs>
          <linearGradient id="cardGrad2" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" style="stop-color: #1a1b2e; stop-opacity: 1"/>
            <stop offset="100%" style="stop-color: #16161e; stop-opacity: 1"/>
          </linearGradient>
          <linearGradient id="borderGrad2" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" style="stop-color: #bb9af7"/>
            <stop offset="100%" style="stop-color: #e0af68"/>
          </linearGradient>
        </defs>
        <rect x="0" y="0" width="320" height="420" rx="12" fill="none" stroke="url(#borderGrad2)" stroke-width="2" stroke-opacity="0.6">
          <animate attributeName="stroke-opacity" values="0.4;0.8;0.4" dur="4s" begin="1s" repeatCount="indefinite"/>
        </rect>
        <rect x="2" y="2" width="316" height="416" rx="11" fill="url(#cardGrad2)"/>
        
        <circle cx="18" cy="18" r="4" fill="#e0af68">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="2s" begin="1s" repeatCount="indefinite"/>
        </circle>
        <text x="28" y="22" font-family="'Courier New', monospace" font-size="9" fill="#e0af68">SOLO SHIP</text>
        
        <text x="160" y="52" text-anchor="middle" font-size="28">🎯</text>
        
        <text x="160" y="80" text-anchor="middle" font-family="'Courier New', monospace" font-size="16" font-weight="bold" fill="#bb9af7">JobPilot</text>
        <text x="160" y="98" text-anchor="middle" font-family="sans-serif" font-size="10" fill="#565f89">LLM-Powered Job Application Tracker</text>
        
        <line x1="20" y1="110" x2="300" y2="110" stroke="#30363d" stroke-width="0.5"/>
        
        <text x="20" y="135" font-family="'Courier New', monospace" font-size="9" fill="#e0af68" font-weight="bold">>_ engine.log</text>
        
        <text x="20" y="155" font-family="'Courier New', monospace" font-size="9" fill="#73daca">✦</text>
        <text x="32" y="155" font-family="sans-serif" font-size="9" fill="#c0caf5">LLM auto-scoring engine</text>
        
        <text x="20" y="172" font-family="'Courier New', monospace" font-size="9" fill="#73daca">✦</text>
        <text x="32" y="172" font-family="sans-serif" font-size="9" fill="#c0caf5">100% client-side privacy</text>
        
        <text x="20" y="189" font-family="'Courier New', monospace" font-size="9" fill="#73daca">✦</text>
        <text x="32" y="189" font-family="sans-serif" font-size="9" fill="#c0caf5">Automated deep-link scraping</text>
        
        <text x="20" y="206" font-family="'Courier New', monospace" font-size="9" fill="#73daca">✦</text>
        <text x="32" y="206" font-family="sans-serif" font-size="9" fill="#c0caf5">Duplicate detection logic</text>
        
        <text x="20" y="223" font-family="'Courier New', monospace" font-size="9" fill="#73daca">✦</text>
        <text x="32" y="223" font-family="sans-serif" font-size="9" fill="#c0caf5">Custom UI design system</text>
        
        <line x1="20" y1="235" x2="300" y2="235" stroke="#30363d" stroke-width="0.5"/>
        
        <text x="20" y="255" font-family="'Courier New', monospace" font-size="9" fill="#e0af68" font-weight="bold">>_ stack.config</text>
        
        <rect x="20" y="265" width="70" height="18" rx="9" fill="#bb9af7" fill-opacity="0.15"/>
        <text x="55" y="278" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#bb9af7" font-weight="bold">Next.js</text>
        
        <rect x="95" y="265" width="70" height="18" rx="9" fill="#7aa2f7" fill-opacity="0.15"/>
        <text x="130" y="278" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#7aa2f7" font-weight="bold">TypeScript</text>
        
        <rect x="170" y="265" width="70" height="18" rx="9" fill="#73daca" fill-opacity="0.15"/>
        <text x="205" y="278" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#73daca" font-weight="bold">OpenRouter</text>
        
        <rect x="20" y="288" width="70" height="18" rx="9" fill="#e0af68" fill-opacity="0.15"/>
        <text x="55" y="301" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#e0af68" font-weight="bold">IndexedDB</text>
        
        <rect x="95" y="288" width="70" height="18" rx="9" fill="#f7768e" fill-opacity="0.15"/>
        <text x="130" y="301" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#f7768e" font-weight="bold">Cheerio</text>
        
        <line x1="20" y1="318" x2="300" y2="318" stroke="#30363d" stroke-width="0.5"/>
        
        <text x="20" y="338" font-family="'Courier New', monospace" font-size="9" fill="#e0af68" font-weight="bold">>_ architecture</text>
        <text x="20" y="358" font-family="sans-serif" font-size="9" fill="#565f89">Local-first SaaS architecture with</text>
        <text x="20" y="375" font-family="sans-serif" font-size="9" fill="#565f89">prompt-engineered LLM matching</text>
        <text x="20" y="392" font-family="sans-serif" font-size="9" fill="#565f89">engine + Cheerio web scraping</text>
        
        <text x="20" y="415" font-family="'Courier New', monospace" font-size="8" fill="#e0af68">#ats: Next.js, TypeScript, LLM APIs, Cheerio, IndexedDB, Full-Stack</text>
      </svg>
    </td>
    
    <!-- Project 3: Hospital Data Pipeline -->
    <td width="33.33%">
      <svg width="100%" height="auto" viewBox="0 0 320 420" xmlns="http://www.w3.org/2000/svg" style="max-width: 320px;">
        <defs>
          <linearGradient id="cardGrad3" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" style="stop-color: #1a1b2e; stop-opacity: 1"/>
            <stop offset="100%" style="stop-color: #16161e; stop-opacity: 1"/>
          </linearGradient>
          <linearGradient id="borderGrad3" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" style="stop-color: #73daca"/>
            <stop offset="100%" style="stop-color: #7aa2f7"/>
          </linearGradient>
        </defs>
        <rect x="0" y="0" width="320" height="420" rx="12" fill="none" stroke="url(#borderGrad3)" stroke-width="2" stroke-opacity="0.6">
          <animate attributeName="stroke-opacity" values="0.4;0.8;0.4" dur="4s" begin="2s" repeatCount="indefinite"/>
        </rect>
        <rect x="2" y="2" width="316" height="416" rx="11" fill="url(#cardGrad3)"/>
        
        <circle cx="18" cy="18" r="4" fill="#7aa2f7">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="2s" begin="2s" repeatCount="indefinite"/>
        </circle>
        <text x="28" y="22" font-family="'Courier New', monospace" font-size="9" fill="#7aa2f7">DATA PIPELINE</text>
        
        <text x="160" y="52" text-anchor="middle" font-size="28">🏥</text>
        
        <text x="160" y="80" text-anchor="middle" font-family="'Courier New', monospace" font-size="16" font-weight="bold" fill="#73daca">Hospital Data</text>
        <text x="160" y="96" text-anchor="middle" font-family="'Courier New', monospace" font-size="16" font-weight="bold" fill="#73daca">Pipeline</text>
        <text x="160" y="114" text-anchor="middle" font-family="sans-serif" font-size="10" fill="#565f89">ETL & Analytics System</text>
        
        <line x1="20" y1="126" x2="300" y2="126" stroke="#30363d" stroke-width="0.5"/>
        
        <text x="20" y="151" font-family="'Courier New', monospace" font-size="9" fill="#73daca" font-weight="bold">>_ engine.log</text>
        
        <text x="20" y="171" font-family="'Courier New', monospace" font-size="9" fill="#73daca">✦</text>
        <text x="32" y="171" font-family="sans-serif" font-size="9" fill="#c0caf5">500+ patient records processed</text>
        
        <text x="20" y="188" font-family="'Courier New', monospace" font-size="9" fill="#73daca">✦</text>
        <text x="32" y="188" font-family="sans-serif" font-size="9" fill="#c0caf5">70% data inconsistency reduction</text>
        
        <text x="20" y="205" font-family="'Courier New', monospace" font-size="9" fill="#73daca">✦</text>
        <text x="32" y="205" font-family="sans-serif" font-size="9" fill="#c0caf5">35% query perf improvement</text>
        
        <text x="20" y="222" font-family="'Courier New', monospace" font-size="9" fill="#73daca">✦</text>
        <text x="32" y="222" font-family="sans-serif" font-size="9" fill="#c0caf5">3-stage ETL (Bronze→Silver→Gold)</text>
        
        <text x="20" y="239" font-family="'Courier New', monospace" font-size="9" fill="#73daca">✦</text>
        <text x="32" y="239" font-family="sans-serif" font-size="9" fill="#c0caf5">Redis + Docker deployment</text>
        
        <line x1="20" y1="251" x2="300" y2="251" stroke="#30363d" stroke-width="0.5"/>
        
        <text x="20" y="271" font-family="'Courier New', monospace" font-size="9" fill="#73daca" font-weight="bold">>_ stack.config</text>
        
        <rect x="20" y="281" width="70" height="18" rx="9" fill="#7aa2f7" fill-opacity="0.15"/>
        <text x="55" y="294" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#7aa2f7" font-weight="bold">Python</text>
        
        <rect x="95" y="281" width="70" height="18" rx="9" fill="#73daca" fill-opacity="0.15"/>
        <text x="130" y="294" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#73daca" font-weight="bold">FastAPI</text>
        
        <rect x="170" y="281" width="70" height="18" rx="9" fill="#f7768e" fill-opacity="0.15"/>
        <text x="205" y="294" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#f7768e" font-weight="bold">SQLite</text>
        
        <rect x="20" y="304" width="70" height="18" rx="9" fill="#e0af68" fill-opacity="0.15"/>
        <text x="55" y="317" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#e0af68" font-weight="bold">Redis</text>
        
        <rect x="95" y="304" width="70" height="18" rx="9" fill="#bb9af7" fill-opacity="0.15"/>
        <text x="130" y="317" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#bb9af7" font-weight="bold">Docker</text>
        
        <line x1="20" y1="334" x2="300" y2="334" stroke="#30363d" stroke-width="0.5"/>
        
        <text x="20" y="354" font-family="'Courier New', monospace" font-size="9" fill="#73daca" font-weight="bold">>_ architecture</text>
        <text x="20" y="374" font-family="sans-serif" font-size="9" fill="#565f89">Modular 3-stage ETL with</text>
        <text x="20" y="391" font-family="sans-serif" font-size="9" fill="#565f89">automated risk scoring, anomaly</text>
        <text x="20" y="408" font-family="sans-serif" font-size="9" fill="#565f89">detection, and threshold alerting</text>
        
        <text x="20" y="420" font-family="'Courier New', monospace" font-size="8" fill="#73daca">#ats: Python, FastAPI, SQL, Redis, Docker, ETL, Data Pipelines</text>
      </svg>
    </td>
  </tr>
</table>

<br>

<!-- ===== EXPERIENCE ===== -->
<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People%20with%20professions/Man%20Technologist%20Light%20Skin%20Tone.png" width="28" />
  <b style="font-size: 22px; color: #e0af68; font-family: 'Courier New', monospace;">$ cat /var/log/experience.log</b>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People%20with%20professions/Man%20Technologist%20Light%20Skin%20Tone.png" width="28" />
</div>

<br>

<!-- Experience Timeline SVG -->
<svg width="100%" height="300" viewBox="0 0 1000 300" xmlns="http://www.w3.org/2000/svg" style="max-width: 1000px; display: block; margin: 0 auto;">
  <rect x="0" y="0" width="1000" height="300" rx="12" fill="#161b22" stroke="#30363d" stroke-width="1"/>
  
  <!-- Title -->
  <text x="30" y="35" font-family="'Courier New', monospace" font-size="14" font-weight="bold" fill="#e0af68">$ TIMELINE: Engineering Journey</text>
  
  <!-- Timeline line -->
  <line x1="50" y1="70" x2="50" y2="270" stroke="#30363d" stroke-width="2"/>
  
  <!-- Timeline node 1: Education -->
  <circle cx="50" cy="90" r="8" fill="#161b22" stroke="#7aa2f7" stroke-width="3">
    <animate attributeName="r" values="8;10;8" dur="2s" repeatCount="indefinite"/>
  </circle>
  <text x="80" y="87" font-family="'Courier New', monospace" font-size="13" font-weight="bold" fill="#7aa2f7">2022 — B.E. Computer Science</text>
  <text x="80" y="104" font-family="sans-serif" font-size="11" fill="#565f89">Jain College of Engineering · CGPA: 8.39</text>
  
  <!-- Timeline node 2: Srishti Hackathon -->
  <circle cx="50" cy="140" r="8" fill="#161b22" stroke="#bb9af7" stroke-width="3">
    <animate attributeName="r" values="8;10;8" dur="2s" begin="0.5s" repeatCount="indefinite"/>
  </circle>
  <text x="80" y="137" font-family="'Courier New', monospace" font-size="13" font-weight="bold" fill="#bb9af7">2025 — Srishti Hackathon</text>
  <text x="80" y="154" font-family="sans-serif" font-size="11" fill="#565f89">48-hour full-stack build · Cross-functional team</text>
  
  <!-- Timeline node 3: HCL Tech -->
  <circle cx="50" cy="190" r="8" fill="#161b22" stroke="#73daca" stroke-width="3">
    <animate attributeName="r" values="8;10;8" dur="2s" begin="1s" repeatCount="indefinite"/>
  </circle>
  <text x="80" y="187" font-family="'Courier New', monospace" font-size="13" font-weight="bold" fill="#73daca">2026 — HCL Tech Hackathon</text>
  <text x="80" y="204" font-family="sans-serif" font-size="11" fill="#565f89">Sole Backend Developer · FastAPI · JWT · ACID Transactions</text>
  
  <!-- Timeline node 4: Present -->
  <circle cx="50" cy="240" r="8" fill="#161b22" stroke="#e0af68" stroke-width="3">
    <animate attributeName="r" values="8;10;8" dur="2s" begin="1.5s" repeatCount="indefinite"/>
  </circle>
  <text x="80" y="237" font-family="'Courier New', monospace" font-size="13" font-weight="bold" fill="#e0af68">2026 — Python / Gen AI Engineer (Active)</text>
  <text x="80" y="254" font-family="sans-serif" font-size="11" fill="#565f89">Agentic AI · RAG · LLM Engineering · Full-Stack Development</text>
  
  <!-- Right side: badges -->
  <rect x="600" y="60" width="340" height="80" rx="8" fill="#1a1b2e" stroke="#30363d" stroke-width="0.5"/>
  <text x="615" y="82" font-family="'Courier New', monospace" font-size="11" font-weight="bold" fill="#565f89"># HCL Tech Hackathon 2026 — Highlights</text>
  <text x="615" y="102" font-family="sans-serif" font-size="10" fill="#c0caf5">🏗️ Production-grade Online Banking System</text>
  <text x="615" y="118" font-family="sans-serif" font-size="10" fill="#c0caf5">🔐 RBAC across 3 roles · Concurrency safeguards</text>
  <text x="615" y="134" font-family="sans-serif" font-size="10" fill="#c0caf5">⚡ Agile sprints · Industry judges evaluation</text>

  <rect x="600" y="155" width="340" height="120" rx="8" fill="#1a1b2e" stroke="#30363d" stroke-width="0.5"/>
  <text x="615" y="177" font-family="'Courier New', monospace" font-size="11" font-weight="bold" fill="#565f89"># Engineering Expertise</text>
  <text x="615" y="197" font-family="sans-serif" font-size="10" fill="#73daca">✓ Production Backend Systems (FastAPI, REST)</text>
  <text x="615" y="214" font-family="sans-serif" font-size="10" fill="#73daca">✓ Agentic AI Workflows (LangChain, LangGraph)</text>
  <text x="615" y="231" font-family="sans-serif" font-size="10" fill="#73daca">✓ RAG Pipelines · Vector Search · Embeddings</text>
  <text x="615" y="248" font-family="sans-serif" font-size="10" fill="#73daca">✓ Cloud Deployment (AWS EC2, S3, Docker)</text>
  <text x="615" y="265" font-family="sans-serif" font-size="10" fill="#73daca">✓ Full-Stack SaaS (Next.js, TypeScript, React)</text>
</svg>

<br>

<!-- ===== ENGINEERING STACK ===== -->
<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" width="28" />
  <b style="font-size: 22px; color: #f7768e; font-family: 'Courier New', monospace;">$ cat /proc/engineering--stack</b>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" width="28" />
</div>

<br>

<!-- SKILL ICONS (via skillicons.dev) -->
<p align="center">
  <b style="font-family: 'Courier New', monospace; color: #7aa2f7;">[[ LANGUAGES ]]</b>
  <br>
  <a href="https://python.org">
    <img src="https://skillicons.dev/icons?i=python&theme=dark" width="45" alt="Python" title="Python"/>
  </a>&nbsp;
  <a href="https://typescriptlang.org">
    <img src="https://skillicons.dev/icons?i=ts&theme=dark" width="45" alt="TypeScript" title="TypeScript"/>
  </a>&nbsp;
  <a href="https://java.com">
    <img src="https://skillicons.dev/icons?i=java&theme=dark" width="45" alt="Java" title="Java"/>
  </a>&nbsp;
  <a href="https://sql.org">
    <img src="https://skillicons.dev/icons?i=mysql&theme=dark" width="45" alt="SQL" title="SQL"/>
  </a>&nbsp;
  <a href="https://bash.org">
    <img src="https://skillicons.dev/icons?i=bash&theme=dark" width="45" alt="Bash" title="Bash"/>
  </a>
</p>

<br>

<p align="center">
  <b style="font-family: 'Courier New', monospace; color: #bb9af7;">[[ AI & MACHINE LEARNING ]]</b>
  <br>
  <a href="https://langchain.com">
    <img src="https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=#73daca" alt="LangChain"/>
  </a>&nbsp;
  <a href="https://langchain.com">
    <img src="https://img.shields.io/badge/LangGraph-121212?style=for-the-badge&logo=graphql&logoColor=#e0af68" alt="LangGraph"/>
  </a>&nbsp;
  <a href="https://react.dev">
    <img src="https://img.shields.io/badge/RAG-121212?style=for-the-badge&logo=readthedocs&logoColor=7aa2f7" alt="RAG"/>
  </a>&nbsp;
  <a href="https://huggingface.co">
    <img src="https://img.shields.io/badge/LLM%20APIs-121212?style=for-the-badge&logo=openai&logoColor=73daca" alt="LLM APIs"/>
  </a>&nbsp;
  <a href="https://llamaindex.ai">
    <img src="https://img.shields.io/badge/LlamaIndex-121212?style=for-the-badge&logo=readthedocs&logoColor=bb9af7" alt="LlamaIndex"/>
  </a>&nbsp;
  <a href="https://pytorch.org">
    <img src="https://img.shields.io/badge/Sentence--Transformers-121212?style=for-the-badge&logo=semantic-web&logoColor=e0af68" alt="SentenceTransformers"/>
  </a>&nbsp;
  <a href="https://scikit-learn.org">
    <img src="https://skillicons.dev/icons?i=sklearn&theme=dark" width="45" alt="Scikit-learn" title="Scikit-learn"/>
  </a>
</p>

<br>

<p align="center">
  <b style="font-family: 'Courier New', monospace; color: #73daca;">[[ BACKEND & API ]]</b>
  <br>
  <a href="https://fastapi.tiangolo.com">
    <img src="https://skillicons.dev/icons?i=fastapi&theme=dark" width="45" alt="FastAPI" title="FastAPI"/>
  </a>&nbsp;
  <a href="https://redis.io">
    <img src="https://skillicons.dev/icons?i=redis&theme=dark" width="45" alt="Redis" title="Redis"/>
  </a>&nbsp;
  <a href="https://postman.com">
    <img src="https://skillicons.dev/icons?i=postman&theme=dark" width="45" alt="Postman" title="Postman"/>
  </a>&nbsp;
  <a href="https://playwright.dev">
    <img src="https://skillicons.dev/icons?i=playwright&theme=dark" width="45" alt="Playwright" title="Playwright"/>
  </a>&nbsp;
  <a href="https://pydantic.dev">
    <img src="https://img.shields.io/badge/Pydantic-121212?style=for-the-badge&logo=python&logoColor=e0af68" alt="Pydantic"/>
  </a>&nbsp;
  <a href="https://pytest.org">
    <img src="https://skillicons.dev/icons?i=pytest&theme=dark" width="45" alt="pytest" title="pytest"/>
  </a>
</p>

<br>

<p align="center">
  <b style="font-family: 'Courier New', monospace; color: #e0af68;">[[ FRONTEND ]]</b>
  <br>
  <a href="https://react.dev">
    <img src="https://skillicons.dev/icons?i=react&theme=dark" width="45" alt="React" title="React"/>
  </a>&nbsp;
  <a href="https://nextjs.org">
    <img src="https://skillicons.dev/icons?i=nextjs&theme=dark" width="45" alt="Next.js" title="Next.js"/>
  </a>&nbsp;
  <a href="https://typescriptlang.org">
    <img src="https://skillicons.dev/icons?i=ts&theme=dark" width="45" alt="TypeScript" title="TypeScript"/>
  </a>&nbsp;
  <a href="https://developer.mozilla.org/en-US/docs/Web/HTML">
    <img src="https://skillicons.dev/icons?i=html&theme=dark" width="45" alt="HTML" title="HTML"/>
  </a>&nbsp;
  <a href="https://developer.mozilla.org/en-US/docs/Web/CSS">
    <img src="https://skillicons.dev/icons?i=css&theme=dark" width="45" alt="CSS" title="CSS"/>
  </a>
</p>

<br>

<p align="center">
  <b style="font-family: 'Courier New', monospace; color: #f7768e;">[[ CLOUD & DEVOPS ]]</b>
  <br>
  <a href="https://aws.amazon.com">
    <img src="https://skillicons.dev/icons?i=aws&theme=dark" width="45" alt="AWS" title="AWS"/>
  </a>&nbsp;
  <a href="https://docker.com">
    <img src="https://skillicons.dev/icons?i=docker&theme=dark" width="45" alt="Docker" title="Docker"/>
  </a>&nbsp;
  <a href="https://git-scm.com">
    <img src="https://skillicons.dev/icons?i=git&theme=dark" width="45" alt="Git" title="Git"/>
  </a>&nbsp;
  <a href="https://github.com/features/actions">
    <img src="https://skillicons.dev/icons?i=githubactions&theme=dark" width="45" alt="GitHub Actions" title="GitHub Actions"/>
  </a>&nbsp;
  <a href="https://linux.org">
    <img src="https://skillicons.dev/icons?i=linux&theme=dark" width="45" alt="Linux" title="Linux"/>
  </a>
</p>

<br>

<p align="center">
  <b style="font-family: 'Courier New', monospace; color: #bb9af7;">[[ DATABASES & DATA ]]</b>
  <br>
  <a href="https://mysql.com">
    <img src="https://skillicons.dev/icons?i=mysql&theme=dark" width="45" alt="MySQL" title="MySQL"/>
  </a>&nbsp;
  <a href="https://sqlite.org">
    <img src="https://skillicons.dev/icons?i=sqlite&theme=dark" width="45" alt="SQLite" title="SQLite"/>
  </a>&nbsp;
  <a href="https://redis.io">
    <img src="https://skillicons.dev/icons?i=redis&theme=dark" width="45" alt="Redis" title="Redis"/>
  </a>&nbsp;
  <a href="https://pandas.pydata.org">
    <img src="https://img.shields.io/badge/Pandas-121212?style=for-the-badge&logo=pandas&logoColor=7aa2f7" alt="Pandas"/>
  </a>&nbsp;
  <a href="https://numpy.org">
    <img src="https://img.shields.io/badge/NumPy-121212?style=for-the-badge&logo=numpy&logoColor=73daca" alt="NumPy"/>
  </a>&nbsp;
  <a href="https://matplotlib.org">
    <img src="https://img.shields.io/badge/Plotly-121212?style=for-the-badge&logo=plotly&logoColor=bb9af7" alt="Plotly"/>
  </a>
</p>

<br>

<!-- ===== PROFESSIONAL HIGHLIGHTS ===== -->
<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Trophy.png" width="28" />
  <b style="font-size: 22px; color: #e0af68; font-family: 'Courier New', monospace;">$ highlight --achievements</b>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Trophy.png" width="28" />
</div>

<br>

<!-- ACHIEVEMENTS -->
<table width="100%" border="0" cellspacing="8" cellpadding="0">
  <tr>
    <td width="50%" valign="top">
      <svg width="100%" height="auto" viewBox="0 0 480 160" xmlns="http://www.w3.org/2000/svg" style="max-width: 480px;">
        <rect x="0" y="0" width="480" height="160" rx="10" fill="#161b22" stroke="#30363d" stroke-width="1"/>
        <rect x="0" y="0" width="480" height="28" rx="10" fill="#161b22"/>
        <rect x="0" y="18" width="480" height="10" fill="#161b22"/>
        <circle cx="14" cy="14" r="4.5" fill="#f7768e"/>
        <circle cx="28" cy="14" r="4.5" fill="#e0af68"/>
        <circle cx="42" cy="14" r="4.5" fill="#73daca"/>
        <text x="240" y="19" text-anchor="middle" font-family="sans-serif" font-size="10" fill="#565f89">achievements.log</text>
        
        <text x="55" y="60" font-family="'Courier New', monospace" font-size="24" fill="#e0af68">🏆</text>
        <text x="95" y="60" font-family="'Courier New', monospace" font-size="13" font-weight="bold" fill="#e0af68">HCL Tech Hackathon 2026</text>
        <text x="95" y="80" font-family="sans-serif" font-size="11" fill="#c0caf5">Sole Backend Developer · 3-person cross-functional team</text>
        <text x="95" y="98" font-family="sans-serif" font-size="10" fill="#565f89">Evaluated by industry judges on code quality & system design</text>
        <text x="95" y="118" font-family="sans-serif" font-size="10" fill="#7aa2f7">#FastAPI #JWT #RBAC #ACID #Agile</text>
        
        <rect x="20" y="135" width="440" height="1" fill="#30363d"/>
      </svg>
    </td>
    <td width="50%" valign="top">
      <svg width="100%" height="auto" viewBox="0 0 480 160" xmlns="http://www.w3.org/2000/svg" style="max-width: 480px;">
        <rect x="0" y="0" width="480" height="160" rx="10" fill="#161b22" stroke="#30363d" stroke-width="1"/>
        <rect x="0" y="0" width="480" height="28" rx="10" fill="#161b22"/>
        <rect x="0" y="18" width="480" height="10" fill="#161b22"/>
        <circle cx="14" cy="14" r="4.5" fill="#f7768e"/>
        <circle cx="28" cy="14" r="4.5" fill="#e0af68"/>
        <circle cx="42" cy="14" r="4.5" fill="#73daca"/>
        <text x="240" y="19" text-anchor="middle" font-family="sans-serif" font-size="10" fill="#565f89">achievements.log</text>
        
        <text x="55" y="60" font-family="'Courier New', monospace" font-size="24">⚡</text>
        <text x="95" y="60" font-family="'Courier New', monospace" font-size="13" font-weight="bold" fill="#7aa2f7">Srishti 2025 Hackathon</text>
        <text x="95" y="80" font-family="sans-serif" font-size="11" fill="#c0caf5">Full-stack web app built in 48 hours</text>
        <text x="95" y="98" font-family="sans-serif" font-size="10" fill="#565f89">Extreme time pressure · Cross-functional team</text>
        <text x="95" y="118" font-family="sans-serif" font-size="10" fill="#bb9af7">#RapidPrototyping #Agile #FullStack</text>
        
        <rect x="20" y="135" width="440" height="1" fill="#30363d"/>
      </svg>
    </td>
  </tr>
</table>

<br>

<!-- ===== GITHUB METRICS ===== -->
<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Chart%20Increasing.png" width="28" />
  <b style="font-size: 22px; color: #7aa2f7; font-family: 'Courier New', monospace;">$ ./monitor --dashboard</b>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Chart%20Increasing.png" width="28" />
</div>

<br>

<!-- GITHUB STATS CARDS -->
<p align="center">
  <a href="https://github.com/Darshanvs0730">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Darshanvs0730&show_icons=true&count_private=true&include_all_commits=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=7aa2f7&icon_color=bb9af7&text_color=c0caf5&border_color=30363d" alt="GitHub Stats" />
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Darshanvs0730&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=7aa2f7&text_color=c0caf5&border_color=30363d" alt="Top Languages" />
  </a>
</p>

<br>

<!-- STREAK & TROPHIES -->
<p align="center">
  <a href="https://github.com/Darshanvs0730">
    <img height="180em" src="https://github-readme-streak-stats.herokuapp.com/?user=Darshanvs0730&theme=tokyonight&hide_border=true&background=0d1117&stroke=30363d&ring=7aa2f7&fire=e0af68&currStreakNum=73daca&sideNums=c0caf5&currStreakLabel=bb9af7&sideLabels=565f89&dates=565f89" alt="GitHub Streak" />
  </a>
</p>

<br>

<!-- TROPHIES -->
<p align="center">
  <a href="https://github.com/Darshanvs0730">
    <img src="https://github-profile-trophy.vercel.app/?username=Darshanvs0730&theme=tokyonight&no-frame=true&column=7&row=1&margin-w=8&margin-h=8" alt="GitHub Trophies" />
  </a>
</p>

<br>

<!-- ACTIVITY GRAPH -->
<a href="https://github.com/Darshanvs0730">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Darshanvs0730&theme=tokyo-night&hide_border=true&bg_color=0d1117&title_color=7aa2f7&color=c0caf5&line=bb9af7&point=73daca&area=true&area_color=7aa2f7" alt="Activity Graph" />
</a>

<br>

<!-- CONTRIBUTION SNAKE -->
<p align="center">
  <img width="100%" src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Contribution Snake" />
  <br>
  <sub style="font-family: 'Courier New', monospace; color: #565f89;">
    <i>// Contribution grid snake — it feeds on your commits</i>
  </sub>
</p>

<br>

<!-- ===== ACHIEVEMENTS BADGES ===== -->
<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Medal.png" width="28" />
  <b style="font-size: 22px; color: #bb9af7; font-family: 'Courier New', monospace;">$ cat /proc/badges/certifications</b>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Medal.png" width="28" />
</div>

<br>

<!-- CERTIFICATION BADGES -->
<p align="center">
  <img src="https://img.shields.io/badge/Python-FastAPI-7aa2f7?style=for-the-badge&logo=fastapi&logoColor=white&labelColor=161b22" alt="FastAPI" />
  <img src="https://img.shields.io/badge/AI-LangChain-73daca?style=for-the-badge&logo=chainlink&logoColor=white&labelColor=161b22" alt="LangChain" />
  <img src="https://img.shields.io/badge/Cloud-AWS%20EC2%2FS3-e0af68?style=for-the-badge&logo=amazonaws&logoColor=white&labelColor=161b22" alt="AWS" />
  <img src="https://img.shields.io/badge/Container-Docker-f7768e?style=for-the-badge&logo=docker&logoColor=white&labelColor=161b22" alt="Docker" />
  <img src="https://img.shields.io/badge/Testing-pytest-bb9af7?style=for-the-badge&logo=pytest&logoColor=white&labelColor=161b22" alt="pytest" />
  <img src="https://img.shields.io/badge/CI-CD%20Actions-7aa2f7?style=for-the-badge&logo=githubactions&logoColor=white&labelColor=161b22" alt="GitHub Actions" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Framework-LangGraph-bb9af7?style=for-the-badge&logo=graphql&logoColor=white&labelColor=161b22" alt="LangGraph" />
  <img src="https://img.shields.io/badge/Vector-FAISS%20%7C%20ChromaDB-73daca?style=for-the-badge&logo=semantic-web&logoColor=white&labelColor=161b22" alt="Vector DB" />
  <img src="https://img.shields.io/badge/Data%20ETL-Bronze%20%E2%86%92%20Gold-e0af68?style=for-the-badge&logo=apache&logoColor=white&labelColor=161b22" alt="ETL" />
  <img src="https://img.shields.io/badge/Auth-JWT%20%7C%20RBAC-f7768e?style=for-the-badge&logo=jsonwebtokens&logoColor=white&labelColor=161b22" alt="Auth" />
  <img src="https://img.shields.io/badge/LLM-Groq%20%7C%20OpenRouter-7aa2f7?style=for-the-badge&logo=openai&logoColor=white&labelColor=161b22" alt="LLM" />
</p>

<br>

<!-- ===== CURRENTLY ENGINEERING ===== -->
<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Satellite%20Antenna.png" width="28" />
  <b style="font-size: 22px; color: #73daca; font-family: 'Courier New', monospace;">$ ps aux | grep "currently-engineering"</b>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Satellite%20Antenna.png" width="28" />
</div>

<br>

<!-- CURRENTLY EXPLORING SVG -->
<svg width="100%" height="220" viewBox="0 0 1000 220" xmlns="http://www.w3.org/2000/svg" style="max-width: 1000px; display: block; margin: 0 auto;">
  <rect x="0" y="0" width="1000" height="220" rx="12" fill="#161b22" stroke="#30363d" stroke-width="1"/>
  
  <!-- Status bar -->
  <rect x="0" y="0" width="1000" height="36" rx="12" fill="#161b22"/>
  <rect x="0" y="24" width="1000" height="12" fill="#161b22"/>
  <circle cx="18" cy="18" r="6" fill="#f7768e"/>
  <circle cx="36" cy="18" r="6" fill="#e0af68"/>
  <circle cx="54" cy="18" r="6" fill="#73daca"/>
  <text x="500" y="23" text-anchor="middle" font-family="'Courier New', monospace" font-size="11" fill="#565f89">currently_engineering.sh — active processes</text>
  
  <!-- Pulsing dot -->
  <circle cx="30" cy="60" r="4" fill="#73daca">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <text x="45" y="64" font-family="'Courier New', monospace" font-size="13" font-weight="bold" fill="#c0caf5">Active Engineering Processes</text>
  
  <!-- Process list -->
  <text x="45" y="92" font-family="'Courier New', monospace" font-size="10" fill="#73daca">PID 1</text>
  <text x="90" y="92" font-family="sans-serif" font-size="11" fill="#c0caf5">AI Agents & Agentic Workflows</text>
  <text x="380" y="92" font-family="'Courier New', monospace" font-size="9" fill="#565f89">[■■■■■■■■■■] 100%</text>
  
  <text x="45" y="114" font-family="'Courier New', monospace" font-size="10" fill="#73daca">PID 2</text>
  <text x="90" y="114" font-family="sans-serif" font-size="11" fill="#c0caf5">LLM Engineering & Multi-Agent RAG</text>
  <text x="380" y="114" font-family="'Courier New', monospace" font-size="9" fill="#565f89">[■■■■■■■■■■] 100%</text>
  
  <text x="45" y="136" font-family="'Courier New', monospace" font-size="10" fill="#e0af68">PID 3</text>
  <text x="90" y="136" font-family="sans-serif" font-size="11" fill="#c0caf5">System Design & Cloud Architecture</text>
  <text x="380" y="136" font-family="'Courier New', monospace" font-size="9" fill="#565f89">[■■■■■■■■□□] 80%</text>
  
  <text x="45" y="158" font-family="'Courier New', monospace" font-size="10" fill="#e0af68">PID 4</text>
  <text x="90" y="158" font-family="sans-serif" font-size="11" fill="#c0caf5">High-Performance Distributed Systems</text>
  <text x="380" y="158" font-family="'Courier New', monospace" font-size="9" fill="#565f89">[■■■■■■□□□□] 60%</text>
  
  <text x="45" y="180" font-family="'Courier New', monospace" font-size="10" fill="#7aa2f7">PID 5</text>
  <text x="90" y="180" font-family="sans-serif" font-size="11" fill="#c0caf5">Agentic AI · RAG Systems · Multi-Agent Orchestration</text>
  <text x="380" y="180" font-family="'Courier New', monospace" font-size="9" fill="#565f89">[■■■■■■■■□□] 75%</text>
  
  <text x="45" y="202" font-family="'Courier New', monospace" font-size="10" fill="#7aa2f7">PID 6</text>
  <text x="90" y="202" font-family="sans-serif" font-size="11" fill="#c0caf5">Cloud-Native Kubernetes & Container Orchestration</text>
  <text x="380" y="202" font-family="'Courier New', monospace" font-size="9" fill="#565f89">[■■■■■□□□□□] 50%</text>
</svg>

<br>

<!-- ===== LET'S CONNECT ===== -->
<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Telephone%20Receiver.png" width="28" />
  <b style="font-size: 22px; color: #7aa2f7; font-family: 'Courier New', monospace;">$ ./connect --all-channels</b>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Telephone%20Receiver.png" width="28" />
</div>

<br>

<!-- CONNECT BADGES -->
<p align="center">
  <a href="mailto:darshansunkanur999@gmail.com">
    <img src="https://img.shields.io/badge/EMAIL-darshansunkanur999%40gmail.com-f7768e?style=for-the-badge&logo=gmail&logoColor=white&labelColor=161b22" alt="Email" />
  </a>&nbsp;
  <a href="https://linkedin.com/in/Darshan-V-S">
    <img src="https://img.shields.io/badge/LINKEDIN-Darshan_V_S-7aa2f7?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=161b22" alt="LinkedIn" />
  </a>&nbsp;
  <a href="https://github.com/Darshanvs0730">
    <img src="https://img.shields.io/badge/GITHUB-Darshanvs0730-bb9af7?style=for-the-badge&logo=github&logoColor=white&labelColor=161b22" alt="GitHub" />
  </a>&nbsp;
  <a href="https://leetcode.com/">
    <img src="https://img.shields.io/badge/LEETCODE-Competitive-e0af68?style=for-the-badge&logo=leetcode&logoColor=white&labelColor=161b22" alt="LeetCode" />
  </a>
</p>

<p align="center">
  <a href="https://www.hackerrank.com/">
    <img src="https://img.shields.io/badge/HACKERRANK-Challenge-73daca?style=for-the-badge&logo=hackerrank&logoColor=white&labelColor=161b22" alt="HackerRank" />
  </a>&nbsp;
  <a href="https://codeforces.com/">
    <img src="https://img.shields.io/badge/CODEFORCES-Algorithm-7aa2f7?style=for-the-badge&logo=codeforces&logoColor=white&labelColor=161b22" alt="Codeforces" />
  </a>&nbsp;
  <a href="https://twitter.com/">
    <img src="https://img.shields.io/badge/TWITTER-X-f7768e?style=for-the-badge&logo=x&logoColor=white&labelColor=161b22" alt="Twitter/X" />
  </a>&nbsp;
  <a href="https://geeksforgeeks.org/">
    <img src="https://img.shields.io/badge/GEEKSFORGEEKS-Coding%20Practice-73daca?style=for-the-badge&logo=geeksforgeeks&logoColor=white&labelColor=161b22" alt="GeeksforGeeks" />
  </a>
</p>

<br>

<!-- ===== SIGNATURE QUOTE ===== -->
<svg width="100%" height="180" viewBox="0 0 1000 180" xmlns="http://www.w3.org/2000/svg" style="max-width: 1000px; display: block; margin: 0 auto;">
  <defs>
    <linearGradient id="quoteGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color: #1a1b2e; stop-opacity: 1"/>
      <stop offset="100%" style="stop-color: #16161e; stop-opacity: 1"/>
    </linearGradient>
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color: #7aa2f7"/>
      <stop offset="50%" style="stop-color: #bb9af7"/>
      <stop offset="100%" style="stop-color: #73daca"/>
    </linearGradient>
  </defs>
  
  <rect x="0" y="0" width="1000" height="180" rx="12" fill="url(#quoteGrad)" stroke="#30363d" stroke-width="1"/>
  
  <!-- Decorative quote marks -->
  <text x="50" y="60" font-family="serif" font-size="72" fill="#7aa2f7" fill-opacity="0.15">"</text>
  
  <!-- Quote text -->
  <text x="90" y="72" font-family="serif" font-size="22" fill="url(#textGrad)" font-style="italic">
    Architecture is not about the tools. It's about the decisions
  </text>
  <text x="90" y="102" font-family="serif" font-size="22" fill="url(#textGrad)" font-style="italic">
    that survive through every layer of abstraction.
  </text>
  
  <!-- Author -->
  <text x="850" y="140" text-anchor="end" font-family="'Courier New', monospace" font-size="13" font-weight="bold" fill="#565f89">— Darshan V S</text>
  
  <!-- Subtitle -->
  <text x="850" y="158" text-anchor="end" font-family="'Courier New', monospace" font-size="11" fill="#565f89">Python / Gen AI Engineer</text>
  
  <!-- Terminal line at bottom -->
  <text x="50" y="168" font-family="'Courier New', monospace" font-size="11" fill="#565f89">
    darshan@gen-ai-engineer:~$
    <animate attributeName="opacity" values="0.7;1;0.7" dur="3s" repeatCount="indefinite"/>
  </text>
  <text x="260" y="168" font-family="'Courier New', monospace" font-size="11" fill="#73daca">
    ▊
    <animate attributeName="opacity" values="1;1;0;0" dur="1s" repeatCount="indefinite" keyTimes="0;0.5;0.51;1"/>
  </text>
</svg>

<br>

<!-- ===== FOOTER ===== -->
<p align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Inbox%20Tray.png" width="24" />
  <sub style="font-family: 'Courier New', monospace; color: #565f89;">
    <i>// Generated from /proc/darshan/vitals — Last updated: 2026-07-09</i>
  </sub>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Inbox%20Tray.png" width="24" />
</p>

<p align="center">
  <sub style="font-family: 'Courier New', monospace; color: #30363d;">
    <code>━━━ ✦ This profile is engineered, not written ✦ ━━━</code>
  </sub>
</p>

<p align="center">
  <a href="https://github.com/Darshanvs0730">
    <img src="https://img.shields.io/badge/⬆%20Back%20to%20top-%20-7aa2f7?style=for-the-badge&labelColor=161b22" alt="Back to top" />
  </a>
</p>
