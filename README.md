<h1 align="center">Chengxiang Qi (齐呈祥)</h1>

<p align="center">
  <a href="https://kuangjux.top">🏠 Homepage</a> •
  <a href="https://www.zhihu.com/people/qi-cheng-xiang-59">📝 Zhihu</a> •
  <a href="https://github.com/KuangjuX">💻 GitHub</a>
</p>

<p align="center">
  <em>M.Eng. Student in Computer Technology @ University of Chinese Academy of Sciences (UCAS)</em><br/>
  <em>B.Eng. in Computer Science @ Tianjin University (Outstanding Thesis Award)</em>
</p>

---

### About Me

I am a final-year master's student at the University of Chinese Academy of Sciences, focusing on **ML Systems**, **Deep Learning Compilers**, and **GPU Programming**. Previously, I worked extensively with the **Rust** programming language on systems-level projects including operating systems and hypervisors.

### Research Interests

`Machine Learning Systems` · `Deep Learning Compilers` · `GPU Kernel Optimization` · `CUDA Programming` · `Operating Systems` · `Virtualization`

---

### Experience

**WeChat — LLM Infra Team** · ML System Intern · *June 2025 – Present*
- Implemented **Light-DuoAttention** using CuTeDSL for efficient long-context inference, integrated and running within [SGLang](https://github.com/sgl-project/sglang).
- Explored NVSHMEM & DeepEP; built [**NVSHMEM-Tutorial**](https://github.com/KuangjuX/NVSHMEM-Tutorial) with hybrid CUDA IPC / RDMA communication for internal technical sharing.
- Implemented **Ring Attention Forward** based on ThunderKittens using the LCF template, outperforming ring-flash-attention on short sequences. Implemented Flash Attention Backward based on LCF.
- Performed performance analysis on MagiAttention, ZigZag Ring Attention, and ZigZag Flex Attention.
- Investigated DSL design on NVIDIA Hopper architecture.

**Microsoft Research Asia — System & Network Group** · Research Intern · *Feb 2024 – May 2025*
- Based on the FractalTensor programming model, optimized GEMM, Back-to-Back GEMMs, Stacked/Dilated LSTM, and FlashAttention-2 using CUTLASS. Achieved up to **5.45× speedup** over SOTA on NVIDIA A100, with **2.14× average acceleration**.
- As a core designer and developer, built [**TileFusion**](https://github.com/microsoft/TileFusion): an efficient C++ macro kernel template library that elevates the abstraction level in CUDA C for tile processing.
- Mentored by [Dr. Ying Cao](https://github.com/lcy-seso). Co-first authored a paper published at **SOSP'24**.

**Tsinghua University — OS Laboratory** · Research Intern · *May 2023 – July 2023*
- Wrote an Intel 82599 NIC driver in Rust (referencing DPDK for optimization) and integrated it into [**ArceOS**](https://github.com/arceos-org/arceos). Performed network performance benchmarking and optimization.
- Developed a Type-2 hypervisor based on ArceOS capable of booting Linux; built [**Hypercraft**](https://github.com/KuangjuX/hypercraft) as a standalone VMM library.

---

### Selected Projects

| Project | Description | Stars |
|---------|-------------|-------|
| [**microsoft/TileFusion**](https://github.com/microsoft/TileFusion) | C++ macro kernel template library for tile processing across GPU memory hierarchy with TensorCore support | ![Stars](https://img.shields.io/github/stars/microsoft/TileFusion?style=flat) |
| [**microsoft/FractalTensor**](https://github.com/microsoft/FractalTensor) | Programming framework for organizing DNN data as nested statically-shaped tensors with automatic compiler analysis | ![Stars](https://img.shields.io/github/stars/microsoft/FractalTensor?style=flat) |
| [**NVSHMEM-Tutorial**](https://github.com/KuangjuX/NVSHMEM-Tutorial) | Build a DeepEP-like GPU communication buffer with NVSHMEM (hybrid CUDA IPC / RDMA) | ![Stars](https://img.shields.io/github/stars/KuangjuX/NVSHMEM-Tutorial?style=flat) |
| [**xv6-rust**](https://github.com/Ko-oK-OS/xv6-rust) | Reimplementation of MIT xv6-riscv in Rust; reference implementation for OSCOMP | ![Stars](https://img.shields.io/github/stars/Ko-oK-OS/xv6-rust?style=flat) |
| [**arceos**](https://github.com/arceos-org/arceos) | Experimental modular OS in Rust — contributed hypervisor, ixgbe NIC driver, and network optimization | ![Stars](https://img.shields.io/github/stars/arceos-org/arceos?style=flat) |
| [**Hypercraft**](https://github.com/KuangjuX/hypercraft) | VMM library in Rust for RISC-V / AArch64 virtualization, capable of booting Linux | ![Stars](https://img.shields.io/github/stars/KuangjuX/hypercraft?style=flat) |
| [**hypocaust-2**](https://github.com/KuangjuX/hypocaust-2) | Hardware-assisted RISC-V hypervisor using H Extension; boots rCore, RT-Thread, and Linux | ![Stars](https://img.shields.io/github/stars/KuangjuX/hypocaust-2?style=flat) |

---

### Publications

- **Uncovering Nested Data Parallelism and Data Reuse in DNN Computation with FractalTensor**
  Siran Liu\*, **Chengxiang Qi**\*, Ying Cao, Chao Yang, Weifang Hu, Xuanhua Shi, Fan Yang, Mao Yang
  *ACM SIGOPS 30th Symposium on Operating Systems Principles (**SOSP'24**)* · (\*equal contribution)
  [[Paper]](https://dl.acm.org/doi/10.1145/3694715.3695961) [[Code]](https://github.com/microsoft/TileFusion)

- **基于 RISC-V 的 Type-1 Hypervisor 的设计与实现**
  **Chengxiang Qi**
  *Bachelor Thesis, Tianjin University* · (Outstanding Thesis Award)
  [[Code]](https://github.com/KuangjuX/hypocaust)

---

### Talks

- **Hypocaust: a RISC-V Type-1 Hypervisor Written in Rust** — *OS2ATC 2022, Beijing (March 2023)*
  Presentation on the design and implementation of a RISC-V Type-1 hypervisor, showcasing virtualization techniques and system-level Rust programming.

---

### Tech Stack

<p>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/RISC--V-283272?style=flat-square&logo=riscv&logoColor=white"/>
</p>

<!-- --- -->

<!-- <p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=KuangjuX&show_icons=true&theme=default&hide_border=true&count_private=true" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KuangjuX&layout=compact&theme=default&hide_border=true" height="165"/>
</p> -->
