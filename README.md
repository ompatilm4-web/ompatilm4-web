<div align="center">

<svg width="100%" viewBox="0 0 860 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="bg" cx="50%" cy="50%" r="60%">
      <stop offset="0%" stop-color="#0f0c29"/>
      <stop offset="50%" stop-color="#1a0533"/>
      <stop offset="100%" stop-color="#050510"/>
    </radialGradient>
    <radialGradient id="orb1" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#8B5CF6" stop-opacity="0.7"/>
      <stop offset="100%" stop-color="#8B5CF6" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="orb2" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#EC4899" stop-opacity="0.6"/>
      <stop offset="100%" stop-color="#EC4899" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="orb3" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#06B6D4" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#06B6D4" stop-opacity="0"/>
    </radialGradient>
    <filter id="textglow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="softglow">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <linearGradient id="namegrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#a78bfa"/>
      <stop offset="40%" stop-color="#f472b6"/>
      <stop offset="100%" stop-color="#38bdf8"/>
    </linearGradient>
    <linearGradient id="linegrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#8B5CF6" stop-opacity="0"/>
      <stop offset="30%"  stop-color="#8B5CF6" stop-opacity="1"/>
      <stop offset="70%"  stop-color="#EC4899" stop-opacity="1"/>
      <stop offset="100%" stop-color="#EC4899" stop-opacity="0"/>
    </linearGradient>
    <clipPath id="nameClip">
      <rect x="0" y="80" width="0" height="120">
        <animate attributeName="width" from="0" to="860" dur="1.8s" begin="0.4s" fill="freeze" calcMode="spline" keySplines="0.4 0 0.2 1"/>
      </rect>
    </clipPath>
    <clipPath id="subClip">
      <rect x="200" y="190" width="0" height="60">
        <animate attributeName="width" from="0" to="460" dur="1.2s" begin="2.4s" fill="freeze" calcMode="spline" keySplines="0.4 0 0.2 1"/>
      </rect>
    </clipPath>
  </defs>

  <rect width="860" height="280" rx="16" fill="url(#bg)"/>

  <ellipse cx="160" cy="130" rx="140" ry="130" fill="url(#orb1)">
    <animate attributeName="cx" values="160;200;140;160" dur="8s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="130;100;160;130" dur="8s" repeatCount="indefinite"/>
  </ellipse>
  <ellipse cx="700" cy="150" rx="130" ry="120" fill="url(#orb2)">
    <animate attributeName="cx" values="700;660;730;700" dur="10s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="150;180;120;150" dur="10s" repeatCount="indefinite"/>
  </ellipse>
  <ellipse cx="430" cy="260" rx="180" ry="80" fill="url(#orb3)">
    <animate attributeName="cy" values="260;240;270;260" dur="7s" repeatCount="indefinite"/>
  </ellipse>

  <g opacity="0.7">
    <circle cx="80"  cy="30"  r="1.2" fill="white"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.1s" repeatCount="indefinite"/></circle>
    <circle cx="200" cy="55"  r="0.9" fill="white"><animate attributeName="opacity" values="1;0.3;1"   dur="1.7s" repeatCount="indefinite"/></circle>
    <circle cx="350" cy="25"  r="1.4" fill="#a78bfa"><animate attributeName="opacity" values="0.5;1;0.5" dur="2.8s" repeatCount="indefinite"/></circle>
    <circle cx="480" cy="40"  r="0.8" fill="white"><animate attributeName="opacity" values="1;0.4;1"   dur="1.4s" repeatCount="indefinite"/></circle>
    <circle cx="620" cy="20"  r="1.1" fill="#38bdf8"><animate attributeName="opacity" values="0.3;1;0.3" dur="2.3s" repeatCount="indefinite"/></circle>
    <circle cx="760" cy="45"  r="1.3" fill="white"><animate attributeName="opacity" values="0.7;1;0.7" dur="1.9s" repeatCount="indefinite"/></circle>
    <circle cx="820" cy="80"  r="0.8" fill="#f472b6"><animate attributeName="opacity" values="1;0.3;1"   dur="2.5s" repeatCount="indefinite"/></circle>
    <circle cx="50"  cy="220" r="1.0" fill="white"><animate attributeName="opacity" values="0.4;0.9;0.4" dur="3.1s" repeatCount="indefinite"/></circle>
    <circle cx="780" cy="230" r="1.2" fill="white"><animate attributeName="opacity" values="0.9;0.3;0.9" dur="2.0s" repeatCount="indefinite"/></circle>
    <circle cx="140" cy="250" r="0.8" fill="#a78bfa"><animate attributeName="opacity" values="0.5;1;0.5" dur="1.6s" repeatCount="indefinite"/></circle>
    <circle cx="700" cy="260" r="1.1" fill="white"><animate attributeName="opacity" values="1;0.4;1"   dur="2.4s" repeatCount="indefinite"/></circle>
    <circle cx="550" cy="15"  r="0.9" fill="#f472b6"><animate attributeName="opacity" values="0.3;1;0.3" dur="1.8s" repeatCount="indefinite"/></circle>
  </g>

  <line x1="0" y1="185" x2="860" y2="185" stroke="url(#linegrad)" stroke-width="0.8" opacity="0.5"/>

  <g clip-path="url(#nameClip)" filter="url(#textglow)">
    <text x="430" y="168" font-family="'Courier New', Courier, monospace" font-size="78" font-weight="900" text-anchor="middle" fill="url(#namegrad)" letter-spacing="6">OM PATIL</text>
  </g>

  <rect x="692" y="100" width="5" height="72" fill="#f472b6" rx="2" opacity="0">
    <animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.3;0.31;0.8;0.81;1" dur="1s" begin="2.2s" repeatCount="indefinite"/>
  </rect>

  <g clip-path="url(#subClip)">
    <text x="430" y="225" font-family="'Courier New', Courier, monospace" font-size="18" font-weight="400" text-anchor="middle" fill="#94a3b8" letter-spacing="5">✦ AI ENGINEER ✦ INDIA ✦</text>
  </g>

  <g filter="url(#softglow)" opacity="0">
    <text x="22"  y="190" font-family="'Courier New', monospace" font-size="90" fill="#8B5CF6" opacity="0.25">〈</text>
    <text x="784" y="190" font-family="'Courier New', monospace" font-size="90" fill="#8B5CF6" opacity="0.25">/〉</text>
    <animate attributeName="opacity" values="0;1" dur="1s" begin="0.2s" fill="freeze"/>
  </g>

  <text x="430" y="265" font-family="'Courier New', monospace" font-size="11" text-anchor="middle" fill="#475569" letter-spacing="3" opacity="0">
    while(alive) { learn(); build(); repeat(); }
    <animate attributeName="opacity" values="0;1" dur="1s" begin="3.2s" fill="freeze"/>
  </text>

  <rect x="1" y="1" width="858" height="278" rx="16" fill="none" stroke="#8B5CF6" stroke-width="1" opacity="0.3"/>
  <rect x="3" y="3" width="854" height="274" rx="15" fill="none" stroke="#EC4899" stroke-width="0.4" opacity="0.2"/>
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
