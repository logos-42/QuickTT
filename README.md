# QuickTTS 🎙️

**QuickTTS** 是一个功能强大且多用途的文本转语音（TTS）工具，采用简洁直观的 Gradio 界面构建。应社区需求，此项目被开发为音频生成、配音等功能的完整解决方案。

[![GitHub](https://img.shields.io/badge/GitHub-logos--42-black.svg)](https://github.com/logos-42)
[![Website](https://img.shields.io/badge/Website-liuyuanjie.xyz-blue.svg)](https://liuyuanjie.xyz)
[![X (Twitter)](https://img.shields.io/badge/X-@canopylist-black.svg)](https://x.com/canopylist)

---

<img width="1180" height="592" alt="主界面" src="https://github.com/logos-42/QuickTT/raw/main/screenshots/main-interface.png" />
_主界面显示提供商选择和音频选项。_ <br>

<img width="1191" height="738" alt="SRT界面" src="https://github.com/logos-42/QuickTT/raw/main/screenshots/srt-interface.png" />
_SRT界面显示提供商选择和音频及进度选项。_

## ✨ 主要功能

QuickTTS 超越了简单的音频生成，为各种需求提供了一套强大的工具：

- **多种TTS提供商**：从 **Edge-TTS** 的大量高质量语音或 **TikTok TTS** 的流行病毒式语音中选择。
- **全球支持**：生成数十种语言和方言的音频，有数百种男性和女性语音可供选择。
- **字幕同步（.SRT）**：加载字幕文件（`.srt`）并自动生成完美同步的音频文件，非常适合视频配音、课程和其他项目。
- **批量处理**：轻松将整个文本文件（`.txt`）的内容转换为单个音频文件。
- **音频精细调节**：控制 Edge-TTS 生成音频的**速度**、**音调**和**音量**。
- **智能静音移除**：可选择性地从最终音频中移除不需要的停顿和静音，获得更动态的结果。
- **集成示例**：使用预配置的 SRT 示例快速开始，一键测试配音功能。
- **实时界面**：通过界面中的交互式进度条实时跟踪 SRT 文件处理进度。

## 🚀 使用方法

您可以通过三种简单的方式使用 QuickTTS，如果不想的话，无需在本地安装任何东西。

### 1. Hugging Face Spaces（推荐用于 Edge-TTS）

直接在浏览器中访问公开且始终可用的版本。非常适合快速测试 Edge-TTS 功能。

- **[在 Hugging Face 上访问 QuickTTS](https://huggingface.co/spaces/logos-42/QuickTT)**
  > **注意：** TikTok TTS 功能在 Hugging Face 上因网络限制而被阻止。

### 2. 本地运行（完全控制）

为了获得最佳性能和离线使用，请在您自己的机器上克隆并运行项目。

1. **前置要求：**
    - Python 3.9+
    - FFmpeg（音频处理必需）。[安装说明在这里](https://ffmpeg.org/download.html)。

2. **克隆仓库：**

   ```bash
   git clone https://github.com/logos-42/QuickTT.git
   cd QuickTT
   ```

3. **安装依赖：**

   ```bash
   pip install -r requirements.txt
   ```

4. **运行应用程序：**

   ```bash
   python app.py
   ```
   - 或者在 Windows 上，只需运行 `webui.bat` 文件。

5. 通过提供的本地 URL（通常是 `http://127.0.0.1:7860`）在浏览器中访问应用程序。

## 🤝 如何贡献

我们始终欢迎贡献！如果您有新功能的想法、发现了错误或想要改进代码，请随时：

- 打开一个 [Issue](https://github.com/logos-42/QuickTT/issues) 来讨论您的想法。
- 提交一个 [Pull Request](https://github.com/logos-42/QuickTT/pulls) 与您的改进。

## 🙏 致谢

这个项目之所以成为可能，要归功于社区开发的优秀开源库：

- **[edge-tts](https://github.com/rany2/edge-tts)** 由 **rany2** 开发
- **[TikTok-Voice-TTS](https://github.com/mark-rez/TikTok-Voice-TTS)** 由 **mark-rez** 开发
- 当然，还有 **[Gradio](https://gradio.app/)** 团队，让 ML 界面的创建变得如此便捷。

## 👤 作者

由 **Leo** 用 ❤️ 开发。

如果您喜欢这个项目并且它对您有用，请考虑支持我的工作。任何金额都有助于保持创建和维护此类工具的动力！

**联系方式：**
- 📧 邮箱：2844169590@qq.com
- 🌐 个人网站：[liuyuanjie.xyz](https://liuyuanjie.xyz)
- 🐦 X (Twitter)：[@canopylist](https://x.com/canopylist)
- 💻 GitHub：[@logos-42](https://github.com/logos-42)

---
