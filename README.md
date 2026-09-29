<!-- ============ HEADER ============ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:0A3D62,100:00E5FF&height=220&section=header&text=Abhishek%20Kumar&fontSize=52&fontColor=FFFFFF&animation=fadeIn&fontAlignY=38&desc=From%20syscalls%20to%20screens&descAlignY=58&descSize=18" width="100%" alt="header" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=00E5FF&center=true&vCenter=true&width=700&height=45&lines=Concurrent+systems+in+C+%F0%9F%A7%B5;Full-stack+MERN+developer+%F0%9F%8C%90;857%2B+DSA+problems+solved+%E2%9A%94%EF%B8%8F;LeetCode+Knight+%E2%80%A2+1860+rating+%F0%9F%8F%86;Open+to+remote+work+worldwide+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=abhiishhekk&label=PROFILE%20VIEWS&color=00E5FF&style=for-the-badge&labelColor=0D1117" alt="Profile views" />
<img src="https://img.shields.io/badge/NIT%20Allahabad-CSE%20'27-0A3D62?style=for-the-badge&labelColor=0D1117" alt="NIT Allahabad" />
<img src="https://img.shields.io/badge/Open%20to-Remote%20Work-00E5FF?style=for-the-badge&labelColor=0D1117" alt="Open to remote" />

<br/><br/>

<a href="https://www.linkedin.com/in/abhishek-kumar-init"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:abhishekkumar.init@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://abhiishhekk.github.io/Portfolio-Des/"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=vercel&logoColor=00E5FF" /></a>
<a href="https://leetcode.com/u/abhiishhek_k/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" /></a>

</div>

<br/>

<!-- ============ WHOAMI ============ -->
## `$ whoami`

```c
#include <stdio.h>
#include <pthread.h>

typedef struct {
    const char *name;
    const char *college;
    const char *focus[3];
    const char *stack[4];
    int   dsa_solved;
    int   leetcode_rating;
    int   open_to_remote;
} Engineer;

Engineer abhishek = {
    .name            = "Abhishek Kumar",
    .college         = "NIT Allahabad (MNNIT), B.Tech CSE '27",
    .focus           = { "Concurrent & multithreaded systems",
                         "Full-stack web (MERN)",
                         "Applied ML + RAG" },
    .stack           = { "C / C++", "Linux", "React + Node", "TensorFlow" },
    .dsa_solved      = 857,
    .leetcode_rating = 1860,
    .open_to_remote  = 1,   // flexible with time zones, async-friendly
};

int main(void) {
    pthread_mutex_lock(&coffee);   // avoid race conditions, always
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
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white" />

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

<img height="180" src="https://github-readme-stats.vercel.app/api?username=abhiishhekk&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00E5FF&icon_color=00E5FF&count_private=true&include_all_commits=true" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=abhiishhekk&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00E5FF&langs_count=8" />

<br/>

<img src="https://streak-stats.demolab.com/?user=abhiishhekk&theme=tokyonight&hide_border=true&background=0D1117&ring=00E5FF&fire=00E5FF&currStreakLabel=00E5FF" />

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=abhiishhekk&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&row=1&column=6" />

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

<img src="https://github-readme-activity-graph.vercel.app/graph?username=abhiishhekk&bg_color=0D1117&color=00E5FF&line=00E5FF&point=FFFFFF&area=true&area_color=00E5FF&hide_border=true&custom_title=Contribution%20Graph" width="100%" />

<br/><br/>

<img src="https://raw.githubusercontent.com/abhiishhekk/abhiishhekk/output/github-snake-dark.svg" alt="Snake animation" width="100%" />

</div>

<br/>

<!-- ============ CONTACT ============ -->
## `> contact`

<div align="center">

Got a systems problem, a product idea, or a role that fits? Let's talk.

**📧 [abhishekkumar.init@gmail.com](mailto:abhishekkumar.init@gmail.com)** · **💼 [LinkedIn](https://www.linkedin.com/in/abhishek-kumar-init)** · **🌐 [Portfolio](https://abhiishhekk.github.io/Portfolio-Des/)**

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00E5FF,50:0A3D62,100:0D1117&height=120&section=footer" width="100%" alt="footer" />

</div>