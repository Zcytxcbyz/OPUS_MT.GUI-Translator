![Screenshot](https://github.com/Zcytxcbyz/OPUS_MT.GUI-Translator/blob/main/screenshot.png)

## English

### 🚀 OPUS-MT.GUI - Release v1.3

This is the first stable release of **OPUS-MT.GUI**, a WPF-based offline neural machine translation tool using ONNX Runtime and DirectML acceleration.

### ✨ Highlights
- **Fully offline** – No internet required after model download
- **GPU acceleration** – DirectML support for faster inference on Windows
- **Self-contained** – Includes .NET 10 runtime, no additional installation
- **Two built-in models** – English ↔ Chinese (en-zh, zh-en)
- **Multi-language UI** – Automatically follows system language (English/Chinese)
- **Settings persistence** – Remembers window position, size and last selected model

### 📦 Download

| File | Description |
|------|-------------|
| [OPUS-MT.GUI-DOTNET10-WIN-X64-WithModels-Setup-v1.3.exe](https://github.com/Zcytxcbyz/OPUS_MT.GUI-Translator/releases/download/v1.3/OPUS-MT.GUI-DOTNET10-WIN-X64-WithModels-Setup-v1.3.exe) | Full package including models (~1.6 GB). Run the installer to set up the application. |

### 🖥️ System Requirements
- Windows 10/11 (64-bit)
- DirectX 12 capable GPU (optional, for GPU acceleration)
- No .NET installation required (runtime included)

### 📖 How to Use
1. Download and run the installer
2. Run `OPUS-MT.GUI.exe`
3. Select a model from the dropdown (auto‑loads)
4. Enter source text, click **Translate**

---

## 中文

### 🚀 OPUS-MT.GUI - 发布版本 v1.3

这是 **OPUS-MT.GUI** 的首个稳定版本，一个基于 WPF、使用 ONNX Runtime 和 DirectML 加速的离线神经机器翻译工具。

### ✨ 主要亮点
- **完全离线** – 模型下载后无需网络
- **GPU 加速** – 支持 DirectML，在 Windows 上获得更快推理速度
- **自包含** – 已集成 .NET 10 运行时，无需额外安装
- **内置两个模型** – 英 ↔ 中（en-zh, zh-en）
- **多语言界面** – 自动跟随系统语言（英文/简体中文）
- **设置持久化** – 记住窗口位置、大小和上次选择的模型

### 📦 下载

| 文件 | 说明 |
|------|------|
| [OPUS-MT.GUI-DOTNET10-WIN-X64-WithModels-Setup-v1.3.exe](https://github.com/Zcytxcbyz/OPUS_MT.GUI-Translator/releases/download/v1.3/OPUS-MT.GUI-DOTNET10-WIN-X64-WithModels-Setup-v1.3.exe) | 完整包（含模型），约 1.6 GB。运行安装程序即可安装应用。|

### 🖥️ 系统要求
- Windows 10/11（64 位）
- 支持 DirectX 12 的 GPU（可选，用于 GPU 加速）
- 无需安装 .NET 运行时（已包含）

### 📖 使用方法
1. 下载并运行安装程序
2. 运行 `OPUS-MT.GUI.exe`
3. 从下拉框选择模型（自动加载）
4. 输入原文，点击“翻译”

---

### Acknowledgments / 致谢
- [Helsinki-NLP](https://huggingface.co/Helsinki-NLP) for OPUS-MT models
- [LMSupply.Translator](https://github.com/iyulab/lm-supply) for ONNX runtime integration
- [WPF-UI](https://github.com/lepoco/wpfui) for modern UI components
- [Microsoft.ML.OnnxRuntime.DirectML](https://github.com/microsoft/onnxruntime) for ONNX runtime
- [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json) for JSON parser
- [CommunityToolkit.Mvvm](https://github.com/CommunityToolkit/dotnet) for MVVM framework
