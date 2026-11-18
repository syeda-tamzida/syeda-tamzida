## Hi, I'm Tamzi (Syeda Tamzida Akter) 👋

PhD student and Graduate Research Assistant in Civil, Environmental & Architectural Engineering at **Worcester Polytechnic Institute (WPI)**.
I work where **transportation research meets NLP and Large Language Models**: I build models that read what people write about transit (comments, complaints, requests, social media posts) and turn it into structured data that agencies can act on.

🌐 [syeda-tamzida.github.io](https://syeda-tamzida.github.io/)

---

### 🔬 Current focus: NLP & LLMs for transportation

- **Understanding transit rider feedback with NLP and LLMs** *(ongoing research, WPI)*
  - Classifying public comments to transit agencies into a **hierarchical taxonomy** (10 parent request categories plus subtypes)
  - **LLM-based information extraction**: pulling the request type and the **place it refers to** (stop, route, street) out of free-text comments
  - Comparing **fine-tuned local models** with **GPT-style API models** for this task
  - **Cross-platform learning**: adding Reddit transit discussions to small agency datasets, and separating new kinds of requests from shifts between platforms
  - Goal: a domain-specific language model for bus transit agencies that works for comments from any city, not just one

### ⭐ Featured project

**[Evidence-Grounded LLM Trading Agent](https://github.com/syeda-tamzida/evidence-grounded-llm-trading-agent)**: an LLM agent that has to cite real, dated evidence for every decision it makes.
- **Qwen2.5-1.5B-Instruct** fine-tuned with **LoRA (PEFT)**, trained on the tool-call turns as well as the final answers
- **Tool calling / agent loop**: news, technical indicators and **SEC EDGAR filings**, each fact tagged with an evidence ID
- **Citation verification** in code: claims that cite no evidence, or the wrong evidence, are rejected (a guard against hallucinated sources)
- **Retrieval memory**: after each decision the agent writes a short reflection, and **BM25** brings the relevant ones back into later prompts
- Point-in-time backtests with no look-ahead, an ablation study, and a week of live paper-trading logs

### 🧰 Tools I use

**NLP / LLMs:** Hugging Face Transformers · PEFT / LoRA fine-tuning · prompt-based extraction · tool-calling agents · BM25 retrieval · OpenAI-style APIs
**ML & data:** Python · PyTorch · scikit-learn · pandas · interpretable ML · clustering (DBSCAN) · reinforcement learning
**Transportation:** SUMO traffic simulation · ns-3 (V2V communication) · travel behavior and mode choice modeling

### 📂 Projects

| Project | Area |
|---|---|
| [Evidence-Grounded LLM Trading Agent](https://github.com/syeda-tamzida/evidence-grounded-llm-trading-agent) | LLM agents · LoRA fine-tuning · tool calling |
| [Traffic Signal Control with Reinforcement Learning](https://github.com/syeda-tamzida/Traffic-Signal-Control-Optimization-for-Heterogeneous-Traffic-Using-Reinforcement-Learning) | RL · traffic control |
| [Explainable ML for Trip Mode Choice](https://github.com/syeda-tamzida/Explainable-Machine-Learning-for-Understanding-Trip-Mode-Choice) | Interpretable ML · travel behavior |
| [Household Access to Heavy Rail (Interpretable ML)](https://github.com/syeda-tamzida/Explaining-Household-Access-to-Heavy-Rail-Services-Using-Interpretable-Machine-Learning) | Interpretable ML · transit access |
| [Accident Blackspots in Melbourne (DBSCAN)](https://github.com/syeda-tamzida/Spatio-Temporal-Analysis-of-Accident-Blackspots-in-Melbourne-Australia-Using-DBSCAN-Clustering) | Spatio-temporal clustering · road safety |
| [V2V Delay Prediction in CAVs (SUMO + ns-3)](https://github.com/syeda-tamzida/Optimizing-V2V-Communication-Delay-Prediction-in-CAV-Vehicles-through-SUMO-and-ns-3-Simulations) | Connected vehicles · simulation |
| [Undergraduate Thesis: Corrosion Assessment of Reinforced Concrete with ML & Multimodal Data](https://github.com/syeda-tamzida/Thesis-) | ML · image processing · infrastructure |

### 📄 Publications

Two Q1 journal papers and one IEEE conference paper from my undergraduate research at CUET, Bangladesh (B.Sc. Civil Engineering). The full list is on my [website](https://syeda-tamzida.github.io/).

---

📫 Open to research collaborations in **NLP / LLMs for transportation and urban mobility**.
