<div align="center">

<svg width="100%" viewBox="0 0 860 260" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg2" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#161b22"/>
    </linearGradient>
    <linearGradient id="sideAccent" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#0ea5e9"/>
      <stop offset="100%" stop-color="#6366f1"/>
    </linearGradient>
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#e2e8f0"/>
      <stop offset="60%"  stop-color="#f1f5f9"/>
      <stop offset="100%" stop-color="#94a3b8"/>
    </linearGradient>
    <linearGradient id="underline" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#0ea5e9"/>
      <stop offset="100%" stop-color="#6366f1"/>
    </linearGradient>
    <clipPath id="cname">
      <rect x="0" y="60" width="0" height="110">
        <animate attributeName="width" from="0" to="860" dur="1.4s" begin="0.2s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      </rect>
    </clipPath>
    <clipPath id="csub">
      <rect x="230" y="168" width="0" height="50">
        <animate attributeName="width" from="0" to="400" dur="1s" begin="1.8s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      </rect>
    </clipPath>
    <clipPath id="ctags">
      <rect x="0" y="208" width="0" height="50">
        <animate attributeName="width" from="0" to="860" dur="1s" begin="2.6s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      </rect>
    </clipPath>
  </defs>

  <!-- Background -->
  <rect width="860" height="260" rx="0" fill="url(#bg2)"/>

  <!-- Left accent bar -->
  <rect x="0" y="0" width="5" height="260" fill="url(#sideAccent)"/>

  <!-- Circuit lines — right side decoration -->
  <g stroke="#0ea5e9" stroke-width="0.7" fill="none" opacity="0.18">
    <line x1="610" y1="20"  x2="840" y2="20"/>
    <line x1="840" y1="20"  x2="840" y2="80"/>
    <line x1="680" y1="45"  x2="840" y2="45"/>
    <line x1="730" y1="80"  x2="840" y2="80"/>
    <line x1="730" y1="80"  x2="730" y2="180"/>
    <line x1="610" y1="180" x2="730" y2="180"/>
    <line x1="660" y1="140" x2="730" y2="140"/>
    <line x1="610" y1="220" x2="800" y2="220"/>
    <line x1="800" y1="200" x2="800" y2="220"/>
  </g>
  <!-- Circuit nodes -->
  <g fill="#0ea5e9" opacity="0.45">
    <circle cx="840" cy="20"  r="3"/>
    <circle cx="840" cy="80"  r="3"/>
    <circle cx="730" cy="80"  r="3"/>
    <circle cx="730" cy="180" r="3"/>
    <circle cx="800" cy="220" r="3"/>
  </g>
  <g fill="#6366f1" opacity="0.45">
    <circle cx="730" cy="140" r="2.5"/>
    <circle cx="610" cy="180" r="2.5"/>
  </g>

  <!-- Subtle horizontal rules -->
  <line x1="20" y1="55"  x2="600" y2="55"  stroke="#ffffff" stroke-width="0.4" opacity="0.06"/>
  <line x1="20" y1="205" x2="600" y2="205" stroke="#ffffff" stroke-width="0.4" opacity="0.06"/>

  <!-- Name — center, wipe in -->
  <g clip-path="url(#cname)">
    <text
      x="430" y="155"
      font-family="Georgia, 'Times New Roman', serif"
      font-size="72"
      font-weight="700"
      text-anchor="middle"
      fill="url(#nameGrad)"
      letter-spacing="4">Om Patil</text>
  </g>

  <!-- Underline accent — animates in after name -->
  <rect x="230" y="163" width="0" height="2.5" rx="1" fill="url(#underline)">
    <animate attributeName="width" from="0" to="400" dur="0.9s" begin="1.6s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
  </rect>

  <!-- Subtitle — centered, wipe in -->
  <g clip-path="url(#csub)">
    <text
      x="430" y="192"
      font-family="'Courier New', Courier, monospace"
      font-size="13"
      font-weight="400"
      text-anchor="middle"
      fill="#38bdf8"
      letter-spacing="6">AI  ENGINEER  &amp;  BUILDER</text>
  </g>

  <!-- Tag pills — fade in -->
  <g clip-path="url(#ctags)">
    <rect x="222" y="213" width="68"  height="22" rx="11" fill="#0ea5e9" opacity="0.12"/>
    <rect x="222" y="213" width="68"  height="22" rx="11" fill="none" stroke="#0ea5e9" stroke-width="0.7"/>
    <text x="256" y="228" font-family="'Courier New', monospace" font-size="11" fill="#7dd3fc" text-anchor="middle">LLMs</text>

    <rect x="300" y="213" width="78"  height="22" rx="11" fill="#6366f1" opacity="0.12"/>
    <rect x="300" y="213" width="78"  height="22" rx="11" fill="none" stroke="#6366f1" stroke-width="0.7"/>
    <text x="339" y="228" font-family="'Courier New', monospace" font-size="11" fill="#a5b4fc" text-anchor="middle">Gen AI</text>

    <rect x="388" y="213" width="78"  height="22" rx="11" fill="#0ea5e9" opacity="0.12"/>
    <rect x="388" y="213" width="78"  height="22" rx="11" fill="none" stroke="#0ea5e9" stroke-width="0.7"/>
    <text x="427" y="228" font-family="'Courier New', monospace" font-size="11" fill="#7dd3fc" text-anchor="middle">MLOps</text>

    <rect x="476" y="213" width="78"  height="22" rx="11" fill="#6366f1" opacity="0.12"/>
    <rect x="476" y="213" width="78"  height="22" rx="11" fill="none" stroke="#6366f1" stroke-width="0.7"/>
    <text x="515" y="228" font-family="'Courier New', monospace" font-size="11" fill="#a5b4fc" text-anchor="middle">Python</text>

    <rect x="564" y="213" width="70"  height="22" rx="11" fill="#0ea5e9" opacity="0.12"/>
    <rect x="564" y="213" width="70"  height="22" rx="11" fill="none" stroke="#0ea5e9" stroke-width="0.7"/>
    <text x="599" y="228" font-family="'Courier New', monospace" font-size="11" fill="#7dd3fc" text-anchor="middle">India</text>
  </g>

  <!-- Bottom tagline -->
  <text x="430" y="252" font-family="'Courier New', monospace" font-size="10" text-anchor="middle" fill="#334155" letter-spacing="2" opacity="0">
    while(alive) { learn(); build(); ship(); }
    <animate attributeName="opacity" values="0;1" dur="1.2s" begin="3.4s" fill="freeze"/>
  </text>

  <!-- Outer border -->
  <rect x="0.5" y="0.5" width="859" height="259" fill="none" stroke="#1e293b" stroke-width="1"/>
</svg>

</div>

---

## 🧠 About Me

<table>
<tr>
<td valign="center">

```python
class OmPatil:
    name        = "Om Patil"
    role        = "AI Engineer"
    location    = "India 🇮🇳"
    passion     = ["LLMs", "Generative AI",
                   "MLOps", "Building cool stuff"]

    def say_hi(self):
        print("Hey there! I'm Om 👋")
        print("I turn caffeine ☕ and curiosity 🔍")
        print("into intelligent systems 🤖")

    def currently(self):
        return {
            "🔭 working_on"  : "AI Agents & LLMs",
            "🌱 learning"    : "Multimodal models",
            "💬 ask_me_about": "AI, ML, Python",
            "⚡ fun_fact"    : "I debug AI so you don't 😄"
        }
```

</td>
<td valign="center" align="center">
<img src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" width="300" alt="AI Engineer Animation"/>
</td>
</tr>
</table>

---

<div align="center">

## 🛠️ Tech Stack & Tools

### 🤖 AI / ML
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

### ⚙️ MLOps & Infrastructure
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### 🗄️ Data & Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,50:EC4899,100:8B5CF6&height=100&section=footer" width="100%"/>

</div>
