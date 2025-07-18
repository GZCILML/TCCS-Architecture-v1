# TCCS Architecture v1.5

**Threaded Cognitive Context System (TCCS) — A Conceptual Middleware for Semantically Threaded Memory in LLMs**  
**語義記憶分線架構：一種面向大型語言模型（LLMs）的概念型上下文中介系統**

---

## 🧠 Project Overview | 專案簡介

TCCS（Threaded Cognitive Context System）是一個概念性架構，旨在解決大型語言模型（LLMs）在長期記憶一致性、多任務語境分化，以及持續學習場景下的災難性遺忘（Catastrophic Forgetting）等問題。  
本架構提出以「語意分線記憶結構」來儲存與檢索跨對話情境的關鍵資訊，使模型具有更類人式的記憶遷移與回溯能力。

TCCS is a conceptual architecture designed to address challenges in long-term memory consistency, multi-task context separation, and catastrophic forgetting in LLMs. It proposes semantic threading as a structure for contextual memory management across conversations.

---

## 📁 Repository Contents | 文件清單

| 檔案 | 說明 |
|------|------|
| `TCCS_Whitepaper.md` | 初版白皮書（Markdown） |
| `TCCS_v1.5_Proposal.docx` | 中文版 v1.5 設計提案 |
| `TCCS_v1.5_Proposal_EN.docx` | English version of v1.5 proposal |
| `thread_example.json` | Thread 實例格式範例（JSON） |
| `TCCS_architecture.png` | 架構圖示意（Visualization Diagram） |

---

## 🚀 Key Features | 核心特性

- **Thread Unit-Based Memory Segmentation**  
- **Semantic Indexing + Trigger-based Retrieval**
- **Contextual Middleware Compatible with RAG / LoRA**
- **Supports Cold Memory Pooling and Dynamic Forgetting**

---

## 🌱 Use & Reference | 使用與引用

本架構作為開源構想釋出，歡迎引用、擴展、研究或實作。作者不主張所有權。  
Released as an open intellectual contribution. Anyone is welcome to adapt, reference, or experiment.

---

## 📌 Topics / Tags

`LLM` `Memory Architecture` `Semantic Indexing` `Continual Learning` `RAG` `Cold Memory` `AI Architecture` `Conceptual Framework`

---

## 📜 License

This work is released into the **public domain** by the author. Attribution optional but appreciated.
