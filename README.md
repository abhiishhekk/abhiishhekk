<!-- ============ HEADER ============ -->
<div align="center">

<img src="./banner.svg" alt="Abhishek Kumar" width="100%" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=F0A868&center=true&vCenter=true&width=700&height=45&lines=Full-stack+MERN+developer;857%2B+DSA+problems+solved;LeetCode+Knight+%E2%80%A2+1860+rating;RAG+Powered+AI+Developer" alt="Typing SVG" />
</a>

<br/>

<img src="https://hits.sh/github.com/abhiishhekk/abhiishhekk.svg?view=today-total&label=VIEWS%20(TODAY%20%2F%20TOTAL)&style=for-the-badge&color=F0A868&labelColor=1C1C1F" alt="Profile views" />
<img src="https://img.shields.io/badge/NIT%20Allahabad-CSE%20'27-2A2A2E?style=for-the-badge&labelColor=1C1C1F" alt="NIT Allahabad" />

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
        857+,    // DSA problems solved
        Knight,   // LeetCode 
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

<img src="https://img.shields.io/github/followers/abhiishhekk?label=FOLLOWERS&style=for-the-badge&labelColor=1C1C1F&color=F0A868" alt="Followers" />
<img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2Fabhiishhekk&query=%24.public_repos&label=PUBLIC%20REPOS&style=for-the-badge&labelColor=1C1C1F&color=F0A868" alt="Public repos" />

<br/><br/>

<img src="https://streak-stats.demolab.com/?user=abhiishhekk&theme=dark&hide_border=true&background=0D1117&stroke=2A2A2E&currStreakNum=ECE8E1&sideNums=ECE8E1&sideLabels=8B8B8B&dates=8B8B8B&ring=F0A868&fire=F0A868&currStreakLabel=F0A868" alt="GitHub streak" />

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

<img src="https://raw.githubusercontent.com/abhiishhekk/abhiishhekk/output/github-snake-dark.svg" alt="Snake animation" width="100%" />

</div>

<br/>

<!-- ============ CONTACT ============ -->
## `> contact`

<div align="center">


**📧 [abhishekkumar.init@gmail.com](mailto:abhishekkumar.init@gmail.com)** · **💼 [LinkedIn](https://www.linkedin.com/in/abhishek-kumar-init)** · **🌐 [Portfolio](https://abhiishhekk.github.io/Portfolio-Des/)**


</div>
