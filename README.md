<div align="center">

<!-- Animated 3D Hero Banner -->
<img src="https://svg-banners.vercel.app/api?type=glitch&text1=Oussama%20Taright&width=1200&height=200" alt="glitch-banner" />

<!-- Interactive 3D Isometric Scene with Game Elements -->
<svg width="100%" height="400" viewBox="0 0 1200 400" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="3D Interactive Gaming Scene">
	<defs>
		<linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
			<stop offset="0%" stop-color="#0B1221" />
			<stop offset="50%" stop-color="#1a1f35" />
			<stop offset="100%" stop-color="#0B1221" />
		</linearGradient>
		<linearGradient id="neonGrad" x1="0%" y1="0%" x2="100%" y2="0%">
			<stop offset="0%" stop-color="#7C3AED" />
			<stop offset="25%" stop-color="#06B6D4" />
			<stop offset="50%" stop-color="#22C55E" />
			<stop offset="75%" stop-color="#F59E0B" />
			<stop offset="100%" stop-color="#EF4444" />
		</linearGradient>
		<filter id="glow">
			<feGaussianBlur stdDeviation="4" result="coloredBlur"/>
			<feMerge>
				<feMergeNode in="coloredBlur"/>
				<feMergeNode in="SourceGraphic"/>
			</feMerge>
		</filter>
		<filter id="shadow3d" x="-50%" y="-50%" width="200%" height="200%">
			<feDropShadow dx="0" dy="8" stdDeviation="8" flood-color="#00000088" />
		</filter>
	</defs>
    
	<rect x="0" y="0" width="1200" height="400" fill="url(#bgGrad)" />
    
	<!-- Floating Grid Background -->
	<g opacity="0.15">
		<line x1="0" y1="100" x2="1200" y2="100" stroke="#06B6D4" stroke-width="1" />
		<line x1="0" y1="200" x2="1200" y2="200" stroke="#06B6D4" stroke-width="1" />
		<line x1="0" y1="300" x2="1200" y2="300" stroke="#06B6D4" stroke-width="1" />
		<line x1="200" y1="0" x2="200" y2="400" stroke="#06B6D4" stroke-width="1" />
		<line x1="400" y1="0" x2="400" y2="400" stroke="#06B6D4" stroke-width="1" />
		<line x1="600" y1="0" x2="600" y2="400" stroke="#06B6D4" stroke-width="1" />
		<line x1="800" y1="0" x2="800" y2="400" stroke="#06B6D4" stroke-width="1" />
		<line x1="1000" y1="0" x2="1000" y2="400" stroke="#06B6D4" stroke-width="1" />
	</g>
    
	<!-- Glowing Title -->
	<text x="50%" y="45" text-anchor="middle" fill="url(#neonGrad)" font-size="36" font-weight="900" font-family="'Arial Black', sans-serif" filter="url(#glow)">
		⚡ FULL-STACK ARCHITECT ⚡
	</text>
	<text x="50%" y="75" text-anchor="middle" fill="#94A3B8" font-size="16" font-weight="600" font-family="'Segoe UI', Arial">
		Building the Future • One Pixel at a Time
	</text>
    
	<!-- Isometric Platform Base -->
	<g transform="translate(600, 280)" filter="url(#shadow3d)">
		<polygon points="0,-80 200,-40 200,0 0,40 -200,0 -200,-40" fill="#1F2937" stroke="#374151" stroke-width="2" opacity="0.9" />
		<polygon points="0,-80 200,-40 0,0 -200,-40" fill="#374151" opacity="0.7" />
	</g>
    
	<!-- Animated 3D Cubes - Level 1 -->
	<g transform="translate(350, 220)" filter="url(#shadow3d)">
		<g>
			<polygon points="0,-50 45,-25 45,25 0,50 -45,25 -45,-25" fill="#111827" stroke="#6B7280" stroke-width="2" />
			<polygon points="0,-50 45,-25 0,0 -45,-25" fill="#0EA5E9" opacity="0.95" />
			<polygon points="-45,-25 0,0 0,50 -45,25" fill="#0284C7" opacity="0.95" />
			<polygon points="45,-25 0,0 0,50 45,25" fill="#0369A1" opacity="0.95" />
			<text x="0" y="10" text-anchor="middle" fill="white" font-size="24" font-weight="bold">JS</text>
			<animateTransform attributeName="transform" type="translate" values="0,0; 0,-15; 0,0" dur="2s" repeatCount="indefinite" />
		</g>
	</g>
    
	<!-- Animated 3D Cubes - Level 2 -->
	<g transform="translate(600, 180)" filter="url(#shadow3d)">
		<g>
			<polygon points="0,-55 50,-27.5 50,27.5 0,55 -50,27.5 -50,-27.5" fill="#0F172A" stroke="#475569" stroke-width="2" />
			<polygon points="0,-55 50,-27.5 0,0 -50,-27.5" fill="#7C3AED" opacity="0.95" />
			<polygon points="-50,-27.5 0,0 0,55 -50,27.5" fill="#6D28D9" opacity="0.95" />
			<polygon points="50,-27.5 0,0 0,55 50,27.5" fill="#5B21B6" opacity="0.95" />
			<text x="0" y="10" text-anchor="middle" fill="white" font-size="28" font-weight="bold">⚛️</text>
			<animateTransform attributeName="transform" type="translate" values="0,0; 0,-20; 0,0" dur="2.5s" repeatCount="indefinite" />
		</g>
	</g>
    
	<!-- Animated 3D Cubes - Level 3 -->
	<g transform="translate(850, 220)" filter="url(#shadow3d)">
		<g>
			<polygon points="0,-50 45,-25 45,25 0,50 -45,25 -45,-25" fill="#111827" stroke="#6B7280" stroke-width="2" />
			<polygon points="0,-50 45,-25 0,0 -45,-25" fill="#22C55E" opacity="0.95" />
			<polygon points="-45,-25 0,0 0,50 -45,25" fill="#16A34A" opacity="0.95" />
			<polygon points="45,-25 0,0 0,50 45,25" fill="#15803D" opacity="0.95" />
			<text x="0" y="12" text-anchor="middle" fill="white" font-size="26" font-weight="bold">TS</text>
			<animateTransform attributeName="transform" type="translate" values="0,0; 0,-15; 0,0" dur="2.2s" repeatCount="indefinite" />
		</g>
	</g>
    
	<!-- Rotating Tech Orbs -->
	<g transform="translate(600, 200)">
		<circle cx="0" cy="0" r="8" fill="#0EA5E9" filter="url(#glow)">
			<animateTransform attributeName="transform" type="rotate" from="0 0 0" to="360 0 0" dur="8s" repeatCount="indefinite" />
			<animate attributeName="r" values="8;12;8" dur="2s" repeatCount="indefinite" />
		</circle>
		<circle cx="150" cy="0" r="8" fill="#22C55E" filter="url(#glow)">
			<animateTransform attributeName="transform" type="rotate" from="0 0 0" to="360 0 0" dur="6s" repeatCount="indefinite" />
			<animate attributeName="r" values="8;12;8" dur="2.5s" repeatCount="indefinite" />
		</circle>
		<circle cx="-150" cy="0" r="8" fill="#7C3AED" filter="url(#glow)">
			<animateTransform attributeName="transform" type="rotate" from="0 0 0" to="360 0 0" dur="10s" repeatCount="indefinite" />
			<animate attributeName="r" values="8;12;8" dur="3s" repeatCount="indefinite" />
		</circle>
	</g>
    
	<!-- Particle Effects -->
	<circle cx="200" cy="150" r="3" fill="#06B6D4" opacity="0.8">
		<animate attributeName="cy" values="150;350;150" dur="4s" repeatCount="indefinite" />
		<animate attributeName="opacity" values="0.8;0;0.8" dur="4s" repeatCount="indefinite" />
	</circle>
	<circle cx="1000" cy="100" r="3" fill="#F59E0B" opacity="0.8">
		<animate attributeName="cy" values="100;300;100" dur="5s" repeatCount="indefinite" />
		<animate attributeName="opacity" values="0.8;0;0.8" dur="5s" repeatCount="indefinite" />
	</circle>
	<circle cx="400" cy="120" r="2" fill="#EF4444" opacity="0.7">
		<animate attributeName="cy" values="120;330;120" dur="6s" repeatCount="indefinite" />
		<animate attributeName="opacity" values="0.7;0;0.7" dur="6s" repeatCount="indefinite" />
	</circle>
    
	<!-- Bottom Status Bar -->
	<rect x="0" y="360" width="1200" height="40" fill="#0B1221" opacity="0.9" />
	<text x="50%" y="385" text-anchor="middle" fill="#CBD5E1" font-size="14" font-weight="600" font-family="'Segoe UI', Arial">
		🎮 LEVEL 99 • 💎 10K+ LINES • ⚡ REAL-TIME MASTER • 🚀 ALWAYS SHIPPING
	</text>
