<img src="https://raw.githubusercontent.com/zunecs/zunecs/main/assets/header.svg" width="100%" alt="" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=EB+Garamond&weight=400&size=24&pause=1600&color=B4552D&center=true&vCenter=true&width=760&lines=Language+models+for+judgment.;Automation+for+the+work.;Pipelines+that+run+without+a+human+in+the+loop." alt="" />
</p>

<p align="center"><img src="https://raw.githubusercontent.com/zunecs/zunecs/main/assets/rule.svg" width="76%" alt="" /></p>

<h3 align="center">I · Provenance</h3>

<p align="center">
  <img src="https://img.shields.io/badge/B.Sc.%20ARTIFICIAL%20INTELLIGENCE-F2EBDD?style=for-the-badge&labelColor=B4552D&color=F2EBDD" />
  <img src="https://img.shields.io/badge/IMAM%20ABDULRAHMAN%20BIN%20FAISAL%20UNIVERSITY-E8DFCC?style=for-the-badge&labelColor=E8DFCC&color=E8DFCC" />
  <br/><br/>
  <img src="https://img.shields.io/badge/COOP%20ENGINEERING%20INTERN-F2EBDD?style=for-the-badge&labelColor=6F7F63&color=F2EBDD" />
  <img src="https://img.shields.io/badge/SAUDI%20ARAMCO%20·%20PLANNING%20%26%20PERFORMANCE-E8DFCC?style=for-the-badge&labelColor=E8DFCC&color=E8DFCC" />
</p>

<p align="center"><img src="https://raw.githubusercontent.com/zunecs/zunecs/main/assets/rule.svg" width="76%" alt="" /></p>

<h3 align="center">II · The Record</h3>

<img src="https://raw.githubusercontent.com/zunecs/zunecs/output/snake.svg" width="100%" alt="" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=zunecs&bg_color=F2EBDD&color=2E2A25&line=B4552D&point=6F7F63&title_color=2E2A25&area=true&area_color=B4552D&hide_border=true&radius=10&custom_title=Commits" width="100%" alt="" />

<p align="center"><img src="https://raw.githubusercontent.com/zunecs/zunecs/main/assets/rule.svg" width="76%" alt="" /></p>

<h3 align="center">III · Plates</h3>

<p align="center">
<a href="https://github.com/zunecs/patent-retriever">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=zunecs&repo=patent-retriever&bg_color=F2EBDD&hide_border=true&border_radius=10&title_color=B4552D&text_color=6B6459&icon_color=6F7F63" />
</a>
<a href="https://github.com/zunecs/AIEmailAssistant">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=zunecs&repo=AIEmailAssistant&bg_color=F2EBDD&hide_border=true&border_radius=10&title_color=B4552D&text_color=6B6459&icon_color=6F7F63" />
</a>
</p>

<br/>

> **PLATE I — Patent Retriever**
> A patent number in, a filing-ready document out. Scrapes and normalizes the full
> patent, then renders a `.docx` matching an exact attorney-filing spec down to the
> custom Word list numbering. Pluggable source layer, CLI and web interface, 147 tests.

```mermaid
%%{init: {'theme':'base','themeVariables':{'background':'#F2EBDD','primaryColor':'#E8DFCC','primaryTextColor':'#2E2A25','primaryBorderColor':'#B4552D','lineColor':'#8A8175','secondaryColor':'#E4E7DE','tertiaryColor':'#F5EFE3','fontFamily':'Georgia, serif'}}}%%
flowchart LR
    A["US20250097171A1"] --> B[Normalize]
    B --> C{Source registry}
    C -->|primary| D[Google Patents]
    C -->|fallback| E[EPO OPS]
    D --> F[(PatentDocument)]
    E --> F
    F --> G[Section mapper]
    G --> H[".docx renderer"]
    G --> I["JSON renderer"]
```

<br/>

> **PLATE II — AI Email Assistant**
> An autonomous mail agent. Reads each email together with its attachments, extracts
> what the sender actually wants, and writes the resulting tasks and calendar entries.
> Suppresses duplicates by vector similarity rather than string matching.

```mermaid
%%{init: {'theme':'base','themeVariables':{'background':'#F2EBDD','primaryColor':'#E8DFCC','primaryTextColor':'#2E2A25','primaryBorderColor':'#B4552D','lineColor':'#8A8175','secondaryColor':'#E4E7DE','tertiaryColor':'#F5EFE3','fontFamily':'Georgia, serif'}}}%%
flowchart LR
    A[Outlook inbox] --> B[Extract attachments]
    B --> C[Gemini]
    C --> D{Structured JSON}
    D --> E[Calendar events]
    D --> F[Tasks]
    D --> G[Reply draft]
    D --> H[Document library]
    F --> I{Embedding<br/>similarity}
    I -->|duplicate| J[Skip]
    I -->|new| K[Create]
    H --> L[Weekly AI report]
```

<p align="center"><img src="https://raw.githubusercontent.com/zunecs/zunecs/main/assets/rule.svg" width="76%" alt="" /></p>

<h3 align="center">IV · Instruments</h3>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,flask,sqlite,git,github,docker,cs,vscode&theme=light" />
</p>

<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=zunecs&show_icons=true&hide_border=true&border_radius=10&bg_color=F2EBDD&title_color=B4552D&text_color=6B6459&icon_color=6F7F63&ring_color=B4552D" />
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=zunecs&layout=compact&hide_border=true&border_radius=10&bg_color=F2EBDD&title_color=B4552D&text_color=6B6459&langs_count=6" />
</p>

<p align="center"><img src="https://raw.githubusercontent.com/zunecs/zunecs/main/assets/rule.svg" width="76%" alt="" /></p>

<h3 align="center">V · Correspondence</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/abdulrahman-alaamri">
    <img src="https://img.shields.io/badge/LINKEDIN-F2EBDD?style=for-the-badge&logo=linkedin&logoColor=F2EBDD&labelColor=B4552D&color=E8DFCC" />
  </a>
  <a href="mailto:2240002427@iau.edu.sa">
    <img src="https://img.shields.io/badge/2240002427@IAU.EDU.SA-E8DFCC?style=for-the-badge&logo=maildotru&logoColor=B4552D&labelColor=E8DFCC&color=E8DFCC" />
  </a>
</p>
