
# Hey, I'm Usama – Doctor × AI Pioneer  

![Followers](https://img.shields.io/github/followers/usama7871?label=Follow&style=social)
![Stars](https://img.shields.io/github/stars/usama7871?label=Stars&style=social)
![Views](https://komarev.com/ghpvc/?username=usama7871&color=8b5cf6&label=Profile%20Views)

<p align="center">
  <strong>3rd-year MBBS • Founder @ <a href="https://medizo-ai.com">Medizo AI</a> • Building autonomous medical agents that save lives</strong>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=700&size=32&duration=3500&pause=800&color=00ff41&center=true&vCenter=true&width=800&lines=Doctor+%E2%9A%A1+AI+Engineer+%F0%9F%A7%A0;LangChain+%E2%86%92+OpenAI+Agents+%E2%86%92+n8n;95%25+Accurate+Medical+Co-Pilots+%F0%9F%A9%BA" />
</p>

<!-- Premium Theme Toggle -->
<p align="center">
  <button id="themeBtn" style="background:none;border:none;cursor:pointer;font-size:28px;" title="Toggle Theme">
    🌙 Dark Mode
  </button>
</p>

<script src="https://cdn.jsdelivr.net/npm/gsap@3.12.5/dist/gsap.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/gsap@3.12.5/dist/ScrollTrigger.min.js"></script>

<script>
  const btn = document.getElementById('themeBtn');
  let isDark = true;

  btn.addEventListener('click', () => {
    isDark = !isDark;
    document.body.classList.toggle('light-theme');
    btn.innerHTML = isDark ? '🌙 Dark Mode' : '☀️ Light Mode';
    
    gsap.to('body', {backgroundColor: isDark ? '#0f0f1e' : '#f8fafc', duration: 0.8, ease: "power2.inOut"});
    gsap.to('.markdown-body', {backgroundColor: isDark ? '#11111f' : '#ffffff', color: isDark ? '#e2e8f0' : '#1e293b', duration: 0.8});
  });

  // Auto-respect system preference
  if (window.matchMedia('(prefers-color-scheme: light)').matches && isDark) {
    btn.click();
  }
</script>

<style>
  body { transition: background 0.6s; background: #0f0f1e; color: #e2e8f0; }
  .light-theme { background: #f8fafc !important; }
  .light-theme .markdown-body { background: #ffffff !important; color: #0f172a !important; }
  .light-theme a { color: #3b82f6 !important; }
  .light-theme img { filter: brightness(1.1); }
  h1, h2, h3 { background: linear-gradient(90deg, #00ff41, #8b5cf6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
</style>

---

## What I Build
Autonomous AI agents reducing diagnostic time by **90%+**  
Real medical co-pilots using OpenAI Agents + LangGraph + n8n

**Medizo AI** – Trusted AI diagnostics platform for doctors worldwide

---

## Tech Arsenal

```text
AI Agents     → LangGraph • CrewAI • AutoGen • n8n • OpenAI Agents SDK
LLMs & RAG    → GPT-4o • Claude 3 • Llama 3 • Pinecone • Weaviate
Frontend      → Next.js 14 • TypeScript • Tailwind • Framer Motion • Shadcn
Backend       → FastAPI • Supabase • Prisma • Redis
Infra         → Docker • Kubernetes • AWS • Vercel • GitHub Actions
```

<div align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/LangChain-1A1A1A?style=for-the-badge&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/n8n-4F46E5?style=for-the-badge&logo=n8n&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</div>

---

## Featured Projects

| Project                    | Description                                              | Stack                                  | Live / Repo                                      |
|----------------------------|----------------------------------------------------------|----------------------------------------|--------------------------------------------------|
| **Medizo AI**              | AI diagnostics platform for hospitals                    | Next.js + LangChain + OpenAI Agents    | [medizo-ai.com](https://medizo-ai.com)          |
| **Agent Orchestrator**     | Multi-agent system with memory & tool delegation        | LangGraph + n8n + FastAPI              | [GitHub](https://github.com/usama7871/ai-agents) |
| **Medical RAG Engine**     | 95%+ accurate symptom → diagnosis                        | GPT-4o + Pinecone + Voice             | Private • DM for demo                            |
| **E-Commerce Platform**    | Hackathon-winning full-stack app                         | Next.js + Node + MongoDB               | [Live](https://hackathon-2-nu-ten.vercel.app/)   |

---

## GitHub Stats (Animated)

<div align="center">
  <img height="190" src="https://github-readme-stats.vercel.app/api?username=usama7871&show_icons=true&theme=react&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" />
  <img height="190" src="https://github-readme-streak-stats.herokuapp.com/?user=usama7871&theme=react&hide_border=true&fire=FF5733" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=usama7871&layout=donut-vertical&theme=react&hide_border=true&langs_count=10" />
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Snake" />
</div>

<script>
  gsap.from(".markdown-body img", { y: 50, opacity: 0, duration: 1, stagger: 0.2, ease: "back.out(1.7)" });
  gsap.from("h2, h3", { x: -100, opacity: 0, duration: 1, stagger: 0.3, scrollTrigger: { trigger: "h2", start: "top 80%" }});
</script>

---

## Currently Building
- Full-stack medical co-pilot with voice + vision (LangGraph)
- Open-source healthcare agent framework
- Real-time multi-modal symptom analyzer

---

## Let's Build the Future Together

<p align="center">
  <a href="https://linkedin.com/in/usama7871"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://twitter.com/usama7871"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" /></a>
  <a href="mailto:kusamakhan1234@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://medizo-ai.com"><img src="https://img.shields.io/badge/Medizo_AI-10B981?style=for-the-badge&logo=react&logoColor=white" /></a>
  <a href="https://my-cv-ashen.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/static/v1?label=&message=Open%20to%20AI%20Health-Tech%20Roles&color=10B981&style=for-the-badge&logo=openai" />
  <img src="https://img.shields.io/static/v1?label=&message=Hiring%20AI%20Engineers&color=8b5cf6&style=for-the-badge&logo=webflow" />
  <img src="https://img.shields.io/static/v1?label=&message=Coffee%20Chat%3F&color=ff6b6b&style=for-the-badge&logo=coffeescript" />
</p>

> **"Medicine saves lives. AI makes it faster."** — Me

**Star this profile if you're into AI agents & healthcare revolution!**
