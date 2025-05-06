# llama4-model-learn


欢迎访问本项目！本仓库旨在帮助中文用户更好地理解 [LLaMA4](https://github.com/meta-llama/llama-models/tree/main/models/llama4) 模型的结构。

📖 [English Version](./README.en.md)

---

## 📌 项目背景

本项目代码大量参考于原作者 [PyTorch-Adventures](https://github.com/priyammaz/PyTorch-Adventures/tree/c3da58451164977aa9439ebe286180ba9676c1b3/PyTorch%20for%20NLP/Llama4) 的开源实现，并特别感谢他的[讲解视频](https://www.youtube.com/watch?v=yXbF-1n9wxs&t=15761s)，为理解LLaMA4提供了极大帮助。

在原有代码的基础上，我对代码部分添加了**中文注释**和**个人理解**，并补充了简单的训练和推理代码。

> ⚠️ 由于我的工作方向偏向 NLP，因此 Vision 模块部分未作深入讲解，仅保留原始实现。

---

## 📂 仓库内容

本项目包含以下主要文件：

| 文件名                        | 简介                                                         |
| ----------------------------- | ------------------------------------------------------------ |
| `llama4-original.ipynb`       | 原作者对 LLaMA4 的完整代码解析，添加了中文注释               |
| `llama4-train_with_cpu.ipynb` | 去除 Vision 模块，仅保留 NLP 结构，支持在 CPU 上训练 / 推理（简单代码） |
| `llama4-train_with_gpu.ipynb` | 同上，支持 GPU（如 Colab 免费 T4）上运行                     |

> 💡 为兼容 Google Colab 免费版，这些文件中使用了较小的超参数设置，可在低资源环境下运行测试。

---

## 🚧 未来计划

- [ ] 增加一个 Notebook 示例：多模态模型的训练流程（如果有精力的话 😄）

---

## 📜 声明

本项目仅供学习与研究使用，不适合用于商业用途。原始代码版权归原作者所有（虽然原作者也是参考huggingface官方的代码 😄）。

---

## 🙌 致谢

感谢原作者[@priyammaz](https://github.com/priyammaz)的分享。

