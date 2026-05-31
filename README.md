<h1 align="center">Namaste <img src="https://raw.githubusercontent.com/googlefonts/noto-emoji/main/png/128/emoji_u1f64f.png" alt="folded hands emoji" width="28" height="28">, I am Varun D Magar</h1>
<h3 align="center">Software Developer & DevOps Enthusiast</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/va-run23" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://va-run23.netlify.app" target="_blank"><img src="https://img.shields.io/badge/Portfolio-Visit-2196F3?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://drive.google.com/file/d/1eKkx9MG2bo5buwSegNKlfv3n00ckW7eC/view?usp=sharing" target="_blank"><img src="https://img.shields.io/badge/Resume-Download-4CAF50?style=for-the-badge&logo=googledrive&logoColor=white" alt="Resume" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=VA-run&color=0e75b6" alt="Profile Views" />
</p>

<h3 align="center"><em>"उद्यमेन हि सिद्ध्यन्ति कार्याणि न मनोरथैः" — Success is achieved through effort, not by mere wishes.</em></h3>

---

## Professional Summary

* **LeetCode Knight** | Peak Rating: 2102 | 500+ Day Coding Streak | 1000+ Day Chess Streak
* **2nd Runner-Up** | IoT Project Expo 2026, IIC-AICTE | **Bronze Medal** | Innovista 2.0 (3rd/50+ teams)
* **Technical Writer** | Publishing on self-built VSKript platform
* **Active Maintainer** | 3 production applications with ongoing feature development

---

## The Engineering Architect (INTJ-T)

I am a Full-Stack MERN Engineer with a systems-first mindset, driven by architectural precision and measurable outcomes. As an INTJ-T, I approach software development through:

* **Performance-Driven Architecture:** Designed APIs with optimized response times through cursor pagination, connection pooling, and strategic caching.
* **Security by Design:** Implemented defense-in-depth strategies across 3 production applications using JWT, RBAC, rate limiting, and XSS prevention.
* **Relentless Consistency:** Maintained a 500+ day coding streak while shipping production features across 3 deployed applications.

**Current Focus:** Containerization (Docker), AWS cloud architecture, and microservices patterns for scalable production systems.

---

<p align="center">
  <img src="https://streak-card23.vercel.app/api/streak-card?platforms=%5B%7B%22platform%22%3A%22github%22%2C%22username%22%3A%22va-run23%22%7D%2C%7B%22platform%22%3A%22gfg%22%2C%22username%22%3A%22neurovarun23%22%7D%2C%7B%22platform%22%3A%22leetcode%22%2C%22username%22%3A%22va-run23%22%7D%5D&name=My%20Streaks%20&greeting=&color=%231A1A2E" alt="Coding Streaks" />
</p>

---

# Featured Engineering Projects

<br/>

## **PrintBridge — IoT Cloud Printing System (PaaS)**
#### [Live Demo](https://printbridge-by-vps.onrender.com/) | [GitHub](https://github.com/VA-run23/IoT-Project)
**Role:** IoT Engineer & Full-Stack Developer | 4-Member Team (Team VPS) | *May 2026*
🏆 *2nd Runner-Up, IoT Project Expo 2026 — IIC, AICTE*
> <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white" /> <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" /> <img src="https://img.shields.io/badge/Razorpay-02042B?style=for-the-badge&logo=razorpay&logoColor=3395FF" /> <img src="https://img.shields.io/badge/ThingSpeak-0076A8?style=for-the-badge&logo=mathworks&logoColor=white" /> <img src="https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white" /> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />

* **Hybrid IoT Architecture:** Designed a three-layer system spanning cloud (Render-hosted Node.js, Cloudinary, Razorpay, ThingSpeak), edge (Arduino UNO R4 WiFi polling server every 5 seconds via HTTPS), and local (Node.js printer agent communicating over Serial UART at 115200 baud); implemented mark-before-execute duplicate print prevention to guarantee exactly-once job processing across polling cycles.
* **Hardware State Machine:** Built an IR proximity sensor pipeline on the output tray with an RGB LED indicator system (green: idle, blue: printing, yellow: collect pages, red: error) and a progressive buzzer that blocks subsequent jobs until tray clearance is detected, eliminating document mixing in high-volume environments.
* **Real-Time Analytics & Payments:** Integrated ThingSpeak for live IoT telemetry (revenue, queue length, colour ratio, printer status) updating every 15 seconds across customer and admin dashboards; Razorpay payment gateway with independent server-side receipt verification before any print command is dispatched.

