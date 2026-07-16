<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=F1F1F1&center=true&vCenter=true&random=false&width=524&lines=%E2%8A%B9+Welcome+to+my+profile!+%CB%99%E1%B5%95%CB%99+%E2%8A%B9+" alt="Typing SVG">
  </a>
</div>

#

Me chamo Daniel Henrique, sou natural do Brasil 🇧🇷 e atuo como Pesquisador de Segurança da Informação. Sou apaixonado por Offensive Security, Reverse Engineering, Malware Analysis e AI/LLM Security, além de caçador de Bug Bounty focado em vulnerabilidades web e API. Gosto de CTFs, Red Team e explorar novos vetores de ataque envolvendo Inteligência Artificial.

#

<h3 align="left">Connect with me!</h3>

[![E-mail](https://img.shields.io/badge/-Email-000?style=for-the-badge&logo=gmail&logoColor=FF00F6&color=FFF)](mailto:seuemail@example.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-000?style=for-the-badge&logo=linkedin&logoColor=FF00F6&color=FFF)](https://www.linkedin.com/in/daniel-henriquesilv/)
[![Instagram](https://img.shields.io/badge/-Instagram-000?style=for-the-badge&logo=instagram&logoColor=F1F1F1&color=FFF)](https://www.instagram.com/snuup___/)

<h3 align="left">My Stack ~</h3>

<img align="left" alt="Python" title="Python" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" />
<img align="left" alt="JavaScript" title="JavaScript" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" />
<img align="left" alt="TypeScript" title="TypeScript" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" />
<img align="left" alt="Bash" title="Bash" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bash/bash-original.svg" />
<img align="left" alt="React" title="React" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" />
<img align="left" alt="Node.js" title="Node.js" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original.svg" />
<img align="left" alt="Docker" title="Docker" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" />
<img align="left" alt="Linux" title="Linux" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" />
<img align="left" alt="Git" title="Git" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" />
<img align="left" alt="MongoDB" title="MongoDB" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original.svg" />
<img align="left" alt="MySQL" title="MySQL" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" />
<br clear="left"/>
<br/>

<h3 align="left">GitHub Stats</h3>

<p>
  <img 
    align="left" 
    alt="GitHub Stats" 
    height="200" 
    style="padding-right: 10px;" 
    src="https://github-readme-stats-two-omega-43.vercel.app/api?username=DanielHenriqueSilv&show_icons=true&locale=pt-br&hide=contribs&cache_seconds=21600&bg_color=000000&title_color=ffffff&text_color=ffffff&icon_color=ffffff&border_color=ffffff&ring_color=ffffff&custom_title=My%20GitHub%20Statistics"
  />
  <img 
    align="left" 
    alt="GitHub Stats" 
    height="200" 
    src="https://github-readme-stats-two-omega-43.vercel.app/api/top-langs/?username=DanielHenriqueSilv&layout=compact&custom_title=Stack&langs_count=8&bg_color=000000&title_color=ffffff&text_color=ffffff&icon_color=ffffff&border_color=ffffff&ring_color=ffffff" 
  />
</p>
<br clear="left"/>
<br/>

<h3 align="left">🐍 Contribution Snake</h3>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/DanielHenriqueSilv/DanielHenriqueSilv/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/DanielHenriqueSilv/DanielHenriqueSilv/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/DanielHenriqueSilv/DanielHenriqueSilv/output/github-contribution-grid-snake.svg" width="100%">
  </picture>
</div>

<details>
<summary><sub>⚙️ Como ativar a snake (clique para expandir)</sub></summary>

Crie o arquivo `.github/workflows/snake.yml` no seu repositório de perfil (`DanielHenriqueSilv/DanielHenriqueSilv`) com o conteúdo abaixo. O GitHub Action roda a cada 12h e gera o SVG animado a partir do seu gráfico de contribuições.

```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Depois de rodar pela primeira vez, a animação acima passa a aparecer automaticamente.

</details>

---

## 🛡️ Security Expertise

**🌐 Web Security**

![OWASP Top 10](https://img.shields.io/badge/OWASP_Top_10-1E293B?style=flat-square) ![Burp Suite](https://img.shields.io/badge/Burp_Suite-1E293B?style=flat-square) ![SQLi](https://img.shields.io/badge/SQLi-1E293B?style=flat-square) ![XSS](https://img.shields.io/badge/XSS-1E293B?style=flat-square) ![SSRF](https://img.shields.io/badge/SSRF-1E293B?style=flat-square)

**🔎 Bug Bounty**

![Recon Automation](https://img.shields.io/badge/Recon_Automation-1E293B?style=flat-square) ![Subdomain Enum](https://img.shields.io/badge/Subdomain_Enumeration-1E293B?style=flat-square) ![API Testing](https://img.shields.io/badge/API_Testing-1E293B?style=flat-square)

**🔬 Reverse Engineering**

![Static Analysis](https://img.shields.io/badge/Static%2FDynamic_Analysis-1E293B?style=flat-square) ![IDA Pro](https://img.shields.io/badge/IDA_Pro-1E293B?style=flat-square) ![Ghidra](https://img.shields.io/badge/Ghidra-1E293B?style=flat-square) ![x64dbg](https://img.shields.io/badge/x64dbg-1E293B?style=flat-square)

**🤖 AI Security**

![LLM Jailbreaking](https://img.shields.io/badge/LLM_Jailbreaking-1E293B?style=flat-square) ![Prompt Injection](https://img.shields.io/badge/Prompt_Injection-1E293B?style=flat-square) ![Model Extraction](https://img.shields.io/badge/Model_Extraction-1E293B?style=flat-square)

**🐧 Linux & Networking**

![Kernel Exploitation](https://img.shields.io/badge/Kernel_Exploitation-1E293B?style=flat-square) ![Privilege Escalation](https://img.shields.io/badge/Privilege_Escalation-1E293B?style=flat-square) ![TCP/IP](https://img.shields.io/badge/TCP%2FIP-1E293B?style=flat-square) ![Wireshark](https://img.shields.io/badge/Wireshark-1E293B?style=flat-square)

**🎯 Malware Analysis & OSINT**

![Sandboxing](https://img.shields.io/badge/Sandboxing-1E293B?style=flat-square) ![Behavioral Analysis](https://img.shields.io/badge/Behavioral_Analysis-1E293B?style=flat-square) ![IOC Extraction](https://img.shields.io/badge/IOC_Extraction-1E293B?style=flat-square) ![Threat Intel](https://img.shields.io/badge/Threat_Intelligence-1E293B?style=flat-square)

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

**🛡️ MemeRadar**

Social media threat intelligence platform that detects and tracks malicious content using AI-powered image & text analysis.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![AI](https://img.shields.io/badge/AI-Powered-7C3AED?style=flat-square)

</td>
<td width="50%" valign="top">

**🤖 AI Security Labs**

Research experiments on LLM vulnerabilities — prompt injection, jailbreaks, model extraction, and AI red-teaming techniques.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LLM](https://img.shields.io/badge/LLM-Security-EF4444?style=flat-square)
![Research](https://img.shields.io/badge/Research-Active-22C55E?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🔬 Reverse Engineering Toolkit**

Malware analysis scripts: unpacking, deobfuscation, IOC extraction, and behavioral profiling for common malware families.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-x86--64-F97316?style=flat-square)
![Malware](https://img.shields.io/badge/Malware-Analysis-DC2626?style=flat-square)

</td>
<td width="50%" valign="top">

**🌐 CineMania**

Full-stack movie discovery platform with real-time recommendations, watchlist management, and review system.

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🛒 Ecommerce Platform**

Scalable e-commerce solution with real-time inventory, payment integration, and admin dashboard.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</td>
<td width="50%" valign="top">

**⚙️ Security Automation Suite**

Recon, fuzzing, and reporting automation for bug bounty — subdomain discovery, port scanning, and vulnerability correlation.

![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![BugBounty](https://img.shields.io/badge/Bug-Bounty-F59E0B?style=flat-square)

</td>
</tr>
</table>

---

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=DanielHenriqueSilv&theme=tokyonight&column=4&margin-w=12&margin-h=12&no-frame=true"/>
</div>

---

## 🌐 Connect

<div align="center">
  <a href="https://www.linkedin.com/in/daniel-henriquesilv/">
    <img width="40" src="https://cdn.simpleicons.org/linkedin/0A66C2"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://www.instagram.com/snuup___/">
    <img width="40" src="https://cdn.simpleicons.org/instagram/E4405F"/>
  </a>
</div>

<br>

<div align="center">
  <i>"Security is not a product, but a process." — Bruce Schneier</i>
</div>

---

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=130&color=0:7C3AED,60:1E3A5F,100:0F172A"/>
</div>
