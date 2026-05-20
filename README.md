<!-- Header Banner -->
<div align="center">
  <img src="assets/header_banner.svg" alt="Saddiq Ur Rehman - Header Banner" width="100%" />
</div>

<br/>

<!-- Social Badges -->
<div align="center">

[![Website](https://img.shields.io/badge/Portfolio-isaddiq.github.io-9B72CF?style=for-the-badge&logo=github-pages&logoColor=white)](https://isaddiq.github.io/)
[![Email](https://img.shields.io/badge/Email-saddiqurrehman@khu.ac.kr-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:saddiqurrehman@khu.ac.kr)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saddiq-ur-rehman-b79212138/)

</div>

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=isaddiq&color=9B72CF&style=for-the-badge&label=Profile+Views)
![GitHub followers](https://img.shields.io/github/followers/isaddiq?label=Followers&style=for-the-badge&color=764ba2)

</div>

---

## 🧑‍🔬 About Me

<img align="right" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="260" alt="coding gif" style="border-radius: 8px; margin-left: 15px;"/>

I am a **PhD Candidate** at the **Department of Architecture, Kyung Hee University, South Korea**, specializing in the intersection of **Building Information Modeling (BIM)**, **Extended Reality (XR)**, and **AI-driven design automation** for the AEC industry.

My research focuses on creating **interoperable digital workflows** that bridge the gap between BIM authoring platforms and immersive real-time environments — enabling smarter, more connected, and highly automated construction processes.

*   **📍 Location:** Seoul, South Korea
*   **🎓 Degree:** PhD in Architecture (Expected Q3 2026)
*   **🔬 Laboratory:** [Information Technology in Architecture Lab (Italab)](http://italab.khu.ac.kr/)

<br clear="right"/>

---

## 🎯 Research Focus & Pillars

Here is a visual map of my PhD research focus areas orbiting our core digital twin and design automation systems:

<div align="center">
  <img src="assets/research_orbit.svg" alt="PhD Research Focus Orbit Diagram" width="100%" />
</div>

### 🔬 Core Research Domains
*   **BIM–XR Integration:** Establishing cross-platform pipelines and semantic data exchange mechanisms.
*   **4D BIM Simulation:** VR-based construction scheduling, workflow planning, and prefabrication assemblies.
*   **Digital Twins:** Creating frameworks for Design for Manufacture and Assembly (DfMA) tracking.
*   **Mixed Reality (MR):** Developing voice-assisted headsets (HoloLens 2) for construction inspection and QC.
*   **AI Design Automation:** Implementing machine learning/LLM agents for design queries and layout automation.

---

## 🧩 Featured Projects

Click on the tabs below to expand and explore my primary research projects and pipelines.

<details>
<summary><b>🔧 Project 1: BIMUniXchange — Cross-Platform Semantic Exchange</b></summary>
<br/>

> *A semantic data exchange framework enabling interoperable BIM-to-XR pipelines across Autodesk Revit, Graphisoft ArchiCAD, and real-time game engines.*

### Pipeline Architecture
Here is how BIMUniXchange extracts structural properties and maps them directly into Unity/Unreal coordinates:

<div align="center">
  <img src="assets/bim_xr_pipeline.svg" alt="BIMUniXchange Pipeline Diagram" width="100%" />
</div>

### ⚙️ Key Technical Features
*   **📦 Semantic Export:** Extracts IFC metadata, material databases, and structural element hierarchies.
*   **🔗 Multi-Platform Support:** Fully supports Revit (OBJ geometry exporter) and ArchiCAD (FBX layout exporter).
*   **🔁 Relational SQLite Mapper:** Bridges element IDs bidirectionally, maintaining data integrity during round-tripping.
*   **🥽 Real-time Optimization:** Automatically optimizes geometry meshes for real-time mobile/standalone VR rendering.

</details>

<details>
<summary><b>🏭 Project 2: Modular Factory 4D BIM Simulation</b></summary>
<br/>

> *Immersive Virtual Reality environment for planning, simulating, and reviewing modular construction factory workflows.*

### 🛠️ Production Sequence Sim
Our system allows engineers to visualize and scrub through the factory floor timeline across 6 key phases:

```
[ Framing ] ──> [ MEP Rough-In ] ──> [ Enclosure ] ──> [ Finishes ] ──> [ Quality Control ] ──> [ Delivery ]
```

### 🎮 Features
*   **First-Person Navigation:** Teleportation and physics-based collision in VR.
*   **Interactive BIM Components:** Pick up, inspect, and snap modular wall/ceiling units.
*   **Timeline Scrubbing:** Slide through the construction schedule in real-time.
*   **Progress Dashboard:** Web-linked metrics showing material availability and assembly completion rates.

</details>

<details>
<summary><b>🗣️ Project 3: Voice-Activated MR Inspection Assistant</b></summary>
<br/>

> *AI-powered natural language interface overlaid on BIM components via HoloLens 2, powered by OpenAI & Azure Speech.*

### 🎙️ Immersive User Interface
*   **Hands-free Voice Commands:** Query any BIM element on-site ("*What is the structural rating of this beam?*").
*   **Visual Highlights:** Overlays colored highlights directly on structural components representing inspection status (Green: Checked, Orange: Warning, Red: Error).
*   **Real-time Logging:** Transcribes inspectorial voice notes and updates the central SQLite BIM database automatically via web APIs.

</details>

---

## 🛠️ Technology Stack

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4>🏛️ AEC & BIM Platforms</h4>
      <img src="https://img.shields.io/badge/Autodesk%20Revit-0696D7?style=flat-square&logo=autodesk&logoColor=white" alt="Revit"/>
      <img src="https://img.shields.io/badge/ArchiCAD-1B365D?style=flat-square&logo=graphisoft&logoColor=white" alt="ArchiCAD"/>
      <img src="https://img.shields.io/badge/AutoCAD-E51050?style=flat-square&logo=autodesk&logoColor=white" alt="AutoCAD"/>
      <img src="https://img.shields.io/badge/Navisworks-0696D7?style=flat-square&logo=autodesk&logoColor=white" alt="Navisworks"/>
      <img src="https://img.shields.io/badge/Dynamo-FFD23F?style=flat-square&logo=autodesk&logoColor=black" alt="Dynamo"/>
    </td>
    <td width="50%" valign="top">
      <h4>🥽 XR & Game Engines</h4>
      <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white" alt="Unity"/>
      <img src="https://img.shields.io/badge/Unreal%20Engine-0E1128?style=flat-square&logo=unrealengine&logoColor=white" alt="Unreal"/>
      <img src="https://img.shields.io/badge/HoloLens%202-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="HoloLens 2"/>
      <img src="https://img.shields.io/badge/Meta%20Quest-1C1E20?style=flat-square&logo=meta&logoColor=white" alt="Meta Quest"/>
      <img src="https://img.shields.io/badge/OpenXR-FF6B35?style=flat-square&logo=khronos&logoColor=white" alt="OpenXR"/>
      <img src="https://img.shields.io/badge/MRTK-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="MRTK"/>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>💻 Programming & AI APIs</h4>
      <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white" alt="C#"/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
      <img src="https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI API"/>
      <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white" alt="Azure"/>
    </td>
    <td width="50%" valign="top">
      <h4>🔄 Data & Interoperability</h4>
      <img src="https://img.shields.io/badge/IFC%20%2F%20OpenBIM-FF6B35?style=flat-square&logoColor=white" alt="IFC / OpenBIM"/>
      <img src="https://img.shields.io/badge/FBX-0696D7?style=flat-square&logo=autodesk&logoColor=white" alt="FBX"/>
      <img src="https://img.shields.io/badge/OBJ%20%2F%20glTF-00D084?style=flat-square&logoColor=white" alt="OBJ / glTF"/>
      <img src="https://img.shields.io/badge/CSV%20%2F%20JSON-000000?style=flat-square&logo=json&logoColor=white" alt="CSV / JSON"/>
      <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite"/>
    </td>
  </tr>
</table>

---

## 📊 GitHub Analytics

<div align="center">

<!-- Summary cards grid -->
<table border="0" cellpadding="0" cellspacing="0">
  <tr>
    <td colspan="3" align="center">
      <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=isaddiq&theme=tokyonight" width="100%" alt="Profile Summary Details" style="margin-bottom: 10px;" />
    </td>
  </tr>
  <tr>
    <td width="33%" align="center">
      <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=isaddiq&theme=tokyonight" width="100%" alt="GitHub Stats" />
    </td>
    <td width="33%" align="center">
      <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=isaddiq&theme=tokyonight" width="100%" alt="Top Languages by Commits" />
    </td>
    <td width="33%" align="center">
      <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=isaddiq&theme=tokyonight" width="100%" alt="Top Languages by Repos" />
    </td>
  </tr>
</table>

</div>

---

## 🌟 Let's Collaborate

I'm always open to connecting and collaborating with researchers, developers, and industry leaders working on:
*   **🏗️ BIM–XR Integration** (workflows, schemas, geometry pipelines)
*   **🤖 AI in Construction** (automatic design reviews, agentic AEC systems)
*   **📦 Modular / DfMA** (prefabricated structural planning, sensor integrations)
*   **🎓 Academic Research** (paper writing, research grants)

<div align="center">

[![Email](https://img.shields.io/badge/Send%20Email-saddiqurrehman@khu.ac.kr-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:saddiqurrehman@khu.ac.kr)
[![Portfolio](https://img.shields.io/badge/Visit%20Portfolio-isaddiq.github.io-9B72CF?style=for-the-badge&logo=github-pages&logoColor=white)](https://isaddiq.github.io/)
[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saddiq-ur-rehman-b79212138/)

<br/>

![PhD Candidate](https://img.shields.io/badge/PhD-Candidate-FFD700?style=flat-square)
![BIM Researcher](https://img.shields.io/badge/BIM-Researcher-00C853?style=flat-square)
![XR Developer](https://img.shields.io/badge/XR-Developer-9B72CF?style=flat-square)
![AI Enthusiast](https://img.shields.io/badge/AI-Enthusiast-FF6B35?style=flat-square)

</div>

---

<div align="center">

*"The future of construction lies at the intersection of physical precision and digital intelligence."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,30&height=120&section=footer&animation=fadeIn" width="100%" />

</div>
