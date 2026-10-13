<!-- GitHub Profile README | github.com/hadi-ce04 -->

<div align="center">
  <img width="100%" alt="Abdul Hadi — Computer Engineering and Intelligent Systems" src="https://capsule-render.vercel.app/api?type=waving&height=215&color=0:0D1117,50:172554,100:0891B2&text=Abdul%20Hadi&fontSize=56&fontColor=FFFFFF&fontAlignY=38&desc=Computer%20Engineering%20%7C%20AI%20%7C%20Robotics%20%7C%20Automation&descSize=17&descAlignY=59&animation=fadeIn" />

  <a href="https://github.com/hadi-ce04">
    <img alt="GitHub profile" src="https://img.shields.io/badge/GitHub-hadi--ce04-0D1117?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://github.com/hadi-ce04/agentgate">
    <img alt="Explore AgentGate" src="https://img.shields.io/badge/Featured-AgentGate-06B6D4?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://studysync-henna-delta.vercel.app">
    <img alt="Try StudySync" src="https://img.shields.io/badge/Live%20App-StudySync-2563EB?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>

  <br /><br />

  <img alt="Current areas of focus" src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=2800&pause=900&color=22D3EE&center=true&vCenter=true&width=700&lines=AI+Agents+%26+Security;Robotics+%26+Computer+Vision;Real-Time+Systems+%26+Automation;From+prototype+to+working+system" />

  <p><b>Computer Engineering @ Epitech Paris</b> 🇫🇷</p>
  <p>Curious about systems that can <b>perceive, decide and act</b>.</p>

  <a href="#agentgate">AgentGate</a> &nbsp;•&nbsp;
  <a href="#projects">Projects</a> &nbsp;•&nbsp;
  <a href="#toolbox">Toolbox</a> &nbsp;•&nbsp;
  <a href="#activity">Activity</a>
</div>

---

<a id="agentgate"></a>

## 🛡️ Featured Project · AgentGate

**A release gate that tests AI agents for security regressions before a configuration change ships.**

Developed as a **team hackathon project** at Secure Horizons. Instead of assuming a prompt or tool change is safe, AgentGate runs adversarial tests against a trusted baseline and a candidate, measures the difference, and records the release decision.

<div align="center">
  <img alt="16 adversarial attacks" src="https://img.shields.io/badge/Attack%20Suite-16%20Scenarios-0891B2?style=flat-square" />
  <img alt="320 trials per configuration" src="https://img.shields.io/badge/Evaluation-320%20Trials%2FConfig-2563EB?style=flat-square" />
  <img alt="Release decisions" src="https://img.shields.io/badge/Verdicts-ALLOW%20%7C%20REVIEW%20%7C%20BLOCK-7C3AED?style=flat-square" />
  <img alt="Signed ledger" src="https://img.shields.io/badge/Evidence-Ed25519%20Signed-0F766E?style=flat-square" />
</div>

<br />

| What it tackles | How |
| :-- | :-- |
| **Prompt injection & tool misuse** | Tests malicious instructions planted across user turns, email, documents and tool descriptions. |
| **Uncertain safety claims** | Uses deterministic breach checks and Wilson confidence intervals instead of asking an LLM to grade itself. |
| **Hard-to-audit deployments** | Produces signed, tamper-evident decision records and exportable evidence packs. |
| **Finding the risky edit** | Isolates configuration changes to identify regressions and interactions. |

**Built with:** `Python` · `Amazon Bedrock` · `Streamlit` · `Cryptography` · `Statistical Testing` · `AI Agent Evaluation`

<p align="center">
  <a href="https://github.com/hadi-ce04/agentgate">
    <img alt="Explore AgentGate code" src="https://img.shields.io/badge/Explore%20the%20Code-0D1117?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://github.com/hadi-ce04/agentgate/blob/main/evidence/samples/pack_v7_llama.pdf">
    <img alt="View sample evidence pack" src="https://img.shields.io/badge/View%20Evidence%20Pack-0E7490?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" />
  </a>
</p>

<details>
<summary><b>🔎 Open the AgentGate architecture</b></summary>

<br />

```mermaid
flowchart TD
    A[Trusted baseline] --> C[16 adversarial scenarios]
    B[Candidate configuration] --> C
    C --> D[Run trials on deployed model]
    D --> E[Deterministic breach checks]
    E --> F[Statistical release gate]
    F --> G{Verdict}
    G --> H[ALLOW]
    G --> I[REVIEW]
    G --> J[BLOCK]
    G --> K[Signed ledger and evidence pack]
```

AgentGate also supports change attribution, signed human overrides, and scheduled rechecks. The project uses synthetic test data, and the gate evaluates configured attack scenarios rather than guaranteeing complete security.

</details>

---

## 👨‍💻 A Little About Me

I'm a **Computer Engineering student** who likes building things that connect software to the real world. I'm especially drawn to the boundary between intelligent software, physical systems and reliable infrastructure.

