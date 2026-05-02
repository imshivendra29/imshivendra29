
<style>
  .rw { font-family: var(--font-sans); font-size: 13px; line-height: 1.6; color: var(--color-text-primary); padding: 1rem 0; }
  .tab-bar { display: flex; gap: 0; margin-bottom: 1.5rem; border-bottom: 0.5px solid var(--color-border-tertiary); }
  .tab { padding: 8px 18px; font-size: 13px; cursor: pointer; border-bottom: 2px solid transparent; color: var(--color-text-secondary); background: none; border-top: none; border-left: none; border-right: none; font-family: var(--font-sans); }
  .tab.active { color: var(--color-text-primary); border-bottom: 2px solid var(--color-text-primary); font-weight: 500; }
  .preview-box { background: var(--color-background-secondary); border-radius: var(--border-radius-lg); border: 0.5px solid var(--color-border-tertiary); padding: 1.5rem; }
  .raw-box { background: var(--color-background-secondary); border-radius: var(--border-radius-lg); border: 0.5px solid var(--color-border-tertiary); padding: 1.5rem; white-space: pre-wrap; word-break: break-all; font-size: 11.5px; font-family: var(--font-mono); }
  .copy-btn { display: inline-block; margin-top: 1rem; padding: 8px 20px; font-size: 13px; font-family: var(--font-sans); cursor: pointer; border: 0.5px solid var(--color-border-secondary); border-radius: var(--border-radius-md); background: var(--color-background-primary); color: var(--color-text-primary); }
  .copy-btn:hover { background: var(--color-background-secondary); }
  .dev-name { font-size: 22px; font-weight: 500; margin: 0 0 4px; }
  .tagline { color: var(--color-text-secondary); font-size: 13px; margin: 0 0 14px; }
  .badges { display: flex; flex-wrap: wrap; gap: 6px; margin-bottom: 16px; }
  .badge { font-size: 11px; padding: 3px 10px; border-radius: 20px; font-weight: 500; }
  .bg { background: #EAF3DE; color: #3B6D11; }
  .bb { background: #E6F1FB; color: #185FA5; }
  .ba { background: #FAEEDA; color: #854F0B; }
  .bt { background: #E1F5EE; color: #0F6E56; }
  .bp { background: #EEEDFE; color: #534AB7; }
  .bc { background: #FAECE7; color: #993C1D; }
  .section-title { font-size: 15px; font-weight: 500; margin: 20px 0 10px; padding-bottom: 4px; border-bottom: 0.5px solid var(--color-border-tertiary); }
  .skill-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(140px, 1fr)); gap: 8px; }
  .skill-card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-md); padding: 8px 12px; }
  .skill-cat { font-size: 11px; color: var(--color-text-secondary); margin-bottom: 3px; }
  .skill-val { font-weight: 500; font-size: 12px; }
  .proj-card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-md); padding: 10px 14px; margin-bottom: 8px; }
  .proj-title { font-weight: 500; font-size: 13px; margin-bottom: 3px; }
  .proj-desc { font-size: 12px; color: var(--color-text-secondary); }
  .proj-tags { display: flex; flex-wrap: wrap; gap: 4px; margin-top: 6px; }
  .proj-tag { font-size: 11px; padding: 2px 8px; border-radius: 10px; background: var(--color-background-secondary); color: var(--color-text-secondary); border: 0.5px solid var(--color-border-tertiary); }
  .contact-row { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 8px; }
  .contact-chip { font-size: 12px; padding: 4px 12px; border-radius: var(--border-radius-md); border: 0.5px solid var(--color-border-tertiary); background: var(--color-background-primary); }
  .curious-box { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-left: 3px solid #7F77DD; border-radius: var(--border-radius-md); padding: 12px 16px; font-size: 12px; color: var(--color-text-secondary); margin-top: 4px; }
  .about-line { font-size: 13px; color: var(--color-text-secondary); margin: 4px 0; }
</style>

<div class="rw">
  <div class="tab-bar">
    <button class="tab active" onclick="show('preview',this)">Preview</button>
    <button class="tab" onclick="show('raw',this)">Raw Markdown</button>
  </div>

  <div id="preview" class="preview-box">
    <p class="dev-name">Hey, I'm Shivendra Pratap Singh</p>
    <p class="tagline">Full Stack Developer · ASP.NET Core & MERN · AI Integrations · Noida, India</p>
    <div class="badges">
      <span class="badge bg">Open to Work</span>
      <span class="badge bb">Freelancer</span>
      <span class="badge bt">2+ yrs experience</span>
      <span class="badge bp">AI / LLM Enthusiast</span>
      <span class="badge ba">Automation Explorer</span>
      <span class="badge bc">Curious by nature</span>
    </div>

    <div class="section-title">About</div>
    <p class="about-line">Full Stack Developer with 2+ years building production-grade web apps — specialising in ASP.NET Core and MERN stack.</p>
    <p class="about-line">Beyond web dev, I actively explore AI/LLM integrations, automation, and emerging tech — not just as theory, but by building real things with them.</p>
    <p class="about-line">I'm the kind of developer who stays curious: if a new technology drops, I want to understand it, break it, and use it to solve real problems.</p>
    <p class="about-line">Currently freelancing and open to full-time roles at startups and product companies.</p>

    <div class="section-title">Tech stack</div>
    <div class="skill-grid">
      <div class="skill-card"><div class="skill-cat">Backend</div><div class="skill-val">ASP.NET Core · Node.js · Express</div></div>
      <div class="skill-card"><div class="skill-cat">Frontend</div><div class="skill-val">React · Angular · Next.js</div></div>
      <div class="skill-card"><div class="skill-cat">Database</div><div class="skill-val">SQL Server · MongoDB · EF Core</div></div>
      <div class="skill-card"><div class="skill-cat">AI & LLM</div><div class="skill-val">Claude API · OpenAI · Prompt Eng.</div></div>
      <div class="skill-card"><div class="skill-cat">Automation</div><div class="skill-val">Task automation · Scripting · Bots</div></div>
      <div class="skill-card"><div class="skill-cat">Real-time</div><div class="skill-val">SignalR · Socket.io</div></div>
      <div class="skill-card"><div class="skill-cat">DevOps & Cloud</div><div class="skill-val">Docker · Azure · Railway · Vercel</div></div>
      <div class="skill-card"><div class="skill-cat">Payments</div><div class="skill-val">Razorpay · PhonePe</div></div>
      <div class="skill-card"><div class="skill-cat">Storage</div><div class="skill-val">Cloudinary · MongoDB Atlas</div></div>
      <div class="skill-card"><div class="skill-cat">Auth & Security</div><div class="skill-val">JWT · RBAC · REST APIs</div></div>
    </div>

    <div class="section-title">Currently exploring</div>
    <div class="curious-box">
      Robotics fundamentals · LLM fine-tuning concepts · AI agents & tool-use · Edge automation · Physics & how things actually work under the hood · Geopolitics & systems thinking · Whatever dropped this week in tech
    </div>

    <div class="section-title">Featured projects</div>
    <div class="proj-card">
      <div class="proj-title">ShopNest API — E-commerce Backend</div>
      <div class="proj-desc">Clean Architecture ASP.NET Core Web API with JWT auth, EF Core, SQL Server, and Cloudinary. Role-based access for Admin and Customer.</div>
      <div class="proj-tags"><span class="proj-tag">ASP.NET Core</span><span class="proj-tag">Clean Architecture</span><span class="proj-tag">EF Core</span><span class="proj-tag">SQL Server</span><span class="proj-tag">JWT</span></div>
    </div>
    <div class="proj-card">
      <div class="proj-title">Real-time Chat App</div>
      <div class="proj-desc">Full-stack chat with private messaging, group rooms, and live presence — built with both SignalR (.NET) and Socket.io (Node.js).</div>
      <div class="proj-tags"><span class="proj-tag">SignalR</span><span class="proj-tag">Socket.io</span><span class="proj-tag">React</span><span class="proj-tag">Node.js</span></div>
    </div>
    <div class="proj-card">
      <div class="proj-title">MERN Shopping App + AI Chatbot</div>
      <div class="proj-desc">Role-based shopping platform (Admin/User) with PhonePe payments, Cloudinary storage, MongoDB Atlas, and an AI-powered product assistant.</div>
      <div class="proj-tags"><span class="proj-tag">MERN</span><span class="proj-tag">PhonePe</span><span class="proj-tag">Cloudinary</span><span class="proj-tag">LLM</span><span class="proj-tag">AI Chatbot</span></div>
    </div>
    <div class="proj-card">
      <div class="proj-title">AI Portfolio Website</div>
      <div class="proj-desc">Personal portfolio with AI chatbot integration, live-deployed on Vercel. Built with Next.js.</div>
      <div class="proj-tags"><span class="proj-tag">Next.js</span><span class="proj-tag">Vercel</span><span class="proj-tag">AI</span><span class="proj-tag">Claude API</span></div>
    </div>

    <div class="section-title">What drives me</div>
    <div class="curious-box">
      I don't just write code — I want to understand why things work the way they do. From LLMs to robotics to physics to geopolitics, I connect dots across fields. That curiosity shows up in every project I build.
    </div>

    <div class="section-title">Connect</div>
    <div class="contact-row">
      <span class="contact-chip">shivendrasingh.vercel.app</span>
      <span class="contact-chip">linkedin.com/in/imshivendra29</span>
      <span class="contact-chip">your@email.com</span>
    </div>
    <p style="font-size:12px;color:var(--color-text-secondary);margin-top:10px;">Open to full-time .NET / MERN roles and freelance projects. Let's build something real.</p>
  </div>

  <div id="raw" style="display:none;">
    <div class="raw-box" id="raw-content"></div>
    <button class="copy-btn" onclick="copyMd()">Copy README</button>
    <span id="copy-confirm" style="font-size:12px;color:var(--color-text-secondary);margin-left:10px;display:none;">Copied!</span>
  </div>
</div>

<script>
const md = `<!-- GitHub Profile README — imshivendra29 -->

<h1>Hey, I'm Shivendra Pratap Singh 👋</h1>

<p>
  <img src="https://img.shields.io/badge/Open%20to%20Work-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Freelancer-Available-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Experience-2%2B%20Years-informational?style=flat-square" />
  <img src="https://img.shields.io/badge/AI%20%2F%20LLM-Enthusiast-purple?style=flat-square" />
  <img src="https://img.shields.io/badge/Automation-Explorer-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Curious-By%20Nature-red?style=flat-square" />
</p>

**Full Stack Developer · ASP.NET Core & MERN · AI Integrations · Noida, India**

---

### 👨‍💻 About Me

Full Stack Developer with **2+ years** of experience building production-grade web applications — specialising in **ASP.NET Core Web APIs** and **MERN stack**.

Beyond web dev, I actively explore **AI/LLM integrations**, **automation**, and emerging tech — not just as theory, but by building real things with them.

I'm the kind of developer who stays curious: if a new technology drops, I want to understand it, break it, and use it to solve real problems.

Currently **freelancing** and **open to full-time roles** at startups and product companies.

- 🔭 Building: MERN Shopping App with PhonePe integration + AI Chatbot
- 🤖 Exploring: LLM integrations, automation, robotics fundamentals
- 💼 Open to: Full Stack Developer / .NET Developer roles
- 🌱 Hobby: Learn new tech → break it → use it in real life
- 📍 Noida, India · 🎓 B.Tech CS · AKTU 2023

---

### 🛠️ Tech Stack

| Layer | Technologies |
|---|---|
| **Backend** | ASP.NET Core Web API, Node.js, Express.js |
| **Frontend** | React.js, Angular, Next.js, HTML/CSS/JS |
| **Database** | SQL Server, MongoDB, EF Core, LINQ |
| **AI & LLM** | Claude API, OpenAI API, Prompt Engineering, AI Chatbot Integration |
| **Automation** | Task automation, Scripting, Bot development |
| **Real-time** | SignalR, Socket.io |
| **Auth & Security** | JWT, Role-Based Access Control, REST APIs |
| **DevOps & Cloud** | Docker, Azure, Railway, Vercel, Render |
| **Storage** | Cloudinary, MongoDB Atlas, AWS S3 |
| **Payments** | Razorpay, PhonePe |
| **Tools** | Git, GitHub, Postman, Visual Studio, VS Code |

---

### 🤖 Currently Exploring

\`\`\`
Robotics fundamentals        →  understanding how machines make decisions
LLM fine-tuning concepts     →  making AI actually useful for specific problems  
AI agents & tool-use         →  giving AI the ability to take real actions
Edge automation              →  automating the boring stuff so I can build more
Physics & systems thinking   →  because curiosity doesn't stop at the code
Geopolitics                  →  understanding the world that tech operates in
Whatever dropped this week   →  always
\`\`\`

---

### 🚀 Featured Projects

#### 🛍️ ShopNest API — E-commerce Backend
> Clean Architecture ASP.NET Core Web API with JWT auth, EF Core, SQL Server & Cloudinary

**Stack:** \`ASP.NET Core\` \`Clean Architecture\` \`EF Core\` \`SQL Server\` \`JWT\` \`Cloudinary\`

---

#### 💬 Real-time Chat App
> Full-stack chat with private messaging, group rooms & live presence indicators

**Stack:** \`SignalR\` \`Socket.io\` \`React\` \`Node.js\` \`MongoDB\`

---

#### 🛒 MERN Shopping App + AI Chatbot *(in progress)*
> Role-based platform (Admin/User) with PhonePe payments + AI-powered product assistant

**Stack:** \`MongoDB Atlas\` \`Express\` \`React\` \`Node.js\` \`PhonePe\` \`Cloudinary\` \`LLM Integration\`

---

#### 🌐 AI Portfolio Website
> Personal portfolio with integrated AI chatbot, live on Vercel

**Stack:** \`Next.js\` \`Claude API\` \`Vercel\`  
🔗 [shivendrasingh.vercel.app](https://shivendrasingh.vercel.app)

---

### 📊 GitHub Stats

![Shivendra's GitHub Stats](https://github-readme-stats.vercel.app/api?username=imshivendra29&show_icons=true&theme=default&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=imshivendra29&layout=compact&theme=default&hide_border=true)

---

### 💡 What drives me

> I don't just write code — I want to understand **why** things work the way they do.  
> From LLMs to robotics to physics to geopolitics, I connect dots across fields.  
> That curiosity shows up in every project I build.

---

### 🤝 Let's Connect

[![Portfolio](https://img.shields.io/badge/Portfolio-shivendrasingh.vercel.app-black?style=flat-square)](https://shivendrasingh.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-imshivendra29-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/imshivendra29)

📧 **Email:** imshivendra29@gmail.com

---

*Open to full-time .NET / MERN roles and freelance projects. Let's build something real.*`;

document.getElementById('raw-content').textContent = md;

function show(tab, btn) {
  document.getElementById('preview').style.display = tab === 'preview' ? 'block' : 'none';
  document.getElementById('raw').style.display = tab === 'raw' ? 'block' : 'none';
  document.querySelectorAll('.tab').forEach(t => t.classList.remove('active'));
  btn.classList.add('active');
}

function copyMd() {
  navigator.clipboard.writeText(document.getElementById('raw-content').textContent).then(() => {
    const c = document.getElementById('copy-confirm');
    c.style.display = 'inline';
    setTimeout(() => c.style.display = 'none', 2500);
  });
}
</script>
