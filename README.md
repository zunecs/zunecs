<img src="https://raw.githubusercontent.com/zunecs/zunecs/main/assets/header.svg" width="100%" alt="" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=300&size=17&pause=1200&color=D2571F&center=true&vCenter=true&width=620&lines=LLMs+for+judgment.+Automation+for+the+work.;Document+pipelines+that+run+end+to+end.;Agents+that+read%2C+decide%2C+and+act." alt="" />
</p>

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/B.Sc.%20Artificial%20Intelligence-FFFFFF?style=for-the-badge&labelColor=D2571F" />
  <img src="https://img.shields.io/badge/Imam%20Abdulrahman%20Bin%20Faisal%20University-F3F4F6?style=for-the-badge&labelColor=F3F4F6" />
  <img src="https://img.shields.io/badge/COOP%20@%20Saudi%20Aramco-F3F4F6?style=for-the-badge&labelColor=F3F4F6" />
</p>

<br/>

<h3 align="center">Contribution activity</h3>

<img src="https://raw.githubusercontent.com/zunecs/zunecs/output/snake.svg" width="100%" alt="" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=zunecs&bg_color=FAFAFA&color=1A1A1A&line=D2571F&point=1A1A1A&title_color=1A1A1A&area=true&area_color=D2571F&hide_border=true&custom_title=Commits" width="100%" alt="" />

<br/>

<h3 align="center">Work</h3>

<p align="center">
<a href="https://github.com/zunecs/patent-retriever">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=zunecs&repo=patent-retriever&bg_color=FAFAFA&hide_border=true&title_color=D2571F&text_color=57606A&icon_color=D2571F" />
</a>
<a href="https://github.com/zunecs/AIEmailAssistant">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=zunecs&repo=AIEmailAssistant&bg_color=FAFAFA&hide_border=true&title_color=D2571F&text_color=57606A&icon_color=D2571F" />
</a>
</p>

<br/>

**Patent Retriever** — a patent number in, a filing-ready document out. Scrapes and
normalizes the full patent, then renders a `.docx` matching an exact attorney-filing
spec down to custom Word list numbering. Pluggable sources, CLI + web UI, 147 tests.

```mermaid
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

**AI Email Assistant** — an autonomous mail agent. Reads each email together with its
attachments, extracts what the sender actually wants, and writes the resulting tasks and
calendar entries. Suppresses duplicates using vector similarity rather than string matching.

```mermaid
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

<br/>

<h3 align="center">Stack</h3>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,flask,sqlite,git,github,docker,cs,vscode&theme=light" />
</p>

<br/>

<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=zunecs&show_icons=true&hide_border=true&bg_color=FAFAFA&title_color=D2571F&text_color=57606A&icon_color=D2571F&ring_color=D2571F" />
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=zunecs&layout=compact&hide_border=true&bg_color=FAFAFA&title_color=D2571F&text_color=57606A&langs_count=6" />
</p>

<br/>

<p align="center">
  <a href="https://www.linkedin.com/in/abdulrahman-alaamri">
    <img src="https://img.shields.io/badge/LinkedIn-FFFFFF?style=for-the-badge&logo=linkedin&logoColor=D2571F&labelColor=F3F4F6" />
  </a>
  <a href="mailto:2240002427@iau.edu.sa">
    <img src="https://img.shields.io/badge/2240002427@iau.edu.sa-FFFFFF?style=for-the-badge&logo=maildotru&logoColor=D2571F&labelColor=F3F4F6" />
  </a>
</p>
