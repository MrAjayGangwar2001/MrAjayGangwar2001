<div align="center">

![Animated Header](https://capsule-render.vercel.app/api?type=waving&color=0:0077B5,100:6DB33F&height=220&section=header&text=Ajay%20Gangwar&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Full%20Stack%20Java%20Developer%20%7C%20Spring%20Boot%20%E2%80%A2%20React%20%E2%80%A2%20System%20Design&descAlignY=55&descSize=18)

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=22&duration=3000&pause=800&color=6DB33F&center=true&vCenter=true&width=900&lines=Building+production+systems+that+actually+work+at+scale;Redis+distributed+locking+%2B+Kafka+%2B+real+concurrency;Not+just+POCs+%E2%80%94+systems+that+survive+real+load" alt="Typing SVG" />
</a>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ajay-gangwar-5234b2268)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:gangwar030@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat-square&logo=whatsapp&logoColor=white)](https://wa.me/919720576210)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-ajay-gangwar.vercel.app/)

<img src="https://komarev.com/ghpvc/?username=MrAjayGangwar2001&style=flat-square&color=6DB33F&label=Profile+Views" alt="profile views" />

---

</div>

## 🎯 About Me

I'm a **Full Stack Java Developer** with **1.1+ years** of production experience building systems that don't just handle happy-path scenarios.

Real concurrency challenges. Real payment flows. Real async workloads.

**My focus:**
- 🔒 Preventing race conditions with **Redis distributed locking** + optimistic concurrency control
- 📡 Event-driven architecture with **Kafka** for decoupled, scalable systems  
- 🧪 Integration tests that prove code works **under load**, not just in theory
- ☁️ Cloud deployment & DevOps (**AWS EC2, S3, CloudFront, GitHub Actions**)
- 🎓 **MCA** — Dr. A.P.J. Abdul Kalam Technical University (AKTU)

**Philosophy:** I'd rather ship something that handles 50 concurrent users correctly than something that impresses in a 2-minute demo.

---

## 🚀 Flagship Project

### [**StubLine** — Real-Time Event Booking & Payment Platform](https://github.com/MrAjayGangwar2001/stubline)
*Solving the hardest problem in ticketing: preventing double-bookings at scale*

```
Problem: 500 users, 10 available seats, all clicking "Book" at 3:00 PM
Solution: Redis atomic locks + JPA @Version + Testcontainers proving it works
```

**What makes this production-ready:**

| Feature | How It Works |
|---------|-------------|
| **🔒 Double-Booking Prevention** | Redis `SETNX` as the first line of defense; JPA optimistic locking (`@Version`) as an independent fallback. Proven with concurrent threads hammering the same seat. |
| **📡 Real-Time Seat Maps** | WebSocket (STOMP/SockJS) — every browser sees seat state instantly. No polling. No stale data. |
| **💳 Payment Handling** | Razorpay integration + server-side HMAC-SHA256 verification, plus a webhook as an independent backup confirmation path. Never trust the client. |
| **⚙️ Async Confirmations** | Kafka decouples PDF ticket generation + email from checkout. User gets a response instantly; ticket arrives in the background. |
| **🛠️ Admin Operations Layer** | Event lifecycle controls (pause/cancel/postpone with auto-notifications), a `SUPER_ADMIN` role hierarchy, site analytics. |
| **🧪 Test Coverage** | JUnit + Mockito for units. **Testcontainers for integration** against real MySQL, Redis, Kafka. |
| **🐳 Deployment-Ready** | Multi-container Docker Compose. GitHub Actions CI/CD. |

**Tech Stack:**
![Java](https://img.shields.io/badge/Java%2017-%23ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DD0031?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=flat-square&logo=apachekafka)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## 📂 Other Live Projects

| Project | Description | Status |
|---------|-------------|--------|
| **[AI Email Assistant](https://github.com/MrAjayGangwar2001)** | Gemini AI-powered email automation with real-time processing | ✅ Live (CloudFront) |
| **DevHire** | AI hiring platform for Indian startups; 7-microservice architecture with WebRTC proctoring | 🚧 In Development |
| **[Portfolio](https://portfolio-ajay-gangwar.vercel.app/)** | React + Vite; fast, minimal, intentional | ✅ Live (Vercel) |
| **NeoChat AI** | Real-time AI chatbot with streaming responses | ✅ Live |

---

## 🛠️ Tech Stack

<table>
<tr>
<td>

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

</td>
<td>

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-457B8D?style=flat-square&logo=hibernate&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=flat-square&logo=apachekafka)
![Redis](https://img.shields.io/badge/Redis-DD0031?style=flat-square&logo=redis&logoColor=white)

</td>
</tr>
<tr>
<td>

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white)

</td>
<td>

**DevOps & Cloud**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2671E5?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

</td>
</tr>
</table>

---

## 📊 GitHub Analytics

<div align="center">

![GitHub Stats](https://github-readme-stats-self-rho-34.vercel.app/api?username=MrAjayGangwar2001&show_icons=true&theme=ambient_gradient&hide_border=false&include_all_commits=true&count_private=true&card_width=500)

![Top Languages](https://github-readme-stats-self-rho-34.vercel.app/api/top-langs/?username=MrAjayGangwar2001&layout=compact&theme=ambient_gradient&hide_border=false)

### 🐍 Contribution Snake

<img src="https://raw.githubusercontent.com/MrAjayGangwar2001/MrAjayGangwar2001/output/github-contribution-grid-snake-dark.svg#gh-dark-mode-only" alt="snake animation" />
<img src="https://raw.githubusercontent.com/MrAjayGangwar2001/MrAjayGangwar2001/output/github-contribution-grid-snake.svg#gh-light-mode-only" alt="snake animation" />

*A snake that literally eats through my contribution graph — regenerated daily via GitHub Actions (setup below).*

</div>

---

## 💡 What I'm Working On

- 🎯 **DevHire** — Scaling an AI-driven hiring platform for the Indian startup ecosystem
- 📚 **System Design** — Deep-diving into distributed systems, caching strategies, and fault tolerance
- ⚡ **Cloud Architecture** — Mastering AWS for production deployments at scale
- 🔐 **Concurrency & Correctness** — Proving that async systems work under realistic load

---

## 🤝 Let's Connect

I'm open to:
- **Full-Stack Java Developer roles** (Spring Boot + React)
- **System Design discussions** — I love talking about scaling problems
- **Collaboration** on projects solving real problems for real users

<a href="https://www.linkedin.com/in/ajay-gangwar-5234b2268">
  <img src="https://img.shields.io/badge/Message%20me%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="https://wa.me/919720576210">
  <img src="https://img.shields.io/badge/Chat%20on%20WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
</a>

<a href="mailto:gangwar030@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

---

<div align="center">

![Footer Wave](https://capsule-render.vercel.app/api?type=waving&color=0:6DB33F,100:0077B5&height=100&section=footer)

**⭐ If you find this interesting, a star means a lot!**

*Last updated: July 2026*

</div>
