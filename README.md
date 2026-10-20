<div align="center">

# Sidharthan S

**Building open-source medical AI.**

Clinical NLP for Indic languages · multimodal diagnostics · reinforcement learning for real-world systems

<sub>Tamilnadu, India · AI Engineer</sub>

<p>
  <a href="https://github.com/Sidharth1743"><img src="https://img.shields.io/badge/GitHub-Sidharth1743-181717?style=flat-square&logo=github" alt="GitHub"></a>
  <a href="https://www.linkedin.com/in/sidharthan1743/"><img src="https://img.shields.io/badge/LinkedIn-Sidharthan_S-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://x.com/sid250581"><img src="https://img.shields.io/badge/X-@sid250581-000000?style=flat-square&logo=x&logoColor=white" alt="X"></a>
  <a href="https://huggingface.co/Sidharth1743"><img src="https://img.shields.io/badge/Hugging_Face-Sidharth1743-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"></a>
  <a href="mailto:sid250581@gmail.com"><img src="https://img.shields.io/badge/Email-sid250581@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

</div>

---

## About

I am an AI engineer working on **open-source medical AI**: clinical NLP and
de-identification for Indian languages, multimodal diagnostics, and models that
can run close to the data. Recent work includes **IndicPHI** (a 23-language
synthetic clinical corpus), **Tamil medical reasoning data and evaluation
harnesses**, and **BigTB6**, a voice-driven TB and anemia screening system that
won the **Agentic Workflow Prize** at the 2026 MedGemma Impact Challenge.

I also work on **reinforcement learning for physical systems** — building control,
power grids, air-traffic management, and weather forecasting — and contribute
fixes upstream when the tools I depend on break.

## Research interests

- Clinical NLP, PHI/PII de-identification, and synthetic data for low-resource and Indic languages
- Multimodal screening with small models that can run locally
- Reinforcement learning for building control, power grids, and air-traffic management
- Reproducible evaluation and open artifacts for medical AI

## Selected projects

### Medical AI & clinical NLP

- **[IndicPHI](https://github.com/Sidharth1743/IndicPHI)** — reproducible synthetic clinical-document pipeline for 22 Indic languages plus English. It generates PHI/PII-annotated records, audits them with an LLM judge and deterministic validators, curates with NeMo Curator, and exports GLiNER-ready train/eval splits. `Python` · `NeMo` · `GLiNER`

- **[tamil-med-sft](https://github.com/Sidharth1743/tamil-med-sft)** — pipeline that designs, generates, judges, and decontaminates native-Tamil medical reasoning SFT data. Sarvam-105B generates items, Grok-4.3 audits them across six dimensions, and salvageable revisions are re-judged and promoted. `Python` · `SFT` · `data curation`

- **[TamilMedicalMILU](https://github.com/Sidharth1743/TamilMedicalMILU)** and **[TamilMedicalMMLU-Pro](https://github.com/Sidharth1743/TamilMedicalMMLU-PRO)** — standalone, `uv`-managed `lm-eval` runners for Tamil health and medicine benchmarks, scored against any OpenAI-compatible vLLM endpoint. `lm-eval` · `vLLM`

- **[BigTB6](https://github.com/Sidharth1743/BigTb6)** — voice-first screening for TB and anemia: cough audio, chest X-ray, palm/eye/nail pallor, and webcam rPPG respiratory rate, orchestrated with Gemini Live and MedGemma. **Agentic Workflow Prize, MedGemma Impact Challenge 2026.** `Gemini Live` · `MedGemma` · `multimodal`

- **Anemia screening models** — MedSigLIP linear probes and QLoRA fine-tunes for [palm](https://github.com/Sidharth1743/palm-medsiglip), [eye](https://github.com/Sidharth1743/medgemma-tb), and [fingernail](https://github.com/Sidharth1743/fingernail_anemia_detection) anemia detection, with weights released on Hugging Face. `MedSigLIP` · `QLoRA`

### RL, simulation & control

- **[google/sbsim](https://github.com/google/sbsim)** — upstream issue reports and fix PRs for Google's Smart Buildings control simulator: SAC actor crash, baseline schedule-policy action order, and local comfort-window handling. `RL` · `building control`

- **[grid2op-openenv](https://github.com/Sidharth1743/grid2op-openenv)** — OpenEnv-compatible IEEE 14-bus grid environment with four topology-control tasks and a Think → Simulate → Act LLM baseline; the server owns simulation state. `OpenEnv` · `Grid2Op`

- **[Complete_RL_Journey](https://github.com/Sidharth1743/Complete_RL_Journey)** — Connect Four AlphaZero from scratch: game environment, MCTS, ResNet policy/value network, parallel self-play, and a released checkpoint. `AlphaZero` · `PyTorch`

## Open source contributions

| Repository | Contribution | Status |
|---|---|---|
| [`maziyarpanahi/openmed`](https://github.com/maziyarpanahi/openmed) | FHIR `deidentify()` operation wrapper | Merged |
| [`maziyarpanahi/openmed`](https://github.com/maziyarpanahi/openmed) | FHIR `OperationOutcome` builder for exporters and validation | Merged |
| [`NVIDIA-MedTech/NV-Generate-CTMR`](https://github.com/NVIDIA-MedTech/NV-Generate-CTMR) | Fix `AttributeError` when `cfg_guidance_scale` is missing | Merged |
| [`openclimatefix/graph_weather`](https://github.com/openclimatefix/graph_weather) | Hierarchical gradient checkpointing | Merged |
| [`openclimatefix/graph_weather`](https://github.com/openclimatefix/graph_weather) | Efficient sequential batching | Merged |
| [`openclimatefix/graph_weather`](https://github.com/openclimatefix/graph_weather) | Open-Meteo gridded weather data fetcher | Open |
| [`google/sbsim`](https://github.com/google/sbsim) | SAC crash, schedule-policy order, and comfort-window issues + fixes | 2 PRs open |
| [`haailabs/HeritageNet-example`](https://github.com/haailabs/HeritageNet-example) | Knowledge-graph pipeline integration | Open |

## Awards & education

- **MedGemma Impact Challenge — Agentic Workflow Prize (2nd)** · Google Research × Kaggle · 2026  
  For **BigTB6**, a voice-driven TB and anemia screening demo.

- **Bio x AI Hackathon — Winner** · bio.xyz · 2025
