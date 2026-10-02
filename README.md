<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F5AF0,100:2CB67D&height=200&section=header&text=Naveen%20Kumaar&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=GenAI%20%2F%20Data%20Scientist%20%E2%80%94%20Multi-Agent%20%26%20Voice%20AI%20Systems&descAlignY=58&descSize=18" width="100%"/>

<a href="https://www.linkedin.com/in/naveen-kumaar-/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:jotheesssivan@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://github.com/Naveenkumaar/design-journal">
  <img src="https://img.shields.io/badge/Design%20Journal-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<img src="https://readme-typing-svg.demolab.com/?lines=Config-driven+multi-agent+platforms;Cascaded+voice+agents+that+explain+themselves;LLM+orchestration+%2B+evals+%2B+guardrails;Always+shipping+with+tests+%26+an+architecture+doc&font=Fira+Code&center=true&width=700&height=50&color=2CB67D&vCenter=true&size=22" />

</div>

<br/>

## About Me

- 🧠 I build **systems that run AI agents from data, not code** — one engine, one guardrail path, one eval gate, applied to every agent instead of copy-pasted per agent.
- 🎙️ I design **cascaded voice agents** (STT → dialogue → TTS) because auditability and offline testability beat an opaque end-to-end model, for the tasks I build.
- 🧪 Every project ships with **tests, an architecture doc, and a written decision log** — I keep a public [design journal](https://github.com/Naveenkumaar/design-journal) of problems faced, decisions made, and what I'd change if I rebuilt it today.
- 🏗️ Currently exploring: eval-gated releases, maker-checker approvals for high-risk agent actions, and routing-by-self-declared-profile instead of hand-written router tables.
- 📫 Reach me on [LinkedIn](https://www.linkedin.com/in/naveen-kumaar-/) or at **jotheesssivan@gmail.com**.

<br/>

## Featured Builds

<table>
<tr>
<td width="50%" valign="top">

### 🧩 [agentblocks](https://github.com/Naveenkumaar/agentblocks)
**Config-driven multi-agent platform**

Run any number of AI agents from versioned JSON — nothing agent-specific lives in code. One engine, one guardrail path, one eval harness for every agent.

- Two-plane design: control plane (author/activate) never touches runtime plane (execute)
- Staged turn pipeline: `govern → guardrails-in → route → assemble → reason-act → effect → guardrails-out → egress`
- Eval-gated activation — a version that fails golden/adversarial suites never goes live
- Maker-checker approvals on high-risk effector actions
- Includes an **autonomous orchestrator**: hands the system a goal, it decomposes, routes to the best-fit specialist by self-declared agent profile (zero hand-written routing), delegates, and synthesizes one coherent answer
- Plan is previewable & human-editable before it runs; routing exposes score/confidence/alternatives and asks to clarify instead of guessing

`FastAPI` `Python` `SQLite→Postgres` `pytest`

</td>
<td width="50%" valign="top">

### 🎙️ [voxbridge](https://github.com/Naveenkumaar/voxbridge)
**Cascaded voice agent (STT → LLM → TTS)**

A task-oriented voice assistant (restaurant booking) built as three inspectable, swappable stages instead of one opaque speech-to-speech model.

- Pure, deterministic dialogue state machine — fully testable with plain strings, no audio or model required
- Folds any slot heard in a turn (handles "table for 4 tomorrow 8pm, Sam" in one shot)
- Lookup / modify / cancel by reference, multi-booking sessions, relative date/time parsing
- Streaming in both directions: partial transcripts in, sentence-chunked TTS out
- Live mic capture with barge-in; runs fully offline via pluggable backend stubs

`Python` `Whisper` `pyttsx3` `SQLite`

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br/>

| Project | What it is |
|---|---|
| [ET_Hackathon_main](https://github.com/Naveenkumaar/ET_Hackathon_main) | Hybrid GraphRAG system |
| [kovai-delivery-hackathon](https://github.com/Naveenkumaar/kovai-delivery-hackathon) | Multi-agent drone delivery simulation |
| [emotionsense](https://github.com/Naveenkumaar/emotionsense) | Multi-label emotion classification |
| [autolysis](https://github.com/Naveenkumaar/autolysis) | LLM-powered automated data analysis |
| [github-users-analysis](https://github.com/Naveenkumaar/github-users-analysis) | GitHub API scraper & analysis |

</details>

<br/>

## Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,fastapi,pytorch,react,js,postgres,sqlite,docker,git,github,linux,bash&theme=dark" />

</div>

<br/>

## GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Naveenkumaar&show_icons=true&theme=synthwave&hide_border=true&bg_color=00000000&include_all_commits=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Naveenkumaar&layout=compact&theme=synthwave&hide_border=true&bg_color=00000000" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Naveenkumaar&theme=synthwave&hide_border=true&background=00000000" />

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=Naveenkumaar&theme=darkhub&no-frame=true&no-bg=true&margin-w=15&column=7" />

</div>

<br/>

<div align="center">

### 🐍 Contribution Snake

<img src="https://raw.githubusercontent.com/Naveenkumaar/Naveenkumaar/output/github-contribution-grid-snake-dark.svg" />

</div>

<br/>

<div align="center">

<img src="https://komarev.com/ghpvc/?username=Naveenkumaar&style=for-the-badge&color=7F5AF0&label=PROFILE+VIEWS" />

<br/><br/>

<i>Design, build, document, ship — in that order.</i>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2CB67D,100:7F5AF0&height=100&section=footer" width="100%"/>

</div>
