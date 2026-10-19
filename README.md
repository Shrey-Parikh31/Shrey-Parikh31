# Hi, I'm Shrey 👋

Computer Science at **Penn State Harrisburg**, graduating **May 2027**. I build AI applications and ship them, and I spend the rest of my time on computational research and making things usable by people who cannot see the screen.

---

### What I'm building

**[tool-picker](https://github.com/Shrey-Parikh31/tool-picker)**: a Claude Code plugin that shows you which of your installed skills, connectors and plugins fit a prompt, before Claude starts working.
I opened this as a feature request on `anthropics/claude-code`, then built it two days later. It runs on the first prompt of a session, ranks what you have installed by how well it fits the task, and lets you choose. MIT licensed.
`JavaScript` · `MCP` · `Claude Code hooks`

**[RBAC RAG Assistant](https://github.com/Shrey-Parikh31/rbac-rag-assistant)** — a knowledge agent that answers only from documents you are cleared to read.
The caller's role is bound outside the tool interface, so a prompt cannot escalate its own access, and the clearance filter runs before ranking so restricted material never reaches the context window. A 48-question evaluation set scores retrieval separately from generation: moving to embedding-based search took retrieval from **83.3% → 93.8%**, at **94.7%** end-to-end correctness with **zero leaks**.
`Python` · `MCP` · `Gemini` · `embeddings` · `NumPy`

**[AI Classroom Assistant](https://github.com/Shrey-Parikh31/highschool-rag-chatbot)** — [live](https://highschool-rag-chatbot.vercel.app)
A study assistant for students and teachers. Model calls run server-side so the API key never reaches the browser, the teacher role is verified on the server (staff data is never put in the payload at all), and every call is bounded by a timeout with failover to a second model when one runs out of daily quota.
`React` · `Vite` · `Gemini` · `Vercel`

**[DriveScore](https://github.com/Shrey-Parikh31/drivescore)** + **[DriveScore Cloud](https://github.com/Shrey-Parikh31/drivescore-cloud)**
Driving-safety scoring from a 10 Hz accelerometer stream, classified on the device itself, with a Go telemetry service behind it on Kubernetes. Prometheus histograms and five PromQL alert rules; deliberate failure drills found memory requests over-provisioned by **4x**.
`React Native` · `Go` · `Kubernetes` · `Terraform` · `Prometheus`

**[splitwise-lite](https://github.com/Shrey-Parikh31/splitwise-lite)** — [live](https://splitwise-lite-vert.vercel.app)
Log shared expenses, get the fewest payments needed to settle up. Everything stays in your browser.
`React` · `JavaScript`

---

### Research

**[Inverse design for multi-layered high-contrast media](https://github.com/Shrey-Parikh31/photonics-inverse-design)** — MCREU Funded Research Fellow, advised by Dr. Taoufik Meklachi.
MATLAB fixed-point solvers for scattering cross section and Q-factor in layered nanostructures, validated against Mie theory and COMSOL. Awarded the **CPEWC Undergraduate Research Award 2026**.

---

### Also

Accessibility matters to me in practice, not in principle: I produce audio description for university lecture video so blind and low-vision students can use it, and I test what I build with a screen reader.

---

### Reach me

[Portfolio](https://shrey-portfolio-psi.vercel.app) · [LinkedIn](https://www.linkedin.com/in/shrey-parikh31/) · srp6025@psu.edu