</svg>

<!-- Premium Game HUD -->
<svg width="100%" height="100" viewBox="0 0 1200 100" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Professional Game HUD">
	<defs>
		<linearGradient id="hudGrad" x1="0%" y1="0%" x2="100%" y2="0%">
			<stop offset="0%" stop-color="#1a1f35" />
			<stop offset="50%" stop-color="#0B1221" />
			<stop offset="100%" stop-color="#1a1f35" />
		</linearGradient>
		<linearGradient id="xpBar" x1="0%" y1="0%" x2="100%" y2="0%">
			<stop offset="0%" stop-color="#06B6D4" />
			<stop offset="50%" stop-color="#7C3AED" />
			<stop offset="100%" stop-color="#EF4444" />
		</linearGradient>
	</defs>
    
	<rect x="0" y="0" width="1200" height="100" fill="url(#hudGrad)" />
	<rect x="10" y="10" width="1180" height="80" fill="#0B1221" stroke="#374151" stroke-width="2" rx="8" />
    
	<!-- Health/Status -->
	<g transform="translate(30, 35)">
		<text x="0" y="20" font-size="16" fill="#94A3B8" font-weight="600">STATUS</text>
		<text x="0" y="42" font-size="32">❤️ ❤️ ❤️</text>
	</g>
    
	<!-- Resources -->
	<g transform="translate(200, 35)">
		<text x="0" y="20" font-size="16" fill="#94A3B8" font-weight="600">COMMITS</text>
		<text x="0" y="45" font-size="28" fill="#FDE68A">⭐ x 500+</text>
	</g>
    
	<!-- XP Progress Bar -->
	<g transform="translate(400, 35)">
		<text x="0" y="20" font-size="16" fill="#94A3B8" font-weight="600">EXPERIENCE</text>
		<rect x="0" y="25" rx="10" ry="10" width="450" height="28" fill="#1F2937" stroke="#374151" stroke-width="2" />
		<rect x="3" y="28" rx="8" ry="8" width="380" height="22" fill="url(#xpBar)" />
		<text x="225" y="45" text-anchor="middle" font-size="14" fill="white" font-weight="700">LEVEL 99 • 84% TO MAX</text>
	</g>
    
	<!-- Action Button -->
	<g transform="translate(920, 35)">
		<rect x="0" y="15" rx="12" ry="12" width="240" height="40" fill="#7C3AED" stroke="#9333EA" stroke-width="2" filter="url(#glow)" />
		<text x="120" y="42" text-anchor="middle" font-size="18" fill="white" font-weight="700">▶ START GAME</text>
		<animate attributeName="opacity" values="1;0.7;1" dur="1.5s" repeatCount="indefinite" />
	</g>