I enjoy the full cycle: **idea → experiment → working prototype → improvement**. That might mean testing an AI agent, streaming telemetry from simulated machines, or getting an object detector running on camera input.

**What I'm focused on:**

- 🤖 **Robotics:** autonomous systems, ROS2 and robot perception
- 🧠 **AI:** computer vision, LLM-powered agents and evaluation
- ⚙️ **Automation:** practical workflows, tooling and system integration
- 🌐 **Software:** full-stack apps and real-time architectures
- 🔌 **Embedded:** connecting code, sensors and hardware

---

<a id="projects"></a>

## 🚀 Other Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📚 <a href="https://github.com/hadi-ce04/studysync">StudySync</a></h3>
      <p><b>Study together. Stay focused.</b></p>
      <p>A collaborative study application with real-time study rooms, Pomodoro sessions, tasks, shared music and AI-assisted learning.</p>
      <p><code>React</code> <code>TypeScript</code> <code>FastAPI</code> <code>WebSockets</code> <code>Tailwind</code></p>
      <a href="https://github.com/hadi-ce04/studysync"><img alt="StudySync source" src="https://img.shields.io/badge/Source-0D1117?style=flat-square&logo=github&logoColor=white" /></a>
      <a href="https://studysync-henna-delta.vercel.app"><img alt="StudySync live demo" src="https://img.shields.io/badge/Live%20Demo-2563EB?style=flat-square&logo=vercel&logoColor=white" /></a>
    </td>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/hadi-ce04/sentinelgrid">SentinelGrid</a></h3>
      <p><b>Real-time visibility into simulated machines.</b></p>
      <p>An industrial fleet simulator and monitoring dashboard with live machine telemetry, anomaly detection, fault injection and incident alerts.</p>
      <p><code>Python</code> <code>FastAPI</code> <code>WebSockets</code> <code>JavaScript</code></p>
      <a href="https://github.com/hadi-ce04/sentinelgrid"><img alt="SentinelGrid source" src="https://img.shields.io/badge/Explore%20Project-0D1117?style=flat-square&logo=github&logoColor=white" /></a>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>👁️ <a href="https://github.com/hadi-ce04/robot-vision-yolo">Robot Vision YOLO</a></h3>
      <p><b>Giving camera-equipped systems a way to understand their surroundings.</b></p>
      <p>A real-time object-detection experiment using YOLO and OpenCV, exploring the perception layer for future robotics applications.</p>
      <p><code>Python</code> <code>YOLO</code> <code>OpenCV</code> <code>Computer Vision</code></p>
      <a href="https://github.com/hadi-ce04/robot-vision-yolo"><img alt="Robot Vision YOLO source" src="https://img.shields.io/badge/Explore%20Project-0D1117?style=flat-square&logo=github&logoColor=white" /></a>
    </td>
  </tr>
</table>

---

<a id="toolbox"></a>

## 🧰 Toolbox

**Languages & web**

<img alt="Python, C++, JavaScript, TypeScript, React" src="https://skillicons.dev/icons?i=python,cpp,js,ts,react&theme=dark" />

**Backend, tools & infrastructure**

<img alt="FastAPI, Docker, Linux, Git, Arduino and Raspberry Pi" src="https://skillicons.dev/icons?i=fastapi,docker,linux,git,arduino,raspberrypi&theme=dark" />

**AI, robotics & automation**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-111827?style=flat-square&logo=ultralytics&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Amazon Bedrock](https://img.shields.io/badge/Amazon%20Bedrock-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

<details>
<summary><b>📍 What I'm exploring right now</b></summary>

- **Robotics:** ROS2, simulation pipelines, control and robot perception
- **AI:** agent evaluation, adversarial testing and computer vision
- **Systems:** real-time communication, streaming telemetry and embedded interfaces
- **Automation:** Python, Docker, n8n and repeatable developer workflows

</details>

---

<a id="activity"></a>

## 📈 GitHub Activity

<div align="center">
  <img width="95%" alt="GitHub contribution activity graph" src="https://github-readme-activity-graph.vercel.app/graph?username=hadi-ce04&bg_color=0D1117&color=22D3EE&line=0891B2&point=FFFFFF&area=true&hide_border=true" />
</div>

---

## 🤝 Let's Build Something

I enjoy **hackathons, open-source experiments and collaborating with people who like turning ideas into real working systems**. If you're working on something involving agents, robotics, intelligent automation or real-time software, I'd love to hear about it.

<div align="center">
  <a href="https://github.com/hadi-ce04">
    <img alt="Follow on GitHub" src="https://img.shields.io/badge/Find%20Me%20on%20GitHub-0D1117?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <p>Discord: <code>hadi__x4__93060</code></p>
  <img width="100%" alt="Footer wave" src="https://capsule-render.vercel.app/api?type=waving&height=95&section=footer&color=0:0D1117,50:172554,100:0891B2" />
</div>
