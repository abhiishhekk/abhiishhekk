<!-- ============ HEADER ============ -->
<div align="center">

<img src="./banner.svg" alt="Abhishek Kumar" width="100%" />"

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=F0A868&center=true&vCenter=true&width=700&height=45&lines=Concurrent+systems+in+C+%F0%9F%A7%B5;Full-stack+MERN+developer+%F0%9F%8C%90;857%2B+DSA+problems+solved+%E2%9A%94%EF%B8%8F;LeetCode+Knight+%E2%80%A2+1860+rating+%F0%9F%8F%86;Open+to+remote+work+worldwide+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=abhiishhekk&label=PROFILE%20VIEWS&color=F0A868&style=for-the-badge&labelColor=1C1C1F" alt="Profile views" />
<img src="https://img.shields.io/badge/NIT%20Allahabad-CSE%20'27-2A2A2E?style=for-the-badge&labelColor=1C1C1F" alt="NIT Allahabad" />
<img src="https://img.shields.io/badge/Open%20to-Remote%20Work-F0A868?style=for-the-badge&labelColor=1C1C1F" alt="Open to remote" />

<br/><br/>

<a href="https://www.linkedin.com/in/abhishek-kumar-init"><img src="https://img.shields.io/badge/LinkedIn-1C1C1F?style=for-the-badge&logo=linkedin&logoColor=ECE8E1" /></a>
<a href="mailto:abhishekkumar.init@gmail.com"><img src="https://img.shields.io/badge/Email-1C1C1F?style=for-the-badge&logo=gmail&logoColor=ECE8E1" /></a>
<a href="https://abhiishhekk.github.io/Portfolio-Des/"><img src="https://img.shields.io/badge/Portfolio-1C1C1F?style=for-the-badge&logo=vercel&logoColor=ECE8E1" /></a>
<a href="https://leetcode.com/u/abhiishhek_k/"><img src="https://img.shields.io/badge/LeetCode-1C1C1F?style=for-the-badge&logo=leetcode&logoColor=ECE8E1" /></a>

</div>

<br/>

<!-- ============ WHOAMI ============ -->
## `$ whoami`

```cpp
#include <iostream>
#include <mutex>
#include <string>
#include <vector>

struct Engineer {
    std::string name;
    std::string college;
    std::vector<std::string> focus;
    std::vector<std::string> stack;
    int  dsaSolved;
    int  leetcodeRating;
    bool openToRemote;
};

void build(const Engineer& e);

int main() {
    std::mutex coffee;

    Engineer abhishek{
        "Abhishek Kumar",
        "NIT Allahabad (MNNIT), B.Tech CSE '27",
        { "Concurrent & multithreaded systems",
          "Full-stack web (MERN)",
          "Applied ML + RAG" },
        { "C / C++", "Linux", "React + Node", "TensorFlow" },
        857,    // DSA problems solved
        1860,   // LeetCode rating
        true    // flexible with time zones, async-friendly
    };

    std::lock_guard<std::mutex> lock(coffee);  // no race conditions, ever
    build(abhishek);
    return 0;
}
```

<br/>

<!-- ============ TECH STACK ============ -->
## `> tech_stack`

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=c,cpp,js,py,mysql&theme=dark" />

**Web**

<img src="https://skillicons.dev/icons?i=react,nodejs,express,mongodb,fastapi,materialui&theme=dark" />

**ML / AI**

<img src="https://skillicons.dev/icons?i=tensorflow&theme=dark" />
<img src="https://img.shields.io/badge/LangChain-1C1C1F?style=for-the-badge&logo=langchain&logoColor=ECE8E1" />
<img src="https://img.shields.io/badge/Gemini-1C1C1F?style=for-the-badge&logo=googlegemini&logoColor=ECE8E1" />

**Tools & Cloud**

<img src="https://skillicons.dev/icons?i=linux,git,github,gcp,postman,vscode&theme=dark" />

</div>

<br/>

<!-- ============ PROJECTS ============ -->
## `> featured_projects`

<table>
<tr>
<td width="50%" valign="top">

### 🧵 [ProcTrace](https://github.com/abhiishhekk/ProcTrace)
**Real-time Linux telemetry system**

A multithreaded C daemon samples CPU and memory stats from `/proc` for every running process, and a decoupled Express backend serves them to a React dashboard.

