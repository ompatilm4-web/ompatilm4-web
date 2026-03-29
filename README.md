<div align="center">

<svg width="700" height="160" viewBox="0 0 700 160" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="glow">
      <feGaussianBlur stdDeviation="2.5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <pattern id="scanlines" x="0" y="0" width="700" height="4" patternUnits="userSpaceOnUse">
      <rect width="700" height="2" fill="black" opacity="0.08"/>
    </pattern>
  </defs>

  <!-- Terminal window background -->
  <rect width="700" height="160" rx="14" fill="#0d0d0d"/>

  <!-- Title bar -->
  <rect width="700" height="36" rx="14" fill="#1e1e1e"/>
  <rect y="22" width="700" height="14" fill="#1e1e1e"/>

  <!-- Traffic lights -->
  <circle cx="24" cy="18" r="7" fill="#ff5f57"/>
  <circle cx="46" cy="18" r="7" fill="#ffbd2e"/>
  <circle cx="68" cy="18" r="7" fill="#28c840"/>

  <!-- Title bar text -->
  <text x="350" y="23" font-family="'Courier New', monospace" font-size="12" fill="#666" text-anchor="middle">om@portfolio ~ zsh</text>

  <!-- Scanlines -->
  <rect width="700" height="160" rx="14" fill="url(#scanlines)"/>

  <!-- H -->
  <text x="40" y="108" font-family="'Courier New',monospace" font-size="52" font-weight="bold" fill="#00ff41" filter="url(#glow)" opacity="0">H
    <animate attributeName="opacity" values="0;1" keyTimes="0;1" dur="0.1s" begin="0.3s" fill="freeze"/>
  </text>
  <!-- i -->
  <text x="76" y="108" font-family="'Courier New',monospace" font-size="52" font-weight="bold" fill="#00ff41" filter="url(#glow)" opacity="0">i
    <animate attributeName="opacity" values="0;1" keyTimes="0;1" dur="0.1s" begin="0.55s" fill="freeze"/>
  </text>
  <!-- space -->
  <!-- I -->
  <text x="120" y="108" font-family="'Courier New',monospace" font-size="52" font-weight="bold" fill="#00e5ff" filter="url(#glow)" opacity="0">I
    <animate attributeName="opacity" values="0;1" keyTimes="0;1" dur="0.1s" begin="0.9s" fill="freeze"/>
  </text>
  <!-- ' -->
  <text x="145" y="108" font-family="'Courier New',monospace" font-size="52" font-weight="bold" fill="#00e5ff" filter="url(#glow)" opacity="0">'
    <animate attributeName="opacity" values="0;1" keyTimes="0;1" dur="0.1s" begin="1.1s" fill="freeze"/>
  </text>
  <!-- m -->
  <text x="163" y="108" font-family="'Courier New',monospace" font-size="52" font-weight="bold" fill="#00e5ff" filter="url(#glow)" opacity="0">m
    <animate attributeName="opacity" values="0;1" keyTimes="0;1" dur="0.1s" begin="1.3s" fill="freeze"/>
  </text>
  <!-- space -->
  <!-- O -->
  <text x="220" y="108" font-family="'Courier New',monospace" font-size="52" font-weight="bold" fill="#ff79c6" filter="url(#glow)" opacity="0">O
    <animate attributeName="opacity" values="0;1" keyTimes="0;1" dur="0.1s" begin="1.65s" fill="freeze"/>
  </text>
  <!-- m -->
  <text x="256" y="108" font-family="'Courier New',monospace" font-size="52" font-weight="bold" fill="#ff79c6" filter="url(#glow)" opacity="0">m
    <animate attributeName="opacity" values="0;1" keyTimes="0;1" dur="0.1s" begin="1.85s" fill="freeze"/>
  </text>
  <!-- space -->
  <!-- P -->
  <text x="313" y="108" font-family="'Courier New',monospace" font-size="52" font-weight="bold" fill="#ffb86c" filter="url(#glow)" opacity="0">P
    <animate attributeName="opacity" values="0;1" keyTimes="0;1" dur="0.1s" begin="2.15s" fill="freeze"/>
  </text>
  <!-- a -->
  <text x="349" y="108" font-family="'Courier New',monospace" font-size="52" font-weight="bold" fill="#ffb86c" filter="url(#glow)" opacity="0">a
    <animate attributeName="opacity" values="0;1" keyTimes="0;1" dur="0.1s" begin="2.35s" fill="freeze"/>
  </text>
  <!-- t -->
  <text x="378" y="108" font-family="'Courier New',monospace" font-size="52" font-weight="bold" fill="#ffb86c" filter="url(#glow)" opacity="0">t
    <animate attributeName="opacity" values="0;1" keyTimes="0;1" dur="0.1s" begin="2.55s" fill="freeze"/>
  </text>
  <!-- i -->
  <text x="400" y="108" font-family="'Courier New',monospace" font-size="52" font-weight="bold" fill="#ffb86c" filter="url(#glow)" opacity="0">i
    <animate attributeName="opacity" values="0;1" keyTimes="0;1" dur="0.1s" begin="2.75s" fill="freeze"/>
  </text>
  <!-- l -->
  <text x="420" y="108" font-family="'Courier New',monospace" font-size="52" font-weight="bold" fill="#ffb86c" filter="url(#glow)" opacity="0">l
    <animate attributeName="opacity" values="0;1" keyTimes="0;1" dur="0.1s" begin="2.95s" fill="freeze"/>
  </text>

  <!-- Blinking cursor -->
  <rect x="447" y="62" width="4" height="50" fill="#00ff41" opacity="1">
    <animate attributeName="opacity" values="1;0;1" dur="0.9s" begin="3.1s" repeatCount="indefinite"/>
    <animate attributeName="x" values="100;100;100;100;100;447" keyTimes="0;0.1;0.3;0.5;0.7;1" dur="3.1s" fill="freeze"/>
  </rect>

  <!-- Border glow -->
  <rect x="1" y="1" width="698" height="158" rx="13" fill="none" stroke="#00ff41" stroke-width="1" opacity="0.25"/>
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
