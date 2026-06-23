# Neil Tripathi

Co-founder and research engineer building **evaluation infrastructure, simulation benchmarks, and sim-to-real systems for embodied AI**. Co-founder at **Cybernetic Labs**, where I work on evaluation for vision-language-action (VLA) models, mechanistic interpretability, and sim-to-real robot deployment.

**[neiltripathi.com](https://website-mauve-nine-60.vercel.app)**

## Embodied AI, Evaluation & Interpretability

- **[Fly-Brain-AI](https://github.com/neilt93/Fly-Brain-AI)** — biologically-inspired locomotion and sim-to-real: a 13k-neuron Drosophila ventral-nerve-cord simulation (Brian2 + FlyGym/MuJoCo) with Hebbian plasticity and connectome-derived descending control, a Unity visualiser, and transfer to a Waveshare HexArth hexapod
- **[Visual-Benchmark](https://github.com/neilt93/Visual-Benchmark)** — VB: tests whether VLMs can determine what is and isn't visible in a photograph and abstain when a human couldn't answer; 9 models, co-authored with Prof. Ernest Davis (arXiv)
- **[mech-interp](https://github.com/neilt93/mech-interp)** — mechanistic interpretability of from-scratch transformers: induction-head vs. previous-token circuit analysis and BPE-tokenisation experiments, with a written research report
- **[OpenKBP-Project](https://github.com/neilt93/OpenKBP-Project)** — adversarial and clinical-perturbation robustness of 3D U-Net radiotherapy dose prediction (FGSM/PGD on DVH metrics); submitted to SERA 2026 (IEEE/ACIS), ASTRO 2026 submission under review, co-authored with Prof. Birjoo Vaishnav (U. Maryland) and Prof. Weixian Liao (Towson)
- **[PeptAgent](https://github.com/neilt93/PeptAgent)** — LLM-orchestrated therapeutic peptide design with ESM-2/ESMFold, AutoDock Vina docking, Pareto multi-objective optimisation, and conformal reliability estimation

## AI Agents & Systems

- **[Rocket-League-World-Model](https://github.com/neilt93/Rocket-League-World-Model)** — world-model RL agent using Conditional Flow Matching latent dynamics, trained via imagination rollouts and deployed to RLBot
- **[AR-glasses](https://github.com/neilt93/AR-glasses)** — smart AR assistant for RayNeo Air 4 Pro: YOLOv8 detection, MediaPipe hand tracking, MiDaS depth, voice feedback; assembly-copilot and assistant modes
- **[Neutral-Journalist-on-Eigen](https://github.com/neilt93/Neutral-Journalist-on-Eigen)** — cryptographically verifiable autonomous journalism: multi-source ingestion, bias scoring, and on-chain attestation with TEE proofs via EigenCloud
- **[Prediction-Market-Agent](https://github.com/neilt93/Prediction-Market-Agent)** — local-first forecasting agent with LLM forecasting, LightGBM calibration, and automated Kalshi trading
- **[mcp-debug](https://github.com/neilt93/mcp-debug)** — testing/debugging toolkit for Model Context Protocol servers: trace recording, cross-run diffing, fuzzing, and failure injection
- **[NeilGPT](https://github.com/neilt93/NeilGPT)** — 24M-parameter decoder-only transformer trained from scratch on personal chat data, with custom BPE tokenisation and a full extraction→PII→train pipeline
- **[Minecraft-bot](https://github.com/neilt93/Minecraft-bot)** — autonomous Minecraft agent on a local LLM via observe–think–act–reflect, with persistent memory, checkpointing, and a real-time dashboard

## Apps & Products

- **[MarketClaw](https://github.com/neilt93/MarketClaw)** — Turborepo monorepo for the Claw product ecosystem (TypeScript + Supabase)
- **[Property-claw](https://github.com/neilt93/Property-claw)** — autonomous property management for short-term rentals as an OpenClaw skill: guest messaging, photo-QA cleaning schedules, maintenance tracking, human escalation
- **[Macro-tracker-agent](https://github.com/neilt93/Macro-tracker-agent)** — MacroLens: Next.js + Supabase calorie and macro tracker, deployed on Vercel
- **[Sympli-Prototype](https://github.com/neilt93/Sympli-Prototype)** — AI healthcare companion that documents symptoms with the SOCRATES clinical framework and generates GP-ready summaries
- **[Digital-persona](https://github.com/neilt93/Digital-persona)** — local-first AI mirror of yourself grounded in your own memories/documents, with citations, semantic search, and an approval queue
- **[lecture-transcriber](https://github.com/neilt93/lecture-transcriber)** — GPU-accelerated lecture transcription (Whisper) with timestamps, SRT export, and batch error recovery
