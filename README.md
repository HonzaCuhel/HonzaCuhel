## Jan Čuhel

I build AI systems that reach production, and I study how they fail before they get there.

Currently: AI Engineer at **[Finviz](https://finviz.com)** · Research collaborator at **[MATS](https://www.matsprogram.org/)** (LLM agent evaluation, Samuel Albanie's stream) · Prague, CZ

### What I work on

**Multi-agent failure modes.** Frontier LLM agents put in game-theoretic settings do things you cannot predict from single-agent evals: collusion, task-splitting to evade monitors, strategy shifts under stakes. I build sandboxed testbeds that measure this before deployment, not after.

**AI products from zero to production.** First employee at a pre-seed startup, where I owned the AI stack, the backend, the GCP pipelines, and the CI/CD through the funding round. I know what breaks between a demo and a system people depend on.

### Selected work

**[Towards Predictive Models of Strategic Behaviour in LLM Agents](https://openreview.net/forum?id=PpRrEWt9yK)**
200,000+ decisions by frontier models across game-theoretic scenarios. Cooperation rates for an unseen model become predictable (R² = 0.51) from 5 to 10 calibration scenarios, so roughly 10% of the data captures 88% of the maximum predictive gain.
*Spotlight, ICML 2026 AI4GOOD · Outstanding Paper, Cooperative AI Foundation*

**[Alquist 5.0](https://doi.org/10.3390/fi16090344)**
Dialogue trees meet generative models. The socialbot that took 3rd place globally in Amazon's Alexa Prize SocialBot Grand Challenge 5. I co-captained the team.

**[Vocaret](https://github.com/HonzaCuhel/vocaret)**
Local-first speech-to-text for macOS. Czech and English, mixed freely, on-device by default. Swift and Apple Silicon.

### Open source

**[Luxonis](https://github.com/luxonis) edge AI toolchain** (2022 to 2025). 130+ merged pull requests across 10 repositories, covering model conversion, dataset generation, and the tutorials people follow to get a model onto an OAK camera.

* **[datadreamer](https://github.com/luxonis/datadreamer)** ⭐ 139 · co-author. Fully annotated computer-vision datasets generated from a text prompt. I added instance segmentation, the SAM 2.1 and AIMv2 annotators, and the Qwen2.5 prompt generator.
* **[tools](https://github.com/luxonis/tools)** · YOLO export pipeline. I owned the export path for YOLOv5 through YOLO11, plus Gold YOLO, including the anchor and output-name handling that makes converted models actually run on device.
* **[ai-tutorials](https://github.com/luxonis/ai-tutorials)** ⭐ 132 · training and deployment tutorials for detection, instance segmentation, and pose estimation.
* Also [modelconverter](https://github.com/luxonis/modelconverter), [depthai-nodes](https://github.com/luxonis/depthai-nodes), [luxonis-train](https://github.com/luxonis/luxonis-train), [luxonis-ml](https://github.com/luxonis/luxonis-ml), [blobconverter](https://github.com/luxonis/blobconverter), [oak-examples](https://github.com/luxonis/oak-examples), [depthai-model-zoo](https://github.com/luxonis/depthai-model-zoo).

**[edgartools](https://github.com/dgunning/edgartools)** ⭐ 2.6k · Python library for reading and analyzing SEC EDGAR filings. I contributed a `Section.markdown()` accessor, a form-aware table-of-contents analyzer that stops 10-Q parsing from inventing phantom items, and 10-K section patterns for Item 1B and Item 1C.

### For fun

**[ASCII Avatar](https://pixel-ascii-magic.lovable.app/)** · drop in a photo, get an ASCII portrait back.

### Publications

[Google Scholar](https://scholar.google.com/citations?user=VwJT9GkAAAAJ&hl=en): multi-agent safety, multimodal QA, conversational AI, automated planning.

### Background

MSc Open Informatics, **CTU Prague**, summa cum laude, GPA 3.92/4.00 · Exchange at **TU Munich** (Deep Learning & NLP) and **DTU** · Alexa Prize finalist · Prev. Luxonis (edge CV), AIM (first employee).

**[cuheljan.com](https://cuheljan.com)** · **[LinkedIn](https://linkedin.com/in/jan-c-55748a106)** · jan.cuhel@protonmail.com

*Open to conversations about AI safety, agent evaluation, and hard production AI problems.*
