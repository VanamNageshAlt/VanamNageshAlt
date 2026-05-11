<h1 align="center">Hi, I'm Nagesh 👋</h1>

<p align="center">
  <em>Building AI/ML systems — and the SWE patterns that make them survive contact with production.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-ML_Systems-1f6feb?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Areas-LLMs_/_Vision_/_RL-3776ab?style=flat-square&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Stack-PyTorch_first-ee4c2c?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Mode-Build_in_private-f59e0b?style=flat-square" />
</p>

---

## 📊 GitHub at a glance

<p align="center">
  <a href="https://github.com/VanamNageshAlt">
    <img alt="GitHub streak"
         src="https://github-readme-streak-stats.herokuapp.com/?user=VanamNageshAlt&theme=tokyonight&hide_border=true&card_width=420"
         height="180" />
  </a>
  <a href="https://github.com/VanamNageshAlt">
    <img alt="Most used languages"
         src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=VanamNageshAlt&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&hide=shell&size_weight=0.5&count_weight=0.5"
         height="180" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/VanamNageshAlt">
    <img alt="Contribution activity graph"
         src="https://github-readme-activity-graph.vercel.app/graph?username=VanamNageshAlt&theme=tokyo-night&hide_border=true&area=true&radius=8" />
  </a>
</p>

---

## 🧠 What I'm Working On

Three modeling areas and one connective concern:

- **LLM fine-tuning** — LoRA / QLoRA on instruction-tuning data, with a small RAG retriever for grounded generation. The interesting work isn't the training loop; it's the eval (perplexity + exact-match + token-F1 + ROUGE-L), the data quality audit, and the calibration check.
- **Computer vision** — image classification with ResNet/ViT backbones, MixUp + label smoothing, GradCAM as a sanity check that the model is looking where I expect.
- **Reinforcement learning** — DQN and PPO on Gymnasium environments. Implemented from scratch (CleanRL-style, single file each) because the implementation details matter more than the algorithm names.
- **The SWE under all of it** — training infrastructure (logger, checkpointing, AMP, EMA, seeding) and eval pipelines that work the same way across LLM, vision, and RL. If a helper only works on one domain, it doesn't belong in the shared modules.

---

## 📦 Projects

### 🧪 ml-systems-lab *(private)*

The main lab. Five sub-projects under one repo, sharing utility modules so the patterns stay honest across domains.

- **llm-finetune** — LoRA + RAG + perplexity / EM / token-F1 eval
- **vision-classifier** — ResNet/ViT classification with MixUp, label smoothing, GradCAM
- **rl-agents** — DQN + PPO on Gymnasium, single-file implementations
- **training-utils** — Logger (TB / W&B), checkpoint, AMP (bf16 default), EMA, seeding
- **eval-pipelines** — Classification + generation metrics, ECE calibration, paired bootstrap CIs

### 📒 [ml-playbook](https://github.com/VanamNageshAlt/ml-playbook)

Quick-reference cheatsheets for ML topics — LR schedules, mixed precision (bf16 vs fp16), LoRA tuning, RL implementation tips, eval honesty, GPU debugging. Each file is one topic, kept short.

### 🔧 [nn-snippets](https://github.com/VanamNageshAlt/nn-snippets)

Small reusable PyTorch utilities I keep copy-pasting: seeding, device picking, parameter counting, warmup-cosine LR schedulers, sane DataLoader defaults, patience-based early stopping, layer freezing, plus a CUDA ReLU kernel and a minimal C++ tensor-extension example. Some notebooks for LR-finding, gradient-norm sanity checks, and attention visualization.

### 🗂 [data-pipeline-tools](https://github.com/VanamNageshAlt/data-pipeline-tools)

CLI helpers for the boring parts of working with ML datasets: download with retry + checksum, stratified train/val/test split for ImageFolder, sanity-check (label distribution, image corruption), HF dataset → instruction-format JSONL, token counting with a HF tokenizer.

---

## 🛠 Tech Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776ab?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-ee4c2c?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging_Face-ffd21e?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/Jupyter-f37626?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/CUDA-76b900?style=for-the-badge&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599c?style=for-the-badge&logo=cplusplus&logoColor=white" />
</p>
<p>
  <img src="https://img.shields.io/badge/TypeScript-3178c6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/SciPy-8caaee?style=for-the-badge&logo=scipy&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-f7931e?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/W%26B-ffbe00?style=for-the-badge&logo=weightsandbiases&logoColor=black" />
</p>
<p>
  <img src="https://img.shields.io/badge/Docker-2496ed?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-f05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088ff?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/VS_Code-007acc?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-fcc624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

**Frameworks I lean on**: `transformers`, `peft`, `accelerate`, `bitsandbytes`, `gymnasium`, `stable-baselines3`, `cleanrl`, `timm`, `albumentations`, `pytorch-lightning`.

---

## 🔬 Things I Care About

- **Eval honesty** — multiple seeds, bootstrap CIs, hold-out test sets touched once. If your eval can't tell signal from noise, it's not a real eval.
- **Calibration matters** — top-1 accuracy doesn't tell you if the model knows what it knows. ECE + reliability bins do.
- **Implementation details > algorithm names** — orthogonal init, advantage normalization, gradient clipping. Skip these and PPO doesn't work.
- **ML is a software problem** — most "model issues" are dataloader bugs, mixed-precision bugs, or off-by-one bugs in label masking. Treat training code like production code and most problems disappear.
- **Build, don't just read** — the difference between knowing about LoRA and being able to ship a fine-tune is roughly one weekend of debugging shape mismatches.

---

## 🔗 Connect

<p>
  <a href="mailto:vanam.nagesh@gmail.com">
    <img src="https://img.shields.io/badge/Email-d14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/VanamNageshAlt">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

<sub>Personal lab account. Most active development happens in private repos.</sub>
