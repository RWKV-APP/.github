# Hi there, welcome to RWKV-APP 👋

<div align="center">

<h3>
  <b>Make Large Models Accessible to Everyone.</b><br>
  让大模型触手可及。
</h3>

<p>
  <i>Powered by RWKV + Flutter + C++ High-Performance Inference Engine</i><br>
  <i>基于 RWKV 架构与 Flutter + C++ 高性能推理引擎的融合</i>
</p>

<p>
  <a href="https://github.com/RWKV-APP/RWKV_APP/actions">
    <img src="https://img.shields.io/github/actions/workflow/status/RWKV-APP/RWKV_APP/commit-and-pr-check.yml?branch=main&label=Build%20Status&style=flat-square" alt="Build Status">
  </a>
  <a href="https://github.com/RWKV-APP/RWKV_APP/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/RWKV-APP/RWKV_APP?style=flat-square&color=blue" alt="License">
  </a>
  <a href="https://discord.gg/8NvyXcAP5W">
    <img src="https://img.shields.io/discord/992359628979568701?color=5865F2&label=Discord&logo=discord&logoColor=white&style=flat-square" alt="Discord">
  </a>
</p>

</div>

---

### 📖 Our Mission / 我们的愿景

**Private, Offline, Everywhere.**
We aim to bring the power of Large Language Models (LLMs) to consumer-grade devices—from mobile phones to laptops—without relying on the cloud. By leveraging the linear complexity of the **RWKV** architecture, we make AI accessible even on low-compute devices.

**隐私、离线、无处不在。**
我们的目标是将大语言模型（LLM）的能力带入普通用户的手机和笔记本电脑，无需依赖昂贵的云端算力。借助 **RWKV** 架构的线性复杂度优势，我们让 AI 在低算力设备上也能流畅运行。

---

### 🏗️ Technical Architecture / 技术架构

Our ecosystem consists of three key layers, ensuring high performance across platforms:
我们的生态系统由三个核心层组成，确保了跨平台的高性能表现：

| Repository (仓库)                                                                | Role (角色)                                                                                                                                                                         | Tech Stack (技术栈)                                                                                                                                                        |
| :------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 📱 **[RWKV_APP](https://github.com/RWKV-APP/RWKV_APP)**                          | **[Frontend]** The UI/UX layer. Manages model weights, chat interface, and platform-specific logic.<br>**[前端交互]** 负责 UI 渲染、权重管理及平台特定代码。                        | ![Flutter](https://img.shields.io/badge/-Flutter-02569B?logo=flutter&logoColor=white) ![Riverpod](https://img.shields.io/badge/-Riverpod-00599C?logo=dart&logoColor=white) |
| 🔗 **[rwkv_mobile_flutter](https://github.com/MollySophia/rwkv_mobile_flutter)** | **[Bridge]** The communication bridge. Uses Dart FFI to connect the Flutter UI with the C++ backend.<br>**[通信桥梁]** 通过 Dart FFI 连接 Flutter 前端与 C++ 后端，实现非阻塞通讯。 | ![Dart](https://img.shields.io/badge/-Dart-0175C2?logo=dart&logoColor=white) ![FFI](https://img.shields.io/badge/-FFI-grey?logo=c&logoColor=white)                         |
| ⚙️ **[rwkv-mobile](https://github.com/MollySophia/rwkv-mobile)**                 | **[Engine]** The high-performance inference runtime. Supports CPU, GPU (Vulkan/Metal), and NPU.<br>**[推理引擎]** 核心 C++ 运行时。支持 WebGPU, NPU, MLX 等多种硬件加速。           | ![C++](https://img.shields.io/badge/-C++-00599C?logo=c%2B%2B&logoColor=white) ![Vulkan](https://img.shields.io/badge/-Vulkan-AC162C?logo=vulkan&logoColor=white)           |

---

### 🚀 Key Features / 核心功能

- **Offline Inference (离线推理)**: Download once, run forever. No internet required.
- **Multi-Modal (多模态)**: Chat, ASR (Speech-to-Text), TTS (Voice Cloning), and Vision (OCR/Description).
- **Hardware Acceleration (硬件加速)**: Optimized for Qualcomm NPU, Apple MLX, and standard GPUs.
- **Cross-Platform (全平台)**: Android, iOS, Windows, macOS, Linux.

---

### 📥 Download / 下载体验

Experience the latest RWKV-7 models on your device today.
立即在您的设备上体验最新的 RWKV-7 模型。

| Platform    | Link                                                                                                                            |
| :---------- | :------------------------------------------------------------------------------------------------------------------------------ |
| **Android** | [Google Play](https://play.google.com/store/apps/details?id=com.rwkvzone.chat) • [Pgyer (Beta)](https://www.pgyer.com/rwkvchat) |
| **iOS**     | [App Store](https://apps.apple.com/us/app/rwkv-chat/id6740192639) • [TestFlight](https://testflight.apple.com/join/DaMqCNKh)    |
| **Desktop** | Join our [QQ Group](https://qm.qq.com/q/y0gOHcguty) for Windows/macOS builds                                                    |

---

### 🤝 Community & Contributors / 社区与贡献

Special thanks to our core contributors: **Molly Sophia** (Core Engine), **Ce Wang** (App Arch), **dengzi**, **chenqi**, and the community.

<div align="center">

| Platform            | Link                                         |
| :------------------ | :------------------------------------------- |
| **Discord**         | [Join Server](https://discord.gg/8NvyXcAP5W) |
| **QQ Group (Tech)** | [325154699](https://qm.qq.com/q/y0gOHcguty)  |
| **QQ Group (Beta)** | [332381861](https://qm.qq.com/q/y0gOHcguty)  |

</div>
