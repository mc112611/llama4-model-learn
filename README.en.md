# 🦙 Building LLaMA4 from Scratch

Welcome to this project! This repository aims to help users—especially those who prefer reading in Chinese—understand the structure and workflow of the [LLaMA4 model](https://github.com/meta-llama/llama-models/tree/main/models/llama4).

📖 [中文版（Chinese Version）](./README.md)

---

## 📌 Project Background

This implementation is heavily inspired by the excellent open-source work from [PyTorch-Adventures](https://github.com/priyammaz/PyTorch-Adventures/tree/c3da58451164977aa9439ebe286180ba9676c1b3/PyTorch%20for%20NLP/Llama4). Special thanks to his [walkthrough video](https://www.youtube.com/watch?v=yXbF-1n9wxs&t=15761s), which greatly helped in understanding LLaMA4’s design.

Based on his work, I’ve added **Chinese comments**, **personal insights**, and **simple training/inference code** to assist learners.

> ⚠️ Since my focus is primarily on NLP, the Vision module is preserved from the original implementation without deep analysis.

---

## 📂 Repository Contents

This project includes the following key files:

| Filename                      | Description                                                  |
| ----------------------------- | ------------------------------------------------------------ |
| `llama4-original.ipynb`       | The original implementation of LLaMA4 with added Chinese comments |
| `llama4-train_with_cpu.ipynb` | NLP-only version (Vision removed), with training/inference examples on CPU |
| `llama4-train_with_gpu.ipynb` | Same as above, optimized for GPU usage (e.g., Colab T4)      |

> 💡 These notebooks use smaller hyperparameters to ensure compatibility with free versions of Google Colab.

---

## 🚧 Future Plans

- [ ] Add a notebook for training multimodal models (if time and energy permit 😄)

---

## 📜 Disclaimer

This repository is intended for **educational and research purposes only**. It is **not suitable for commercial use**. Original code copyrights belong to the respective author(s), though the base implementation also references Hugging Face’s official code 😄.

---

## 🙌 Acknowledgements

Thanks to [@priyammaz](https://github.com/priyammaz) for the original work and generous sharing.