</svg>

<!-- Typing Animation -->
<img src="https://readme-typing-svg.demolab.com/?lines=🎯+Full-Stack+Developer;⚡+Real-Time+Systems+Expert;🚀+UI/UX+Enthusiast;💎+Clean+Code+Advocate;🔥+Problem+Solver;🌟+Always+Learning&center=true&width=800&height=50&duration=3000&pause=1000&color=06B6D4&vCenter=true&size=24&weight=600" alt="typing-animation" />

<br/>

<!-- Social Badges with Glow Effect -->

[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/oussamatght)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/tarightoussama)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/oussama_soul_)
[![Email](https://img.shields.io/badge/Email-%23D14836.svg?style=for-the-badge&logo=gmail&logoColor=white)](mailto:oussamatght6@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)](#)

</div>

---

## 🎮 MINI GAME: Code Quest Challenge

<details>
<summary>🕹️ <b>CLICK TO PLAY</b> - Test Your Developer Skills!</summary>

<br/>

### 🎯 Mission Objectives

- Level 1: Fix Bugs
  - [ ] Polish README visuals and layout
  - [ ] Push clean, meaningful commits
  - [ ] Lint and format code
- Level 2: Ship Features
  - [ ] Add i18n (Arabic, French, English)
  - [ ] Implement real-time chat (WebSocket)
  - [ ] Dark/Light theme toggle
- Boss Fight: Deploy
  - [ ] Frontend on Vercel
  - [ ] Backend on Render
  - [ ] Configure env vars (HTTP/WS)

### ⚙️ Controls

- Start: Click badges and explore projects
- Move: Scroll through sections (Quest Log, Skill Tree, Leaderboard)
- Action: Star repos, fork, and contribute

### 🏆 Rewards

- +100 XP: Every merged PR
- +50 XP: Each useful issue or discussion
- +10 XP: Daily commits streak

</details>

---

## 🎮 Quest Log

Leveling up full‑stack builds with real‑time features.

- 🎯 Current quest: WebSocket experiences, mobile‑first UI
- 📚 Study: L2 Computer Science @ USTHB
- 🏆 Focus: System design, scalable architectures
- ⚡ Next skill: Advanced TypeScript, microservices, cloud

---

## 🧩 Skill Tree

![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white)
![Render](https://img.shields.io/badge/Render-%2346E3B7.svg?style=for-the-badge&logo=render&logoColor=white)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=%2300C7B7)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%23BBDEAD)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-%23EC5990.svg?style=for-the-badge&logo=reacthookform&logoColor=white)
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)
![Strapi](https://img.shields.io/badge/strapi-%232E7EEA.svg?style=for-the-badge&logo=strapi&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

---

## 🏁 Leaderboard

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=oussamatght&theme=dark&hide_border=true&include_all_commits=false&count_private=false" height="140" />
<img src="https://nirzak-streak-stats.vercel.app/?user=oussamatght&theme=dark&hide_border=true" height="140" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=oussamatght&theme=dark&hide_border=true&include_all_commits=false&count_private=false&layout=compact" height="140" />

</div>

---

## 🏆 Achievements & Activity

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=oussamatght&theme=onedark&margin-w=10&margin-h=10&column=6" alt="trophies" />

<img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg?user=oussamatght" alt="snake" />

</div>

---

## 🔧 Power-Ups

- ✅ Full-Stack: from UI to API
- ✅ Real-Time Systems: WebSocket, live updates
- ✅ Responsive Design: mobile-first, RTL/LTR
- ✅ Data & Auth: schema modeling, JWT
- ✅ Deployment: Vercel/Render, CI/CD
- ✅ Problem Solving: architecture, debugging

---

## 📫 Let's Connect

I'm open to collaborations, internships, and freelance opportunities.

- 💼 LinkedIn: [tarightoussama](https://linkedin.com/in/tarightoussama)
- 📧 Email: [oussamatght6@gmail.com](mailto:oussamatght6@gmail.com)
- 💬 Discord: [oussamatght](https://discord.gg/oussamatght)
- 📸 Instagram: [@oussama*soul*](https://instagram.com/oussama_soul_)

<div align="center">

✨ _"Code is a solution to real-world problems"_ ✨

![Profile Views](https://visitcount.itsvg.in/api?id=oussamatght&icon=0&color=0)

</div>

[![](https://visitcount.itsvg.in/api?id=oussamatght&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
