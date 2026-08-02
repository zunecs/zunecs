<img src="https://raw.githubusercontent.com/zunecs/zunecs/main/assets/header.svg" width="100%" alt="" />

<br/>

I build systems where a language model does the judgment and automation does the work.
Document pipelines, email agents, RPA robots — designed to run end to end with no human in the loop.

Currently a COOP intern at **Saudi Aramco**, Planning &amp; Performance Management.

<br/>

### Education

**B.Sc. Artificial Intelligence** — Imam Abdulrahman Bin Faisal Univerisy
`Machine Learning` · `Robotics` · `Information Security` · `Data Structures` · `Databases`

<br/>

### Work

<a href="https://github.com/zunecs/patent-retriever">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=zunecs&repo=patent-retriever&theme=transparent&hide_border=true&title_color=E86A33&text_color=8B949E&icon_color=E86A33" />
</a>
<a href="https://github.com/zunecs/AIEmailAssistant">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=zunecs&repo=ai-email-assistant&theme=transparent&hide_border=true&title_color=E86A33&text_color=8B949E&icon_color=E86A33" />
</a>

<br/><br/>

**Patent Retriever** — enter a patent number, get back a formatted legal filing.
Scrapes and normalizes the full document, then renders a `.docx` that matches an exact
attorney-filing spec down to the custom Word list numbering. Pluggable source layer,
CLI and web interface, 147 tests.

```mermaid
flowchart LR
    A["US20250097171A1"] --> B[Normalize]
    B --> C{Source registry}
    C -->|primary| D[Google Patents]
    C -->|fallback| E[EPO OPS]
    D --> F[PatentDocument]
    E --> F
    F --> G[Section mapper]
    G --> H[.docx renderer]
    G --> I[JSON renderer]
```

**AI Email Assistant** — an autonomous mail agent. Reads incoming email and its
attachments together, extracts action items, deadlines and meetings, then writes
Outlook tasks and calendar events. Uses vector embeddings and cosine similarity to
suppress duplicate tasks, files attachments into a categorized library with
AI-written summaries, and emails a generated weekly report.

<br/>

### Stack

`Python` `Flask` `pytest` `SQL` `Git` `UiPath` `Gemini API` `Embeddings` `python-docx`

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=zunecs&show_icons=true&hide_border=true&bg_color=00000000&title_color=E86A33&text_color=8B949E&icon_color=E86A33" />
  <img height="140" src="https://github-readme-stats.vercel.app/api?username=zunecs&show_icons=true&hide_border=true&bg_color=00000000&title_color=E86A33&text_color=57606A&icon_color=E86A33" />
</picture>

<br/><br/>

<a href="www.linkedin.com/in/abdulrahman-alaamri">LinkedIn</a> &nbsp;·&nbsp; <a href="mailto:2240002427@iau.edu.sa">Email</a>
