<h1 align="center">VLA-Research</h1>

<p align="center"> </p>


> VLA-Research includes papers and open-source projects related to VLA, especially in the field of embodied manipulation. It aims to collect and summarize all VLA work, hoping to help friends with embodied AI to understand VLA work efficiently. Welcome to click Star, share and communicate.
# 📝 TODO
| 任务 | 状态 | 描述 |
|------|------|------|
| 🔵 VLA分类 | 待完成 | 对VLA模型进行分类整理 |
| 💠 VLA-RL整理 | 待完成 | 整理VLA与强化学习相关的工作 |

# Contents

<nav>
  <ul>
    <li><a href="#VLA Research List">VLA Research List</a></li>
    <li><a href="#acknowledgement">Acknowledgement</a></li>
    <li><a href="#cite">👍 Citation</a></li>
    <li><a href="#license">🏷️ License</a></li>
  </ul>
</nav>


# VLA Research List

<section id="VLA Research List"></section>



| 模型名称 | Paper | Code | Project | 机构 | 时间 | 模型大小 | 会议/期刊 | 特点 |
|---------|-------|------|--------------|------|------|----------|-----------|------|
| RT-1 | [paper](https://arxiv.org/pdf/2212.06817) | [code](https://github.com/google-research/robotics_transformer) | [page](https://robotics-transformer1.github.io/) | Google Deepmind | 2022.12 | - | - | 机器人Transformer系列的开山之作 |
| RT-2 | [paper](https://arxiv.org/pdf/2307.15818) | - | [page](https://robotics-transformer2.github.io/) | Google Deepmind | 2023.7 | 55B |  | 机器人Transformer第二代，支持视觉推理 |
| RT-Trajectory | [paper](https://arxiv.org/pdf/2311.01977) | - | [page](https://rt-trajectory.github.io/) | Google Deepmind, UCSD, 斯坦福 | 2023.11 | - | ICLR 2024 (Spotlight) | 轨迹预测能力增强 |
| AUTO-RT | [paper](https://arxiv.org/pdf/2401.12963) | - | [page](https://auto-rt.github.io/) | Google Deepmind | 2024.1 | - |  | 自动化机器人Transformer |
| RoboFlamingo | [paper](https://arxiv.org/pdf/2311.01378) | [code](https://github.com/roboflamingo) | - | 字节、清华 | 2024.2 | - |  | 基于Flamingo架构 |
| OpenVLA | [paper](https://arxiv.org/pdf/2406.09246) | [code](https://github.com/openvla) | - | Stanford | 2024.6 | 7B |  | 开源VLA模型 |
| TinyVLA | [paper](https://arxiv.org/abs/2409.12514) | - | - | 上海大学 | 2024.11 | - | | 轻量级VLA模型 |
| TraceVLA | [paper](https://arxiv.org/pdf/2412.10345) | [code](https://github.com/umd-huang-lab/tracevla) | - | 微软 | 2024.12 | - |  | 轨迹追踪能力 |
| Octo | [paper](https://arxiv.org/pdf/2405.12213) | [code](https://octo-models.github.io/) | - | 斯坦福，伯克利 | 2024.5 | 93M |  | 轻量级扩散模型 |
| π0 | [paper](https://arxiv.org/pdf/2410.24164) | [code](https://github.com/Physical-Intelligence/openpi) | - | 斯坦福, Physical Intelligence | 2024.10 | 3.3B |  | 基于流的扩散VLA，使用PaliGemma (3B VLM) |
| CogACT | [paper](https://arxiv.org/pdf/2411.19650) | [code](https://github.com/microsoft/CogACT.git) | - | 清华，MSRA | 2024.11 | 7B |  | 认知动作Transformer |
| Diffusion-VLA | [paper](https://arxiv.org/abs/2412.03293) | [code](https://arxiv.org/pdf/2410.07864) | - | 华东师范，上海大学，美的 | 2024.12 | - |  | 扩散模型VLA |
| 3D-VLA | [paper](https://arxiv.org/pdf/2403.09631) | [code](https://github.com/UMass-Foundation-Model/3D-VLA/tree/main) | - | UMass | 2024.3 | CVPR 2024 | 3D-based LLM |
| SpatialVLA | [paper](https://arxiv.org/pdf/2501.15830) | [code](https://github.com/SpatialVLA/SpatialVLA) | - | 上海AI Lab | 2025.1 |  | Adaptive Action Grid |
| Figure: Helix | - | - | [Figure](https://www.figure.ai/news/helix) | Figure | 2025.2.20 | - | 机器人全身上半身控制 |
| GO-1 | - | - | [智元官网](https://www.zhiyuan-robot.com/article/189/detail/56.html) | 智元 | 2025.3.10 | - | VLM+MoE架构 |
| pi-0.5 | [paper](https://arxiv.org/abs/2504.16054) | [code](https://github.com/Physical-Intelligence/openpi) | [blog](https://blog.csdn.net/) | Physical Intelligence | 2025.4.22 | | 单模型架构，高级任务分解 |
| Hi Robot | [paper](https://arxiv.org/abs/2502.19417) | [code](https://github.com/Physical-Intelligence/openpi) | [blog](https://blog.csdn.net/) | Physical Intelligence | 2025.2.26 | | VLM+VLA双模型架构 |
| GROOT-N1 | [paper](https://arxiv.org/abs/2503.14734) | [code](https://github.com/NVIDIA/Isaac-GR00T) | [blog](https://developer.nvidia.com/blog/) | Nvidia | 2025.3.27 |  | 2B参数，全身控制，NVIDIA-Eagle架构 |
| Psi-R1 | - | - | [blog](https://www.jiqizhixin.com/articles/2025-03-03-9) | 灵初智能 | 2025.4.27 | - | 分层端到端VLA+RL，验证test-time scaling |
| Gemini Robotics | [paper](https://arxiv.org/pdf/2503.20020) | - | - | Google DeepMind | 2025.3.25 |  | Gemini 2.0构建，50Hz动作输出频率 |
| SafeVLA | [paper](https://arxiv.org/abs/2503.03480) | [code](https://github.com/PKU-Alignment/SafeVLA) | - | 北大 | 2025.3.5 | - |  | 解决传统VLA模型在抓取和导航任务中的不安全行为 |
| HybridVLA | [paper](https://arxiv.org/pdf/2503.10631) | [code](https://github.com/PKU-HMI-Lab/Hybrid-VLA) | - | 北大 | 2025.3.17 | 2.7B/7B |  | 用统一模型集成扩散和自回归动作预测 |
| DexVLA | [paper](https://arxiv.org/pdf/2502.05855) | [code](https://github.com/juruobenruo/DexVLA) | - | 美的, 东南大学 | 2025.2.9 | 1B |  | Diffusion expert，采用多个action head |
| DexGraspVLA | [paper](https://arxiv.org/abs/2502.20900) | [code](https://github.com/Psi-Robot/DexGraspVLA) | - | 北大 | 2025.2.28 | - |  | 灵巧手抓取VLA |
| UP-VLA | [paper](https://arxiv.org/pdf/2501.18867) | - | - | 清华 | 2025.2.3 | - |  | 加入goal-image预测任务帮助动作生成 |
| CoT-VLA | [paper](https://arxiv.org/pdf/2503.22020) | - | - | Nvidia, Stanford | 2025.3 | 7B |  | 将CoT融入VLA中，通过自回归地预测未来的图像帧作为视觉目标 |
| UniAct | [paper](https://arxiv.org/abs/2501.10105) | [code](https://github.com/2toinf/UniAct) | - | 清华 | 2025.1 | - |  | 基于通用动作空间的具身基础模型 |
| UniVLA | [paper](https://arxiv.org/pdf/2505.06111) | [code](https://github.com/OpenDriveLab/UniVLA) | - | 港大, 上海AI Lab, 智元 | 2025.5.9 | - |  | 利用潜在动作模型从多样化数据中提取任务核心表征，提升泛化能力 |


<section id="acknowledgement"></section>

# Acknowledgement
本文参考/引用了一些博主的文章, 我们对他们的知识分享表示感谢, 引用列表如下：[1] 知乎 [张乐](https://www.zhihu.com/people/zhang-le-3-67-28)
[1] Github [Tianxing Chen](https://github.com/TianxingChen/Embodied-AI-Guide)

<section id="cite"></section>

# 👍 Citation
If you find this repository helpful, please consider citing:

```
@misc{vlaresearch2025,
      title = {VLA-Research},
      author = {VLA-Research-Contributors},
      year = {2025},
      howpublished = {\url{https://github.com/Louis-ZhangLe/VLA-Research}},
}
```

<section id="license"></section>

# 🏷️ License
This repository is released under the MIT license. See [LICENSE](./LICENSE) for additional details.
