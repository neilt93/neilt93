# Neil Tripathi

CS graduate from NYU. I work at the intersection of ML research and systems engineering, with a focus on runtime safety for robot learning, temporal reasoning in language models, and biologically-inspired locomotion from connectome data.

**[neiltripathi.com](https://website-mauve-nine-60.vercel.app)**

## Research

- **[Fly-Brain-AI](https://github.com/neilt93/Fly-Brain-AI)** — biologically-inspired locomotion: a 13k-neuron Drosophila ventral-nerve-cord simulation (Brian2 + FlyGym/MuJoCo) with Hebbian plasticity and connectome-derived descending control, a Unity visualiser, and sim-to-real transfer to a Waveshare HexArth hexapod
- **[TAP-Score](https://github.com/neilt93/TAP-Score)** — runtime failure detection for Diffusion Policy; predicts when a visuomotor policy is about to fail so the robot can abstain from risky actions (Can AUROC 0.972, Lift obs-only 0.982)
- **[temporal-bench](https://github.com/neilt93/temporal-bench)** — do LLMs know when their context is stale? A benchmark for temporal reasoning; finding: more capable models are *more* confidently wrong when timestamps are absent
- **[Visual-Benchmark](https://github.com/neilt93/Visual-Benchmark)** — VB: tests whether VLMs can determine what is and isn't visible in a photograph and abstain when a human couldn't answer; 9 models, co-authored with Prof. Ernest Davis (arXiv)
- **[OpenKBP-Project](https://github.com/neilt93/OpenKBP-Project)** — adversarial and clinical-perturbation robustness of 3D U-Net radiotherapy dose prediction (FGSM/PGD on DVH metrics; submitted to SERA 2026)
- **[PeptAgent](https://github.com/neilt93/PeptAgent)** — LLM-orchestrated therapeutic peptide design with ESM-2/ESMFold, AutoDock Vina docking, Pareto multi-objective optimisation, and conformal reliability estimation

## AI Agents & Systems

- **[Neutral-Journalist-on-Eigen](https://github.com/neilt93/Neutral-Journalist-on-Eigen)** — cryptographically verifiable autonomous journalism: multi-source ingestion, bias scoring, and on-chain attestation with TEE proofs via EigenCloud
- **[Property-claw](https://github.com/neilt93/Property-claw)** — autonomous property management for short-term rentals as an OpenClaw skill: guest messaging, photo-QA cleaning schedules, maintenance tracking, human escalation
- **[Prediction-Market-Agent](https://github.com/neilt93/Prediction-Market-Agent)** — local-first forecasting agent with LLM forecasting, LightGBM calibration, and automated Kalshi trading
- **[Rocket-League-World-Model](https://github.com/neilt93/Rocket-League-World-Model)** — world-model RL agent using Conditional Flow Matching latent dynamics, trained via imagination rollouts and deployed to RLBot
- **[AR-glasses](https://github.com/neilt93/AR-glasses)** — smart AR assistant for RayNeo Air 4 Pro: YOLOv8 detection, MediaPipe hand tracking, MiDaS depth, voice feedback; assembly-copilot and assistant modes
- **[mcp-debug](https://github.com/neilt93/mcp-debug)** — testing/debugging toolkit for Model Context Protocol servers: trace recording, cross-run diffing, fuzzing, and failure injection
- **[NeilGPT](https://github.com/neilt93/NeilGPT)** — 24M-parameter decoder-only transformer trained from scratch on personal chat data, with custom BPE tokenisation and a full extraction→PII→train pipeline
- **[Minecraft-bot](https://github.com/neilt93/Minecraft-bot)** — autonomous Minecraft agent on a local LLM via observe–think–act–reflect, with persistent memory, checkpointing, and a real-time dashboard

## Apps & Products

- **[Macro-tracker-agent](https://github.com/neilt93/Macro-tracker-agent)** — MacroLens: Next.js + Supabase calorie and macro tracker, deployed on Vercel
- **[Sympli-Prototype](https://github.com/neilt93/Sympli-Prototype)** — AI healthcare companion that documents symptoms with the SOCRATES clinical framework and generates GP-ready summaries
- **[Crypto-signal-dashboard](https://github.com/neilt93/Crypto-signal-dashboard)** — real-time crypto portfolio monitor detecting whale moves and volume anomalies from Nansen on-chain data (Next.js + Postgres)
- **[Digital-persona](https://github.com/neilt93/Digital-persona)** — local-first AI mirror of yourself grounded in your own memories/documents, with citations, semantic search, and an approval queue
- **[lecture-transcriber](https://github.com/neilt93/lecture-transcriber)** — GPU-accelerated lecture transcription (Whisper) with timestamps, SRT export, and batch error recovery
- **[HVAC-project](https://github.com/neilt93/HVAC-project)** — HVAC component detector (YOLOv12m) with a Python training pipeline and a companion iOS app
