<div align="center">

# 🌟 Awesome-Document-Understanding [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of awesome Document Understanding resources, including papers, codes, and datasets.
</div>

---
continue update 🤗

## 📋 Table of contents

- [Milestone](#Milestone)
- [Document Understanding](#document-understanding)
- [MLLM](#mllm)
- [Grounded MLLM](#grounded-mllm)
- [Video LLM](#video-llm)


## 🏆 Milestone


<details open>
<summary>MiniCPM</summary>

- [MiniCPM-o 4.5: Towards Real-Time Full-Duplex Omni-Modal Interaction](https://arxiv.org/abs/2604.27393) **(OpenBMB)** | 26.4.30
- [MiniCPM-SALA: Hybridizing Sparse and Linear Attention for Efficient Long-Context Modeling](https://arxiv.org/abs/2602.11761) **(OpenBMB)** | 26.2.12
- [InfLLM-V2: Dense-Sparse Switchable Attention for Seamless Short-to-Long Adaptation](https://arxiv.org/abs/2509.24663) **(THU,OpenBMB,HIT)** | 25.9.29
- [MiniCPM-V 4.5: Cooking Efficient MLLMs via Architecture, Data, and Training Recipe](https://arxiv.org/abs/2509.18154) **(OpenBMB)** | 25.9.16
- [MiniCPM4: Ultra-Efficient LLMs on End Devices](https://arxiv.org/abs/2506.07900) **(OpenBMB)** | 25.6.9
- [MiniCPM-V: A GPT-4V Level MLLM on Your Phone](https://arxiv.org/abs/2408.01800) **(OpenBMB)** | 24.8.3
- [MiniCPM: Unveiling the Potential of Small Language Models with Scalable Training Strategies](https://arxiv.org/abs/2404.06395) **(THU,ModelBest)** | 24.4.9
- [LLaVA-UHD: an LMM Perceiving Any Aspect Ratio and High-Resolution Images](https://arxiv.org/abs/2403.11703) **(THU,NUS,UCAS)** | 24.3.18
- [Large Multilingual Models Pivot Zero-Shot Multimodal Learning across Languages](https://arxiv.org/abs/2308.12038) **(THU,ShanghaiAILab,BUPT,RUC,Zhihu,ModelBest)** | 23.8.23

</details>



<details open>
<summary>VILA</summary>


- [NVILA: Efficient Frontier Visual Language Models](https://arxiv.org/abs/2412.04468) **(NVIDIA,MIT,UCB,TW,THU)** | 24.12.5
- [VILA-U: a Unified Foundation Model Integrating Visual Understanding and Generation](https://arxiv.org/abs/2409.04429) **(THU,MIT,NVIDIA,UCB,UCSD)** | 24.9.6
- [LongVILA: Scaling Long-Context Visual Language Models for Long Videos](https://arxiv.org/abs/2408.10188) **(NVIDIA,MIT,KAUST)** | 24.8.19
- [VILA2: VILA Augmented VILA](https://arxiv.org/abs/2407.17453) **(NVIDIA,MIT,UT-Austin)** | 24.7.24
- [X-VILA: Cross-Modality Alignment for Large Language Model](https://arxiv.org/abs/2405.19335) **(NVIDIA,MIT,KAUST)** | 24.5.29
- [VILA: On Pre-training for Visual Language Models](https://arxiv.org/abs/2312.07533) **(NVIDIA,MIT)** | 23.12.12

</details>


<details open>
<summary>LLaMA</summary>

- [The Llama 4 herd: The beginning of a new era of natively multimodal AI innovation](https://ai.meta.com/blog/llama-4-multimodal-intelligence/) **(Meta)** | 25.4.5
- [The Llama 3 Herd of Models](https://arxiv.org/abs/2407.21783) **(Meta)** | 24.7.31
- [Llama 2: Open Foundation and Fine-Tuned Chat Models](https://arxiv.org/abs/2307.09288) **(Meta)** | 23.7.18
- [LLaMA: Open and Efficient Foundation Language Models](https://arxiv.org/abs/2302.13971) **(Meta)** | 23.2.27

</details>



<details open>
<summary>Qwen</summary>

- [Qwen3-VL Technical Report](https://arxiv.org/abs/2511.21631) **(Alibaba)** | 25.11.26
- [Qwen3-Omni Technical Report](https://arxiv.org/abs/2509.17765) **(Alibaba)** | 25.9.22
- [Qwen3 Technical Report](https://arxiv.org/abs/2505.09388) **(Alibaba)** | 25.5.14
- [Qwen2.5-VL Technical Report](https://arxiv.org/abs/2502.13923) **(Alibaba)** | 25.2.19
- [Qwen2-VL: Enhancing Vision-Language Model's Perception of the World at Any Resolution](https://arxiv.org/abs/2409.12191) **(Alibaba)** | 24.9.18
- [Qwen2 Technical Report](https://arxiv.org/abs/2407.10671) **(Alibaba)** | 24.7.15
- [Qwen Technical Report](https://arxiv.org/abs/2309.16609) **(Alibaba)** | 23.9.28
- [Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond](https://arxiv.org/abs/2308.12966) **(Alibaba)** | 23.8.24

</details>


<details open>
<summary>Intern</summary>

- [InternVL3.5: Advancing Open-Source Multimodal Models in Versatility, Reasoning, and Efficiency](https://arxiv.org/abs/2508.18265) **(Shanghai AI Lab)** | 25.8.25
- [InternVL3: Exploring Advanced Training and Test-Time Recipes for Open-Source Multimodal Models](https://arxiv.org/abs/2504.10479) **(Shanghai AI Lab)** | 25.4.14
- [Expanding Performance Boundaries of Open-Source Multimodal Models with Model, Data, and Test-Time Scaling](https://arxiv.org/abs/2412.05271) **(Shanghai AI Lab)** | 24.12.6
- [Mini-InternVL: A Flexible-Transfer Pocket Multimodal Model with 5% Parameters and 90% Performance](https://arxiv.org/abs/2410.16261) **(Shanghai AI Lab)** | 24.10.21
- [InternLM-XComposer-2.5: A Versatile Large Vision Language Model Supporting Long-Contextual Input and Output](https://arxiv.org/abs/2407.03320) **(Shanghai AI Lab)** | 24.7.3
- [How Far Are We to GPT-4V? Closing the Gap to Commercial Multimodal Models with Open-Source Suites](https://arxiv.org/abs/2404.16821) **(Shanghai AI Lab)** | 24.4.25
- [InternLM-XComposer2-4KHD: A Pioneering Large Vision-Language Model Handling Resolutions from 336 Pixels to 4K HD](https://arxiv.org/abs/2404.06512) **(Shanghai AI Lab)** | 24.4.9
- [InternLM2 Technical Report](https://arxiv.org/abs/2403.17297) **(Shanghai AI Lab)** | 24.3.26
- [InternLM-XComposer2: Mastering Free-form Text-Image Composition and Comprehension in Vision-Language Large Model](https://arxiv.org/abs/2401.16420) **(Shanghai AI Lab)** | 24.1.29
- [InternVL: Scaling up Vision Foundation Models and Aligning for Generic Visual-Linguistic Tasks](https://arxiv.org/abs/2312.14238) **(Shanghai AI Lab)** | 23.12.21
- [InternLM-XComposer: A Vision-Language Large Model for Advanced Text-image Comprehension and Composition](https://arxiv.org/abs/2309.15112) **(Shanghai AI Lab)** | 23.9.26
- [InternLM: A Multilingual Language Model with Progressively Enhanced Capabilities](https://github.com/InternLM/InternLM-techreport/blob/main/InternLM.pdf) **(Shanghai AI Lab)** | 23.6.3

</details>

<details open>
<summary>GPT</summary>

- [OpenAI GPT-5 System Card](https://arxiv.org/abs/2601.03267) **(OpenAI)** | 25.12.19
- [GPT-4o System Card](https://arxiv.org/abs/2410.21276) **(OpenAI)** | 24.10.25
- [GPT-4 Technical Report](https://arxiv.org/abs/2303.08774) **(OpenAI)** | 23.3.15

</details>

<details open>
<summary>Gemini</summary>

- [Gemini 2.5: Pushing the Frontier with Advanced Reasoning, Multimodality, Long Context, and Next Generation Agentic Capabilities](https://arxiv.org/abs/2507.06261) **(Google DeepMind)** | 25.7.7
- [Gemini 1.5: Unlocking multimodal understanding across millions of tokens of context](https://arxiv.org/abs/2403.05530) **(Google DeepMind)** | 24.3.8
- [Gemini: A Family of Highly Capable Multimodal Models](https://arxiv.org/abs/2312.11805) **(Google DeepMind)** | 23.12.19

</details>

<details open>
<summary>Gemma</summary>

- [Gemma 3 Technical Report](https://arxiv.org/abs/2503.19786) **(Google DeepMind)** | 25.3.25
- [PaliGemma 2: A Family of Versatile VLMs for Transfer](https://arxiv.org/abs/2412.03555) **(Google DeepMind)** | 24.12.4
- [PaliGemma: A versatile 3B VLM for transfer](https://arxiv.org/abs/2407.07726) **(Google DeepMind)** | 24.7.10

</details>

<details open>
<summary>Phi</summary>

- [Phi-4-reasoning-vision-15B Technical Report](https://arxiv.org/abs/2603.03975) **(Microsoft)** | 26.3.4
- [Phi-4-Mini Technical Report: Compact yet Powerful Multimodal Language Models via Mixture-of-LoRAs](https://arxiv.org/abs/2503.01743) **(Microsoft)** | 25.3.3
- [Phi-3 Technical Report: A Highly Capable Language Model Locally on Your Phone](https://arxiv.org/abs/2404.14219) **(Microsoft)** | 24.4.22

</details>

<details open>
<summary>DeepSeek</summary>

- [DeepSeek-VL2: Mixture-of-Experts Vision-Language Models for Advanced Multimodal Understanding](https://arxiv.org/abs/2412.10302) **(DeepSeek-AI)** | 24.12.13
- [DeepSeek-VL: Towards Real-World Vision-Language Understanding](https://arxiv.org/abs/2403.05525) **(DeepSeek-AI)** | 24.3.8

</details>

<details open>
<summary>Seed</summary>

- [Seed1.5-VL Technical Report](https://arxiv.org/abs/2505.07062) **(ByteDance)** | 25.5.11

</details>

<details open>
<summary>MM1</summary>

- [MM1.5: Methods, Analysis & Insights from Multimodal LLM Fine-tuning](https://arxiv.org/abs/2409.20566) **(Apple)** | 24.9.30
- [MM1: Methods, Analysis & Insights from Multimodal LLM Pre-training](https://arxiv.org/abs/2403.09611) **(Apple)** | 24.3.14

</details>

<details open>
<summary>Nova</summary>

- [The Amazon Nova Family of Models: Technical Report and Model Card](https://arxiv.org/abs/2506.12103) **(Amazon)** | 25.3.17

</details>

<details open>
<summary>Kimi</summary>

- [Kimi K2.5: Visual Agentic Intelligence](https://arxiv.org/abs/2602.02276) **(Moonshot AI)** | 26.2.2
- [Kimi-VL Technical Report](https://arxiv.org/abs/2504.07491) **(Moonshot AI)** | 25.4.10

</details>

<details open>
<summary>GLM-V</summary>

- [GLM-4.5V and GLM-4.1V-Thinking: Towards Versatile Multimodal Reasoning with Scalable Reinforcement Learning](https://arxiv.org/abs/2507.01006) **(Zhipu AI,THU)** | 25.7.1
- [CogVLM2: Visual Language Models for Image and Video Understanding](https://arxiv.org/abs/2408.16500) **(Zhipu AI,THU)** | 24.8.29
- [CogVLM: Visual Expert for Pretrained Language Models](https://arxiv.org/abs/2311.03079) **(Zhipu AI,THU)** | 23.11.6

</details>

<details open>
<summary>Kwai Keye</summary>

- [Kwai Keye-VL-2.0 Technical Report](https://arxiv.org/abs/2606.10651) **(Kuaishou)** | 26.6.9
- [Kwai Keye-VL 1.5 Technical Report](https://arxiv.org/abs/2509.01563) **(Kuaishou)** | 25.9.1
- [Kwai Keye-VL Technical Report](https://arxiv.org/abs/2507.01949) **(Kuaishou)** | 25.7.2

</details>

<details open>
<summary>LLaVA</summary>

- [LLaVA-UHD v4: What Makes Efficient Visual Encoding in MLLMs?](https://arxiv.org/abs/2605.08985) **(THU,ModelBest)** | 26.5.9
- [LLaVA-OneVision-1.5: Fully Open Framework for Democratized Multimodal Training](https://arxiv.org/abs/2509.23661) **(LLaVA Community)** | 25.9.28
- [LLaVA-OneVision: Easy Visual Task Transfer](https://arxiv.org/abs/2408.03326) **(ByteDance,NTU,CUHK,HKUST)** | 24.8.6
- [Improved Baselines with Visual Instruction Tuning](https://arxiv.org/abs/2310.03744) **(UWM,Microsoft)** | 23.10.5
- [Visual Instruction Tuning](https://arxiv.org/abs/2304.08485) **(UWM,Microsoft)** | 23.4.17

</details>

<details open>
<summary>MiMo</summary>

- [MiMo-VL Technical Report](https://arxiv.org/abs/2506.03569) **(Xiaomi)** | 25.6.4

</details>

<details open>
<summary>PaddleOCR</summary>

- [PaddleOCR-VL: Boosting Multilingual Document Parsing via a 0.9B Ultra-Compact Vision-Language Model](https://arxiv.org/abs/2510.14528) **(Baidu)** | 25.10.16

</details>

<details open>
<summary>HunyuanOCR</summary>

- [HunyuanOCR Technical Report](https://arxiv.org/abs/2511.19575) **(Tencent)** | 25.11.24

</details>




## 📑 Document Understanding


<details open>
<summary>2026</summary>

- [MonkeyOCRv2: A Visual-Text Foundation Model for Document AI](https://arxiv.org/abs/2607.11562) **(HUST)** | 26.7.13
- [HunyuanOCR-1.5: Making Lightweight OCR VLMs Faster and Better](https://arxiv.org/abs/2607.04884) **(Tencent)** | 26.7.6
- [Multimodal OCR: Parse Anything from Documents](https://arxiv.org/abs/2603.13032) **(HUST,Xiaohongshu)** | 26.3.13
- [Qianfan-OCR: A Unified End-to-End Model for Document Intelligence](https://arxiv.org/abs/2603.13398) **(Baidu)** | 26.3.11
- [GLM-OCR Technical Report](https://arxiv.org/abs/2603.10910) **(Zhipu AI,THU)** | 26.3.11
- [Dolphin-v2: Universal Document Parsing via Scalable Anchor Prompting](https://arxiv.org/abs/2602.05384) **(ByteDance)** | 26.2.5
- [PaddleOCR-VL-1.5: Towards a Multi-Task 0.9B VLM for Robust In-the-Wild Document Parsing](https://arxiv.org/abs/2601.21957) **(Baidu)** | 26.1.29
- [OCRVerse: Towards Holistic OCR in End-to-End Vision-Language Models](https://arxiv.org/abs/2601.21639) **(Meituan)** | 26.1.29
- [DeepSeek-OCR 2: Visual Causal Flow](https://arxiv.org/abs/2601.20552) **(DeepSeek-AI)** | 26.1.28

</details>


<details open>
<summary>2025</summary>


- [dots.ocr: Multilingual Document Layout Parsing in a Single Vision-Language Model](https://arxiv.org/abs/2512.02498) **(Xiaohongshu)** | 25.12.2
- [HunyuanOCR Technical Report](https://arxiv.org/abs/2511.19575) **(Tencent)** | 25.11.24
- [MonkeyOCR v1.5 Technical Report: Unlocking Robust Document Parsing for Complex Patterns](https://arxiv.org/abs/2511.10390) **(HUST)** | 25.11.13
- [DeepSeek-OCR: Contexts Optical Compression](https://arxiv.org/abs/2510.18234) **(DeepSeek-AI)** | 25.10.21
- [PaddleOCR-VL: Boosting Multilingual Document Parsing via a 0.9B Ultra-Compact Vision-Language Model](https://arxiv.org/abs/2510.14528) **(Baidu)** | 25.10.16
- [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://arxiv.org/abs/2509.22186) **(Shanghai AI Lab)** | 25.9.26
- [Logics-Parsing Technical Report](https://arxiv.org/abs/2509.19760) **(Alibaba)** | 25.9.24
- [POINTS-Reader: Distillation-Free Adaptation of Vision-Language Models for Document Conversion](https://arxiv.org/abs/2509.01215) **(Tencent)** | 25.9.1
- [DocThinker: Explainable Multimodal Large Language Models with Rule-based Reinforcement Learning for Document Understanding](https://arxiv.org/abs/2508.08589) **(HUST,Alibaba)** | 25.8.12
- [MonkeyOCR: Document Parsing with a Structure-Recognition-Relation Triplet Paradigm](https://arxiv.org/abs/2506.05218) **(HUST)** | 25.6.5
- [Dolphin: Document Image Parsing via Heterogeneous Anchor Prompting](https://arxiv.org/abs/2505.14059) **(ByteDance)** | 25.5.20
- [Towards Visual Text Grounding of Multimodal Large Language Model](https://www.arxiv.org/abs/2504.04974) **(Adobe,Maryland)** | 25.4.7
- [A Simple yet Effective Layout Token in Large Language Models for Document Understanding](https://arxiv.org/abs/2503.18434) **(ZJU,Alibaba)** | 25.3.24
- [MDocAgent: A Multi-Modal Multi-Agent Framework for Document Understanding](https://arxiv.org/abs/2503.13964) **(Adobe)** | 25.3.18
- [SmolDocling: An ultra-compact vision-language model for end-to-end multi-modal document conversion](https://arxiv.org/abs/2503.11576) **(IBM)** | 25.3.14
- [PP-DocBee: Improving Multimodal Document Understanding Through a Bag of Tricks](https://arxiv.org/abs/2503.04065) **(Baidu)** | 25.3.6
- [olmOCR: Unlocking Trillions of Tokens in PDFs with Vision Language Models](https://arxiv.org/abs/2502.18443) **(Allen AI)** | 25.2.25
- [Ocean-OCR: Towards General OCR Application via a Vision-Language Model](https://arxiv.org/abs/2501.15558) **(Baichuan)** | 25.1.26

</details>



<details open>
<summary>2024</summary>

- [DocVLM: Make Your VLM an Efficient Reader](https://arxiv.org/abs/2412.08746) **(AWS)** | 24.12.11
- [DocLayout-YOLO: Enhancing Document Layout Analysis through Diverse Synthetic Data and Global-to-Local Adaptive Perception](https://arxiv.org/abs/2410.12628) **(Shanghai AI Lab)** | 24.10.16
- [TextHawk2: A Large Vision-Language Model Excels in Bilingual OCR and Grounding with 16x Fewer Tokens](https://arxiv.org/abs/2410.05261) **(Huawei)** | 24.10.7 | arXiv | Code
- [DocKD: Knowledge Distillation from LLMs for Open-World Document Understanding Models](https://arxiv.org/abs/2410.03061) **(KAIST,AWS)** | 24.10.4 | arXiv | Code
- [MinerU: An Open-Source Solution for Precise Document Content Extraction](https://arxiv.org/abs/2409.18839) **(Shanghai AI Lab)** | 24.9.27
- [mPLUG-DocOwl2: High-resolution Compressing for OCR-free Multi-page Document Understanding](https://arxiv.org/abs/2409.03420) **(Alibaba,RUC)** | 24.9.5 | arXiv | [Code](https://github.com/X-PLUG/mPLUG-DocOwl/tree/main/DocOwl2)
- [General OCR Theory: Towards OCR-2.0 via a Unified End-to-end Model](https://arxiv.org/abs/2409.01704) **(StepFun,Megvii,UCAS,THU)** | 24.9.3 | arXiv | [Code](https://github.com/Ucas-HaoranWei/GOT-OCR2.0)
- [Docling Technical Report](https://arxiv.org/abs/2408.09869) **(IBM)** | 24.8.19
- [Mini-Monkey: Alleviating the Semantic Sawtooth Effect for Lightweight MLLMs via Complementary Image Pyramid](https://arxiv.org/abs/2408.02034) **(HUST,SCUT)** | 24.8.4
- [LLaVA-Read: Enhancing Reading Ability of Multimodal Language Models](https://arxiv.org/abs/2407.19185) **(Adobe,Buffalo)** | 24.7.27 | arXiv | Code
- [Harmonizing Visual Text Comprehension and Generation](https://arxiv.org/abs/2407.16364) **(ECNU,ByteDance)** | 24.7.23 | 24NIPS | Code
- [A Bounding Box is Worth One Token: Interleaving Layout and Text in a Large Language Model for Document Understanding](https://arxiv.org/abs/2407.01976) **(FDU,ByteDance)** | 24.7.2 | arXiv | Code
- [DocKylin: A Large Multimodal Model for Visual Document Understanding with Efficient Visual Slimming](https://arxiv.org/abs/2406.19101) **(SCUT)** | 24.6.27
- [Multimodal Table Understanding](https://arxiv.org/abs/2406.08100) **(UCAS,Baidu)** | 24.06.12 | ACL24 | [Code](https://github.com/SpursGoZmy/Table-LLaVA)
- [TRINS: Towards Multimodal Language Models that Can Read](https://arxiv.org/abs/2406.06730) **(Adobe,GIT)** | 24.06.10 | CVPR24 | Code
- [TabPedia: Towards Comprehensive Visual Table Understanding with Concept Synergy](https://arxiv.org/abs/2406.01326) **(USTC,ByteDance)** | 24.6.3 | arXiv | [Code](https://huggingface.co/datasets/ByteDance/ComTQA)
- [StrucTexTv3: An Efficient Vision-Language Model for Text-rich Image Perception, Comprehension, and Beyond](https://arxiv.org/abs/2405.21013) **(Baidu)** | 24.5.31 | arXiv | Code
- [Focus Anywhere for Fine-grained Multi-page Document Understanding](https://arxiv.org/abs/2405.14295) **(UCAS,MEGVII)** | 24.5.23 | arXiv | [Code](https://github.com/ucaslcl/Fox)
- [MTVQA: Benchmarking Multilingual Text-Centric Visual Question Answering](https://arxiv.org/abs/2405.11985) **(ByteDance,HUST)** | 24.5.20 | arXiv | [Code](https://github.com/bytedance/MTVQA)
- [Exploring the Capabilities of Large Multimodal Models on Dense Text](https://arxiv.org/abs/2405.06706) **(HUST)** | 24.5.9 | arXiv | [Code](https://github.com/Yuliang-Liu/MultimodalOCR)
- [How Far Are We to GPT-4V? Closing the Gap to Commercial Multimodal Models with Open-Source Suites](https://arxiv.org/abs/2404.16821) **(Shanghai AI Lab,CUHK,THU,NJU,FDU,SenseTime)** | 24.4.25 | arXiv | [Code](https://github.com/OpenGVLab/InternVL)
- [TextCoT: Zoom In for Enhanced Multimodal Text-Rich Image Understanding](https://arxiv.org/abs/2404.09797) **(USTC)** | 24.4.15 | arXiv | [Code](https://github.com/bzluan/TextCoT)
- [HRVDA: High-Resolution Visual Document Assistant](https://arxiv.org/abs/2404.06918) **(Tencent YouTu Lab,USTC)** | 24.4.10 | CVPR24
- [InternLM-XComposer2-4KHD: A Pioneering Large Vision-Language Model Handling Resolutions from 336 Pixels to 4K HD](https://arxiv.org/abs/2404.06512) **(Shanghai AI Lab,CUHK,THU,SenseTime)** | 24.4.9 | arXiv | [Code](https://github.com/InternLM/InternLM-XComposer)
- [LayoutLLM: Layout Instruction Tuning with Large Language Models for Document Understanding](https://arxiv.org/abs/2404.05225) **(Alibaba,ZJU)** | 24.4.8 | arXiv | Code
- [Visual CoT: Unleashing Chain-of-Thought Reasoning in Multi-Modal Language Models](https://arxiv.org/abs/2403.16999) **(CUHK,Shanghai AI Lab,SenseTime)** | 24.3.25 | arXiv | [Code](https://github.com/deepcs233/Visual-CoT)
- [mPLUG-DocOwl 1.5: Unified Structure Learning for OCR-free Document Understanding](https://arxiv.org/abs/2403.12895) **(Alibaba,RUC)** | 24.3.19 | arXiv | [Code](https://github.com/X-PLUG/mPLUG-DocOwl/tree/main/DocOwl1.5)
- [TextMonkey: An OCR-Free Large Multimodal Model for Understanding Document](https://arxiv.org/abs/2403.04473) **(HUST)** | 24.3.7 | arXiv | [Code](https://github.com/Yuliang-Liu/Monkey)
- [Enhancing Visual Document Understanding with Contrastive Learning in Large Visual-Language Models](https://arxiv.org/abs/2402.19014) **(Tencent YouTu Lab)** | 24.2.29 | CVPR24
- [InternLM-XComposer2: Mastering Free-form Text-Image Composition and Comprehension in Vision-Language Large Model](https://arxiv.org/abs/2401.16420) **(Shanghai AI Lab,CUHK,SenseTime)** | 24.1.29 | arXiv | [Code](https://github.com/InternLM/InternLM-XComposer)
- [Small Language Model Meets with Reinforced Vision Vocabulary](https://arxiv.org/abs/2401.12503) **(MEGVII,UCAS,HUST)** | 24.1.23 | arXiv | [Code](https://github.com/Ucas-HaoranWei/Vary-toy)

</details>


<details open>
<summary>2023</summary>

- [DocLLM: A layout-aware generative language model for multimodal document understanding](https://arxiv.org/abs/2401.00908) **(JPMorgan AI Research)** | 23.12.31 | arXiv
- [Vary: Scaling up the Vision Vocabulary for Large Vision-Language Models](https://arxiv.org/abs/2312.06109) **(MEGVII,UCAS,HUST)** | 23.12.11 | ECCV24 | [Code](https://github.com/Ucas-HaoranWei/Vary)
- [mPLUG-PaperOwl: Scientific Diagram Analysis with the Multimodal Large Language Model](https://arxiv.org/abs/2311.18248) **(Alibaba)** | 23.11.30  | arXiv | [Code](https://github.com/X-PLUG/mPLUG-DocOwl/tree/main)
- [Towards Improving Document Understanding: An Exploration on Text-Grounding via MLLMs](https://arxiv.org/abs/2311.13194) **(USTC)** | 23.11.22 | arXiv | [Code](https://github.com/harrytea/TGDoc)
- [DocPedia: Unleashing the Power of Large Multimodal Model in the Frequency Domain for Versatile Document Understanding](https://arxiv.org/abs/2311.11810) **(USTC,ByteDance)** | 23.11.20 | arXiv
- [Monkey: Image Resolution and Text Label Are Important Things for Large Multi-modal Models](https://arxiv.org/abs/2311.06607) **(HUST)** | 23.11.11 | CVPR24 | [Code](https://github.com/Yuliang-Liu/Monkey)
- [mPLUG-Owl2: Revolutionizing Multi-modal Large Language Model with Modality Collaboration](https://arxiv.org/abs/2311.04257) **(Alibaba)** | 23.11.07 | CVPR24 | [Code](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2)
- [Exploring OCR Capabilities of GPT-4V(ision) : A Quantitative and In-depth Evaluation](https://arxiv.org/abs/2310.16809) **(SCUT)** | 23.10.25 | arXiv | [Code](https://github.com/SCUT-DLVCLab/GPT-4V_OCR)
- [UReader: Universal OCR-free Visually-situated Language Understanding with Multimodal Large Language Model](https://arxiv.org/abs/2310.05126) **(DAMO,RUC,ECNU)** | 23.10.08 | arXiv | [Code](https://github.com/LukeForeverYoung/UReader)
- [Kosmos-2.5: A Multimodal Literate Model](https://arxiv.org/abs/2309.11419) **(MSRA)** | 23.9.20 | arXiv | [Code](https://thegenerality.com/agi/)
- [Nougat: Neural Optical Understanding for Academic Documents](https://arxiv.org/abs/2308.13418) **(Meta)** | 23.8.25
- [BLIVA: A Simple Multimodal LLM for Better Handling of Text-Rich Visual Questions](https://arxiv.org/abs/2308.09936) **(UC San Diego)** | 23.8.19 | AAAI24 | [Code](https://github.com/mlpc-ucsd/BLIVA)
- [UniDoc: A Universal Large Multimodal Model for Simultaneous Text Detection, Recognition, Spotting and Understanding](https://arxiv.org/abs/2308.11592) **(USTC,ByteDance)** | 23.8.19 | arXiv
- [mPLUG-DocOwl: Modularized Multimodal Large Language Model for Document Understanding](https://arxiv.org/abs/2307.02499) **(DAMO)** | 23.7.4 | arXiv | [Code](https://github.com/X-PLUG/mPLUG-DocOwl)
- [LLaVAR: Enhanced Visual Instruction Tuning for Text-Rich Image Understanding](https://arxiv.org/abs/2306.17107) **(Adobe,Stanford)** | 23.6.29
- [Document Understanding Dataset and Evaluation (DUDE)](https://arxiv.org/abs/2305.08455) | 23.5.15 | arXiv | [Website](https://rrc.cvc.uab.es/?ch=23)
- [On the Hidden Mystery of OCR in Large Multimodal Models](https://arxiv.org/abs/2305.07895) **(HUST,SCUT,Microsoft)** | 23.5.13 | arXiv | [Code](https://github.com/Yuliang-Liu/MultimodalOCR)
- [Visual Information Extraction in the Wild: Practical Dataset and End-to-end Solution](https://arxiv.org/abs/2305.07498) **(HUST)** | 23.5.12 | arXiv | [Code](https://github.com/jfkuang/CFAM)
- [StrucTexTv2: Masked Visual-Textual Prediction for Document Image Pre-training](https://arxiv.org/abs/2303.00289) **(Baidu)** | 23.03.01 | ICLR23 | [Code](https://github.com/PaddlePaddle/VIMER/tree/main/StrucTexT)

</details>

<details open>
<summary>2022</summary>

- [Wukong-Reader: Multi-modal Pre-training for Fine-grained Visual Document Understanding](https://arxiv.org/abs/2212.09621) **(Huawei)** | 22.12.19 | ACL23
- [Unifying Vision, Text, and Layout for Universal Document Processing](https://arxiv.org/abs/2212.02623) **(Microsoft)** | 22.12.05 | CVPR23 | [Code](https://github.com/microsoft/i-Code/tree/main/i-Code-Doc)
- [ERNIE-Layout: Layout Knowledge Enhanced Pre-training for Visually-rich Document Understanding](https://arxiv.org/abs/2210.06155) **(Baidu)** | 22.10.12 | arXiv | [Code](https://github.com/PaddlePaddle/PaddleNLP/tree/develop/model_zoo/ernie-layout)
- [Pix2Struct: Screenshot Parsing as Pretraining for Visual Language Understanding](https://arxiv.org/abs/2210.03347) **(Google)** | 22.10.7
- [Unified Pretraining Framework for Document Understanding](https://arxiv.org/abs/2204.10939) **(Adobe)** | 22.04.22 | NIPS21
- [LayoutLMv3: Pre-training for Document AI with Unified Text and Image Masking](https://arxiv.org/abs/2204.08387) **(Microsoft)** | 22.04.18 | ACM MM22 | [Code](https://github.com/microsoft/unilm/tree/master/layoutlmv3)
- [XYLayoutLM: Towards Layout-Aware Multimodal Networks For Visually-Rich Document Understanding](https://arxiv.org/abs/2203.06947) **(Alibaba)** | 22.3.14 | [Code Unofficial](https://github.com/Sanster/xy-cut)
- [DiT: Self-supervised Pre-training for Document Image Transformer](https://arxiv.org/abs/2203.02378) **(Microsoft)** | 22.03.04 | ACM MM22 | [Code](https://github.com/microsoft/unilm/tree/master/dit)
- [Wukong: A 100 Million Large-scale Chinese Cross-modal Pre-training Benchmark](https://arxiv.org/abs/2202.06767) **(Huawei)** | 22.2.14 | NIPS22 | [Code](https://wukong-dataset.github.io/wukong-dataset/)

</details>


<details open>
<summary>2021</summary>

- [OCR-free Document Understanding Transformer](https://arxiv.org/abs/2111.15664) **(NAVER CLOVA)** | 21.11.30
- [LayoutReader: Pre-training of Text and Layout for Reading Order Detection](https://arxiv.org/abs/2108.11591) **(Microsoft)** | 21.08.26 | EMNLP21 | [Code](https://github.com/microsoft/unilm/tree/master/layoutreader)
- [DocFormer: End-to-End Transformer for Document Understanding](https://arxiv.org/abs/2106.11539) **(Amazon)** | 21.6.22
- [LayoutXLM: Multimodal Pre-training for Multilingual Visually-rich Document Understanding](https://arxiv.org/abs/2104.08836) **(Microsoft)** | 21.04.18 | arXiv | [Code](https://github.com/microsoft/unilm/tree/master/layoutxlm)
- [Going Full-TILT Boogie on Document Understanding with Text-Image-Layout Transformer](https://arxiv.org/abs/2102.09550) **(Applica)** | 21.02.18 | ICDAR21 | [Code](https://github.com/uakarsh/TiLT-Implementation)

</details>


<details open>
<summary>2020</summary>

- [LayoutLMv2: Multi-modal Pre-training for Visually-rich Document Understanding](https://arxiv.org/abs/2012.14740) **(Microsoft)** | 20.12.29 | arXiv | [Code](https://github.com/microsoft/unilm/tree/master/layoutlmv2)

</details>

<details open>
<summary>2019</summary>
  
- [LayoutLM: Pre-training of Text and Layout for Document Image Understanding](https://arxiv.org/abs/1912.13318) **(Microsoft)** | 19.12.31 | KDD20 | [Code](https://github.com/microsoft/unilm/tree/master/layoutlm)

</details>

## 🔮 MLLM


<details open>
<summary>2025</summary>

- [VLM-R1: A Stable and Generalizable R1-style Large Vision-Language Model](https://arxiv.org/abs/2504.04974) **(ZJU,Om AI)** | 25.4.10
- [Open-Qwen2VL: Compute-Efficient Pre-Training of Fully-Open Multimodal LLMs on Academic Resources](https://arxiv.org/abs/2504.00595) **(UCSB,ByteDance,Nvidia)** | 25.4.1 
- [R1-VL: Learning to Reason with Multimodal Large Language Models via Step-wise Group Relative Policy Optimization](https://arxiv.org/abs/2503.12937) **(NTU,THU)** | 25.3.17
- [R1-Onevision: Advancing Generalized Multimodal Reasoning through Cross-Modal Formalization](https://arxiv.org/abs/2503.10615) **(ZJU,RUC,Tencent)** | 25.3.13
- [Oasis: One Image is All You Need for Multimodal Instruction Data Synthesis](https://arxiv.org/abs/2503.08741) **(TJU,ByteDance)** | 25.3.11
- [LMM-R1: Empowering 3B LMMs with Strong Reasoning Abilities Through Two-Stage Rule-Based RL](https://arxiv.org/abs/2503.07536) **(CUHK,FDU,Ant Group)** | 25.3.10
- [Vision-R1: Incentivizing Reasoning Capability in Multimodal Large Language Models](https://arxiv.org/abs/2503.06749) **(ECNU,Xionghongshu)** | 25.3.9

</details>

<details open>
<summary>2024</summary>

- [FastVLM: Efficient Vision Encoding for Vision Language Models](https://arxiv.org/abs/2412.13303) **(Apple)** | 24.12.17
- [OmniVLM: A Token-Compressed, Sub-Billion-Parameter Vision-Language Model for Efficient On-Device Inference](https://arxiv.org/abs/2412.11475) **(NexaAI)** | 24.12.16
- [Improving Multi-modal Large Language Model through Boosting Vision Capabilities](https://arxiv.org/abs/2410.13733) **(NJUST,Baidu,HUST)** | 24.10.17
- [Molmo and PixMo: Open Weights and Open Data for State-of-the-Art Vision-Language Models](https://arxiv.org/abs/2409.17146) **(Allen,UW)** | 24.9.25
- [LLaVA-OneVision: Easy Visual Task Transfer](https://arxiv.org/abs/2408.03326) **(ByteDance,NTU,CUHK,HKUST)** | 24.8.6
- [MiniCPM-V: A GPT-4V Level MLLM on Your Phone](https://arxiv.org/abs/2408.01800) **(OpenBMB)** | 24.8.3
- [Cambrian-1: A Fully Open, Vision-Centric Exploration of Multimodal LLMs](https://arxiv.org/abs/2406.16860) **(NYU)** | 24.6.24
- [X-VILA: Cross-Modality Alignment for Large Language Model](https://arxiv.org/abs/2405.19335) **(NVIDIA,HKUST,MIT)** | 24.5.29 | arXiv | Code
- [How Far Are We to GPT-4V? Closing the Gap to Commercial Multimodal Models with Open-Source Suites](https://arxiv.org/abs/2404.16821) **(Shanghai AI Lab,SenseTime,THU,NJU,FU,CUHK)** | 24.04.25 | arXiv | [Code](https://github.com/OpenGVLab/InternVL)
- [MiniCPM: Unveiling the Potential of Small Language Models with Scalable Training Strategies](https://arxiv.org/abs/2404.06395) **(THU,ModelBest)** | 24.4.9
- [Mini-Gemini: Mining the Potential of Multi-modality Vision Language Models](https://arxiv.org/abs/2403.18814) **(CUHK,SmartMore)** | 24.3.27 | [Code](https://github.com/dvlab-research/MGM)
- [LLaVA-UHD: an LMM Perceiving Any Aspect Ratio and High-Resolution Images](https://arxiv.org/abs/2403.11703) **(THU,NUS,UCAS)** | 24.03.18 | arXiv | [Code](https://github.com/thunlp/LLaVA-UHD)
- [Feast Your Eyes: Mixture-of-Resolution Adaptation for Multimodal Large Language Models](https://arxiv.org/abs/2403.03003) **(XMU)** | 24.03.05 | arXiv | [Code](https://github.com/luogen1996/LLaVA-HR)
- [DualFocus: Integrating Macro and Micro Perspectives in Multi-modal Large Language Models](https://arxiv.org/abs/2402.14767) **(CUHK,Shanghai AI Lab)** | 24.2.22 | arXiv | [Code](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/DualFocus)
- [InternLM-XComposer2: Mastering Free-form Text-Image Composition and Comprehension in Vision-Language Large Model](https://arxiv.org/abs/2401.16420) **(Shanghai AI Lab)** | 24.01.29 | arXiv | [Code](https://github.com/InternLM/InternLM-XComposer)

</details>



<details open>
<summary>2023</summary>

- [InternVL: Scaling up Vision Foundation Models and Aligning for Generic Visual-Linguistic Tasks](https://arxiv.org/abs/2312.14238) **(OpenGVLab,NJU,HKU,CUHK,THU,USTC,SenseTime)** | 23.12.21 | CVPR24 | [Code](https://github.com/OpenGVLab/InternVL)
- [ViP-LLaVA: Making Large Multimodal Models Understand Arbitrary Visual Prompts](https://arxiv.org/abs/2312.00784) **(UWM,Cruise LLC)** | 23.12.01 | CVPR24 | [Code](https://github.com/WisconsinAIVision/ViP-LLaVA)
- [ShareGPT4V: Improving Large Multi-Modal Models with Better Captions](https://arxiv.org/abs/2311.12793) **(USTC,Shanghai AI Lab)** | 23.11.28 | arXiv | [Code](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V)
- [MiniGPT-v2: large language model as a unified interface for vision-language multi-task learning](https://arxiv.org/abs/2310.09478) **(KAUST,Meta)** | 23.10.14 | arXiv | [Code](https://github.com/Vision-CAIR/MiniGPT-4)
- [Improved Baselines with Visual Instruction Tuning](https://arxiv.org/abs/2310.03744) **(UWM,Microsoft)** | 23.10.05 | arXiv | [Code](https://github.com/haotian-liu/LLaVA)
- [InternLM-XComposer: A Vision-Language Large Model for Advanced Text-image Comprehension and Composition](https://arxiv.org/abs/2309.15112) **(Shanghai AI Lab)** | 23.02.26 | arXiv | [Code](https://github.com/InternLM/InternLM-XComposer)
- [Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond](https://arxiv.org/abs/2308.12966) **(Alibaba)** | 23.08.24 | arXiv | [Code](https://github.com/QwenLM/Qwen-VL)
- [MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action](https://arxiv.org/abs/2303.11381) **(Azure)** | 23.05.20 | arXiv | [Code](https://github.com/microsoft/MM-REACT)
- [InstructBLIP: Towards General-purpose Vision-Language Models with Instruction Tuning](https://arxiv.org/abs/2305.06500) **(Salesforce)** | 23.05.11 | arXiv | [Code](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip)
- [mPLUG-Owl: Modularization Empowers Large Language Models with Multimodality](https://arxiv.org/abs/2304.14178) **(DAMO)** | 23.04.27 | arXiv | [Code](https://github.com/X-PLUG/mPLUG-Owl)
- [MiniGPT-4: Enhancing Vision-Language Understanding with Advanced Large Language Models](https://arxiv.org/abs/2304.10592) **(KAUST)** | 23.04.20 | arXiv | [Code](https://github.com/Vision-CAIR/MiniGPT-4)
- [Visual Instruction Tuning](https://arxiv.org/abs/2304.08485) **(UWM,Microsoft)** | 23.04.17 | NeurIPS | [Code](https://github.com/haotian-liu/LLaVA)
- [BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models](https://arxiv.org/abs/2301.12597) **(Salesforce)** | 23.01.30 | arXiv | [Code](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)

</details>


<details open>
<summary>2022</summary>

- [Flamingo: a Visual Language Model for Few-Shot Learning](https://arxiv.org/abs/2204.14198) **(Deepmind)** | 22.11.15 | Nips22 | Code

</details>



## 🎯 Grounded MLLM

<details open>
<summary>2024</summary>

- [SpatialRGPT: Grounded Spatial Reasoning in Vision Language Model](https://arxiv.org/abs/2406.01584) **(UCSD,HKU,NVIDIA)** | 24.6.3 | arXiv | [Code](https://www.anjiecheng.me/SpatialRGPT)
- [Groma: Localized Visual Tokenization for Grounding Multimodal Large Language Models](https://arxiv.org/abs/2404.13013) **(HKU,ByteDance)** | 24.4.19 | ECCV24 | [Code](https://github.com/FoundationVision/Groma)
- [Ferret-v2: An Improved Baseline for Referring and Grounding with Large Language Models](https://arxiv.org/abs/2404.07973) **(CU,UCSB,Apple)** | 24.04.11 | arXiv | Code
- [SpatialPIN: Enhancing Spatial Reasoning Capabilities of Vision-Language Models through Prompting and Interacting 3D Priors](https://arxiv.org/abs/2403.13438) **(University of Oxford)** | 24.3.18
- [Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs](https://arxiv.org/abs/2404.05719) **(Apple)** | 24.04.08 | arXiv | Code
- [GroundingGPT: Language Enhanced Multi-modal Grounding Model](https://arxiv.org/abs/2401.06071) **(ByteDance,FDU)** | 24.03.05 | arXiv | [Code](https://github.com/lzw-lzw/GroundingGPT)

</details>


<details open>
<summary>2023</summary>

- [LLaVA-Grounding: Grounded Visual Chat with Large Multimodal Models](https://arxiv.org/abs/2312.02949) **(HKUST,SCUT,IDEA,CUHK)** | 23.12.05 | arXiv | [Code](https://github.com/UX-Decoder/LLaVA-Grounding)
- [Ferret: Refer and Ground Anything Anywhere at Any Granularity](https://arxiv.org/abs/2310.03744) **(CU,Apple)** | 23.10.11 | arXiv | [Code](https://github.com/apple/ml-ferret)
- [BuboGPT: Enabling Visual Grounding in Multi-Modal LLMs](https://arxiv.org/abs/2307.08581) **(ByteDance)** | 23.07.17 | arXiv | [Code](https://github.com/magic-research/bubogpt)
- [Shikra: Unleashing Multimodal LLM's Referential Dialogue Magic](https://arxiv.org/abs/2306.15195) **(SenseTime,BUAA,SJTU)** | 23.06.27 | arXiv | [Code](https://github.com/shikras/shikra)
- [Kosmos-2: Grounding Multimodal Large Language Models to the World](https://arxiv.org/abs/2306.14824) **(Microsoft)** | 23.06.26 | arXiv | [Code](https://github.com/microsoft/unilm/tree/master/kosmos-2)

</details>



## 🎬 Video LLM


<details open>
<summary>2024</summary>

- [Artemis: Towards Referential Understanding in Complex Videos](https://arxiv.org/abs/2406.00258) **(UCAS,UB)** | 24.6.1 | arXiv | [Code](https://github.com/qiujihao19/Artemis)

</details>


<details open>
<summary>2023</summary>

- [TimeChat: A Time-sensitive Multimodal Large Language Model for Long Video Understanding](https://arxiv.org/abs/2312.02051) **(PKU,Noah)** | 23.12.04  | CVPR24 | [Code](https://github.com/RenShuhuai-Andy/TimeChat)
- [Video-Bench: A Comprehensive Benchmark and Toolkit for Evaluating Video-based Large Language Models](https://arxiv.org/abs/2311.16103) **(PKU,PengCheng,Microsoft,FarReel)** | 23.11.27 | arXiv | [Code](https://github.com/PKU-YuanGroup/Video-Bench)
- [Video-LLaVA: Learning United Visual Representation by Alignment Before Projection](https://arxiv.org/abs/2311.10122) **(PKU,PengCheng)** | 23.11.16 | arXiv | [code](https://github.com/PKU-YuanGroup/Video-LLaVA)
- [Chat-UniVi: Unified Visual Representation Empowers Large Language Models with Image and Video Understanding](https://arxiv.org/abs/2311.08046) **(PKU,PengCheng)** | 23.11.14  | arXiv | [Code](https://github.com/PKU-YuanGroup/Chat-UniVi)
- [Video-LLaMA: An Instruction-tuned Audio-Visual Language Model for Video Understanding](https://arxiv.org/abs/2306.02858) **(DAMO)** | 23.06.05 | arXiv | [code](https://github.com/DAMO-NLP-SG/Video-LLaMA)

</details>