- pthreads sampler with a **mutex-fixed race condition**
- In-memory caching → **sub-millisecond** REST responses
- React + Shadcn/ui live dashboard

`C` `pthreads` `Linux /proc` `Node.js` `Express` `React`

</td>
<td width="50%" valign="top">

### 🌾 [KrishiMitra](https://github.com/abhiishhekk/KrishiMitra)
**AI crop-disease detection + RAG advisor**

ResNet50 classifier for leaf diseases, paired with a Gemini + LangChain advisor that streams remedies in Hindi and English.

- **98.65% test accuracy**, 22K+ images, 21 classes
- Float16 TFLite model, just **45 MB**
- FastAPI + Express microservices, rate-limited on Cloud Run

`TensorFlow` `ResNet50` `LangChain` `FastAPI` `MERN`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛠️ [Complaint Tracking System](https://github.com/abhiishhekk/Complaint-Tracking-System)
**Multi-role civic complaint platform**

Citizens file complaints with image proof, staff resolve them, and admins audit before dispatch.

- **RBAC** for Citizen, Staff and Admin with permission middleware
- Email activation via Brevo
- MongoDB aggregation dashboards for SLAs and workload

`React` `Node.js` `Express` `MongoDB` `Material-UI`

</td>
<td width="50%" valign="top">

### 📈 More on my portfolio
Full write-ups, live demos and architecture notes live on my portfolio.

**[Visit portfolio →](https://abhiishhekk.github.io/Portfolio-Des/)**

<br/>

Or browse all repositories:

**[github.com/abhiishhekk?tab=repositories](https://github.com/abhiishhekk?tab=repositories)**

</td>
</tr>
</table>

<br/>

<!-- ============ STATS ============ -->
## `> github_stats`

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=abhiishhekk&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=F0A868&icon_color=F0A868&text_color=C9C5BD&count_private=true&include_all_commits=true" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=abhiishhekk&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&title_color=F0A868&text_color=C9C5BD&langs_count=8" />

<br/>

<img src="https://streak-stats.demolab.com/?user=abhiishhekk&theme=dark&hide_border=true&background=0D1117&stroke=2A2A2E&currStreakNum=ECE8E1&sideNums=ECE8E1&sideLabels=8B8B8B&dates=8B8B8B&ring=F0A868&fire=F0A868&currStreakLabel=F0A868" />

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=abhiishhekk&theme=gruvbox&no-frame=true&no-bg=true&margin-w=8&row=1&column=6" />

</div>

<br/>

<!-- ============ COMPETITIVE PROGRAMMING ============ -->
## `> competitive_programming`

<div align="center">

<img src="https://leetcard.jacoblin.cool/abhiishhek_k?theme=dark&font=Fira%20Code&ext=heatmap" alt="LeetCode stats" />

| 🏅 Badge | 📊 Rating | 🧮 Solved | 🏁 Contests |
|:---:|:---:|:---:|:---:|
| **Knight** | **1860** (Top 15%) | **857+** | **35+** weekly |

</div>

<br/>

<!-- ============ ACHIEVEMENTS ============ -->
## `> achievements`

- 🎓 **JEE Mains 2023:** AIR 5,581 (99.52 percentile)
- 🎓 **JEE Advanced 2023:** AIR 12,725
- 🧠 **Young Turks National Talent Exam:** 97.46 percentile
- ✅ **HackerRank:** Software Engineer Intern Assessment (Intermediate) certified

<br/>

<!-- ============ ACTIVITY ============ -->
## `> contribution_activity`

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=abhiishhekk&bg_color=0D1117&color=F0A868&line=F0A868&point=FFFFFF&area=true&area_color=F0A868&hide_border=true&custom_title=Contribution%20Graph" width="100%" />

<br/><br/>

<img src="https://raw.githubusercontent.com/abhiishhekk/abhiishhekk/output/github-snake-dark.svg" alt="Snake animation" width="100%" />

</div>

<br/>

<!-- ============ CONTACT ============ -->
## `> contact`

<div align="center">

Got a systems problem, a product idea, or a role that fits? Let's talk.

**📧 [abhishekkumar.init@gmail.com](mailto:abhishekkumar.init@gmail.com)** · **💼 [LinkedIn](https://www.linkedin.com/in/abhishek-kumar-init)** · **🌐 [Portfolio](https://abhiishhekk.github.io/Portfolio-Des/)**


</div>