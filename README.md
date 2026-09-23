# Irtiqa Haider

**AI Systems Engineer & MLSys Researcher** — GPU kernels · heterogeneous CPU–GPU execution · LLM training & serving efficiency

I build and benchmark the systems layer under large language models: memory-efficient training kernels, CPU–GPU execution placement, and quantized inference serving. Background in production multi-tenant LLM infrastructure; currently applying to PhD programs in Machine Learning Systems (MLSys).

✉️ [irtiqahaidermalik@gmail.com](mailto:irtiqahaidermalik@gmail.com) · 🔗 [LinkedIn](https://www.linkedin.com/in/irtiqahaider)

---

### 📄 Preprint

**Preference Optimization for Open-Weight Language Models: A Survey and Low-Resource RLHF Case Study**
Irtiqa Haider, Muhammad Shahnawaz · *Preprints.org*, v2, Sept 2026
[doi:10.20944/preprints202506.2381.v2](https://doi.org/10.20944/preprints202506.2381.v2)

---

### 🔬 Selected Research & Systems Projects

Independent technical reports with linked code, measurements, and reproduction instructions.

**[BudgetCE — Memory-Efficient Transformer Training](https://github.com/IrtiqaHaider/REPLACE_ME_REPO)**
Custom CUDA row-reduction and gradient-transformation kernels inside a recomputing autograd path. **14.8%** higher training throughput and **32.3%** lower peak memory than native PyTorch, validated across 900 measured optimizer updates.

**[CPU–GPU Transformer Inference: Budgeted Placement](https://github.com/IrtiqaHaider/REPLACE_ME_REPO)**
A GPT-2 runtime with explicit CPU/GPU block placement, activation transfer, and layer-local KV caches. Transfer-aware latency model holds to **11.09%** median error across held-out workload shapes; 1,060 measured generations.

**[Weight Quantization under Concurrent LLM Serving](https://github.com/IrtiqaHaider/t4-quantization-serving)**
Controlled benchmark of Qwen2.5 1.5B/3B (F16 / Q8_0 / Q4_K_M) under concurrency 1 and 8. **1.89–2.00×** throughput and **50–57%** lower memory for Q4 at low concurrency — advantage narrows under load. 1,152 validated requests.

---

### 🛠️ Core Stack

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Systems & parallelism:** MPI, OpenMP, OpenCL, operating systems, parallel & distributed computing
**Inference & training:** llama.cpp, GGUF quantization, KV-cache management, TRL, RLHF/PPO, mixed precision

---

Open to research collaborations and discussing MLSys, LLM inference efficiency, and heterogeneous computing.
