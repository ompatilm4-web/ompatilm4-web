<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8B5CF6,50:EC4899,100:06B6D4&height=120&section=header&fontSize=60&fontColor=ffffff" width="100%"/>

</div>

<div align="center">

<svg width="860" height="120" viewBox="0 0 860 120" xmlns="http://www.w3.org/2000/svg">
  <rect width="860" height="120" rx="12" fill="#0a0a0a"/>
  <!-- LED grid dots -->
  <rect width="860" height="120" rx="12" fill="url(#dots)" opacity="0.18"/>
  <defs>
    <pattern id="dots" x="0" y="0" width="10" height="10" patternUnits="userSpaceOnUse">
      <circle cx="5" cy="5" r="1" fill="#00ff41"/>
    </pattern>
    <!-- Glow filter -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <!-- Scanline overlay -->
    <pattern id="scanlines" x="0" y="0" width="860" height="4" patternUnits="userSpaceOnUse">
      <rect width="860" height="2" fill="black" opacity="0.15"/>
    </pattern>
  </defs>

  <!-- Outer LED border glow -->
  <rect x="2" y="2" width="856" height="116" rx="11" fill="none" stroke="#00ff41" stroke-width="1.5" opacity="0.4"/>
  <rect x="5" y="5" width="850" height="110" rx="10" fill="none" stroke="#00ff41" stroke-width="0.5" opacity="0.2"/>

  <!-- Scrolling marquee text -->
  <clipPath id="clip">
    <rect x="20" y="0" width="820" height="120"/>
  </clipPath>
  <g clip-path="url(#clip)" filter="url(#glow)">
    <!-- Main scrolling text -->
    <text font-family="'Courier New', Courier, monospace" font-size="42" font-weight="bold" fill="#00ff41" y="72" letter-spacing="3">
      <tspan>👋 Hi there! I'm OM PATIL &nbsp;&nbsp;&nbsp;·&nbsp;&nbsp;&nbsp; 🤖 AI Engineer &nbsp;&nbsp;&nbsp;·&nbsp;&nbsp;&nbsp; 👋 Hi there! I'm OM PATIL &nbsp;&nbsp;&nbsp;·&nbsp;&nbsp;&nbsp; 🤖 AI Engineer &nbsp;&nbsp;&nbsp;</tspan>
      <animate attributeName="x" from="860" to="-2200" dur="14s" repeatCount="indefinite"/>
    </text>
    <!-- Shadow/echo layer for LED depth -->
    <text font-family="'Courier New', Courier, monospace" font-size="42" font-weight="bold" fill="#005c1a" y="74" letter-spacing="3" opacity="0.5">
      <tspan>👋 Hi there! I'm OM PATIL &nbsp;&nbsp;&nbsp;·&nbsp;&nbsp;&nbsp; 🤖 AI Engineer &nbsp;&nbsp;&nbsp;·&nbsp;&nbsp;&nbsp; 👋 Hi there! I'm OM PATIL &nbsp;&nbsp;&nbsp;·&nbsp;&nbsp;&nbsp; 🤖 AI Engineer &nbsp;&nbsp;&nbsp;</tspan>
      <animate attributeName="x" from="860" to="-2200" dur="14s" repeatCount="indefinite"/>
    </text>
  </g>

  <!-- Scanline effect overlay -->
  <rect width="860" height="120" rx="12" fill="url(#scanlines)" opacity="1"/>

  <!-- Corner brackets for LED display look -->
  <polyline points="20,10 10,10 10,20" fill="none" stroke="#00ff41" stroke-width="2" opacity="0.8"/>
  <polyline points="840,10 850,10 850,20" fill="none" stroke="#00ff41" stroke-width="2" opacity="0.8"/>
  <polyline points="20,110 10,110 10,100" fill="none" stroke="#00ff41" stroke-width="2" opacity="0.8"/>
  <polyline points="840,110 850,110 850,100" fill="none" stroke="#00ff41" stroke-width="2" opacity="0.8"/>
</svg>

</div>

---

<div align="center">

### ✨ `while (alive) { eat(); sleep(); build_AI(); repeat(); }` ✨

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
