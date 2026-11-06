# 🚀 AEGIS
### MISSION OPERATIONS COPILOT
#### Intelligence for the Next Frontier.

<p align="center">
  <strong>🛰️ Simulate. Investigate. Understand. Respond.</strong>
  <br/>
  An AI-assisted spacecraft operations simulation built for hackathon problem ST-10.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PROJECT-AEGIS-00D4FF?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/AI-GOOGLE_GEMINI-4285F4?style=for-the-badge&logo=google"/>
  <img src="https://img.shields.io/badge/RUNTIME-NODE.JS-339933?style=for-the-badge&logo=nodedotjs"/>
  <img src="https://img.shields.io/badge/MODE-LOCAL_SIMULATION-22C55E?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/HACKATHON-ST--10-8B5CF6?style=for-the-badge"/>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:020617,50:0C4A6E,100:06B6D4&height=6" width="100%"/>
</p>

---

## 🌌 MISSION OVERVIEW

Spacecraft operations involve complex systems, technical documentation, telemetry, and unexpected operational incidents.

Understanding these situations requires the ability to investigate information, interpret technical documents, and make sense of available system data.

**AEGIS – Mission Operations Copilot** explores how AI can assist with spacecraft operations through a local-only simulation environment.

Designed around hackathon problem ST-10, AEGIS provides a simulated environment for mission investigations using demo telemetry, incident data, and uploaded technical documents.

> **One Mission. Multiple Signals. Smarter Investigations.**

---

## ✦ CORE CAPABILITIES

<table>
<tr>
<td width="50%">

### 🛰️ Mission Operations Simulation

Explore a simulated spacecraft operations environment using demonstration incidents and telemetry.

</td>
<td width="50%">

### 🧠 AI-Assisted Investigations

Use Google Gemini to assist with mission-related investigations and analyze relevant contextual information.

</td>
</tr>
<tr>
<td width="50%">

### 📄 Technical Document Intelligence

Upload PDF documents, parse their contents, and index information for relevant investigation context.

</td>
<td width="50%">

### 🔍 Context-Aware Retrieval

Retrieve a small number of relevant document excerpts to provide context during investigations.

</td>
</tr>
<tr>
<td width="50%">

### 🔐 Local-First Architecture

Keep the Gemini API key on the local backend rather than exposing it to the browser.

</td>
<td width="50%">

### ⚙️ Demo Fallback Mode

Explore the simulation even without a configured Gemini API key using the available demo fallback.

</td>
</tr>
</table>

---

## 🧠 HOW AEGIS WORKS

<p align="center">
  <img src="https://img.shields.io/badge/01-DATA_INPUT-0E7490?style=for-the-badge"/>
  &nbsp;➜&nbsp;
  <img src="https://img.shields.io/badge/02-DOCUMENT_PARSING-0369A1?style=for-the-badge"/>
  &nbsp;➜&nbsp;
  <img src="https://img.shields.io/badge/03-CONTEXT_RETRIEVAL-4338CA?style=for-the-badge"/>
  &nbsp;➜&nbsp;
  <img src="https://img.shields.io/badge/04-AI_INVESTIGATION-7C3AED?style=for-the-badge"/>
</p>

| Stage | Process | Description |
|:---:|---|---|
| 01 | 🛰️ Input | Work with simulated incidents and telemetry. |
| 02 | 📄 Parsing | Upload and parse technical PDF documents. |
| 03 | 🔍 Indexing | Index document content in local memory. |
| 04 | 🧠 Retrieval | Identify relevant document excerpts. |
| 05 | ✦ Investigation | Include selected context in a Gemini-assisted investigation. |
| 06 | 📋 Results | Explore investigation output within the simulation. |

---

## 🤖 AI-POWERED INVESTIGATION

AEGIS integrates Google's Gemini API to support AI-assisted mission investigations.

The investigation workflow is designed around:

- Relevant technical document context.
- Selected document excerpts.
- Simulated operational incidents.
- Available demonstration telemetry.
- AI-assisted interpretation and investigation.

### Why Gemini?

The integration allows the simulation to explore how generative AI can help interpret technical information and support structured investigations.

<blockquote>
  <strong>Mission Intelligence, Powered by AI.</strong>
  <br/>
  Turning technical information into more accessible investigation context.
</blockquote>

---

## 🔐 LOCAL-FIRST & SECURITY DESIGN

AEGIS follows a local-first approach for its simulation workflow.

