<!-- <style>
  html,
  body,
  .markdown-body {
    font-size: 18px;
    line-height: 1.6;
  }

  @media (max-width: 700px) {
    html,
    body,
    .markdown-body {
      font-size: 16px;
    }

    h1,
    .timeline-title {
      font-size: 1.5em !important;
    }

    .header-profile-stats,
    .card,
    .section-vertical,
    .timeline-table {
      margin-left: 0 !important;
      margin-right: 0 !important;
      max-width: 100vw !important;
      padding-left: 0 !important;
      padding-right: 0 !important;
    }

    .timeline-block,
    .timeline-block-green,
    .timeline-block-orange,
    .timeline-block-light {
      font-size: 0.98em !important;
      padding: 10px 10px !important;
    }

    .timeline-table td {
      padding: 0 2px !important;
    }
  }

  a,
  a:visited {
    color: #C2A83E;
    outline: none;
  }

  a:focus,
  button:focus,
  input:focus {
    outline: 2px solid #C2A83E;
    outline-offset: 2px;
  }

  .timeline-block,
  .timeline-block-green,
  .timeline-block-orange,
  .timeline-block-light {
    background: #232A25;
    color: #E0EEC6;
    border: 2px solid #7CA982;
  }

  .timeline-block-orange {
    color: #FFA500;
    border-color: #FFA500;
  }

  .timeline-block-green {
    color: #7CA982;
    border-color: #7CA982;
  }

  .timeline-block-light {
    color: #E0EEC6;
    border-color: #C2A83E;
  }

  .timeline-date {
    font-size: 1em;
  }

  .section-vertical,
  .card,
  .header-profile-stats,
  .timeline-title,
  .timeline-table {
    margin-bottom: 44px !important;
    margin-top: 0 !important;
  }

  .footer-github {
    margin-top: 64px !important;
  }

  body::selection,
  ::selection {
    color: #243E36;
    background-color: #E0EEC6;
  }

  .project-card {
    background: #232A25;
    border-radius: 22px;
    box-shadow: 0 4px 18px #243E3633;
    padding: 0;
    border: none;
    width: 260px;
    min-width: 200px;
    max-width: 100%;
    height: 420px;
    min-height: 420px;
    max-height: 420px;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 32px;
    overflow: hidden;
    transition: box-shadow 0.4s, width 0.4s, height 0.4s;
    font-family: 'Montserrat', 'Segoe UI', Arial, sans-serif;
  }

  .project-card:hover {
    width: 500px;
    min-width: 200px;
    max-width: 100%;
    height: 420px;
    min-height: 420px;
    max-height: 420px;
    z-index: 2;
    transition: background 0.4s, box-shadow 0.4s, width 0.4s, height 0.4s;
  }

  .project-card .project-img {
    width: 100%;
    height: 140px;
    object-fit: cover;
    background: #E0EEC6;
    display: block;
    border-radius: 22px 22px 0 0;
    border-bottom: 2px solid #C2A83E;
  }

  .project-card .project-content {
    background: #232A25;
    width: 100%;
    padding: 18px 18px 14px 18px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    border-radius: 0 0 22px 22px;
    border-top: 2px solid #C2A83E;
    text-align: center;
  }

  .project-card .project-title {
    font-weight: 800;
    font-size: 1.12rem;
    color: #E0EEC6;
    margin-bottom: 6px;
    letter-spacing: 0.5px;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    text-align: center;
    gap: 8px;
  }

  .project-card .project-desc {
    color: #7CA982;
    font-size: 0.98rem;
    margin-bottom: 10px;
    font-weight: 500;
    text-align: center;
  }

  .project-card .project-links {
    margin-top: auto;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    padding-bottom: 16px;
  }

  .project-card .project-links a {
    margin-right: 16px;
    color: #C2A83E;
    font-weight: 700;
    font-size: 0.98em;
    text-decoration: none;
    border-radius: 6px;
    padding: 2px 8px;
    background: #243E36;
    transition: background 0.2s, color 0.2s;
  }

  .project-card .project-links a:last-child {
    margin-right: 0;
  }

  .project-card .project-links a:hover {
    color: #fff;
    background: #C2A83E;
    text-decoration: underline;
  }

  body,
  .markdown-body {
    background: #181C1F;
    color: #F1F7ED;
    font-family: 'Montserrat', 'Segoe UI', Arial, sans-serif;
    letter-spacing: 0.01em;
  }

  .header-profile {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 40px 0 32px 0;
  }

  .avatar {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    border: 3px solid #7CA982;
    box-shadow: 0 4px 24px #0008;
    object-fit: cover;
    margin-bottom: 18px;
  }

  .profile-role {
    font-size: 1.2em;
    font-weight: 600;
    color: #7CA982;
    margin-bottom: 6px;
  }

  .profile-desc {
    font-size: 1.05em;
    color: #E0EEC6;
    max-width: 420px;
    text-align: center;
  }

  .stack-list {
    font-size: 1.05em;
    color: #C2A83E;
    margin-bottom: 8px;
  }

  .current-projects {
    font-size: 0.98em;
    color: #7CA982;
  }

  .card-searching {
    background: #22282C;
    border-radius: 22px;
    box-shadow: 0 4px 32px #0007;
    padding: 32px 36px;
    margin: 0 auto 36px auto;
    max-width: 700px;
    border: 1.5px solid #243E36;
    display: flex;
    flex-direction: column;
    align-items: center;
	  transition: background 0.4s, box-shadow 0.4s, border-color 0.4s;
  }

	.card-searching:hover {
    box-shadow: 0 8px 32px #243E3633;
    background: #232A25;
    border-color: #7CA982;
    transition: background 0.4s, box-shadow 0.4s, border-color 0.4s;
	}

  .card {
    background: #22282C;
    border-radius: 22px;
    box-shadow: 0 4px 32px #0007;
    padding: 32px 36px;
    margin: 0 auto 36px auto;
    max-width: 700px;
    border: 1.5px solid #243E36;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .card:hover {
    box-shadow: 0 8px 32px #243E3633;
    background: #232A25;
    border-color: #7CA982;
    transition: background 0.4s, box-shadow 0.4s, border-color 0.4s;
  }

  h1 {
    font-size: 2.7rem;
    margin-bottom: 0.1em;
    text-align: center;
    letter-spacing: 2px;
    color: #E0EEC6;
  }

  h2 {
    font-size: 1.1rem;
    margin-top: 2.2em;
    margin-bottom: 1.1em;
    text-transform: uppercase;
    letter-spacing: 1.5px;
    border-bottom: 2px solid #7CA982;
    padding-bottom: 6px;
    background: none;
    border-radius: 0;
    text-align: center;
    color: #C2A83E;
  }

  .section-vertical {
    width: 100%;
    max-width: 820px;
    margin: 0 auto 48px auto;
    padding: 48px 0 0 0;
    border: none;
    background: none;
    box-shadow: none;
  }

  .section-vertical h2 {
    color: #C2A83E;
    font-size: 1.3rem;
    margin-bottom: 18px;
    text-transform: uppercase;
    letter-spacing: 1.5px;
    border: none;
    background: none;
    text-align: left;
  }

  .section-vertical ul,
  .section-vertical li {
    font-size: 1.08em;
  }

  .section-vertical .badges img {
    margin: 0 8px 10px 0;
    vertical-align: middle;
    filter: drop-shadow(0 2px 6px #0005);
  }

  .section-vertical blockquote {
    background: #243E36;
    border-left: 5px solid #C2A83E;
    margin: 2em 0;
    padding: 1.2em 2em;
    font-style: italic;
    color: #E0EEC6;
    font-size: 1.1em;
    box-shadow: 0 2px 12px #0004;
  }

  .section-vertical .project-list {
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    gap: 32px;
    justify-content: flex-start;
    align-items: stretch;
    overflow-x: auto;
    padding-bottom: 12px;
    margin-bottom: 8px;
    position: relative;
    z-index: 1;
    width: 100%;
    max-width: 100%;
    scrollbar-color: #C2A83E #232A25;
    scrollbar-width: thin;
  }

  .section-vertical .project-item {
    display: flex;
    align-items: flex-start;
    gap: 24px;
    margin-bottom: 8px;
  }

  .section-vertical .project-item img {
    width: 120px;
    border-radius: 12px;
    box-shadow: 0 2px 8px #0002;
  }

  .section-vertical .project-info {
    flex: 1;
  }

  .section-vertical .project-title {
    font-weight: bold;
    font-size: 1.13rem;
    color: #C2A83E;
    margin-bottom: 2px;
  }

  .section-vertical .project-links a {
    margin-right: 16px;
    color: #7CA982;
    font-weight: 600;
  }

  .section-vertical .project-links a:last-child {
    margin-right: 0;
  }

  .section-vertical .badges-custom {
    display: flex;
    gap: 12px;
    margin-top: 12px;
  }

  .section-vertical .badges-custom span {
    display: inline-block;
    padding: 6px 16px;
    border-radius: 8px;
    font-weight: 700;
    font-size: 0.98em;
    background: #23282D;
    color: #C2A83E;
    box-shadow: 0 2px 8px #0002;
  }

  .center {
    text-align: center;
  }

  .badges img {
    margin: 0 8px 10px 0;
    vertical-align: middle;
    filter: drop-shadow(0 2px 6px #0005);
  }

  .badges {
    margin-bottom: 10px;
  }

  a {
    color: #C2A83E;
    text-decoration: none;
    font-weight: 700;
    transition: color 0.2s;
  }

  a:hover {
    color: #7CA982;
    text-decoration: underline;
  }

  blockquote {
    background: #243E36;
    border-left: 5px solid #C2A83E;
    margin: 2em 0;
    padding: 1.2em 2em;
    font-style: italic;
    color: #E0EEC6;
    font-size: 1.1em;
    box-shadow: 0 2px 12px #0004;
  }

  ul {
    margin-left: 1.5em;
    font-size: 1.05em;
  }

  .contact {
    background: #7CA982;
    color: #181C1F;
    border-radius: 16px;
    box-shadow: 0 2px 12px #0003;
    padding: 18px 24px;
    margin: 36px auto 0 auto;
    max-width: 420px;
    text-align: center;
    font-weight: 600;
    font-size: 1.1em;
  }

  .divider {
    width: 80px;
    height: 4px;
    background: linear-gradient(90deg, #7CA982 0%, #C2A83E 100%);
    border-radius: 2px;
    margin: 32px auto;
  }

  .banner-github-profile img {
    width: 100%;
    max-height: 300px;
    object-fit: cover;
    border-radius: 0 0 32px 32px;
    box-shadow: 0 4px 32px #0007;
    margin-bottom: 18px;
  }

  .footer-github {
    width: 100%;
    margin-top: 48px;
    padding: 36px 0 18px 0;
    background: transparent;
    border-top: 2px solid #fff;
  }

  .footer-container {
    max-width: 1100px;
    margin: auto;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: flex-start;
    gap: 32px;
  }

  .footer-col {
    flex: 1;
    min-width: 160px;
  }

  .footer-title {
    color: #fff;
    font-weight: 600;
    margin-bottom: 12px;
    letter-spacing: 1px;
  }

  .footer-links {
    color: #e0eec6;
    line-height: 2;
  }

  .footer-links a {
    color: #e0eec6;
    text-decoration: none;
  }

  .footer-newsletter-input {
    width: 80%;
    max-width: 260px;
    padding: 8px 12px;
    border-radius: 6px;
    border: 1.5px solid #fff;
    background: #fff;
    color: #232323;
    font-size: 1em;
    margin-bottom: 12px;
    outline: none;
  }

  .footer-newsletter-btn {
    margin-top: 6px;
    padding: 7px 22px;
    border-radius: 20px;
    border: 2px solid #fff;
    background: transparent;
    color: #fff;
    font-weight: 600;
    font-size: 1em;
    cursor: pointer;
    opacity: 0.7;
  }

  .footer-contact {
    color: #e0eec6;
    font-size: 1em;
    line-height: 1.7;
  }

  .footer-social {
    margin-top: 10px;
  }

  .footer-social a {
    margin-right: 10px;
  }

  .footer-social img {
    vertical-align: middle;
    opacity: 0.7;
  }

  .header-profile-stats {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: center;
    gap: 48px;
    margin: 40px 0 32px 0;
  }

  .header-profile-left {
    display: flex;
    flex-direction: column;
    align-items: center;
    min-width: 220px;
  }

  .header-profile-right {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 18px;
    min-width: 260px;
  }

  .header-profile-right img {
	  max-width: 320px;
	  min-width: 220px;
	  width: 100%;
	  border-radius: 18px;
	  box-shadow: 0 2px 12px #0006;
	  background: #232A25;
	  margin-bottom: 0;
  }

  @media (max-width: 900px) {
    .header-profile-stats {
      flex-direction: column;
      gap: 24px;
      align-items: center;
    }

    .header-profile-right img {
      max-width: 100vw;
      min-width: 0;
    }
  }

  .timeline-title {
    color: #C2A83E;
    font-size: 1.5em;
    margin-top: 2em;
    margin-bottom: 0.5em;
    letter-spacing: 1px;
    text-align: center;
    border-bottom: none !important;
    padding-bottom: 0 !important;
  }

  .timeline-table {
    margin: 0 auto;
    background: transparent;
    border-collapse: separate;
    border-spacing: 0 0.5em;
  }

  .timeline-date {
    color: #7CA982;
    font-weight: 700;
    font-size: 1.1em;
    text-align: right;
    padding-right: 24px;
    vertical-align: top;
  }

  .timeline-block {
    display: inline-block;
    background: #232A25;
    color: #C2A83E;
    padding: 12px 28px;
    border-radius: 18px;
    font-weight: 600;
    box-shadow: 0 2px 8px #0003;
  }

  .timeline-block-light {
    color: #E0EEC6;
  }

  .timeline-block-orange {
    color: #FFA500;
  }

  .timeline-block-green {
    color: #7CA982;
  }

  .timeline-desc {
    color: #7CA982;
  }

  .timeline-center {
    text-align: center;
  }

  .banner-github-profile {
    margin-bottom: 64px !important;
    display: block;
    width: 100%;
  }

  .banner-github-profile img {
    margin-bottom: 0 !important;
  }

  .header-profile-stats {
    margin: 0 0 64px 0 !important;
    padding-top: 0;
  }

  .card {
    margin: 0 auto 64px auto !important;
  }

  .section-vertical,
  .timeline-title,
  .timeline-table {
    margin-bottom: 64px !important;
  }
</style>

<div class="banner-github-profile">
	<img src="./bannière tunedr.png" alt="Bannière GitHub MathisFerreira" />
</div>

<div class="header-profile-stats">
	<div class="header-profile-left">
		<img class="avatar" src="./IMG_0520.jpeg" alt="Avatar Mathis Ferreira" />
		<h1>Mathis Ferreira</h1>
		<div class="profile-role">Développeur Full‑Stack & Maker</div>
		<div class="profile-desc">Je conçois des apps web immersives pour musiciens et créateurs.</div>
	</div>
	<p class="align-center">
		<img src="https://github-readme-streak-stats.herokuapp.com/?user=1-mathis&theme=dark&hide_border=true&background=232A25&ring=C2A83E&fire=C2A83E&currStreakLabel=C2A83E" alt="GitHub Streak" />
		<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=1-mathis&theme=github_dark" alt="GitHub Profile Details" />
	</p>
</div>

<div class="card">
	<div class="badges">
		<img src="https://img.shields.io/badge/Symfony-000?logo=symfony&logoColor=white" />
		<img src="https://img.shields.io/badge/React-20232a?logo=react&logoColor=61dafb" />
		<img src="https://img.shields.io/badge/PHP-777bb4?logo=php&logoColor=white" />
		<img src="https://img.shields.io/badge/JS-F7DF1E?logo=javascript&logoColor=black" />
		<img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
		<img src="https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white" />
		<img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white" />
	</div>
	<div class="stack-list">Symfony · React · PHP · JS · Docker · Figma · MySQL</div>
	<div class="current-projects">Actuellement : Tunedr v2, Stéréo, UX pour musiciens</div>
</div>

<div class="section-vertical">
	<h2 style="text-align: center;"><img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/github.svg" width="22" style="vertical-align:middle; margin-right:8px; margin-top: 8px;" alt="projets"/> Projets en action</h2>
	<div class="project-list">
		<div class="project-card">
			<img class="project-img" src="./bannière tunedr.png" alt="Tunedr Logo" />
			<div class="project-content">
				<div class="project-title">Tunedr</div>
				<div class="project-desc">
          <p>
            Tunedr est une application web immersive dédiée à la musique indépendante.
          </p>
        </div>
				<div class="project-links">
					<a href="#">Repo</a>
					<a href="www.preprod-tunedr.fr">Site web</a>
				</div>
			</div>
		</div>
		<div class="project-card">
			<img class="project-img" src="https://raw.githubusercontent.com/MathisFerreira/MathisFerreira/main/assets/stereo-demo.gif" alt="Stéréo Demo" />
			<div class="project-content">
				<div class="project-title">Stéréo</div>
				<div class="project-desc">Social feed musical & UX</div>
				<div class="project-links">
					<a href="#">Repo</a>
					<a href="#">Site web</a>
				</div>
			</div>
		</div>
		<div class="project-card">
			<img class="project-img" src="https://raw.githubusercontent.com/MathisFerreira/MathisFerreira/main/assets/ux-ui-demo.gif" alt="UX UI Demo" />
			<div class="project-content">
				<div class="project-title">UX UI Music Tools</div>
				<div class="project-desc">Interfaces immersives</div>
				<div class="project-links">
					<a href="#">Repo</a>
					<a href="#">Site web</a>
				</div>
			</div>
		</div>
	</div>
</div>

<h2 class="timeline-title">🕓 Mon parcours & milestones</h2>

<table class="timeline-table">
	<tr>
		<td class="timeline-date" width="45%"></td>
		<td class="timeline-center" width="10%">
			<img src="https://img.icons8.com/ios-filled/32/C2A83E/vertical-line.png"/>
			<br>🎓
		</td>
		<td width="45%">
			<div class="timeline-block">Entrée en formation dev<br><span class="timeline-desc">Début du parcours de développeur</span></div>
			<div class="timeline-date" style="text-align:left; color:#7CA982;">2022</div>
		</td>
	</tr>
	<tr><td></td><td class="timeline-center"><span style="color:#C2A83E;font-size:2em;">│</span></td><td></td></tr>
	<tr>
		<td width="45%">
			<div class="timeline-block timeline-block-light" style="float:right;">Stage gestion de projet web<br><span class="timeline-desc">Première expérience en entreprise</span></div>
			<div class="timeline-date" style="text-align:right; color:#7CA982;">2023</div>
		</td>
		<td class="timeline-center" width="10%">
			<img src="https://img.icons8.com/ios-filled/32/C2A83E/vertical-line.png"/>
			<br>💼
		</td>
		<td width="45%"></td>
	</tr>
	<tr><td></td><td class="timeline-center"><span style="color:#C2A83E;font-size:2em;">│</span></td><td></td></tr>
	<tr>
		<td class="timeline-date" width="45%"></td>
		<td class="timeline-center" width="10%">
			<img src="https://img.icons8.com/ios-filled/32/C2A83E/vertical-line.png"/>
			<br>🚀
		</td>
		<td width="45%">
			<div class="timeline-block timeline-block-orange">1ers projets freelance<br><span class="timeline-desc">Lancement en indépendant</span></div>
			<div class="timeline-date" style="text-align:left; color:#7CA982;">2024</div>
		</td>
	</tr>
	<tr><td></td><td class="timeline-center"><span style="color:#C2A83E;font-size:2em;">│</span></td><td></td></tr>
	<tr>
		<td width="45%">
			<div style="display: flex; flex-direction: column; align-items: flex-end;">
				<div class="timeline-block timeline-block-green">Lancement Tunedr v2<br><span class="timeline-desc">Projet musical majeur</span></div>
				<div class="timeline-date" style="text-align:right; color:#7CA982; margin-top: 4px;">2025</div>
			</div>
		</td>
		<td class="timeline-center" width="10%">
			<img src="https://img.icons8.com/ios-filled/32/C2A83E/vertical-line.png"/>
			<br>🎵
		</td>
		<td width="45%"></td>
	</tr>
	<tr><td></td><td class="timeline-center"><span style="color:#C2A83E;font-size:2em;">│</span></td><td></td></tr>
	<tr>
		<td class="timeline-date" width="45%"></td>
		<td class="timeline-center" width="10%">
			<img src="https://img.icons8.com/ios-filled/32/C2A83E/vertical-line.png"/>
			<br>🤝
		</td>
		<td width="45%">
			<div class="timeline-block">Open Source & Mentorat<br><span class="timeline-desc">Partage et accompagnement</span></div>
			<div class="timeline-date" style="text-align:left; color:#7CA982;">2026</div>
		</td>
	</tr>
</table>

<footer class="footer-github">
	<div class="footer-container">
		<div class="footer-col">
			<div class="footer-title">USEFUL LINKS</div>
			<div class="footer-links">
				<a href="#">About</a><br>
				<a href="#">Services</a><br>
				<a href="#">Contact</a><br>
				<a href="#">Shop</a><br>
				<a href="#">Blog</a>
			</div>
		</div>
		<div class="footer-col" style="min-width:220px;text-align:center;">
			<div class="footer-title">NEWSLETTER</div>
			<input type="text" class="footer-newsletter-input" placeholder="Your Email Address" disabled />
			<br>
			<button class="footer-newsletter-btn">S'abonner maintenant</button>
		</div>
		<div class="footer-col" style="min-width:200px;text-align:right;">
			<div class="footer-title">Me contacter</div>
			<div class="footer-contact">123, XYZ Road, BSK-3<br>Bangalore, Karnataka, IN</div>
			<div class="footer-social">
				<a href="https://www.facebook.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/facebook.svg" width="22" alt="fb"/></a>
				<a href="https://twitter.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/twitter.svg" width="22" alt="twitter"/></a>
				<a href="https://www.instagram.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/instagram.svg" width="22" alt="insta"/></a>
				<a href="https://www.behance.net/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/behance.svg" width="22" alt="behance"/></a>
			</div>
		</div>
	</div>
</footer> -->