## **VSKript — Production Blogging Platform**

#### [Live Demo](https://vskript.netlify.app) | Private Repository

**Role:** Full-Stack Developer | 3-Member Team | *Dec 2025 – Mar 2026*

> <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white" /> <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" /> <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" /> <img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />

* **Security & Performance:** Defense-in-depth via JWT httpOnly cookies, RBAC, bcrypt, and Token Bucket rate limiting; optimized API response times utilizing cursor pagination and database connection pooling.
* **Production Infrastructure:** Multi-container Docker architecture with Cloudinary CDN integration; actively publishing technical articles with ongoing IaaS and microservices iteration.
* **Efficiency:** Redux Toolkit state management with 40% bundle size reduction through code splitting and lazy loading.
* **Engagement:** Built custom GitHub-style activity calendar for user engagement metrics.

---

## **Digital Democracy – AI-Powered Civic Engagement Platform**

#### [Live Link](https://d-05-minor-project.netlify.app/) | Private Repository

**Role:** DevOps Engineer & Full-Stack Developer | 4-Member Team | *Sep 2025 – Dec 2025*

> <img src="https://img.shields.io/badge/Node.js-FFA500?style=for-the-badge&logo=nodedotjs&logoColor=white" /> <img src="https://img.shields.io/badge/React-FFA500?style=for-the-badge&logo=react&logoColor=white" /> <img src="https://img.shields.io/badge/MongoDB-FFFFFF?style=for-the-badge&logo=mongodb&logoColor=black" /> <img src="https://img.shields.io/badge/Docker-28A745?style=for-the-badge&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/Gemini_AI-4285F4?style=for-the-badge&logo=google&logoColor=white" />

* **Backend & System Engineering:** Engineered scalable RESTful API with MVC architecture featuring RBAC, event-driven notifications, and fault-tolerant NLP legal assistant powered by Gemini AI.
* **Database & Concurrency:** Designed normalized schemas with composite indexing and Optimistic Locking to prevent race conditions during high-concurrency voting events.
* **Security:** Stateless JWT APIs with XSS prevention, centralized error handling, and comprehensive unit testing via Jest.


---

# Side Projects

## **ABOVE_INFLUENCE — YouTube Consumption Analysis**

#### [Live App](https://above-influence.vercel.app/) | [Source Code](https://github.com/VA-run23/Above_Influence)

**Role:** Workflow Automation Engineer (n8n) | *Feb 2026*

> <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" /> <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" /> <img src="https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white" />

* **Workflow Automation:** Designed complete n8n pipeline handling YouTube data fetching, processing, and routing to AI analysis with 3-tier Gemini AI fallback strategy.
* **AI Integration:** Connected Google Gemini AI to generate personalized insights with fallback models for rate limit resilience.
* **Email Delivery:** Integrated Gmail API for automated report delivery directly to user inbox.

<p align="center">
  <img src="https://github.com/user-attachments/assets/b952e40b-75e8-4f72-b041-aef90b2059a8" alt="Above Influence n8n Workflow" width="400"/>
  <br/>
  <em>n8n Workflow Architecture</em>
</p>

---

## **Streak Card 23 — Unified Coding Activity Card**

#### [Live App](https://streak-card23.vercel.app/) | [Source Code](https://github.com/VA-run23/streak-card23)

**Role:** Solo Developer | *Weekend Project*

> <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" /> <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" /> <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />

* **Live Data:** Fetches real-time streak data from GitHub, LeetCode, and GeeksforGeeks APIs on each request for always up-to-date cards.
* **Customizable:** Multiple color themes and personalization options for developers to match their GitHub profile style.
* **Embeddable:** Generates ready-to-use Markdown/HTML snippets for GitHub READMEs and personal websites.
* **Impact:** 200+ cards generated and served via Vercel Serverless Functions, verified through function invocation logs, enabling developers to showcase unified coding activity.

<p align="center">
  <img src="https://github.com/user-attachments/assets/4b8dadbc-bdf1-42d3-90b2-c0b5d6d50c37" alt="Streak Card Dashboard" width="400"/>
  <br/>
  <em>Streak Card Generator Dashboard</em>
</p>

---

## Tech Stack & Tools

### Languages
<p>
  <img src="https://img.shields.io/badge/C%2B%2B-FFA500?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/JavaScript-FFA500?style=for-the-badge&logo=javascript&logoColor=white" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Python-FFA500?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-FFA500?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Java-FFA500?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/SQL-FFA500?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL" />
