<h1 align="center">Hrittik Chatterjee</h1>

<p align="center"><b>Software Engineer · CS @ UC Santa Cruz</b></p>
<p align="center"><i>I build hard technology — and the products around it.</i></p>

<p align="center">
  <a href="https://hrittik.com"><img src="https://img.shields.io/badge/hrittik.com-0b0c0e?style=flat-square&logo=vercel&logoColor=2fe3c0" alt="website"></a>
  <a href="mailto:hrittikchatterjee@gmail.com"><img src="https://img.shields.io/badge/email-0b0c0e?style=flat-square&logo=gmail&logoColor=2fe3c0" alt="email"></a>
  <img src="https://img.shields.io/badge/Santa%20Cruz,%20CA-0b0c0e?style=flat-square" alt="location">
</p>

---

Software engineer working on autonomy and AI systems: sensor pipelines on edge hardware, the
backend services around them, and the AI tooling that ties them together. Currently a CS student at
**UC Santa Cruz**, building in parallel with school.

### 🚩 Flagships

**[Forge](https://hrittik.com/#forge) — the OS for agentic hardware engineering.**
LLM engineering agents take real actions across the toolchain — reasoning about a design,
executing steps, handing work off to one another — while a cloud layer versions everything and
keeps human + agent teams in sync. The OS for the agentic pathways that actually get engineering done.

**[Argus](https://hrittik.com/#argus) — fully autonomous drones that navigate where GPS can't reach.**
Natural-language mission in → an on-device LLM commander plans and executes → vision-inertial
odometry fused with satellite-imagery localization holds position without drift → the aircraft
detects, returns to launch, and writes its own report. The entire brain runs on a single **$200
Jetson Orin Nano**; PX4 owns flight and hardware failsafe. `0 humans in the loop`.

### 🛠 Also building

- **Terrain-Relative Navigation** — satellite place recognition for GPS-denied flight: DINOv2-ViT-S/14 fine-tuned with contrastive loss on 198K satellite tiles, searched through a FAISS index over the continental US. In flight, absolute fixes currently come from template + SIFT matching against cached tiles.
- **Verix Credential** — face-authenticated payments backend: card authorization across Stripe and Square point-of-sale (sandbox), made idempotent so a cashier retry can't double-charge; single-use tokens consumed atomically in PostgreSQL, verified with a 12-thread contention test.
- **Sentinel** — backpack-deployable tactical C2 (MAVLink over LoRa, ImGui, AIS/ADS-B/OSINT fusion + LLM tools).
- **LLM-Driven Trading Bot** — local Llama 3.1 + classical technical analysis paper trading through Interactive Brokers, under a risk manager with hard position and loss limits.
- **[Nexus](https://github.com/hrittikchatterjee/nexus-agentic)** — agentic mission control: a Claude planner splits a typed or spoken request across a fleet of role-specialized agents, with human escalation, an audit log, per-run cost tracking, and a 3D control room.
- **WebGL 3D Engine** — a rendering engine written from scratch in JavaScript (OBJ/glTF pipeline).

### 💼 Experience

| | |
|---|---|
| **Founder & Software Lead** | Argus Defense Systems · 2025–present |
| **President of Technology and Product** | Verix Credential (biometric payments) |
| **Software Developer Intern** | IBM (DataStax) · Jun–Aug 2026 |
| **B.S. Computer Science** | UC Santa Cruz · expected December 2027 |

### 🧰 Stack

`Python` · `C / C++` · `Rust` · `Go` · `TypeScript` · `ROS2` · `PX4 / MAVLink` · `Jetson / Edge AI`
`Computer Vision (DINOv2 · SuperPoint · YOLO)` · `VIO / SLAM` · `On-device LLMs` · `FAISS`
`TensorRT` · `Distributed Systems` · `LLM evaluation`
`SQL` · `PostgreSQL` · `FastAPI` · `Payments / idempotency` · `Docker`

---

<sub>Most flagship source is private (defense / early-stage) — happy to walk through it, just reach out.</sub>

<p align="center"><a href="https://hrittik.com"><b>hrittik.com</b></a></p>
