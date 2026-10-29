---
permalink: /
title: "Jiarui Wang"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I’m a Ph.D. student in Computer Science at the [School of Computer Science, Shanghai Jiao Tong University (SJTU)](https://cs.sjtu.edu.cn/), advised by Prof. [Zhouhan Lin](https://hantek.github.io/) in [Language Understanding and Machine Intelligence Algorithms (LUMIA) Group](https://lumia-group.github.io/). I received my B.S. in Computer Science from SJTU.

My research focuses on machine learning and large language models (LLMs), with particular interests in:

- **Next-Generation LLM Architectures** — exploring new architectural paradigms that decouple knowledge storage from reasoning to improve knowledge acquisition, reasoning, and generalization.

- **Parametric Memory** — developing parametric memory modules for LLMs that efficiently acquire, retain, and update knowledge.

I'm always open to discussing research, collaboration, and new ideas. Please feel free to reach out!

## 🔥 <a id="news"></a>News
- **2026.07** 🚀 [*Intern-S2-Preview-397B*](https://huggingface.co/internlm/Intern-S2-Preview-397B) released — led the research and development of its memory architecture.
- **2026.07** 🚀 [*MemSFT*](https://arxiv.org/abs/2607.25614) released — paper, model weights, and code are now open-sourced.
- **2026.07** 🚀 [*Memory Decoder at Scale*](https://arxiv.org/abs/2607.27919) released.
- **2026.01** 🎉 [*MLP Memory*](https://arxiv.org/abs/2508.01832) accepted to **ICLR 2026**
- **2025.10** 🚀 [*MLP Memory*](https://arxiv.org/abs/2508.01832) released.
- **2025.09** 🚀 [*Memory Decoder*](https://arxiv.org/abs/2508.09874) released.
- **2025.09** 🎉 [*Memory Decoder*](https://arxiv.org/abs/2508.09874) accepted to **NeurIPS 2025**
- **2024.05** 🏆 Our Robocup team SRC won Second Place in **RoboCup China Open**

## 📚 <a id="publications"></a>Publications

<ul class="publication-list">
  <li class="publication-item">
    <a class="publication-figure" href="https://arxiv.org/abs/2607.25614">
      <img src="{{ '/images/publications/memsft.svg' | relative_url }}" alt="MemSFT architecture: memory training, router training, and inference" loading="lazy" decoding="async" width="180" height="120">
    </a>
    <div class="publication-details">
      <p><strong>MemSFT: Mitigating Alignment Tax with an External Parametric Memory</strong><br>
      <em><strong>Jiarui Wang</strong>*, Xiang Shi*, Jiaqi Cao, Rubin Wei, Xiquan Wang, Hao Sun, Jingzhi Wang, Zhiqi Yang, Qipeng Guo, Bowen Zhou, Zhouhan Lin</em><br>
      <em>arXiv preprint (2026)</em><br>
      🔗 <a href="https://arxiv.org/abs/2607.25614">arXiv</a> · <a href="https://github.com/LUMIA-Group/MemSFT">GitHub</a> · <a href="https://huggingface.co/Jiarui-Wang/MemSFT-Qwen3-OpenSWI-Memory-8B">Hugging Face</a> · * Equal Contribution</p>
    </div>
  </li>
  <li class="publication-item">
    <a class="publication-figure" href="https://arxiv.org/abs/2608.13505">
      <img src="{{ '/images/publications/intern-s2-preview.svg' | relative_url }}" alt="Intern-S2-Preview memory architecture" loading="lazy" decoding="async" width="180" height="120">
    </a>
    <div class="publication-details">
      <p><strong>Intern-S2-Preview: Scientific Agentic Foundation Model</strong><br>
      <em>Intern-S2-Preview Team, Shanghai AI Laboratory</em><br>
      <em>Co-author; arXiv preprint (2026)</em><br>
      🔗 <a href="https://arxiv.org/abs/2608.13505">arXiv</a> · <a href="https://github.com/InternLM/Intern-S1">GitHub</a> · <a href="https://huggingface.co/collections/internlm/intern-s2">Hugging Face</a></p>
    </div>
  </li>
  <li class="publication-item">
    <a class="publication-figure" href="https://arxiv.org/abs/2607.27919">
      <img src="{{ '/images/publications/memory-decoder-at-scale.svg' | relative_url }}" alt="Memory Decoder at Scale results" loading="lazy" decoding="async" width="180" height="120">
    </a>
    <div class="publication-details">
      <p><strong>Memory Decoder at Scale: A Pretrained, Parametric Long-Term Memory</strong><br>
      <em>Rubin Wei, Jiaqi Cao, <strong>Jiarui Wang</strong>, Junming Zhang, Qipeng Guo, Bowen Zhou, Zhouhan Lin</em><br>
      <em>arXiv preprint (2026)</em><br>
      🔗 <a href="https://arxiv.org/abs/2607.27919">arXiv</a> · <a href="https://github.com/LUMIA-Group/MemoryDecoder-at-Scale">GitHub</a> · <a href="https://huggingface.co/collections/Rubin-Wei/memorydecoder-at-scale">Hugging Face</a></p>
    </div>
  </li>
  <li class="publication-item">
    <a class="publication-figure" href="https://arxiv.org/abs/2610.25100">
      <img src="{{ '/images/publications/deep-fusion-memory.svg' | relative_url }}" alt="Deep Fusion Memory architecture" loading="lazy" decoding="async" width="180" height="120">
    </a>
    <div class="publication-details">
      <p><strong>Deep Fusion Memory: A Chunk-Level Parametric Memory for Large Language Models</strong><br>
      <em>Rubin Wei, Siyuan Sun, Hao Sun, Yuliang Liu, Xiang Shi, <strong>Jiarui Wang</strong>, Junming Zhang, Zhouhan Lin</em><br>
      <em>arXiv preprint (2026)</em><br>
      🔗 <a href="https://arxiv.org/abs/2610.25100">arXiv</a></p>
    </div>
  </li>
  <li class="publication-item">
    <a class="publication-figure" href="https://arxiv.org/abs/2610.24520">
      <img src="{{ '/images/publications/habit-bench.png' | relative_url }}" alt="HABIT-Bench framework" loading="lazy" decoding="async" width="180" height="120">
    </a>
    <div class="publication-details">
      <p><strong>HABIT-Bench: Evaluating Habit Induction from Longitudinal Weak Evidence in Agent Memory</strong><br>
      <em>Junming Zhang, Rubin Wei, Xu Cheng, Hao Sun, <strong>Jiarui Wang</strong>, Ruoxi Cheng, Xiquan Wang, Peisong Wu, Mingsong Chen, Zhouhan Lin</em><br>
      <em>arXiv preprint (2026)</em><br>
      🔗 <a href="https://arxiv.org/abs/2610.24520">arXiv</a></p>
    </div>
  </li>
  <li class="publication-item">
    <a class="publication-figure" href="https://arxiv.org/abs/2508.01832">
      <img src="{{ '/images/publications/mlp-memory.svg' | relative_url }}" alt="MLP Memory training and inference architecture" loading="lazy" decoding="async" width="180" height="120">
    </a>
    <div class="publication-details">
      <p><strong>MLP Memory: A Retriever-Pretrained Memory for Large Language Models</strong><br>
      <em>Rubin Wei*, Jiaqi Cao*, <strong>Jiarui Wang</strong>, Jushi Kai, Qipeng Guo, Bowen Zhou, Zhouhan Lin</em><br>
      <em>ICLR 2026</em><br>
      🔗 <a href="https://arxiv.org/abs/2508.01832">arXiv</a> · <a href="https://github.com/LUMIA-Group/MLPMemory">GitHub</a> · <a href="https://huggingface.co/collections/Rubin-Wei/mlpmemory">Hugging Face</a> · * Equal Contribution</p>
    </div>
  </li>
  <li class="publication-item">
    <a class="publication-figure" href="https://arxiv.org/abs/2508.09874">
      <img src="{{ '/images/publications/memory-decoder.png' | relative_url }}" alt="Memory Decoder compared with domain-adaptive pretraining and retrieval augmentation" loading="lazy" decoding="async" width="180" height="120">
    </a>
    <div class="publication-details">
      <p><strong>Memory Decoder: A Pretrained, Plug-and-Play Memory for Large Language Models</strong><br>
      <em>Jiaqi Cao*, <strong>Jiarui Wang</strong>*, Rubin Wei, Qipeng Guo, Kai Chen, Bowen Zhou, Zhouhan Lin</em><br>
      <em>NeurIPS 2025</em><br>
      🔗 <a href="https://arxiv.org/abs/2508.09874">arXiv</a> · <a href="https://github.com/LUMIA-Group/MemoryDecoder">GitHub</a> · <a href="https://huggingface.co/collections/Clover-Hill/memorydecoder">Hugging Face</a> · * Equal Contribution</p>
    </div>
  </li>
</ul>

## 🎓 <a id="education"></a>Education

- *2025.09–Present*, Ph.D. Student, [School of Computer Science](https://cs.sjtu.edu.cn/), [Shanghai Jiao Tong University](https://www.sjtu.edu.cn/)
- *2021.09–2025.06*, B.E. in Computer Science, [Shanghai Jiao Tong University](https://www.sjtu.edu.cn/)


## 💼 <a id="internships"></a>Internships

- *2025.08–Present*, [Shanghai AI Lab](https://www.shlab.org.cn/), Shanghai, China


## 🏅 <a id="honors_and_awards"></a>Honors and Awards

- Second Place, RoboCup China Open - Small Size League, 2024
- Third Prize, Prototype System Competition, CCF Chinasoft, 2023
- Provincial First Prize, Senior Group, National Olympiad in Informatics in Provinces (NOIP), 2018