</p>

### Frontend Development
<p>
  <img src="https://img.shields.io/badge/React-007BFF?style=for-the-badge&logo=react&logoColor=white" alt="React" />
  <img src="https://img.shields.io/badge/Redux-007BFF?style=for-the-badge&logo=redux&logoColor=white" alt="Redux" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-007BFF?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
</p>

### Backend & Databases
<p>
  <img src="https://img.shields.io/badge/Node.js-FFFFFF?style=for-the-badge&logo=nodedotjs&logoColor=black" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express-FFFFFF?style=for-the-badge&logo=express&logoColor=black" alt="Express.js" />
  <img src="https://img.shields.io/badge/Socket.io-FFFFFF?style=for-the-badge&logo=socket.io&logoColor=black" alt="Socket.io" />
  <img src="https://img.shields.io/badge/MongoDB-FFFFFF?style=for-the-badge&logo=mongodb&logoColor=black" alt="MongoDB" />
  <img src="https://img.shields.io/badge/MySQL-FFFFFF?style=for-the-badge&logo=mysql&logoColor=black" alt="MySQL" />
  <img src="https://img.shields.io/badge/Mongoose-FFFFFF?style=for-the-badge&logo=mongoose&logoColor=black" alt="Mongoose" />
</p>

### DevOps & Cloud
<p>
  <img src="https://img.shields.io/badge/Git-28A745?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Docker-28A745?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/AWS-28A745?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/GitHub_Actions-28A745?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Vercel-28A745?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
  <img src="https://img.shields.io/badge/Linux-28A745?style=for-the-badge&logo=linux&logoColor=white" alt="Linux" />
</p>

### Tools & Testing
<p>
  <img src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white" alt="Jest" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
</p>

---

## Certifications & Achievements

**Certifications**
* **IBM DevOps and Software Engineering Professional Certificate** | [Credly Badges](https://www.coursera.org/account/accomplishments/professional-cert/79ACEP9QOPAG)
* <img src="https://img.shields.io/badge/AWS_Cloud_Practitioner-In_Progress-orange?style=flat-square&logo=amazon-aws" alt="AWS in progress" />

**Achievements**
* **2nd Runner-Up:** IoT Project Expo 2026, IIC-AICTE initiative — PrintBridge
* **Bronze Medal:** Innovista 2.0 (3rd/50+ teams) — Digital Democracy Platform (2025)
* **500+ Day Coding Streak** across GitHub, LeetCode, and GeeksforGeeks
* **1000+ Day Chess Streak** on chess.com (Sep 2023 to present)
* **LeetCode Knight** | Peak Rating: 2102
---

## GitHub Stats

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github-readme-stats-six-seven.vercel.app/api/top-langs/?username=VA-run23&layout=compact&langs_count=8&theme=github_dark&title_color=00bfff&text_color=ffffff" alt="Top Languages" height="200px"/>
    </td>
    <td align="center">
      <img src="https://github-readme-streak-stats-mu-lovat.vercel.app?user=VA-run23&theme=github-dark-blue&hide_border=true" alt="GitHub Streak" height="220px"/>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://leetcard.jacoblin.cool/VA-run23?theme=dark&font=Nunito&ext=heatmap" alt="LeetCode Stats" height="220px"/>
    </td>
    <td align="center">
      <img src="https://gfgstatscard.vercel.app/neurovarun23" alt="GFG stats" height="220px"/>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://leetcode.com/VA-run23" target="_blank"><img src="https://img.shields.io/badge/-LeetCode-FFA116?style=for-the-badge&logo=LeetCode&logoColor=black" /></a>
  <a href="https://auth.geeksforgeeks.org/user/neurovarun23" target="_blank"><img src="https://img.shields.io/badge/-GeeksforGeeks-298D46?style=for-the-badge&logo=GeeksforGeeks&logoColor=white" /></a>
</p>

---

<p align="center">
  <b>Open to Full-Stack Development, DevOps & Software Engineering opportunities.</b><br>
  <a href="https://drive.google.com/file/d/1eKkx9MG2bo5buwSegNKlfv3n00ckW7eC/view?usp=sharing" target="_blank"><strong>View Full Resume</strong></a>
</p>

<p align="center">
  <em>Fun Fact: I maintain a 500+ day coding streak because consistency beats intensity in the long run!</em>
</p>