| Component | Implementation |
|---|---|
| Application | Runs locally |
| Gemini API Key | Stored on the local backend |
| Browser | Does not receive the Gemini secret key |
| PDF Processing | Parsed locally |
| Document Indexing | Local memory |
| Investigation Context | Only selected relevant excerpts |
| Telemetry | Simulated demonstration data |

**Privacy-focused design decisions:**

- API credentials are kept outside the browser.
- Uploaded PDFs are processed and indexed in local memory.
- Investigations use only a limited number of matching document excerpts.
- The simulation does not connect to an actual spacecraft.

---

## 🛠️ TECHNOLOGY & INTEGRATION

| Technology | Purpose |
|---|---|
| Node.js 20+ | Application runtime |
| Google Gemini API | AI-assisted investigations |
| PDF Parsing | Technical document processing |
| Local Memory Indexing | Document context retrieval |
| Vite Development Server | Local development environment |

---

## ⚙️ GETTING STARTED

Ready to initialize your mission environment?

### Prerequisites

- Node.js 20 or higher
- npm
- Google Gemini API key (optional)

### 01. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/AEGIS.git
```

### 02. Enter the Project Directory

```bash
cd AEGIS
```

### 03. Install Dependencies

```bash
npm install
```

### 04. Configure Environment Variables

Copy the example environment file:

```bash
cp .env.example .env
```

Add your Gemini API key to `.env`:

```env
GEMINI_API_KEY=your_google_gemini_api_key
```

**Note:** Gemini configuration is optional. The demo fallback allows the application to run without a live API key.

### 05. Launch AEGIS

```bash
npm run dev
```

### 06. Access Mission Control

Open your browser:

```text
http://localhost:5173
```

<badge color="success">MISSION ENVIRONMENT READY</badge>

---

## 📸 MISSION CONTROL PREVIEW

<p align="center">
  <strong>Explore the AEGIS Mission Operations Interface</strong>
  <br/>
  <sub>Add actual application screenshots below.</sub>
</p>

<!-- Replace these paths with your actual screenshots -->

<p align="center">
  <img src="screenshots/dashboard.png" width="90%" alt="AEGIS Mission Dashboard"/>
</p>

<p align="center">
  <img src="screenshots/investigation.png" width="90%" alt="AI Investigation Interface"/>
</p>

<p align="center">
  <sub>Mission Dashboard • AI Investigation • Technical Document Analysis</sub>
</p>

---

## 🎯 PROBLEM STATEMENT — ST-10

**Building an AI-assisted mission operations experience.**

AEGIS explores how artificial intelligence and document intelligence can be combined in a spacecraft operations simulation.

### Our Approach

- Create a simulated mission operations environment.
- Provide demonstration incidents and telemetry.
- Enable technical PDF document uploads.
- Retrieve relevant information from indexed documents.
- Use AI to assist with contextual investigations.
- Maintain a local-first application architecture.

---

## 🔭 FUTURE MISSION ROADMAP

The AEGIS concept can be extended with additional capabilities:

- [ ] Advanced mission dashboard visualizations.
- [ ] Interactive telemetry charts.
- [ ] More simulated spacecraft incidents.
- [ ] Enhanced document retrieval.
- [ ] Multi-document investigation support.
- [ ] Structured investigation reports.
- [ ] Historical incident comparison.
- [ ] Expanded AI-assisted mission analysis.

---

## ⚠️ IMPORTANT SIMULATION DISCLAIMER

AEGIS is a **local-only spacecraft operations simulation** developed for hackathon problem ST-10.

- It does not connect to an actual spacecraft.
- It does not receive real spacecraft telemetry.
- All included incidents and telemetry are simulated demonstration data.
- AI-generated investigations are experimental and informational.
- It is not designed or validated for real spacecraft operations.

---

## 🏆 BUILT FOR INNOVATION

AEGIS demonstrates how AI-assisted investigation, document processing, and contextual information retrieval can be brought together in a simulated aerospace operations environment.

**Our vision:** Make complex mission information easier to explore, investigate, and understand through intelligent software.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:06B6D4,50:0C4A6E,100:020617&height=6" width="100%"/>
</p>

<h1 align="center">🚀 AEGIS</h1>

<h3 align="center">MISSION OPERATIONS COPILOT</h3>

<p align="center">
  <strong>Intelligence for the Next Frontier.</strong>
  <br/>
  <sub>Built with curiosity, engineering, and AI.</sub>
</p>

<p align="center">
  <sub>© 2026 AEGIS | Hackathon Project ST-10</sub>
</p>
