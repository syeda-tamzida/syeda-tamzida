## Hi, I'm Tamzi (Syeda Tamzida Akter) 👋

PhD student in Civil Engineering (Transportation) at **Worcester Polytechnic Institute (WPI)**.
I apply **machine learning, NLP and large language models** to transportation planning and operations. My current work combines **LLM-based information extraction** with **geospatial analysis** to support data-driven public transit planning.

🌐 [Website](https://syeda-tamzida.github.io/) · 🎓 [Google Scholar](https://scholar.google.com/citations?user=PxQRnjsAAAAJ&hl=en) · ✉️ sakter@wpi.edu

---

### 🔬 Current research: NLP & LLMs for transportation

**LLM-Based Extraction of Transit Service Requests from Public Comments** · *Graduate Research Assistant, WPI · Fall 2026 – ongoing*
- Classifying public comments to transit agencies into a **hierarchical taxonomy**
- **LLM-based information extraction**: pulling the request type and the **place it refers to** out of free-text comments (text classification, NER)
- Comparing **fine-tuned local models** with **GPT-style API models**, evaluated against manually annotated data

**Distinguishing Semantic Novelty from Domain Shift in Transportation Feedback** · *CS 554 NLP, WPI · Fall 2026 – ongoing*
- **Cross-platform learning**: adding Reddit transit discussions to small agency datasets, and separating new kinds of requests from shifts between platforms
- Goal: a domain-specific language model for bus transit agencies that works for comments from any city, not just one

### ⭐ Featured project

**[Evidence-Grounded LLM Trading Agent](https://github.com/syeda-tamzida/evidence-grounded-llm-trading-agent)**: an LLM agent that has to cite real, dated evidence for every decision it makes.
- **Qwen2.5-1.5B-Instruct** fine-tuned with **LoRA (PEFT)**, trained on the tool-call turns as well as the final answers
- **Tool calling / agent loop**: news, technical indicators and **SEC EDGAR filings**, each fact tagged with an evidence ID
- **Citation verification** in code: claims that cite no evidence, or the wrong evidence, are rejected (a guard against hallucinated sources)
- **Retrieval memory**: after each decision the agent writes a short reflection, and **BM25** brings the relevant ones back into later prompts
- Point-in-time backtests with no look-ahead, an ablation study, and a week of live paper trading through the Alpaca API

---

### 📄 Publications

**Journal articles**
- **Akter, S. T.**, Lamun, S. S., Zisan, M. B., & Rahman, M. A. (2026). Concrete surface deterioration detection and classification using YOLO26n: An AI-driven approach. *Scientific Reports*. [[Paper]](https://doi.org/10.1038/s41598-026-68706-0) [[Code]](https://github.com/syeda-tamzida/concrete-defect-detection-yolo26)
- Hassan, M., Kabir, M. E., **Akter, S. T.**, Shraban, S. S., Basaruddin, K. S., & Islam, M. A. (2025). Machine learning in travel mode choice studies: A systematic literature review of applications, methods, and challenges. *Results in Engineering*. [[Paper]](https://doi.org/10.1016/j.rineng.2025.108140)

**Conference papers**
- Sultana, S., Shafique, S., **Akter, S. T.**, Roy, C., Khan, A. M., & Zisan, M. B. (2026). Seismic Risk Assessment in Chattogram: An Explainable Machine Learning Approach. *IEEE iCONEECT 2026*. [[Code]](https://github.com/syeda-tamzida/seismic-risk-chattogram-xai)
- **Akter, S. T.**, Lamun, S. S. I., Ahmed, E., Sarkar, S., Roy, C. (2026). Machine Learning Based CO2 Emission Prediction at an Urban Intersection under Heterogeneous Traffic Using SUMO Microsimulation. *IEEE QPAIN 2026*. [[Paper]](https://doi.org/10.1109/QPAIN69676.2026.11546352)
- Hassan, M., **Akter, S. T.**, Lamun, S. S. I., Bhuiyan, T., Hassan, M. M. (2025). Explainable Machine Learning for Understanding Trip Mode Choice: Evidence from the 2022 U.S. National Household Travel Survey. *IEEE IICAIET 2025*. [[Paper]](https://doi.org/10.1109/IICAIET67254.2025.11265593) [[Code]](https://github.com/syeda-tamzida/Explainable-Machine-Learning-for-Understanding-Trip-Mode-Choice)
- Lamun, S. S. I., **Akter, S. T.**, Tahsin, J., Sarkar, S. (2025). Explaining Household Access to Heavy Rail Services Using Interpretable Machine Learning: Evidence from the 2022 U.S. National Household Travel Survey. *IEEE SPICSCON 2025*. [[Paper]](https://doi.org/10.1109/SPICSCON69221.2025.11504226) [[Code]](https://github.com/syeda-tamzida/Explaining-Household-Access-to-Heavy-Rail-Services-Using-Interpretable-Machine-Learning)
- **Akter, S. T.**, Biswas, D., Debnath, A., Zisan, M. B. (2025). Evaluation of Concrete Strength by Using Fly Ash and Brick Kiln Ash as a Partial Replacement for Cement. *ICERIE 2025*. [[Paper]](https://www.researchgate.net/publication/395230963_Evaluation_of_Concrete_Strength_by_Using_Fly_Ash_and_Brick_Kiln_Ash_as_a_Partial_Replacement_for_Cement)

**Under review**
- Non-Destructive Corrosion Assessment of Reinforced Concrete Using Machine Learning and Multimodal Surface Data. *Advances in Civil Engineering*. [[Preprint]](https://dx.doi.org/10.2139/ssrn.6002394) [[Code]](https://github.com/syeda-tamzida/Thesis-)
- Traffic Signal Control Optimization for Heterogeneous Traffic Using Reinforcement Learning. *Journal of Traffic and Transportation Engineering*. [[Preprint]](https://drive.google.com/file/d/11IZLD1PHiMUmfwVvhPO8S80DtDUedo6k/view?usp=sharing) [[Code]](https://github.com/syeda-tamzida/Traffic-Signal-Control-Optimization-for-Heterogeneous-Traffic-Using-Reinforcement-Learning)

---

### 📂 Projects

| Project | What it does | Area |
|---|---|---|
| [**mixed-traffic-sumo**: Open Mixed-Traffic Benchmark for SUMO](https://github.com/syeda-tamzida/mixed-traffic-sumo) | pip-installable real-world mixed-traffic scenarios for RL signal control; first scenario: a Chattogram intersection with 9 vehicle classes (rickshaws, CNGs, human haulers). Works with sumo-rl / Gymnasium / PettingZoo | Open-source tool · SUMO · RL |
| [Evidence-Grounded LLM Trading Agent](https://github.com/syeda-tamzida/evidence-grounded-llm-trading-agent) | LoRA-tuned Qwen 2.5 agent that checks SEC filings and news before each trade | LLM agents · fine-tuning |
| [Open-World Transit Feedback from Reddit](https://github.com/syeda-tamzida/reddit-transit-feedback-nlp) | Finds what riders ask for, and where, in 41,907 Reddit comments from 12 cities; flags concerns outside a fixed category list for new-category discovery | NLP · LLM extraction |
| [Gemma-3-1B: Prompting, LoRA/QLoRA & BM25 RAG](https://github.com/syeda-tamzida/gemma3-lora-qlora-rag) | Fine-tuned Gemma to answer from passages and abstain when the answer is absent; BM25 retrieval lifted QA accuracy from 0.7 to 80.7 EM | LLM fine-tuning · RAG |
| [Concrete Defect Detection with YOLO26n](https://github.com/syeda-tamzida/concrete-defect-detection-yolo26) | Detects six types of concrete surface damage in photos (mAP@50 0.988); *Scientific Reports* 2026 | Computer vision · object detection |
| [Seismic Risk Assessment in Chattogram](https://github.com/syeda-tamzida/seismic-risk-chattogram-xai) | Building-level earthquake risk for 92,469 buildings using AHP scoring, Random Forest/XGBoost and SHAP | Explainable ML · disaster risk |
| [BanReady: Snow-Ban Parking Assistant](https://github.com/syeda-tamzida/BanReady) | Shows Worcester drivers where they can legally park during snow bans (WPI i3 Lab Demo Day) | Urban mobility app |
| [Salary Disclosure & Job-Posting Engagement](https://github.com/syeda-tamzida/salary-disclosure-job-engagement) | Does disclosing salary on LinkedIn postings raise views and applications, and does it differ by career level? (DS 502 group project) | Regression · Ridge/Lasso · inference |
| [RL Traffic Signal Control](https://github.com/syeda-tamzida/Traffic-Signal-Control-Optimization-for-Heterogeneous-Traffic-Using-Reinforcement-Learning) | Compares MPLight, IDQN and fixed-time control under heterogeneous traffic | Reinforcement learning |
| [Explainable ML for Trip Mode Choice](https://github.com/syeda-tamzida/Explainable-Machine-Learning-for-Understanding-Trip-Mode-Choice) | Interpretable models of travel mode choice from the 2022 NHTS | Interpretable ML · travel behavior |
| [Household Access to Heavy Rail](https://github.com/syeda-tamzida/Explaining-Household-Access-to-Heavy-Rail-Services-Using-Interpretable-Machine-Learning) | Explains which households have access to heavy rail, using the 2022 NHTS | Interpretable ML · transit access |
| [CAV Penetration on a 2-km Expressway](https://github.com/syeda-tamzida/Epressway_SUMO) | Speed, delay, safety and emissions at 25–100% CAV penetration in SUMO | Connected vehicles · simulation |
| [V2V Delay in CAV Platoons: SUMO + ns-3 Pipeline](https://github.com/syeda-tamzida/v2v-delay-sumo-ns3) | SUMO → ns-3 co-simulation pipeline and open V2V packet dataset; shows channel saturation in CAV platoons | Connected vehicles · ML |
| [Accident Blackspots in Melbourne](https://github.com/syeda-tamzida/Spatio-Temporal-Analysis-of-Accident-Blackspots-in-Melbourne-Australia-Using-DBSCAN-Clustering) · [Risk chatbot](https://huggingface.co/spaces/lemonslayer/accident_risk) | DBSCAN hotspot analysis plus a chatbot that warns about high-risk zones | Road safety · clustering |
| [Undergraduate Thesis: Corrosion Assessment of Reinforced Concrete](https://github.com/syeda-tamzida/Thesis-) | Predicts corrosion from surface images, resistivity and weather | ML · image processing |

---

### 🧰 Skills

- **NLP & LLMs:** text classification · LLM-based information extraction · NER · LoRA fine-tuning (Qwen 2.5) · Hugging Face Transformers / PEFT · tool-calling agents · retrieval-augmented generation (BM25) · QLoRA
- **Machine learning:** PyTorch · scikit-learn · XGBoost · TensorFlow/Keras · SHAP · reinforcement learning (MPLight, IDQN)
- **Computer vision:** OpenCV · Ultralytics YOLO
- **Programming:** Python · R · Jupyter · Git/GitHub · LaTeX
- **Transportation:** SUMO · VISSIM · SIDRA · ArcGIS Pro

### 🎓 Education

- **PhD, Civil Engineering (Transportation)**, Worcester Polytechnic Institute, 2026 – present
- **BS, Civil Engineering**, Chittagong University of Engineering and Technology (CUET), Bangladesh, 2020 – 2025

### 🏆 Awards

- Champion, ACI Intra-CUET Concrete Solutions Competition (2022); 11th internationally, ACI Concrete Solutions Competition (2022)
- Third Place, National Concrete Idea Competition (2023)
- Co-founder, [Two Min Civil Engineering](https://www.youtube.com/@2_MIN_CIVIL_ENGINEERING), a YouTube channel explaining civil engineering concepts

---

📫 Open to research collaborations in **NLP / LLMs for transportation and urban mobility**.
