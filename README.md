# Awesome-Multimodal-Large-Language-Models

<img src="./images/xmind.png" width="96%" height="96%">

## Our MLLM works

🔥🔥🔥 **A Survey on Multimodal Large Language Models**  
**[Project Page [This Page]](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models)** | **[Paper](https://arxiv.org/pdf/2306.13549.pdf)**

The first survey for Multimodal Large Language Models (MLLMs). :sparkles: 

Welcome to add WeChat ID (wmd_ustc) to join our MLLM communication group! :star2:

---

🔥🔥🔥 **MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models**  
**[Project Page [Leaderboards]](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation)** | **[Paper](https://arxiv.org/pdf/2306.13394.pdf)**

The first comprehensive evaluation benchmark for MLLMs. Now the leaderboards include **53** advanced models, such as Qwen-VL-Max, Gemini Pro, and GPT-4V. :sparkles:

If you want to add your model in our leaderboards, please feel free to email bradyfu24@gmail.com. We will update the leaderboards in time. :sparkles:

<details><summary>Download MME :star2::star2: </summary>

The benchmark dataset is collected by Xiamen University for academic research only. You can email yongdongluo@stu.xmu.edu.cn to obtain the dataset, according to the following requirement. 

**Requirement**: A real-name system is encouraged for better academic communication. Your email suffix needs to match your affiliation, such as xx@stu.xmu.edu.cn and Xiamen University. Otherwise, you need to explain why. Please include the information bellow when sending your application email.

```
Name: (tell us who you are.)
Affiliation: (the name/url of your university or company)
Job Title: (e.g., professor, PhD, and researcher)
Email: (your email address)
How to use: (only for non-commercial use)
```

</details>

---

🔥🔥🔥 **Woodpecker: Hallucination Correction for Multimodal Large Language Models**  
**[Paper](https://arxiv.org/pdf/2310.16045.pdf)** | **[Online Demo](https://deb6a97bae6fab67ae.gradio.live/)** | **[Source Code![Star](https://img.shields.io/github/stars/BradyFU/Woodpecker.svg?style=social&label=Star)](https://github.com/BradyFU/Woodpecker)**

The first work to correct hallucinations in MLLMs. :sparkles:

---

🔥🔥🔥 **A Challenger to GPT-4V? Early Explorations of Gemini in Visual Expertise**  
<p align="center">
    <img src="./images/gemini_vs_gpt.png" width="50%" height="50%">
</p>  

<font size=7><div align='center' > :apple: \[[Read our arXiv Paper](https://arxiv.org/pdf/2312.12436.pdf)\] </div></font>

<div align='center'> The first technical report for <b>Gemini vs GPT-4V</b>. A total of <b>128 pages</b>. :sparkles: </div>  
<div align='center'> Completed within one week of the Gemini API opening. :star2: </div>

---

<br> **📑 If you find our projects helpful to your research, please consider citing:** <br>
```
@article{yin2023survey,
  title={A Survey on Multimodal Large Language Models},
  author={Yin, Shukang and Fu, Chaoyou and Zhao, Sirui and Li, Ke and Sun, Xing and Xu, Tong and Chen, Enhong},
  journal={arXiv preprint arXiv:2306.13549},
  year={2023}
}

@article{fu2023mme,
  title={MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models},
  author={Fu, Chaoyou and Chen, Peixian and Shen, Yunhang and Qin, Yulei and Zhang, Mengdan and Lin, Xu and Yang, Jinrui and Zheng, Xiawu and Li, Ke and Sun, Xing and Wu, Yunsheng and Ji, Rongrong},
  journal={arXiv preprint arXiv:2306.13394},
  year={2023}
}

@article{yin2023woodpecker,
  title={Woodpecker: Hallucination Correction for Multimodal Large Language Models},
  author={Yin, Shukang and Fu, Chaoyou and Zhao, Sirui and Xu, Tong and Wang, Hao and Sui, Dianbo and Shen, Yunhang and Li, Ke and Sun, Xing and Chen, Enhong},
  journal={arXiv preprint arXiv:2310.16045},
  year={2023}
}

@article{fu2023gemini,
  title={A Challenger to GPT-4V? Early Explorations of Gemini in Visual Expertise},
  author={Fu, Chaoyou and Zhang, Renrui and Wang, Zihan and Huang, Yubo and Zhang, Zhengye and Qiu, Longtian and Ye, Gaoxiang and Shen, Yunhang and Zhang, Mengdan and Chen, Peixian and Zhao, Sirui and Lin, Shaohui and Jiang, Deqiang and Yin, Di and Gao, Peng and Li, Ke and Li, Hongsheng and Sun, Xing},
  journal={arXiv preprint arXiv:2312.12436},
  year={2023}
}
```

 

---

<font size=5><center><b> Table of Contents </b> </center></font>
- [Awesome Papers](#awesome-papers)
  - [Multimodal Instruction Tuning](#multimodal-instruction-tuning)
  - [Multimodal In-Context Learning](#multimodal-in-context-learning)
  - [Multimodal Chain-of-Thought](#multimodal-chain-of-thought)
  - [LLM-Aided Visual Reasoning](#llm-aided-visual-reasoning)
  - [Foundation Models](#foundation-models)
  - [Evaluation](#evaluation)
  - [Multimodal Hallucination](#multimodal-hallucination)
  - [Multimodal RLHF](#multimodal-rlhf)
  - [Others](#others)
- [Awesome Datasets](#awesome-datasets)
  - [Datasets of Pre-Training for Alignment](#datasets-of-pre-training-for-alignment)
  - [Datasets of Multimodal Instruction Tuning](#datasets-of-multimodal-instruction-tuning)
  - [Datasets of In-Context Learning](#datasets-of-in-context-learning)
  - [Datasets of Multimodal Chain-of-Thought](#datasets-of-multimodal-chain-of-thought)
  - [Datasets of Multimodal RLHF](#datasets-of-multimodal-rlhf)
  - [Benchmarks for Evaluation](#benchmarks-for-evaluation)
  - [Others](#others-1)
---

# Awesome Papers

## Multimodal Instruction Tuning
|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![Star](https://img.shields.io/github/stars/Meituan-AutoML/MobileVLM.svg?style=social&label=Star) <br> [**MobileVLM V2: Faster and Stronger Baseline for Vision Language Model**](https://arxiv.org/pdf/2402.03766.pdf) <br> | arXiv | 2024-02-06 | [Github](https://github.com/Meituan-AutoML/MobileVLM) | - |
| [**Enhancing Multimodal Large Language Models with Vision Detection Models: An Empirical Study**](https://arxiv.org/pdf/2401.17981.pdf) | arXiv | 2024-01-31 | [Coming soon]() | - |
| ![Star](https://img.shields.io/github/stars/PKU-YuanGroup/MoE-LLaVA.svg?style=social&label=Star) <br> [**MoE-LLaVA: Mixture of Experts for Large Vision-Language Models**](https://arxiv.org/pdf/2401.15947.pdf) <br> | arXiv | 2024-01-29 | [Github](https://github.com/PKU-YuanGroup/MoE-LLaVA) | [Demo](https://huggingface.co/spaces/LanguageBind/MoE-LLaVA) |
| ![Star](https://img.shields.io/github/stars/InternLM/InternLM-XComposer.svg?style=social&label=Star) <br> [**InternLM-XComposer2: Mastering Free-form Text-Image Composition and Comprehension in Vision-Language Large Model**](https://arxiv.org/pdf/2401.16420.pdf) <br> | arXiv | 2024-01-29 | [Github](https://github.com/InternLM/InternLM-XComposer) | [Demo](https://openxlab.org.cn/apps/detail/WillowBreeze/InternLM-XComposer) |
| ![Star](https://img.shields.io/github/stars/01-ai/Yi.svg?style=social&label=Star) <br> [**Yi-VL**](https://github.com/01-ai/Yi/tree/main/VL) <br> | - | 2024-01-23 | [Github](https://github.com/01-ai/Yi/tree/main/VL) | Local Demo |
| [**SpatialVLM: Endowing Vision-Language Models with Spatial Reasoning Capabilities**](https://arxiv.org/pdf/2401.12168.pdf) | arXiv | 2024-01-22 | - | - |
| ![Star](https://img.shields.io/github/stars/Meituan-AutoML/MobileVLM.svg?style=social&label=Star) <br> [**MobileVLM : A Fast, Reproducible and Strong Vision Language Assistant for Mobile Devices**](https://arxiv.org/pdf/2312.16886.pdf) <br> | arXiv | 2023-12-28 | [Github](https://github.com/Meituan-AutoML/MobileVLM) | - | 
| ![Star](https://img.shields.io/github/stars/OpenGVLab/InternVL.svg?style=social&label=Star) <br> [**InternVL: Scaling up Vision Foundation Models and Aligning for Generic Visual-Linguistic Tasks**](https://arxiv.org/pdf/2312.14238.pdf) <br> | arXiv | 2023-12-21 | [Github](https://github.com/OpenGVLab/InternVL) | [Demo](https://internvl.opengvlab.com) |
| ![Star](https://img.shields.io/github/stars/CircleRadon/Osprey.svg?style=social&label=Star) <br> [**Osprey: Pixel Understanding with Visual Instruction Tuning**](https://arxiv.org/pdf/2312.10032.pdf) <br> | arXiv | 2023-12-15 | [Github](https://github.com/CircleRadon/Osprey) | [Demo](http://111.0.123.204:8000/) |
| ![Star](https://img.shields.io/github/stars/THUDM/CogVLM.svg?style=social&label=Star) <br> [**CogAgent: A Visual Language Model for GUI Agents**](https://arxiv.org/pdf/2312.08914.pdf) <br> | arXiv | 2023-12-14 | [Github](https://github.com/THUDM/CogVLM) | [Coming soon]() |
| [**Pixel Aligned Language Models**](https://arxiv.org/pdf/2312.09237.pdf) | arXiv | 2023-12-14 | [Coming soon]() | - |
| [**See, Say, and Segment: Teaching LMMs to Overcome False Premises**](https://arxiv.org/pdf/2312.08366.pdf) | arXiv | 2023-12-13 | [Coming soon]() | - | 
| ![Star](https://img.shields.io/github/stars/Ucas-HaoranWei/Vary.svg?style=social&label=Star) <br> [**Vary: Scaling up the Vision Vocabulary for Large Vision-Language Models**](https://arxiv.org/pdf/2312.06109.pdf) <br> | arXiv | 2023-12-11 | [Github](https://github.com/Ucas-HaoranWei/Vary) | [Demo](http://region-31.seetacloud.com:22701/) |
| ![Star](https://img.shields.io/github/stars/kakaobrain/honeybee.svg?style=social&label=Star) <br> [**Honeybee: Locality-enhanced Projector for Multimodal LLM**](https://arxiv.org/pdf/2312.06742.pdf) <br> | arXiv | 2023-12-11 | [Github](https://github.com/kakaobrain/honeybee) | - |
| [**Gemini: A Family of Highly Capable Multimodal Models**](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | Google | 2023-12-06 | - | - |
| ![Star](https://img.shields.io/github/stars/csuhan/OneLLM.svg?style=social&label=Star) <br> [**OneLLM: One Framework to Align All Modalities with Language**](https://arxiv.org/pdf/2312.03700.pdf) <br> | arXiv | 2023-12-06 | [Github](https://github.com/csuhan/OneLLM) | [Demo](https://huggingface.co/spaces/csuhan/OneLLM) |
| ![Star](https://img.shields.io/github/stars/Meituan-AutoML/Lenna.svg?style=social&label=Star) <br> [**Lenna: Language Enhanced Reasoning Detection Assistant**](https://arxiv.org/pdf/2312.02433.pdf) <br> | arXiv | 2023-12-05 | [Github](https://github.com/Meituan-AutoML/Lenna) | - | 
| ![Star](https://img.shields.io/github/stars/RenShuhuai-Andy/TimeChat.svg?style=social&label=Star) <br> [**TimeChat: A Time-sensitive Multimodal Large Language Model for Long Video Understanding**](https://arxiv.org/pdf/2312.02051.pdf) <br> | arXiv | 2023-12-04 | [Github](https://github.com/RenShuhuai-Andy/TimeChat) | Local Demo | 
| ![Star](https://img.shields.io/github/stars/mu-cai/vip-llava.svg?style=social&label=Star) <br> [**Making Large Multimodal Models Understand Arbitrary Visual Prompts**](https://arxiv.org/pdf/2312.00784.pdf) <br> | arXiv | 2023-12-01 | [Github](https://github.com/mu-cai/vip-llava) | [Demo](https://pages.cs.wisc.edu/~mucai/vip-llava.html) | 
| ![Star](https://img.shields.io/github/stars/vlm-driver/Dolphins.svg?style=social&label=Star) <br> [**Dolphins: Multimodal Language Model for Driving**](https://arxiv.org/pdf/2312.00438.pdf) <br> | arXiv | 2023-12-01 | [Github](https://github.com/vlm-driver/Dolphins) | - |
| ![Star](https://img.shields.io/github/stars/Open3DA/LL3DA.svg?style=social&label=Star) <br> [**LL3DA: Visual Interactive Instruction Tuning for Omni-3D Understanding, Reasoning, and Planning**](https://arxiv.org/pdf/2311.18651.pdf) <br> | arXiv | 2023-11-30 | [Github](https://github.com/Open3DA/LL3DA) | [Coming soon]() |
| ![Star](https://img.shields.io/github/stars/huangb23/VTimeLLM.svg?style=social&label=Star) <br> [**VTimeLLM: Empower LLM to Grasp Video Moments**](https://arxiv.org/pdf/2311.18445.pdf) <br> | arXiv | 2023-11-30 | [Github](https://github.com/huangb23/VTimeLLM/) | Local Demo |
| ![Star](https://img.shields.io/github/stars/X-PLUG/mPLUG-DocOwl.svg?style=social&label=Star) <br> [**mPLUG-PaperOwl: Scientific Diagram Analysis with the Multimodal Large Language Model**](https://arxiv.org/pdf/2311.18248.pdf) <br> | arXiv | 2023-11-30 | [Github](https://github.com/X-PLUG/mPLUG-DocOwl/tree/main/PaperOwl) | - |
| ![Star](https://img.shields.io/github/stars/dvlab-research/LLaMA-VID.svg?style=social&label=Star) <br> [**LLaMA-VID: An Image is Worth 2 Tokens in Large Language Models**](https://arxiv.org/pdf/2311.17043.pdf) <br> | arXiv | 2023-11-28 | [Github](https://github.com/dvlab-research/LLaMA-VID) | [Coming soon]() |
| ![Star](https://img.shields.io/github/stars/dvlab-research/LLMGA.svg?style=social&label=Star) <br> [**LLMGA: Multimodal Large Language Model based Generation Assistant**](https://arxiv.org/pdf/2311.16500.pdf) <br> | arXiv | 2023-11-27 | [Github](https://github.com/dvlab-research/LLMGA) | [Demo](https://baa55ef8590b623f18.gradio.live/) |
| ![Star](https://img.shields.io/github/stars/tingxueronghua/ChartLlama-code.svg?style=social&label=Star) <br> [**ChartLlama: A Multimodal LLM for Chart Understanding and Generation**](https://arxiv.org/pdf/2311.16483.pdf) <br> | arXiv | 2023-11-27 | [Github](https://github.com/tingxueronghua/ChartLlama-code) | - |
| ![Star](https://img.shields.io/github/stars/InternLM/InternLM-XComposer.svg?style=social&label=Star) <br> [**ShareGPT4V: Improving Large Multi-Modal Models with Better Captions**](https://arxiv.org/pdf/2311.12793.pdf) <br> | arXiv | 2023-11-21 | [Github](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) | [Demo](https://huggingface.co/spaces/Lin-Chen/ShareGPT4V-7B) |
| ![Star](https://img.shields.io/github/stars/rshaojimmy/JiuTian.svg?style=social&label=Star) <br> [**LION : Empowering Multimodal Large Language Model with Dual-Level Visual Knowledge**](https://arxiv.org/pdf/2311.11860.pdf) <br> | arXiv | 2023-11-20 | [Github](https://github.com/rshaojimmy/JiuTian) | - |
| ![Star](https://img.shields.io/github/stars/embodied-generalist/embodied-generalist.svg?style=social&label=Star) <br> [**An Embodied Generalist Agent in 3D World**](https://arxiv.org/pdf/2311.12871.pdf) <br> | arXiv | 2023-11-18 | [Github](https://github.com/embodied-generalist/embodied-generalist) | [Demo](https://www.youtube.com/watch?v=mlnjz4eSjB4) |
| ![Star](https://img.shields.io/github/stars/PKU-YuanGroup/Video-LLaVA.svg?style=social&label=Star) <br> [**Video-LLaVA: Learning United Visual Representation by Alignment Before Projection**](https://arxiv.org/pdf/2311.10122.pdf) <br> | arXiv | 2023-11-16 | [Github](https://github.com/PKU-YuanGroup/Video-LLaVA) | [Demo](https://huggingface.co/spaces/LanguageBind/Video-LLaVA) |
| ![Star](https://img.shields.io/github/stars/X2FD/LVIS-INSTRUCT4V.svg?style=social&label=Star) <br> [**To See is to Believe: Prompting GPT-4V for Better Visual Instruction Tuning**](https://arxiv.org/pdf/2311.07574.pdf) <br> | arXiv | 2023-11-13 | [Github](https://github.com/X2FD/LVIS-INSTRUCT4V) | - |
| ![Star](https://img.shields.io/github/stars/Alpha-VLLM/LLaMA2-Accessory.svg?style=social&label=Star) <br> [**SPHINX: The Joint Mixing of Weights, Tasks, and Visual Embeddings for Multi-modal Large Language Models**](https://arxiv.org/pdf/2311.07575.pdf) <br> | arXiv | 2023-11-13 | [Github](https://github.com/Alpha-VLLM/LLaMA2-Accessory) | [Demo](http://imagebind-llm.opengvlab.com/) |
| ![Star](https://img.shields.io/github/stars/Yuliang-Liu/Monkey.svg?style=social&label=Star) <br> [**Monkey: Image Resolution and Text Label Are Important Things for Large Multi-modal Models**](https://arxiv.org/pdf/2311.06607.pdf) <br> | arXiv | 2023-11-11 | [Github](https://github.com/Yuliang-Liu/Monkey) | [Demo](http://27.17.184.224:7681/) |
| [**LLaVA-Plus: Learning to Use Tools for Creating Multimodal Agents**](https://arxiv.org/pdf/2311.05437.pdf) | arXiv | 2023-11-09 | [Coming soon]() | [Demo](https://llavaplus.ngrok.io/) |
| ![Star](https://img.shields.io/github/stars/NExT-ChatV/NExT-Chat.svg?style=social&label=Star) <br> [**NExT-Chat: An LMM for Chat, Detection and Segmentation**](https://arxiv.org/pdf/2311.04498.pdf) <br> | arXiv | 2023-11-08 | [Github](https://github.com/NExT-ChatV/NExT-Chat) | Local Demo | 
| ![Star](https://img.shields.io/github/stars/X-PLUG/mPLUG-Owl.svg?style=social&label=Star) <br> [**mPLUG-Owl2: Revolutionizing Multi-modal Large Language Model with Modality Collaboration**](https://arxiv.org/pdf/2311.04257.pdf) <br> | arXiv | 2023-11-07 | [Github](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) | [Demo](https://modelscope.cn/studios/damo/mPLUG-Owl2/summary) |
| ![Star](https://img.shields.io/github/stars/Luodian/Otter.svg?style=social&label=Star) <br> [**OtterHD: A High-Resolution Multi-modality Model**](https://arxiv.org/pdf/2311.04219.pdf) <br> | arXiv | 2023-11-07 | [Github](https://github.com/Luodian/Otter) | - |
| [**CoVLM: Composing Visual Entities and Relationships in Large Language Models Via Communicative Decoding**](https://arxiv.org/pdf/2311.03354.pdf) | arXiv | 2023-11-06 | [Coming soon]() | - |
| ![Star](https://img.shields.io/github/stars/mbzuai-oryx/groundingLMM.svg?style=social&label=Star) <br> [**GLaMM: Pixel Grounding Large Multimodal Model**](https://arxiv.org/pdf/2311.03356.pdf) <br> | arXiv | 2023-11-06 | [Github](https://github.com/mbzuai-oryx/groundingLMM) | [Demo](https://glamm.mbzuai-oryx.ngrok.app/) |
| ![Star](https://img.shields.io/github/stars/RUCAIBox/ComVint.svg?style=social&label=Star) <br> [**What Makes for Good Visual Instructions? Synthesizing Complex Visual Reasoning Instructions for Visual Instruction Tuning**](https://arxiv.org/pdf/2311.01487.pdf) <br> | arXiv | 2023-11-02| [Github](https://github.com/RUCAIBox/ComVint) | - |
| ![Star](https://img.shields.io/github/stars/Vision-CAIR/MiniGPT-4.svg?style=social&label=Star) <br> [**MiniGPT-v2: large language model as a unified interface for vision-language multi-task learning**](https://arxiv.org/pdf/2310.09478.pdf) <br> | arXiv | 2023-10-14 | [Github](https://github.com/Vision-CAIR/MiniGPT-4) | Local Demo | 
| ![Star](https://img.shields.io/github/stars/apple/ml-ferret.svg?style=social&label=Star) <br> [**Ferret: Refer and Ground Anything Anywhere at Any Granularity**](https://arxiv.org/pdf/2310.07704.pdf) <br> | arXiv | 2023-10-11 | [Github](https://github.com/apple/ml-ferret) | - |
| ![Star](https://img.shields.io/github/stars/THUDM/CogVLM.svg?style=social&label=Star) <br> [**CogVLM: Visual Expert For Large Language Models**](https://arxiv.org/pdf/2311.03079.pdf) <br> | arXiv | 2023-10-09 | [Github](https://github.com/THUDM/CogVLM) | [Demo](http://36.103.203.44:7861/) | 
| ![Star](https://img.shields.io/github/stars/haotian-liu/LLaVA.svg?style=social&label=Star) <br> [**Improved Baselines with Visual Instruction Tuning**](https://arxiv.org/pdf/2310.03744.pdf) <br> | arXiv | 2023-10-05 | [Github](https://github.com/haotian-liu/LLaVA) | [Demo](https://llava.hliu.cc/) |
| ![Star](https://img.shields.io/github/stars/PKU-YuanGroup/LanguageBind.svg?style=social&label=Star) <br> [**LanguageBind: Extending Video-Language Pretraining to N-modality by Language-based Semantic Alignment**](https://arxiv.org/pdf/2310.01852.pdf) <br> | ICLR | 2023-10-03 | [Github](https://github.com/PKU-YuanGroup/LanguageBind) | [Demo](https://huggingface.co/spaces/LanguageBind/LanguageBind) | 
![Star](https://img.shields.io/github/stars/SY-Xuan/Pink.svg?style=social&label=Star) <br> [**Pink: Unveiling the Power of Referential Comprehension for Multi-modal LLMs**](https://arxiv.org/pdf/2310.00582.pdf) | arXiv | 2023-10-01 | [Github](https://github.com/SY-Xuan/Pink) | - |
| ![Star](https://img.shields.io/github/stars/thunlp/Muffin.svg?style=social&label=Star) <br> [**Reformulating Vision-Language Foundation Models and Datasets Towards Universal Multimodal Assistants**](https://arxiv.org/pdf/2310.00653.pdf) <br> | arXiv | 2023-10-01 | [Github](https://github.com/thunlp/Muffin) | Local Demo | 
| [**AnyMAL: An Efficient and Scalable Any-Modality Augmented Language Model**](https://arxiv.org/pdf/2309.16058.pdf) | arXiv | 2023-09-27 | - | - |
| ![Star](https://img.shields.io/github/stars/InternLM/InternLM-XComposer.svg?style=social&label=Star) <br> [**InternLM-XComposer: A Vision-Language Large Model for Advanced Text-image Comprehension and Composition**](https://arxiv.org/pdf/2309.15112.pdf) <br> | arXiv | 2023-09-26 | [Github](https://github.com/InternLM/InternLM-XComposer) | Local Demo |
| ![Star](https://img.shields.io/github/stars/RunpeiDong/DreamLLM.svg?style=social&label=Star) <br> [**DreamLLM: Synergistic Multimodal Comprehension and Creation**](https://arxiv.org/pdf/2309.11499.pdf) <br> | arXiv | 2023-09-20 | [Github](https://github.com/RunpeiDong/DreamLLM) | [Coming soon]() |
| [**An Empirical Study of Scaling Instruction-Tuned Large Multimodal Models**](https://arxiv.org/pdf/2309.09958.pdf) | arXiv | 2023-09-18 | [Coming soon]() | - |
| ![Star](https://img.shields.io/github/stars/SihengLi99/TextBind.svg?style=social&label=Star) <br> [**TextBind: Multi-turn Interleaved Multimodal Instruction-following**](https://arxiv.org/pdf/2309.08637.pdf) <br> | arXiv | 2023-09-14 | [Github](https://github.com/SihengLi99/TextBind) | [Demo](https://ailabnlp.tencent.com/research_demos/textbind/) |
| ![Star](https://img.shields.io/github/stars/NExT-GPT/NExT-GPT.svg?style=social&label=Star) <br> [**NExT-GPT: Any-to-Any Multimodal LLM**](https://arxiv.org/pdf/2309.05519.pdf) <br> | arXiv | 2023-09-11 | [Github](https://github.com/NExT-GPT/NExT-GPT) | [Demo](https://fc7a82a1c76b336b6f.gradio.live/) |
| ![Star](https://img.shields.io/github/stars/UCSC-VLAA/Sight-Beyond-Text.svg?style=social&label=Star) <br> [**Sight Beyond Text: Multi-Modal Training Enhances LLMs in Truthfulness and Ethics**](https://arxiv.org/pdf/2309.07120.pdf) <br> | arXiv | 2023-09-13 | [Github](https://github.com/UCSC-VLAA/Sight-Beyond-Text) | - |
| ![Star](https://img.shields.io/github/stars/OpenGVLab/LLaMA-Adapter.svg?style=social&label=Star) <br> [**ImageBind-LLM: Multi-modality Instruction Tuning**](https://arxiv.org/pdf/2309.03905.pdf) <br> | arXiv | 2023-09-07 | [Github](https://github.com/OpenGVLab/LLaMA-Adapter) | [Demo](http://imagebind-llm.opengvlab.com/) |
| [**Scaling Autoregressive Multi-Modal Models: Pretraining and Instruction Tuning**](https://arxiv.org/pdf/2309.02591.pdf) | arXiv | 2023-09-05 | - | - | 
| ![Star](https://img.shields.io/github/stars/OpenRobotLab/PointLLM.svg?style=social&label=Star) <br> [**PointLLM: Empowering Large Language Models to Understand Point Clouds**](https://arxiv.org/pdf/2308.16911.pdf) <br> | arXiv | 2023-08-31 | [Github](https://github.com/OpenRobotLab/PointLLM) | [Demo](http://101.230.144.196/) |
| ![Star](https://img.shields.io/github/stars/HYPJUDY/Sparkles.svg?style=social&label=Star) <br> [**✨Sparkles: Unlocking Chats Across Multiple Images for Multimodal Instruction-Following Models**](https://arxiv.org/pdf/2308.16463.pdf) <br> | arXiv | 2023-08-31 | [Github](https://github.com/HYPJUDY/Sparkles) | Local Demo |
| ![Star](https://img.shields.io/github/stars/opendatalab/MLLM-DataEngine.svg?style=social&label=Star) <br> [**MLLM-DataEngine: An Iterative Refinement Approach for MLLM**](https://arxiv.org/pdf/2308.13566.pdf) <br> | arXiv | 2023-08-25 | [Github](https://github.com/opendatalab/MLLM-DataEngine) | - |
| ![Star](https://img.shields.io/github/stars/PVIT-official/PVIT.svg?style=social&label=Star) <br> [**Position-Enhanced Visual Instruction Tuning for Multimodal Large Language Models**](https://arxiv.org/pdf/2308.13437.pdf) <br> | arXiv | 2023-08-25 | [Github](https://github.com/PVIT-official/PVIT) | [Demo](https://huggingface.co/spaces/PVIT/pvit) |  
| ![Star](https://img.shields.io/github/stars/QwenLM/Qwen-VL.svg?style=social&label=Star) <br> [**Qwen-VL: A Frontier Large Vision-Language Model with Versatile Abilities**](https://arxiv.org/pdf/2308.12966.pdf) <br> | arXiv | 2023-08-24 | [Github](https://github.com/QwenLM/Qwen-VL) | [Demo](https://modelscope.cn/studios/qwen/Qwen-VL-Chat-Demo/summary) | 
| ![Star](https://img.shields.io/github/stars/OpenBMB/VisCPM.svg?style=social&label=Star) <br> [**Large Multilingual Models Pivot Zero-Shot Multimodal Learning across Languages**](https://arxiv.org/pdf/2308.12038.pdf) <br> | ICLR | 2023-08-23 | [Github](https://github.com/OpenBMB/VisCPM) | [Demo](https://huggingface.co/spaces/openbmb/viscpm-chat) | 
| ![Star](https://img.shields.io/github/stars/icoz69/StableLLAVA.svg?style=social&label=Star) <br> [**StableLLaVA: Enhanced Visual Instruction Tuning with Synthesized Image-Dialogue Data**](https://arxiv.org/pdf/2308.10253.pdf) <br> | arXiv | 2023-08-20 | [Github](https://github.com/icoz69/StableLLAVA) | - |
| ![Star](https://img.shields.io/github/stars/mlpc-ucsd/BLIVA.svg?style=social&label=Star) <br> [**BLIVA: A Simple Multimodal LLM for Better Handling of Text-rich Visual Questions**](https://arxiv.org/pdf/2308.09936.pdf) <br> | arXiv | 2023-08-19 | [Github](https://github.com/mlpc-ucsd/BLIVA) | [Demo](https://huggingface.co/spaces/mlpc-lab/BLIVA) |
| ![Star](https://img.shields.io/github/stars/DCDmllm/Cheetah.svg?style=social&label=Star) <br> [**Fine-tuning Multimodal LLMs to Follow Zero-shot Demonstrative Instructions**](https://arxiv.org/pdf/2308.04152.pdf) <br> | arXiv | 2023-08-08 | [Github](https://github.com/DCDmllm/Cheetah) | - |
| ![Star](https://img.shields.io/github/stars/OpenGVLab/All-Seeing.svg?style=social&label=Star) <br> [**The All-Seeing Project: Towards Panoptic Visual Recognition and Understanding of the Open World**](https://arxiv.org/pdf/2308.01907.pdf) <br> | arXiv | 2023-08-03 | [Github](https://github.com/OpenGVLab/All-Seeing) | [Demo](https://huggingface.co/spaces/OpenGVLab/all-seeing) | 
| ![Star](https://img.shields.io/github/stars/dvlab-research/LISA.svg?style=social&label=Star) <br> [**LISA: Reasoning Segmentation via Large Language Model**](https://arxiv.org/pdf/2308.00692.pdf) <br> | arXiv | 2023-08-01 | [Github](https://github.com/dvlab-research/LISA) | [Demo](http://103.170.5.190:7860) |
| ![Star](https://img.shields.io/github/stars/rese1f/MovieChat.svg?style=social&label=Star) <br> [**MovieChat: From Dense Token to Sparse Memory for Long Video Understanding**](https://arxiv.org/pdf/2307.16449.pdf) <br> | arXiv | 2023-07-31 | [Github](https://github.com/rese1f/MovieChat) | Local Demo |
| ![Star](https://img.shields.io/github/stars/UMass-Foundation-Model/3D-LLM.svg?style=social&label=Star) <br> [**3D-LLM: Injecting the 3D World into Large Language Models**](https://arxiv.org/pdf/2307.12981.pdf) <br> | arXiv | 2023-07-24 | [Github](https://github.com/UMass-Foundation-Model/3D-LLM) | - | 
| [**ChatSpot: Bootstrapping Multimodal LLMs via Precise Referring Instruction Tuning**](https://arxiv.org/pdf/2307.09474.pdf) <br> | arXiv | 2023-07-18 | - | [Demo](https://chatspot.streamlit.app/) |
| ![Star](https://img.shields.io/github/stars/magic-research/bubogpt.svg?style=social&label=Star) <br> [**BuboGPT: Enabling Visual Grounding in Multi-Modal LLMs**](https://arxiv.org/pdf/2307.08581.pdf) <br> | arXiv | 2023-07-17 | [Github](https://github.com/magic-research/bubogpt) | [Demo](https://huggingface.co/spaces/magicr/BuboGPT) |
| ![Star](https://img.shields.io/github/stars/BAAI-DCAI/Visual-Instruction-Tuning.svg?style=social&label=Star) <br> [**SVIT: Scaling up Visual Instruction Tuning**](https://arxiv.org/pdf/2307.04087.pdf) <br> | arXiv | 2023-07-09 | [Github](https://github.com/BAAI-DCAI/Visual-Instruction-Tuning) | - |
| ![Star](https://img.shields.io/github/stars/jshilong/GPT4RoI.svg?style=social&label=Star) <br> [**GPT4RoI: Instruction Tuning Large Language Model on Region-of-Interest**](https://arxiv.org/pdf/2307.03601.pdf) <br> | arXiv | 2023-07-07 | [Github](https://github.com/jshilong/GPT4RoI) | [Demo](http://139.196.83.164:7000/) |
| ![Star](https://img.shields.io/github/stars/bytedance/lynx-llm.svg?style=social&label=Star) <br> [**What Matters in Training a GPT4-Style Language Model with Multimodal Inputs?**](https://arxiv.org/pdf/2307.02469.pdf) <br> | arXiv | 2023-07-05 | [Github](https://github.com/bytedance/lynx-llm)  | - | 
| ![Star](https://img.shields.io/github/stars/X-PLUG/mPLUG-DocOwl.svg?style=social&label=Star) <br> [**mPLUG-DocOwl: Modularized Multimodal Large Language Model for Document Understanding**](https://arxiv.org/pdf/2307.02499.pdf) <br> | arXiv | 2023-07-04 | [Github](https://github.com/X-PLUG/mPLUG-DocOwl) | [Demo](https://modelscope.cn/studios/damo/mPLUG-DocOwl/summary) | 
| ![Star](https://img.shields.io/github/stars/ChenDelong1999/polite_flamingo.svg?style=social&label=Star) <br> [**Visual Instruction Tuning with Polite Flamingo**](https://arxiv.org/pdf/2307.01003.pdf) <br >| arXiv | 2023-07-03 | [Github](https://github.com/ChenDelong1999/polite_flamingo) | [Demo](http://clever_flamingo.xiaoice.com/) |
| ![Star](https://img.shields.io/github/stars/SALT-NLP/LLaVAR.svg?style=social&label=Star) <br> [**LLaVAR: Enhanced Visual Instruction Tuning for Text-Rich Image Understanding**](https://arxiv.org/pdf/2306.17107.pdf) <br> | arXiv | 2023-06-29 | [Github](https://github.com/SALT-NLP/LLaVAR) | [Demo](https://eba470c07c805702b8.gradio.live/) |
| ![Star](https://img.shields.io/github/stars/shikras/shikra.svg?style=social&label=Star) <br> [**Shikra: Unleashing Multimodal LLM's Referential Dialogue Magic**](https://arxiv.org/pdf/2306.15195.pdf) <br> | arXiv | 2023-06-27 | [Github](https://github.com/shikras/shikra) | [Demo](http://demo.zhaozhang.net:7860/) |
| ![Star](https://img.shields.io/github/stars/OpenMotionLab/MotionGPT.svg?style=social&label=Star) <br> [**MotionGPT: Human Motion as a Foreign Language**](https://arxiv.org/pdf/2306.14795.pdf) <br> | arXiv | 2023-06-26 | [Github](https://github.com/OpenMotionLab/MotionGPT) | - | 
| ![Star](https://img.shields.io/github/stars/lyuchenyang/Macaw-LLM.svg?style=social&label=Star) <br> [**Macaw-LLM: Multi-Modal Language Modeling with Image, Audio, Video, and Text Integration**](https://arxiv.org/pdf/2306.09093.pdf) <br> | arXiv | 2023-06-15 | [Github](https://github.com/lyuchenyang/Macaw-LLM) | [Coming soon]() |
| ![Star](https://img.shields.io/github/stars/OpenLAMM/LAMM.svg?style=social&label=Star) <br> [**LAMM: Language-Assisted Multi-Modal Instruction-Tuning Dataset, Framework, and Benchmark**](https://arxiv.org/pdf/2306.06687.pdf) <br> | arXiv | 2023-06-11 | [Github](https://github.com/OpenLAMM/LAMM) | [Demo](https://huggingface.co/spaces/openlamm/LAMM) | 
| ![Star](https://img.shields.io/github/stars/mbzuai-oryx/Video-ChatGPT.svg?style=social&label=Star) <br> [**Video-ChatGPT: Towards Detailed Video Understanding via Large Vision and Language Models**](https://arxiv.org/pdf/2306.05424.pdf) <br> | arXiv | 2023-06-08 | [Github](https://github.com/mbzuai-oryx/Video-ChatGPT) | [Demo](https://www.ival-mbzuai.com/video-chatgpt) |
| ![Star](https://img.shields.io/github/stars/Luodian/Otter.svg?style=social&label=Star) <br> [**MIMIC-IT: Multi-Modal In-Context Instruction Tuning**](https://arxiv.org/pdf/2306.05425.pdf) <br> | arXiv | 2023-06-08 | [Github](https://github.com/Luodian/Otter) | [Demo](https://otter.cliangyu.com/) |
| [**M<sup>3</sup>IT: A Large-Scale Dataset towards Multi-Modal Multilingual Instruction Tuning**](https://arxiv.org/pdf/2306.04387.pdf) | arXiv | 2023-06-07 | - | - | 
| ![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/Video-LLaMA.svg?style=social&label=Star) <br> [**Video-LLaMA: An Instruction-tuned Audio-Visual Language Model for Video Understanding**](https://arxiv.org/pdf/2306.02858.pdf) <br> | arXiv | 2023-06-05 | [Github](https://github.com/DAMO-NLP-SG/Video-LLaMA) | [Demo](https://huggingface.co/spaces/DAMO-NLP-SG/Video-LLaMA) |
| ![Star](https://img.shields.io/github/stars/microsoft/LLaVA-Med.svg?style=social&label=Star) <br> [**LLaVA-Med: Training a Large Language-and-Vision Assistant for Biomedicine in One Day**](https://arxiv.org/pdf/2306.00890.pdf) <br> | arXiv | 2023-06-01 | [Github](https://github.com/microsoft/LLaVA-Med) | - |
| ![Star](https://img.shields.io/github/stars/StevenGrove/GPT4Tools.svg?style=social&label=Star) <br> [**GPT4Tools: Teaching Large Language Model to Use Tools via Self-instruction**](https://arxiv.org/pdf/2305.18752.pdf) <br> | arXiv | 2023-05-30 | [Github](https://github.com/StevenGrove/GPT4Tools) | [Demo](https://huggingface.co/spaces/stevengrove/GPT4Tools) | 
| ![Star](https://img.shields.io/github/stars/yxuansu/PandaGPT.svg?style=social&label=Star) <br> [**PandaGPT: One Model To Instruction-Follow Them All**](https://arxiv.org/pdf/2305.16355.pdf) <br> | arXiv | 2023-05-25 | [Github](https://github.com/yxuansu/PandaGPT) | [Demo](https://huggingface.co/spaces/GMFTBY/PandaGPT) | 
| ![Star](https://img.shields.io/github/stars/joez17/ChatBridge.svg?style=social&label=Star) <br> [**ChatBridge: Bridging Modalities with Large Language Model as a Language Catalyst**](https://arxiv.org/pdf/2305.16103.pdf) <br> | arXiv | 2023-05-25 | [Github](https://github.com/joez17/ChatBridge) | - | 
| ![Star](https://img.shields.io/github/stars/luogen1996/LaVIN.svg?style=social&label=Star) <br> [**Cheap and Quick: Efficient Vision-Language Instruction Tuning for Large Language Models**](https://arxiv.org/pdf/2305.15023.pdf) <br> | arXiv | 2023-05-24 | [Github](https://github.com/luogen1996/LaVIN) | Local Demo |
| ![Star](https://img.shields.io/github/stars/OptimalScale/DetGPT.svg?style=social&label=Star) <br> [**DetGPT: Detect What You Need via Reasoning**](https://arxiv.org/pdf/2305.14167.pdf) <br> | arXiv | 2023-05-23 | [Github](https://github.com/OptimalScale/DetGPT) | [Demo](https://d3c431c0c77b1d9010.gradio.live/) | 
| ![Star](https://img.shields.io/github/stars/microsoft/Pengi.svg?style=social&label=Star) <br> [**Pengi: An Audio Language Model for Audio Tasks**](https://arxiv.org/pdf/2305.11834.pdf) <br> | arXiv | 2023-05-19 | [Github](https://github.com/microsoft/Pengi) | - |
| ![Star](https://img.shields.io/github/stars/OpenGVLab/VisionLLM.svg?style=social&label=Star) <br> [**VisionLLM: Large Language Model is also an Open-Ended Decoder for Vision-Centric Tasks**](https://arxiv.org/pdf/2305.11175.pdf) <br> | arXiv | 2023-05-18 | [Github](https://github.com/OpenGVLab/VisionLLM) | - |
| ![Star](https://img.shields.io/github/stars/YuanGongND/ltu.svg?style=social&label=Star) <br> [**Listen, Think, and Understand**](https://arxiv.org/pdf/2305.10790.pdf) <br> | arXiv | 2023-05-18 | [Github](https://github.com/YuanGongND/ltu) | [Demo](https://github.com/YuanGongND/ltu) |
| ![Star](https://img.shields.io/github/stars/THUDM/VisualGLM-6B.svg?style=social&label=Star) <br> **VisualGLM-6B** <br> | - | 2023-05-17 | [Github](https://github.com/THUDM/VisualGLM-6B) | Local Demo |
| ![Star](https://img.shields.io/github/stars/xiaoman-zhang/PMC-VQA.svg?style=social&label=Star) <br> [**PMC-VQA: Visual Instruction Tuning for Medical Visual Question Answering**](https://arxiv.org/pdf/2305.10415.pdf) <br> | arXiv | 2023-05-17 | [Github](https://github.com/xiaoman-zhang/PMC-VQA) | - | 
| ![Star](https://img.shields.io/github/stars/salesforce/LAVIS.svg?style=social&label=Star) <br> [**InstructBLIP: Towards General-purpose Vision-Language Models with Instruction Tuning**](https://arxiv.org/pdf/2305.06500.pdf) <br> | arXiv | 2023-05-11 | [Github](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | Local Demo |
| ![Star](https://img.shields.io/github/stars/OpenGVLab/Ask-Anything.svg?style=social&label=Star) <br> [**VideoChat: Chat-Centric Video Understanding**](https://arxiv.org/pdf/2305.06355.pdf) <br> | arXiv | 2023-05-10 | [Github](https://github.com/OpenGVLab/Ask-Anything) | [Demo](https://ask.opengvlab.com/) |
| ![Star](https://img.shields.io/github/stars/open-mmlab/Multimodal-GPT.svg?style=social&label=Star) <br> [**MultiModal-GPT: A Vision and Language Model for Dialogue with Humans**](https://arxiv.org/pdf/2305.04790.pdf) <br> | arXiv | 2023-05-08 | [Github](https://github.com/open-mmlab/Multimodal-GPT) | [Demo](https://mmgpt.openmmlab.org.cn/) |
| ![Star](https://img.shields.io/github/stars/phellonchen/X-LLM.svg?style=social&label=Star) <br> [**X-LLM: Bootstrapping Advanced Large Language Models by Treating Multi-Modalities as Foreign Languages**](https://arxiv.org/pdf/2305.04160.pdf) <br> | arXiv | 2023-05-07 | [Github](https://github.com/phellonchen/X-LLM) | - | 
| ![Star](https://img.shields.io/github/stars/YunxinLi/LingCloud.svg?style=social&label=Star) <br> [**LMEye: An Interactive Perception Network for Large Language Models**](https://arxiv.org/pdf/2305.03701.pdf) <br> | arXiv | 2023-05-05 | [Github](https://github.com/YunxinLi/LingCloud) | Local Demo |
| ![Star](https://img.shields.io/github/stars/OpenGVLab/LLaMA-Adapter.svg?style=social&label=Star) <br> [**LLaMA-Adapter V2: Parameter-Efficient Visual Instruction Model**](https://arxiv.org/pdf/2304.15010.pdf) <br> | arXiv | 2023-04-28 | [Github](https://github.com/OpenGVLab/LLaMA-Adapter) | [Demo](http://llama-adapter.opengvlab.com/) | 
| ![Star](https://img.shields.io/github/stars/X-PLUG/mPLUG-Owl.svg?style=social&label=Star) <br> [**mPLUG-Owl: Modularization Empowers Large Language Models with Multimodality**](https://arxiv.org/pdf/2304.14178.pdf) <br> | arXiv | 2023-04-27 | [Github](https://github.com/X-PLUG/mPLUG-Owl) | [Demo](https://huggingface.co/spaces/MAGAer13/mPLUG-Owl) |
| ![Star](https://img.shields.io/github/stars/Vision-CAIR/MiniGPT-4.svg?style=social&label=Star) <br> [**MiniGPT-4: Enhancing Vision-Language Understanding with Advanced Large Language Models**](https://arxiv.org/pdf/2304.10592.pdf) <br> | arXiv | 2023-04-20 | [Github](https://github.com/Vision-CAIR/MiniGPT-4) | - |
| ![Star](https://img.shields.io/github/stars/haotian-liu/LLaVA.svg?style=social&label=Star) <br> [**Visual Instruction Tuning**](https://arxiv.org/pdf/2304.08485.pdf) <br> | NeurIPS | 2023-04-17 | [GitHub](https://github.com/haotian-liu/LLaVA) | [Demo](https://llava.hliu.cc/) |
| ![Star](https://img.shields.io/github/stars/OpenGVLab/LLaMA-Adapter.svg?style=social&label=Star) <br> [**LLaMA-Adapter: Efficient Fine-tuning of Language Models with Zero-init Attention**](https://arxiv.org/pdf/2303.16199.pdf) <br> | ICLR | 2023-03-28 | [Github](https://github.com/OpenGVLab/LLaMA-Adapter) | [Demo](https://huggingface.co/spaces/csuhan/LLaMA-Adapter) |
| ![Star](https://img.shields.io/github/stars/VT-NLP/MultiInstruct.svg?style=social&label=Star) <br> [**MultiInstruct: Improving Multi-Modal Zero-Shot Learning via Instruction Tuning**](https://arxiv.org/pdf/2212.10773.pdf) <br> | ACL | 2022-12-21 | [Github](https://github.com/VT-NLP/MultiInstruct) | - | 


## Multimodal In-Context Learning
|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Hijacking Context in Large Multi-modal Models**](https://arxiv.org/pdf/2312.07553.pdf) | arXiv | 2023-12-07 | - | - |
| [**Towards More Unified In-context Visual Understanding**](https://arxiv.org/pdf/2312.02520.pdf) | arXiv | 2023-12-05 | - | - | 
| ![Star](https://img.shields.io/github/stars/HaozheZhao/MIC.svg?style=social&label=Star) <br> [**MMICL: Empowering Vision-language Model with Multi-Modal In-Context Learning**](https://arxiv.org/pdf/2309.07915.pdf) <br> | arXiv | 2023-09-14 | [Github](https://github.com/HaozheZhao/MIC) | [Demo](https://8904cdd23621858859.gradio.live/) |
| ![Star](https://img.shields.io/github/stars/isekai-portal/Link-Context-Learning.svg?style=social&label=Star) <br> [**Link-Context Learning for Multimodal LLMs**](https://arxiv.org/pdf/2308.07891.pdf) <br> | arXiv | 2023-08-15 | [Github](https://github.com/isekai-portal/Link-Context-Learning) | [Demo](http://117.144.81.99:20488/) | 
| ![Star](https://img.shields.io/github/stars/mlfoundations/open_flamingo.svg?style=social&label=Star) <br> [**OpenFlamingo: An Open-Source Framework for Training Large Autoregressive Vision-Language Models**](https://arxiv.org/pdf/2308.01390.pdf) <br> | arXiv | 2023-08-02 | [Github](https://github.com/mlfoundations/open_flamingo) | [Demo](https://huggingface.co/spaces/openflamingo/OpenFlamingo) | 
| ![Star](https://img.shields.io/github/stars/snap-stanford/med-flamingo.svg?style=social&label=Star) <br> [**Med-Flamingo: a Multimodal Medical Few-shot Learner**](https://arxiv.org/pdf/2307.15189.pdf) <br> | arXiv | 2023-07-27 | [Github](https://github.com/snap-stanford/med-flamingo) | Local Demo | 
| ![Star](https://img.shields.io/github/stars/baaivision/Emu.svg?style=social&label=Star) <br> [**Generative Pretraining in Multimodality**](https://arxiv.org/pdf/2307.05222.pdf) <br> | arXiv | 2023-07-11 | [Github](https://github.com/baaivision/Emu) | [Demo](http://218.91.113.230:9002/) |
| [**AVIS: Autonomous Visual Information Seeking with Large Language Models**](https://arxiv.org/pdf/2306.08129.pdf) | arXiv | 2023-06-13 | - | - |
| ![Star](https://img.shields.io/github/stars/Luodian/Otter.svg?style=social&label=Star) <br> [**MIMIC-IT: Multi-Modal In-Context Instruction Tuning**](https://arxiv.org/pdf/2306.05425.pdf) <br> | arXiv | 2023-06-08 | [Github](https://github.com/Luodian/Otter) | [Demo](https://otter.cliangyu.com/) |
| ![Star](https://img.shields.io/github/stars/yongliang-wu/ExploreCfg.svg?style=social&label=Star) <br> [**Exploring Diverse In-Context Configurations for Image Captioning**](https://arxiv.org/pdf/2305.14800.pdf) <br> | NeurIPS | 2023-05-24 | [Github](https://github.com/yongliang-wu/ExploreCfg) | - |
| ![Star](https://img.shields.io/github/stars/lupantech/chameleon-llm.svg?style=social&label=Star) <br> [**Chameleon: Plug-and-Play Compositional Reasoning with Large Language Models**](https://arxiv.org/pdf/2304.09842.pdf) <br> | arXiv | 2023-04-19 | [Github](https://github.com/lupantech/chameleon-llm) | [Demo](https://chameleon-llm.github.io/) | 
| ![Star](https://img.shields.io/github/stars/microsoft/JARVIS.svg?style=social&label=Star) <br> [**HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in HuggingFace**](https://arxiv.org/pdf/2303.17580.pdf) <br> | arXiv | 2023-03-30 | [Github](https://github.com/microsoft/JARVIS) | [Demo](https://huggingface.co/spaces/microsoft/HuggingGPT) | 
| ![Star](https://img.shields.io/github/stars/microsoft/MM-REACT.svg?style=social&label=Star) <br> [**MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action**](https://arxiv.org/pdf/2303.11381.pdf) <br> | arXiv | 2023-03-20 | [Github](https://github.com/microsoft/MM-REACT) | [Demo](https://huggingface.co/spaces/microsoft-cognitive-service/mm-react) |
| ![Star](https://img.shields.io/github/stars/MAEHCM/ICL-D3IE.svg?style=social&label=Star) <br> [**ICL-D3IE: In-Context Learning with Diverse Demonstrations Updating for Document Information Extraction**](https://arxiv.org/pdf/2303.05063.pdf) <br> | ICCV | 2023-03-09 | [Github](https://github.com/MAEHCM/ICL-D3IE) | - |
| ![Star](https://img.shields.io/github/stars/MILVLG/prophet.svg?style=social&label=Star) <br> [**Prompting Large Language Models with Answer Heuristics for Knowledge-based Visual Question Answering**](https://arxiv.org/pdf/2303.01903.pdf) <br> | CVPR | 2023-03-03 | [Github](https://github.com/MILVLG/prophet) | - |
| ![Star](https://img.shields.io/github/stars/allenai/visprog.svg?style=social&label=Star) <br> [**Visual Programming: Compositional visual reasoning without training**](https://openaccess.thecvf.com/content/CVPR2023/papers/Gupta_Visual_Programming_Compositional_Visual_Reasoning_Without_Training_CVPR_2023_paper.pdf) <br> | CVPR | 2022-11-18 | [Github](https://github.com/allenai/visprog) | Local Demo | 
| ![Star](https://img.shields.io/github/stars/microsoft/PICa.svg?style=social&label=Star) <br> [**An Empirical Study of GPT-3 for Few-Shot Knowledge-Based VQA**](https://ojs.aaai.org/index.php/AAAI/article/download/20215/19974) <br> | AAAI | 2022-06-28 | [Github](https://github.com/microsoft/PICa) | - |
| ![Star](https://img.shields.io/github/stars/mlfoundations/open_flamingo.svg?style=social&label=Star) <br> [**Flamingo: a Visual Language Model for Few-Shot Learning**](https://arxiv.org/pdf/2204.14198.pdf) <br> | NeurIPS | 2022-04-29 | [Github](https://github.com/mlfoundations/open_flamingo) | [Demo](https://huggingface.co/spaces/dhansmair/flamingo-mini-cap) | 
| [**Multimodal Few-Shot Learning with Frozen Language Models**](https://arxiv.org/pdf/2106.13884.pdf) | NeurIPS | 2021-06-25 | - | - |


## Multimodal Chain-of-Thought
|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![Star](https://img.shields.io/github/stars/SooLab/DDCOT.svg?style=social&label=Star) <br> [**DDCoT: Duty-Distinct Chain-of-Thought Prompting for Multimodal Reasoning in Language Models**](https://arxiv.org/pdf/2310.16436.pdf) <br> | NeurIPS | 2023-10-25 | [Github](https://github.com/SooLab/DDCOT) | - |
| ![Star](https://img.shields.io/github/stars/shikras/shikra.svg?style=social&label=Star) <br> [**Shikra: Unleashing Multimodal LLM's Referential Dialogue Magic**](https://arxiv.org/pdf/2306.15195.pdf) <br> | arXiv | 2023-06-27 | [Github](https://github.com/shikras/shikra) | [Demo](http://demo.zhaozhang.net:7860/) |
| ![Star](https://img.shields.io/github/stars/zeroQiaoba/Explainable-Multimodal-Emotion-Reasoning.svg?style=social&label=Star) <br> [**Explainable Multimodal Emotion Reasoning**](https://arxiv.org/pdf/2306.15401.pdf) <br> | arXiv | 2023-06-27 | [Github](https://github.com/zeroQiaoba/Explainable-Multimodal-Emotion-Reasoning) | - | 
| ![Star](https://img.shields.io/github/stars/EmbodiedGPT/EmbodiedGPT_Pytorch.svg?style=social&label=Star) <br> [**EmbodiedGPT: Vision-Language Pre-Training via Embodied Chain of Thought**](https://arxiv.org/pdf/2305.15021.pdf) <br> | arXiv | 2023-05-24 | [Github](https://github.com/EmbodiedGPT/EmbodiedGPT_Pytorch) | - | 
| [**Let’s Think Frame by Frame: Evaluating Video Chain of Thought with Video Infilling and Prediction**](https://arxiv.org/pdf/2305.13903.pdf) | arXiv | 2023-05-23 | - | - |
| [**T-SciQ: Teaching Multimodal Chain-of-Thought Reasoning via Large Language Model Signals for Science Question Answering**](https://arxiv.org/pdf/2305.03453.pdf) | arXiv | 2023-05-05 | - | - |
| ![Star](https://img.shields.io/github/stars/ttengwang/Caption-Anything.svg?style=social&label=Star) <br> [**Caption Anything: Interactive Image Description with Diverse Multimodal Controls**](https://arxiv.org/pdf/2305.02677.pdf) <br> | arXiv | 2023-05-04 | [Github](https://github.com/ttengwang/Caption-Anything) | [Demo](https://huggingface.co/spaces/TencentARC/Caption-Anything) |
| [**Visual Chain of Thought: Bridging Logical Gaps with Multimodal Infillings**](https://arxiv.org/pdf/2305.02317.pdf) | arXiv | 2023-05-03 | [Coming soon](https://github.com/dannyrose30/VCOT) | - |
| ![Star](https://img.shields.io/github/stars/lupantech/chameleon-llm.svg?style=social&label=Star) <br> [**Chameleon: Plug-and-Play Compositional Reasoning with Large Language Models**](https://arxiv.org/pdf/2304.09842.pdf) <br> | arXiv | 2023-04-19 | [Github](https://github.com/lupantech/chameleon-llm) | [Demo](https://chameleon-llm.github.io/) | 
| [**Chain of Thought Prompt Tuning in Vision Language Models**](https://arxiv.org/pdf/2304.07919.pdf) | arXiv | 2023-04-16 | [Coming soon]() | - |
| ![Star](https://img.shields.io/github/stars/microsoft/MM-REACT.svg?style=social&label=Star) <br> [**MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action**](https://arxiv.org/pdf/2303.11381.pdf) <br> | arXiv | 2023-03-20 | [Github](https://github.com/microsoft/MM-REACT) | [Demo](https://huggingface.co/spaces/microsoft-cognitive-service/mm-react) |
| ![Star](https://img.shields.io/github/stars/microsoft/TaskMatrix.svg?style=social&label=Star) <br> [**Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models**](https://arxiv.org/pdf/2303.04671.pdf) <br> | arXiv | 2023-03-08 | [Github](https://github.com/microsoft/TaskMatrix) | [Demo](https://huggingface.co/spaces/microsoft/visual_chatgpt) |
| ![Star](https://img.shields.io/github/stars/amazon-science/mm-cot.svg?style=social&label=Star) <br> [**Multimodal Chain-of-Thought Reasoning in Language Models**](https://arxiv.org/pdf/2302.00923.pdf) <br> | arXiv | 2023-02-02 | [Github](https://github.com/amazon-science/mm-cot) | - |
| ![Star](https://img.shields.io/github/stars/allenai/visprog.svg?style=social&label=Star) <br> [**Visual Programming: Compositional visual reasoning without training**](https://openaccess.thecvf.com/content/CVPR2023/papers/Gupta_Visual_Programming_Compositional_Visual_Reasoning_Without_Training_CVPR_2023_paper.pdf) <br> | CVPR | 2022-11-18 | [Github](https://github.com/allenai/visprog) | Local Demo | 
| ![Star](https://img.shields.io/github/stars/lupantech/ScienceQA.svg?style=social&label=Star) <br> [**Learn to Explain: Multimodal Reasoning via Thought Chains for Science Question Answering**](https://proceedings.neurips.cc/paper_files/paper/2022/file/11332b6b6cf4485b84afadb1352d3a9a-Paper-Conference.pdf) <br> | NeurIPS | 2022-09-20 | [Github](https://github.com/lupantech/ScienceQA) | - |


## LLM-Aided Visual Reasoning
|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![Star](https://img.shields.io/github/stars/penghao-wu/vstar.svg?style=social&label=Star) <br> [**V∗: Guided Visual Search as a Core Mechanism in Multimodal LLMs**](https://arxiv.org/pdf/2312.14135.pdf) <br> | arXiv | 2023-12-21 | [Github](https://github.com/penghao-wu/vstar) | Local Demo |
| ![Star](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-Interactive-Demo.svg?style=social&label=Star) <br> [**LLaVA-Interactive: An All-in-One Demo for Image Chat, Segmentation, Generation and Editing**](https://arxiv.org/pdf/2311.00571.pdf) <br> | arXiv | 2023-11-01 | [Github](https://github.com/LLaVA-VL/LLaVA-Interactive-Demo) | [Demo](https://6dd3-20-163-117-69.ngrok-free.app/) |
| [**MM-VID: Advancing Video Understanding with GPT-4V(vision)**](https://arxiv.org/pdf/2310.19773.pdf) | arXiv | 2023-10-30 | - | - |
| ![Star](https://img.shields.io/github/stars/OpenGVLab/ControlLLM.svg?style=social&label=Star) <br> [**ControlLLM: Augment Language Models with Tools by Searching on Graphs**](https://arxiv.org/pdf/2310.17796.pdf) <br> | arXiv | 2023-10-26 | [Github](https://github.com/OpenGVLab/ControlLLM) | - |
| ![Star](https://img.shields.io/github/stars/BradyFU/Woodpecker.svg?style=social&label=Star) <br> [**Woodpecker: Hallucination Correction for Multimodal Large Language Models**](https://arxiv.org/pdf/2310.16045.pdf) <br> | arXiv | 2023-10-24 | [Github](https://github.com/BradyFU/Woodpecker) | [Demo](https://deb6a97bae6fab67ae.gradio.live/) |
| ![Star](https://img.shields.io/github/stars/mindagent/mindagent.svg?style=social&label=Star) <br> [**MindAgent: Emergent Gaming Interaction**](https://arxiv.org/pdf/2309.09971.pdf) <br> | arXiv | 2023-09-18 | [Github](https://github.com/mindagent/mindagent) | - | 
| ![Star](https://img.shields.io/github/stars/ContextualAI/lens.svg?style=social&label=Star) <br> [**Towards Language Models That Can See: Computer Vision Through the LENS of Natural Language**](https://arxiv.org/pdf/2306.16410.pdf) <br> | arXiv | 2023-06-28 | [Github](https://github.com/ContextualAI/lens) | [Demo](https://lens.contextual.ai/) |
| [**Retrieving-to-Answer: Zero-Shot Video Question Answering with Frozen Large Language Models**](https://arxiv.org/pdf/2306.11732.pdf) | arXiv | 2023-06-15 | - | - |
| ![Star](https://img.shields.io/github/stars/showlab/assistgpt.svg?style=social&label=Star) <br> [**AssistGPT: A General Multi-modal Assistant that can Plan, Execute, Inspect, and Learn**](https://arxiv.org/pdf/2306.08640.pdf) <br> | arXiv | 2023-06-14 | [Github](https://github.com/showlab/assistgpt) | - |
| [**AVIS: Autonomous Visual Information Seeking with Large Language Models**](https://arxiv.org/pdf/2306.08129.pdf) | arXiv | 2023-06-13 | - | - |
| ![Star](https://img.shields.io/github/stars/StevenGrove/GPT4Tools.svg?style=social&label=Star) <br> [**GPT4Tools: Teaching Large Language Model to Use Tools via Self-instruction**](https://arxiv.org/pdf/2305.18752.pdf) <br> | arXiv | 2023-05-30 | [Github](https://github.com/StevenGrove/GPT4Tools) | [Demo](https://c60eb7e9400930f31b.gradio.live/) | 
| [**Mindstorms in Natural Language-Based Societies of Mind**](https://arxiv.org/pdf/2305.17066.pdf) | arXiv | 2023-05-26 | - | - | 
| ![Star](https://img.shields.io/github/stars/weixi-feng/LayoutGPT.svg?style=social&label=Star) <br> [**LayoutGPT: Compositional Visual Planning and Generation with Large Language Models**](https://arxiv.org/pdf/2305.15393.pdf) <br> | arXiv | 2023-05-24 | [Github](https://github.com/weixi-feng/LayoutGPT) | - |
| ![Star](https://img.shields.io/github/stars/Hxyou/IdealGPT.svg?style=social&label=Star) <br> [**IdealGPT: Iteratively Decomposing Vision and Language Reasoning via Large Language Models**](https://arxiv.org/pdf/2305.14985.pdf) <br> | arXiv | 2023-05-24 | [Github](https://github.com/Hxyou/IdealGPT) | Local Demo | 
| ![Star](https://img.shields.io/github/stars/matrix-alpha/Accountable-Textual-Visual-Chat.svg?style=social&label=Star) <br> [**Accountable Textual-Visual Chat Learns to Reject Human Instructions in Image Re-creation**](https://arxiv.org/pdf/2303.05983.pdf) <br> | arXiv | 2023-05-10 | [Github](https://github.com/matrix-alpha/Accountable-Textual-Visual-Chat) | - |
| ![Star](https://img.shields.io/github/stars/ttengwang/Caption-Anything.svg?style=social&label=Star) <br> [**Caption Anything: Interactive Image Description with Diverse Multimodal Controls**](https://arxiv.org/pdf/2305.02677.pdf) <br> | arXiv | 2023-05-04 | [Github](https://github.com/ttengwang/Caption-Anything) | [Demo](https://huggingface.co/spaces/TencentARC/Caption-Anything) |
| ![Star](https://img.shields.io/github/stars/lupantech/chameleon-llm.svg?style=social&label=Star) <br> [**Chameleon: Plug-and-Play Compositional Reasoning with Large Language Models**](https://arxiv.org/pdf/2304.09842.pdf) <br> | arXiv | 2023-04-19 | [Github](https://github.com/lupantech/chameleon-llm) | [Demo](https://chameleon-llm.github.io/) | 
| ![Star](https://img.shields.io/github/stars/microsoft/JARVIS.svg?style=social&label=Star) <br> [**HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in HuggingFace**](https://arxiv.org/pdf/2303.17580.pdf) <br> | arXiv | 2023-03-30 | [Github](https://github.com/microsoft/JARVIS) | [Demo](https://huggingface.co/spaces/microsoft/HuggingGPT) | 
| ![Star](https://img.shields.io/github/stars/microsoft/MM-REACT.svg?style=social&label=Star) <br> [**MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action**](https://arxiv.org/pdf/2303.11381.pdf) <br> | arXiv | 2023-03-20 | [Github](https://github.com/microsoft/MM-REACT) | [Demo](https://huggingface.co/spaces/microsoft-cognitive-service/mm-react) |
| ![Star](https://img.shields.io/github/stars/cvlab-columbia/viper.svg?style=social&label=Star) <br> [**ViperGPT: Visual Inference via Python Execution for Reasoning**](https://arxiv.org/pdf/2303.08128.pdf) <br> | arXiv | 2023-03-14 | [Github](https://github.com/cvlab-columbia/viper) | Local Demo | 
| ![Star](https://img.shields.io/github/stars/Vision-CAIR/ChatCaptioner.svg?style=social&label=Star) <br> [**ChatGPT Asks, BLIP-2 Answers: Automatic Questioning Towards Enriched Visual Descriptions**](https://arxiv.org/pdf/2303.06594.pdf) <br> | arXiv | 2023-03-12 | [Github](https://github.com/Vision-CAIR/ChatCaptioner) | Local Demo |
| [**ICL-D3IE: In-Context Learning with Diverse Demonstrations Updating for Document Information Extraction**](https://arxiv.org/pdf/2303.05063.pdf) | ICCV | 2023-03-09 | - | - |
| ![Star](https://img.shields.io/github/stars/microsoft/TaskMatrix.svg?style=social&label=Star) <br> [**Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models**](https://arxiv.org/pdf/2303.04671.pdf) <br> | arXiv | 2023-03-08 | [Github](https://github.com/microsoft/TaskMatrix) | [Demo](https://huggingface.co/spaces/microsoft/visual_chatgpt) |
| ![Star](https://img.shields.io/github/stars/ZrrSkywalker/CaFo.svg?style=social&label=Star) <br> [**Prompt, Generate, then Cache: Cascade of Foundation Models makes Strong Few-shot Learners**](https://arxiv.org/pdf/2303.02151.pdf) <br> | CVPR | 2023-03-03 | [Github](https://github.com/ZrrSkywalker/CaFo) | - |
| ![Star](https://img.shields.io/github/stars/salesforce/LAVIS.svg?style=social&label=Star) <br> [**From Images to Textual Prompts: Zero-shot VQA with Frozen Large Language Models**](https://arxiv.org/pdf/2212.10846.pdf) <br> | CVPR | 2022-12-21 | [Github](https://github.com/salesforce/LAVIS/tree/main/projects/img2llm-vqa) | [Demo](https://colab.research.google.com/github/salesforce/LAVIS/blob/main/projects/img2llm-vqa/img2llm_vqa.ipynb) | 
| ![Star](https://img.shields.io/github/stars/vishaal27/SuS-X.svg?style=social&label=Star) <br> [**SuS-X: Training-Free Name-Only Transfer of Vision-Language Models**](https://arxiv.org/pdf/2211.16198.pdf) <br> | arXiv | 2022-11-28 | [Github](https://github.com/vishaal27/SuS-X) | - |
| ![Star](https://img.shields.io/github/stars/yangyangyang127/PointCLIP_V2.svg?style=social&label=Star) <br> [**PointCLIP V2: Adapting CLIP for Powerful 3D Open-world Learning**](https://arxiv.org/pdf/2211.11682.pdf) <br> | CVPR | 2022-11-21 | [Github](https://github.com/yangyangyang127/PointCLIP_V2) | - |
| ![Star](https://img.shields.io/github/stars/allenai/visprog.svg?style=social&label=Star) <br> [**Visual Programming: Compositional visual reasoning without training**](https://openaccess.thecvf.com/content/CVPR2023/papers/Gupta_Visual_Programming_Compositional_Visual_Reasoning_Without_Training_CVPR_2023_paper.pdf) <br> | CVPR | 2022-11-18 | [Github](https://github.com/allenai/visprog) | Local Demo | 
| ![Star](https://img.shields.io/github/stars/google-research/google-research.svg?style=social&label=Star) <br> [**Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language**](https://arxiv.org/pdf/2204.00598.pdf) <br> | arXiv | 2022-04-01 | [Github](https://github.com/google-research/google-research/tree/master/socraticmodels) | - |


## Foundation Models
|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Gemini 1.5: Unlocking multimodal understanding across millions of tokens of context**](https://storage.googleapis.com/deepmind-media/gemini/gemini_v1_5_report.pdf) | Google | 2024-02-15 | - | - |
| [**Gemini: A Family of Highly Capable Multimodal Models**](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | Google | 2023-12-06 | - | - |
| [**Fuyu-8B: A Multimodal Architecture for AI Agents**](https://www.adept.ai/blog/fuyu-8b) | blog | 2023-10-17 | [Huggingface](https://huggingface.co/adept/fuyu-8b) | [Demo](https://huggingface.co/adept/fuyu-8b) 
| ![Star](https://img.shields.io/github/stars/mshukor/UnIVAL.svg?style=social&label=Star) <br> [**Unified Model for Image, Video, Audio and Language Tasks**](https://arxiv.org/pdf/2307.16184.pdf) <br> | arXiv | 2023-07-30 | [Github](https://github.com/mshukor/UnIVAL) | [Demo](https://huggingface.co/spaces/mshukor/UnIVAL) |
| [**PaLI-3 Vision Language Models: Smaller, Faster, Stronger**](https://arxiv.org/pdf/2310.09199.pdf) | arXiv | 2023-10-13 | - | - |
| [**GPT-4V(ision) System Card**](https://cdn.openai.com/papers/GPTV_System_Card.pdf) | OpenAI | 2023-09-25 | - | - |
| ![Star](https://img.shields.io/github/stars/jy0205/LaVIT.svg?style=social&label=Star) <br> [**Unified Language-Vision Pretraining in LLM with Dynamic Discrete Visual Tokenization**](https://arxiv.org/pdf/2309.04669.pdf) <br> | arXiv | 2023-09-09 | [Github](https://github.com/jy0205/LaVIT) | - |
| [**Multimodal Foundation Models: From Specialists to General-Purpose Assistants**](https://browse.arxiv.org/pdf/2309.10020.pdf) | arXiv | 2023-09-18 | - | - |
| ![Star](https://img.shields.io/github/stars/yiren-jian/BLIText.svg?style=social&label=Star) <br> [**Bootstrapping Vision-Language Learning with Decoupled Language Pre-training**](https://arxiv.org/pdf/2307.07063.pdf) <br> | NeurIPS | 2023-07-13 | [Github](https://github.com/yiren-jian/BLIText) | - |
| ![Star](https://img.shields.io/github/stars/baaivision/Emu.svg?style=social&label=Star) <br> [**Generative Pretraining in Multimodality**](https://arxiv.org/pdf/2307.05222.pdf) <br> | arXiv | 2023-07-11 | [Github](https://github.com/baaivision/Emu) | [Demo](http://218.91.113.230:9002/) |
| ![Star](https://img.shields.io/github/stars/microsoft/unilm.svg?style=social&label=Star) <br> [**Kosmos-2: Grounding Multimodal Large Language Models to the World**](https://arxiv.org/pdf/2306.14824.pdf) <br> | arXiv | 2023-06-26 | [Github](https://github.com/microsoft/unilm/tree/master/kosmos-2) | [Demo](https://aka.ms/kosmos-2-demo) |
| ![Star](https://img.shields.io/github/stars/VPGTrans/VPGTrans.svg?style=social&label=Star) <br> [**Transfer Visual Prompt Generator across LLMs**](https://arxiv.org/pdf/2305.01278.pdf) <br> | arXiv | 2023-05-02 | [Github](https://github.com/VPGTrans/VPGTrans) | [Demo](https://3fc7715dbc44234a7f.gradio.live/) | 
| [**GPT-4 Technical Report**](https://arxiv.org/pdf/2303.08774.pdf) | arXiv | 2023-03-15 | - | - |
| [**PaLM-E: An Embodied Multimodal Language Model**](https://arxiv.org/pdf/2303.03378.pdf) | arXiv | 2023-03-06 | - | [Demo](https://palm-e.github.io/#demo) | 
| ![Star](https://img.shields.io/github/stars/NVlabs/prismer.svg?style=social&label=Star) <br> [**Prismer: A Vision-Language Model with An Ensemble of Experts**](https://arxiv.org/pdf/2303.02506.pdf) <br> | arXiv | 2023-03-04 | [Github](https://github.com/NVlabs/prismer) | [Demo](https://huggingface.co/spaces/lorenmt/prismer) |
| ![Star](https://img.shields.io/github/stars/microsoft/unilm.svg?style=social&label=Star) <br> [**Language Is Not All You Need: Aligning Perception with Language Models**](https://arxiv.org/pdf/2302.14045.pdf) <br> | arXiv | 2023-02-27 | [Github](https://github.com/microsoft/unilm) | - |
| ![Star](https://img.shields.io/github/stars/salesforce/LAVIS.svg?style=social&label=Star) <br> [**BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models**](https://arxiv.org/pdf/2301.12597.pdf) <br> | arXiv | 2023-01-30 | [Github](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | [Demo](https://colab.research.google.com/github/salesforce/LAVIS/blob/main/examples/blip2_instructed_generation.ipynb) | 
| ![Star](https://img.shields.io/github/stars/vimalabs/VIMA.svg?style=social&label=Star) <br> [**VIMA: General Robot Manipulation with Multimodal Prompts**](https://arxiv.org/pdf/2210.03094.pdf) <br> | ICML | 2022-10-06 | [Github](https://github.com/vimalabs/VIMA) | Local Demo | 
| ![Star](https://img.shields.io/github/stars/MineDojo/MineDojo.svg?style=social&label=Star) <br> [**MineDojo: Building Open-Ended Embodied Agents with Internet-Scale Knowledge**](https://arxiv.org/pdf/2206.08853.pdf) <br> | NeurIPS | 2022-06-17 | [Github](https://github.com/MineDojo/MineDojo) | - |
| ![Star](https://img.shields.io/github/stars/shizhediao/DaVinci.svg?style=social&label=Star) <br> [**Write and Paint: Generative Vision-Language Models are Unified Modal Learners**](https://arxiv.org/pdf/2206.07699.pdf) <br> | ICLR | 2022-06-15 | [Github](https://github.com/shizhediao/DaVinci) | - |
| ![Star](https://img.shields.io/github/stars/microsoft/unilm.svg?style=social&label=Star) <br> [**Language Models are General-Purpose Interfaces**](https://arxiv.org/pdf/2206.06336.pdf) <br> | arXiv | 2022-06-13 | [Github](https://github.com/microsoft/unilm) | - |

## Evaluation
|  Title  |   Venue  |   Date   |   Page   |
|:--------|:--------:|:--------:|:--------:|
| ![Stars](https://img.shields.io/github/stars/sail-sg/MMCBench?style=social&label=Star) <br> [**Benchmarking Large Multimodal Models against Common Corruptions**](https://arxiv.org/pdf/2401.11943.pdf) <br> | arXiv | 2024-01-22 | [Github](https://github.com/sail-sg/MMCBench) |
| ![Stars](https://img.shields.io/github/stars/tsb0601/MMVP?style=social&label=Star) <br> [**Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs**](https://arxiv.org/pdf/2401.06209.pdf) <br> | arXiv | 2024-01-11 | [Github](https://github.com/tsb0601/MMVP) | 
| ![Stars](https://img.shields.io/github/stars/BradyFU/Awesome-Multimodal-Large-Language-Models?style=social&label=Star) <br> [**A Challenger to GPT-4V? Early Explorations of Gemini in Visual Expertise**](https://arxiv.org/pdf/2312.12436.pdf) <br> | arXiv | 2023-12-19 | [Github](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models) | 
| ![Stars](https://img.shields.io/github/stars/AIFEG/BenchLMM?style=social&label=Star) <br> [**BenchLMM: Benchmarking Cross-style Visual Capability of Large Multimodal Models**](https://arxiv.org/pdf/2312.02896.pdf) <br> | arXiv | 2023-12-05 | [Github](https://github.com/AIFEG/BenchLMM) |
| ![Star](https://img.shields.io/github/stars/UCSC-VLAA/vllm-safety-benchmark.svg?style=social&label=Star) <br> [**How Many Unicorns Are in This Image? A Safety Evaluation Benchmark for Vision LLMs**](https://arxiv.org/pdf/2311.16101.pdf) <br> | arXiv | 2023-11-27 | [Github](https://github.com/UCSC-VLAA/vllm-safety-benchmark) |
| ![Star](https://img.shields.io/github/stars/FreedomIntelligence/MLLM-Bench?style=social&label=Star) <br> [**MLLM-Bench, Evaluating Multi-modal LLMs using GPT-4V**](https://arxiv.org/pdf/2311.13951) <br> | arXiv | 2023-11-23 | [Github](https://github.com/FreedomIntelligence/MLLM-Bench) |
| [**VLM-Eval: A General Evaluation on Video Large Language Models**](https://arxiv.org/pdf/2311.11865.pdf) | arXiv | 2023-11-20 | [Coming soon]() |
| ![Star](https://img.shields.io/github/stars/gzcch/Bingo.svg?style=social&label=Star) <br> [**Holistic Analysis of Hallucination in GPT-4V(ision): Bias and Interference Challenges**](https://arxiv.org/pdf/2311.03287.pdf) <br> | arXiv | 2023-11-06 | [Github](https://github.com/gzcch/Bingo) |
| ![Star](https://img.shields.io/github/stars/PJLab-ADG/GPT4V-AD-Exploration.svg?style=social&label=Star) <br> [**On the Road with GPT-4V(ision): Early Explorations of Visual-Language Model on Autonomous Driving**](https://arxiv.org/pdf/2311.05332.pdf) <br> | arXiv | 2023-11-09 | [Github](https://github.com/PJLab-ADG/GPT4V-AD-Exploration) |
| [**Towards Generic Anomaly Detection and Understanding: Large-scale Visual-linguistic Model (GPT-4V) Takes the Lead**](https://arxiv.org/pdf/2311.02782.pdf) | arXiv | 2023-11-05 | - |
| [**A Comprehensive Study of GPT-4V's Multimodal Capabilities in Medical Imaging**](https://arxiv.org/pdf/2310.20381.pdf) | arXiv | 2023-10-31 | - |
| ![Star](https://img.shields.io/github/stars/albertwy/GPT-4V-Evaluation.svg?style=social&label=Star) <br> [**An Early Evaluation of GPT-4V(ision)**](https://arxiv.org/pdf/2310.16534.pdf) <br> | arXiv | 2023-10-25 | [Github](https://github.com/albertwy/GPT-4V-Evaluation) |
| ![Star](https://img.shields.io/github/stars/SCUT-DLVCLab/GPT-4V_OCR.svg?style=social&label=Star) <br> [**Exploring OCR Capabilities of GPT-4V(ision) : A Quantitative and In-depth Evaluation**](https://arxiv.org/pdf/2310.16809.pdf) <br> | arXiv | 2023-10-25 | [Github](https://github.com/SCUT-DLVCLab/GPT-4V_OCR) |
| ![Star](https://img.shields.io/github/stars/tianyi-lab/HallusionBench.svg?style=social&label=Star) <br> [**HallusionBench: You See What You Think? Or You Think What You See? An Image-Context Reasoning Benchmark Challenging for GPT-4V(ision), LLaVA-1.5, and Other Multi-modality Models**](https://arxiv.org/pdf/2310.14566.pdf) <br> | arXiv | 2023-10-23 | [Github](https://github.com/tianyi-lab/HallusionBench) |
| ![Star](https://img.shields.io/github/stars/lupantech/MathVista.svg?style=social&label=Star) <br> [**MathVista: Evaluating Math Reasoning in Visual Contexts with GPT-4V, Bard, and Other Large Multimodal Models**](https://arxiv.org/pdf/2310.02255.pdf) <br> | arXiv | 2023-10-03 | [Github](https://github.com/lupantech/MathVista) |
| ![Star](https://img.shields.io/github/stars/ys-zong/FoolyourVLLMs.svg?style=social&label=Star) <br> [**Fool Your (Vision and) Language Model With Embarrassingly Simple Permutations**](https://arxiv.org/pdf/2310.01651.pdf) <br> | arXiv | 2023-10-02 | [Github](https://github.com/ys-zong/FoolyourVLLMs) | 
| ![Star](https://img.shields.io/github/stars/mshukor/EvALign-ICL.svg?style=social&label=Star) <br> [**Beyond Task Performance: Evaluating and Reducing the Flaws of Large Multimodal Models with In-Context Learning**](https://arxiv.org/pdf/2310.00647.pdf) <br> | arXiv | 2023-10-01 | [Github](https://github.com/mshukor/EvALign-ICL) | 
| ![Star](https://img.shields.io/github/stars/zjunlp/EasyEdit.svg?style=social&label=Star) <br> [**Can We Edit Multimodal Large Language Models?**](https://arxiv.org/pdf/2310.08475.pdf) <br> | arXiv | 2023-10-12 | [Github](https://github.com/zjunlp/EasyEdit) | 
| ![Star](https://img.shields.io/github/stars/liaoning97/REVO-LION.svg?style=social&label=Star) <br> [**REVO-LION: Evaluating and Refining Vision-Language Instruction Tuning Datasets**](https://arxiv.org/pdf/2310.06594.pdf) <br> | arXiv | 2023-10-10 | [Github](https://github.com/liaoning97/REVO-LION) |
| [**The Dawn of LMMs: Preliminary Explorations with GPT-4V(vision)**](https://arxiv.org/pdf/2309.17421.pdf) | arXiv | 2023-09-29 | - |
| ![Star](https://img.shields.io/github/stars/OFA-Sys/TouchStone.svg?style=social&label=Star) <br> [**TouchStone: Evaluating Vision-Language Models by Language Models**](https://arxiv.org/pdf/2308.16890.pdf) <br>| arXiv | 2023-08-31 | [Github](https://github.com/OFA-Sys/TouchStone) |
| ![Star](https://img.shields.io/github/stars/HYPJUDY/Sparkles.svg?style=social&label=Star) <br> [**✨Sparkles: Unlocking Chats Across Multiple Images for Multimodal Instruction-Following Models**](https://arxiv.org/pdf/2308.16463.pdf) <br> | arXiv | 2023-08-31 | [Github](https://github.com/HYPJUDY/Sparkles#sparkleseval) |
| ![Star](https://img.shields.io/github/stars/findalexli/SciGraphQA.svg?style=social&label=Star) <br> [**SciGraphQA: A Large-Scale Synthetic Multi-Turn Question-Answering Dataset for Scientific Graphs**](https://arxiv.org/pdf/2308.03349.pdf) <br> | arXiv | 2023-08-07 | [Github](https://github.com/findalexli/SciGraphQA) | 
| ![Star](https://img.shields.io/github/stars/OpenGVLab/Multi-Modality-Arena.svg?style=social&label=Star) <br> [**Tiny LVLM-eHub: Early Multimodal Experiments with Bard**](https://arxiv.org/pdf/2308.03729.pdf) <br> | arXiv | 2023-08-07 | [Github](https://github.com/OpenGVLab/Multi-Modality-Arena) | 
| ![Star](https://img.shields.io/github/stars/yuweihao/MM-Vet.svg?style=social&label=Star) <br> [**MM-Vet: Evaluating Large Multimodal Models for Integrated Capabilities**](https://arxiv.org/pdf/2308.02490.pdf) <br> | arXiv | 2023-08-04 | [Github](https://github.com/yuweihao/MM-Vet) |
| ![Star](https://img.shields.io/github/stars/AILab-CVC/SEED-Bench.svg?style=social&label=Star) <br> [**SEED-Bench: Benchmarking Multimodal LLMs with Generative Comprehension**](https://arxiv.org/pdf/2307.16125.pdf) <br> | arXiv | 2023-07-30 | [Github](https://github.com/AILab-CVC/SEED-Bench) |
| ![Star](https://img.shields.io/github/stars/open-compass/MMBench.svg?style=social&label=Star) <br> [**MMBench: Is Your Multi-modal Model an All-around Player?**](https://arxiv.org/pdf/2307.06281.pdf) <br> | arXiv | 2023-07-12 | [Github](https://github.com/open-compass/MMBench) |
| ![Star](https://img.shields.io/github/stars/BradyFU/Awesome-Multimodal-Large-Language-Models.svg?style=social&label=Star) <br> [**MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models**](https://arxiv.org/pdf/2306.13394.pdf) <br> | arXiv | 2023-06-23 | [Github](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation) |
| ![Star](https://img.shields.io/github/stars/OpenGVLab/Multi-Modality-Arena.svg?style=social&label=Star) <br> [**LVLM-eHub: A Comprehensive Evaluation Benchmark for Large Vision-Language Models**](https://arxiv.org/pdf/2306.09265.pdf) <br> | arXiv | 2023-06-15 | [Github](https://github.com/OpenGVLab/Multi-Modality-Arena) | 
| ![Star](https://img.shields.io/github/stars/OpenLAMM/LAMM.svg?style=social&label=Star) <br> [**LAMM: Language-Assisted Multi-Modal Instruction-Tuning Dataset, Framework, and Benchmark**](https://arxiv.org/pdf/2306.06687.pdf) <br> | arXiv | 2023-06-11 | [Github](https://github.com/OpenLAMM/LAMM#lamm-benchmark) |
| ![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/M3Exam.svg?style=social&label=Star) <br> [**M3Exam: A Multilingual, Multimodal, Multilevel Benchmark for Examining Large Language Models**](https://arxiv.org/pdf/2306.05179.pdf) <br> | arXiv | 2023-06-08 | [Github](https://github.com/DAMO-NLP-SG/M3Exam) | 
| ![Star](https://img.shields.io/github/stars/Yuliang-Liu/MultimodalOCR.svg?style=social&label=Star) <br> [**On The Hidden Mystery of OCR in Large Multimodal Models**](https://arxiv.org/pdf/2305.07895.pdf) <br> | arXiv | 2023-05-13 | [Github](https://github.com/Yuliang-Liu/MultimodalOCR) | 

## Multimodal Hallucination
|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![Star](https://img.shields.io/github/stars/MasaiahHan/CorrelationQA.svg?style=social&label=Star) <br> [**The Instinctive Bias: Spurious Images lead to Hallucination in MLLMs**](https://arxiv.org/pdf/2402.03757.pdf) <br> | arXiv | 2024-02-06 | [Github](https://github.com/MasaiahHan/CorrelationQA) | - |
| [**A Survey on Hallucination in Large Vision-Language Models**](https://arxiv.org/pdf/2402.00253.pdf) | arXiv | 2024-02-01 | - | - |
| [**Temporal Insight Enhancement: Mitigating Temporal Hallucination in Multimodal Large Language Models**](https://arxiv.org/pdf/2401.09861.pdf) | arXiv | 2024-01-18 | - | - |
| ![Star](https://img.shields.io/github/stars/X-PLUG/mPLUG-HalOwl.svg?style=social&label=Star) <br> [**Hallucination Augmented Contrastive Learning for Multimodal Large Language Model**](https://arxiv.org/pdf/2312.06968.pdf) <br> | arXiv | 2023-12-12 | [Github](https://github.com/X-PLUG/mPLUG-HalOwl/tree/main/hacl) | - |
| ![Star](https://img.shields.io/github/stars/assafbk/mocha_code.svg?style=social&label=Star) <br> [**MOCHa: Multi-Objective Reinforcement Mitigating Caption Hallucinations**](https://arxiv.org/pdf/2312.03631.pdf) <br> | arXiv | 2023-12-06 | [Github](https://github.com/assafbk/mocha_code) | - |
| ![Star](https://img.shields.io/github/stars/Anonymousanoy/FOHE.svg?style=social&label=Star) <br> [**Mitigating Fine-Grained Hallucination by Fine-Tuning Large Vision-Language Models with Caption Rewrites**](https://arxiv.org/pdf/2312.01701.pdf) <br> | arXiv | 2023-12-04 | [Github](https://github.com/Anonymousanoy/FOHE) | - |
| ![Star](https://img.shields.io/github/stars/RLHF-V/RLHF-V.svg?style=social&label=Star) <br> [**RLHF-V: Towards Trustworthy MLLMs via Behavior Alignment from Fine-grained Correctional Human Feedback**](https://arxiv.org/pdf/2312.00849.pdf) <br> | arXiv | 2023-12-01 | [Github](https://github.com/RLHF-V/RLHF-V) | [Demo](http://120.92.209.146:8081/) |
| ![Star](https://img.shields.io/github/stars/shikiw/OPERA.svg?style=social&label=Star) <br> [**OPERA: Alleviating Hallucination in Multi-Modal Large Language Models via Over-Trust Penalty and Retrospection-Allocation**](https://arxiv.org/pdf/2311.17911.pdf) <br> | arXiv | 2023-11-29 | [Github](https://github.com/shikiw/OPERA) | - |
| ![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/VCD.svg?style=social&label=Star) <br> [**Mitigating Object Hallucinations in Large Vision-Language Models through Visual Contrastive Decoding**](https://arxiv.org/pdf/2311.16922.pdf) <br> | arXiv | 2023-11-28 | [Github](https://github.com/DAMO-NLP-SG/VCD) | - |
| [**Beyond Hallucinations: Enhancing LVLMs through Hallucination-Aware Direct Preference Optimization**](https://arxiv.org/pdf/2311.16839.pdf) | arXiv | 2023-11-28 | [Coming soon]() | - |
| [**Mitigating Hallucination in Visual Language Models with Visual Supervision**](https://arxiv.org/pdf/2311.16479.pdf) | arXiv | 2023-11-27 | - | - |
| ![Star](https://img.shields.io/github/stars/Yuqifan1117/HalluciDoctor.svg?style=social&label=Star) <br> [**HalluciDoctor: Mitigating Hallucinatory Toxicity in Visual Instruction Data**](https://arxiv.org/pdf/2311.13614.pdf) <br> | arXiv | 2023-11-22 | [Github](https://github.com/Yuqifan1117/HalluciDoctor) | - |
| ![Star](https://img.shields.io/github/stars/junyangwang0410/AMBER.svg?style=social&label=Star) <br> [**An LLM-free Multi-dimensional Benchmark for MLLMs Hallucination Evaluation**](https://arxiv.org/pdf/2311.07397.pdf) <br> | arXiv | 2023-11-13 | [Github](https://github.com/junyangwang0410/AMBER) | - |
| ![Star](https://img.shields.io/github/stars/bcdnlp/FAITHSCORE.svg?style=social&label=Star) <br> [**FAITHSCORE: Evaluating Hallucinations in Large Vision-Language Models**](https://arxiv.org/pdf/2311.01477.pdf) <br> | arXiv | 2023-11-02 | [Github](https://github.com/bcdnlp/FAITHSCORE) | - |
| ![Star](https://img.shields.io/github/stars/BradyFU/Woodpecker.svg?style=social&label=Star) <br> [**Woodpecker: Hallucination Correction for Multimodal Large Language Models**](https://arxiv.org/pdf/2310.16045.pdf) <br> | arXiv | 2023-10-24 | [Github](https://github.com/BradyFU/Woodpecker) | [Demo](https://deb6a97bae6fab67ae.gradio.live/) |
| [**Negative Object Presence Evaluation (NOPE) to Measure Object Hallucination in Vision-Language Models**](https://arxiv.org/pdf/2310.05338.pdf) | arXiv | 2023-10-09 | - | - |
| ![Star](https://img.shields.io/github/stars/bronyayang/HallE_Switch.svg?style=social&label=Star) <br> [**HallE-Switch: Rethinking and Controlling Object Existence Hallucinations in Large Vision Language Models for Detailed Caption**](https://arxiv.org/pdf/2310.01779.pdf) <br> | arXiv | 2023-10-03 | [Github](https://github.com/bronyayang/HallE_Switch) | - |
| ![Star](https://img.shields.io/github/stars/YiyangZhou/LURE.svg?style=social&label=Star) <br> [**Analyzing and Mitigating Object Hallucination in Large Vision-Language Models**](https://arxiv.org/pdf/2310.00754.pdf) <br> | ICLR | 2023-10-01 | [Github](https://github.com/YiyangZhou/LURE) | - |
| ![Star](https://img.shields.io/github/stars/llava-rlhf/LLaVA-RLHF.svg?style=social&label=Star) <br> [**Aligning Large Multimodal Models with Factually Augmented RLHF**](https://arxiv.org/pdf/2309.14525.pdf) <br> | arXiv | 2023-09-25 | [Github](https://github.com/llava-rlhf/LLaVA-RLHF) | [Demo](http://pitt.lti.cs.cmu.edu:7890/) |
| [**Evaluation and Mitigation of Agnosia in Multimodal Large Language Models**](https://arxiv.org/pdf/2309.04041.pdf) | arXiv | 2023-09-07 | - | - |
| [**CIEM: Contrastive Instruction Evaluation Method for Better Instruction Tuning**](https://arxiv.org/pdf/2309.02301.pdf) | arXiv | 2023-09-05 | - | - | 
| ![Star](https://img.shields.io/github/stars/junyangwang0410/HaELM.svg?style=social&label=Star) <br> [**Evaluation and Analysis of Hallucination in Large Vision-Language Models**](https://arxiv.org/pdf/2308.15126.pdf) <br> | arXiv | 2023-08-29 | [Github](https://github.com/junyangwang0410/HaELM) | - |
| ![Star](https://img.shields.io/github/stars/opendatalab/VIGC.svg?style=social&label=Star) <br> [**VIGC: Visual Instruction Generation and Correction**](https://arxiv.org/pdf/2308.12714.pdf) <br> | arXiv | 2023-08-24 | [Github](https://github.com/opendatalab/VIGC) | [Demo](https://opendatalab.github.io/VIGC) | 
| [**Detecting and Preventing Hallucinations in Large Vision Language Models**](https://arxiv.org/pdf/2308.06394.pdf) | arXiv | 2023-08-11 | - | - |
| ![Star](https://img.shields.io/github/stars/FuxiaoLiu/LRV-Instruction.svg?style=social&label=Star) <br> [**Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning**](https://arxiv.org/pdf/2306.14565.pdf) <br> | ICLR | 2023-06-26 | [Github](https://github.com/FuxiaoLiu/LRV-Instruction) | [Demo](https://7b6590ed039a06475d.gradio.live/) |
| ![Star](https://img.shields.io/github/stars/RUCAIBox/POPE.svg?style=social&label=Star) <br> [**Evaluating Object Hallucination in Large Vision-Language Models**](https://arxiv.org/pdf/2305.10355.pdf) <br> | EMNLP | 2023-05-17 | [Github](https://github.com/RUCAIBox/POPE) | - |

## Multimodal RLHF
|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![Star](https://img.shields.io/github/stars/vlf-silkie/VLFeedback.svg?style=social&label=Star) <br> [**Silkie: Preference Distillation for Large Visual Language Models**](https://arxiv.org/pdf/2312.10665.pdf) <br> | arXiv | 2023-12-17 | [Github](https://github.com/vlf-silkie/VLFeedback) | - |
| ![Star](https://img.shields.io/github/stars/RLHF-V/RLHF-V.svg?style=social&label=Star) <br> [**RLHF-V: Towards Trustworthy MLLMs via Behavior Alignment from Fine-grained Correctional Human Feedback**](https://arxiv.org/pdf/2312.00849.pdf) <br> | arXiv | 2023-12-01 | [Github](https://github.com/RLHF-V/RLHF-V) | [Demo](http://120.92.209.146:8081/) |
| ![Star](https://img.shields.io/github/stars/llava-rlhf/LLaVA-RLHF.svg?style=social&label=Star) <br> [**Aligning Large Multimodal Models with Factually Augmented RLHF**](https://arxiv.org/pdf/2309.14525.pdf) <br> | arXiv | 2023-09-25 | [Github](https://github.com/llava-rlhf/LLaVA-RLHF) | [Demo](http://pitt.lti.cs.cmu.edu:7890/) |

## Others
|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![Star](https://img.shields.io/github/stars/SHI-Labs/VCoder.svg?style=social&label=Star) <br> [**VCoder: Versatile Vision Encoders for Multimodal Large Language Models**](https://arxiv.org/pdf/2312.14233.pdf) <br> | arXiv | 2023-12-21 | [Github](https://github.com/SHI-Labs/VCoder) | Local Demo | 
| ![Star](https://img.shields.io/github/stars/dvlab-research/Prompt-Highlighter.svg?style=social&label=Star) <br> [**Prompt Highlighter: Interactive Control for Multi-Modal LLMs**](https://arxiv.org/pdf/2312.04302.pdf) <br> | arXiv | 2023-12-07 | [Github](https://github.com/dvlab-research/Prompt-Highlighter) | - |
| ![Star](https://img.shields.io/github/stars/AIlab-CVC/SEED.svg?style=social&label=Star) <br> [**Planting a SEED of Vision in Large Language Model**](https://arxiv.org/pdf/2307.08041.pdf) <br> | arXiv | 2023-07-16 | [Github](https://github.com/AILab-CVC/SEED) |
| ![Star](https://img.shields.io/github/stars/huawei-noah/Efficient-Computing.svg?style=social&label=Star) <br> [**Can Large Pre-trained Models Help Vision Models on Perception Tasks?**](https://arxiv.org/pdf/2306.00693.pdf) <br> | arXiv | 2023-06-01 | [Github](https://github.com/huawei-noah/Efficient-Computing/tree/master/GPT4Image/) | - | 
| ![Star](https://img.shields.io/github/stars/yuhangzang/ContextDET.svg?style=social&label=Star) <br> [**Contextual Object Detection with Multimodal Large Language Models**](https://arxiv.org/pdf/2305.18279.pdf) <br> | arXiv | 2023-05-29 | [Github](https://github.com/yuhangzang/ContextDET) | [Demo](https://huggingface.co/spaces/yuhangzang/ContextDet-Demo) |
| ![Star](https://img.shields.io/github/stars/kohjingyu/gill.svg?style=social&label=Star) <br> [**Generating Images with Multimodal Language Models**](https://arxiv.org/pdf/2305.17216.pdf) <br> | arXiv | 2023-05-26 | [Github](https://github.com/kohjingyu/gill) | - |
| ![Star](https://img.shields.io/github/stars/yunqing-me/AttackVLM.svg?style=social&label=Star) <br> [**On Evaluating Adversarial Robustness of Large Vision-Language Models**](https://arxiv.org/pdf/2305.16934.pdf) <br> | arXiv | 2023-05-26 | [Github](https://github.com/yunqing-me/AttackVLM) | - | 
| ![Star](https://img.shields.io/github/stars/kohjingyu/fromage.svg?style=social&label=Star) <br> [**Grounding Language Models to Images for Multimodal Inputs and Outputs**](https://arxiv.org/pdf/2301.13823.pdf) <br> | ICML | 2023-01-31 | [Github](https://github.com/kohjingyu/fromage) | [Demo](https://huggingface.co/spaces/jykoh/fromage) |

---

# Awesome Datasets

## Datasets of Pre-Training for Alignment
| Name | Paper | Type | Modalities |
|:-----|:-----:|:----:|:----------:|
| **COYO-700M** | [COYO-700M: Image-Text Pair Dataset](https://github.com/kakaobrain/coyo-dataset/) | Caption | Image-Text |
| **ShareGPT4V** | [ShareGPT4V: Improving Large Multi-Modal Models with Better Captions](https://arxiv.org/pdf/2311.12793.pdf) | Caption | Image-Text |
| **AS-1B** | [The All-Seeing Project: Towards Panoptic Visual Recognition and Understanding of the Open World](https://arxiv.org/pdf/2308.01907.pdf) | Hybrid | Image-Text |
| **InternVid** | [InternVid: A Large-scale Video-Text Dataset for Multimodal Understanding and Generation](https://arxiv.org/pdf/2307.06942.pdf) | Caption | Video-Text |
| **MS-COCO** | [Microsoft COCO: Common Objects in Context](https://arxiv.org/pdf/1405.0312.pdf) | Caption | Image-Text |
| **SBU Captions** | [Im2Text: Describing Images Using 1 Million Captioned Photographs](https://proceedings.neurips.cc/paper/2011/file/5dd9db5e033da9c6fb5ba83c7a7ebea9-Paper.pdf) | Caption | Image-Text |
| **Conceptual Captions** | [Conceptual Captions: A Cleaned, Hypernymed, Image Alt-text Dataset For Automatic Image Captioning](https://aclanthology.org/P18-1238.pdf) | Caption | Image-Text |
| **LAION-400M** | [LAION-400M: Open Dataset of CLIP-Filtered 400 Million Image-Text Pairs](https://arxiv.org/pdf/2111.02114.pdf) | Caption | Image-Text |
| **VG Captions** |[Visual Genome: Connecting Language and Vision Using Crowdsourced Dense Image Annotations](https://link.springer.com/content/pdf/10.1007/s11263-016-0981-7.pdf) | Caption | Image-Text |
| **Flickr30k** | [Flickr30k Entities: Collecting Region-to-Phrase Correspondences for Richer Image-to-Sentence Models](https://openaccess.thecvf.com/content_iccv_2015/papers/Plummer_Flickr30k_Entities_Collecting_ICCV_2015_paper.pdf) | Caption | Image-Text |
| **AI-Caps** | [AI Challenger : A Large-scale Dataset for Going Deeper in Image Understanding](https://arxiv.org/pdf/1711.06475.pdf) | Caption | Image-Text | 
| **Wukong Captions** | [Wukong: A 100 Million Large-scale Chinese Cross-modal Pre-training Benchmark](https://proceedings.neurips.cc/paper_files/paper/2022/file/a90b9a09a6ee43d6631cf42e225d73b4-Paper-Datasets_and_Benchmarks.pdf) | Caption | Image-Text |
| **GRIT** | [Kosmos-2: Grounding Multimodal Large Language Models to the World](https://arxiv.org/pdf/2306.14824.pdf) | Caption | Image-Text-Bounding-Box |
| **Youku-mPLUG** | [Youku-mPLUG: A 10 Million Large-scale Chinese Video-Language Dataset for Pre-training and Benchmarks](https://arxiv.org/pdf/2306.04362.pdf) | Caption | Video-Text |
| **MSR-VTT** | [MSR-VTT: A Large Video Description Dataset for Bridging Video and Language](https://openaccess.thecvf.com/content_cvpr_2016/papers/Xu_MSR-VTT_A_Large_CVPR_2016_paper.pdf) | Caption | Video-Text |
| **Webvid10M** | [Frozen in Time: A Joint Video and Image Encoder for End-to-End Retrieval](https://arxiv.org/pdf/2104.00650.pdf) | Caption | Video-Text |
| **WavCaps** | [WavCaps: A ChatGPT-Assisted Weakly-Labelled Audio Captioning Dataset for Audio-Language Multimodal Research](https://arxiv.org/pdf/2303.17395.pdf) | Caption | Audio-Text |
| **AISHELL-1** | [AISHELL-1: An open-source Mandarin speech corpus and a speech recognition baseline](https://arxiv.org/pdf/1709.05522.pdf) | ASR | Audio-Text |
| **AISHELL-2** | [AISHELL-2: Transforming Mandarin ASR Research Into Industrial Scale](https://arxiv.org/pdf/1808.10583.pdf) | ASR | Audio-Text |
| **VSDial-CN** | [X-LLM: Bootstrapping Advanced Large Language Models by Treating Multi-Modalities as Foreign Languages](https://arxiv.org/pdf/2305.04160.pdf) | ASR | Image-Audio-Text |


## Datasets of Multimodal Instruction Tuning
| Name | Paper | Link | Notes |
|:-----|:-----:|:----:|:-----:|
| **M3DBench** | [M3DBench: Let's Instruct Large Models with Multi-modal 3D Prompts](https://arxiv.org/pdf/2312.10763.pdf) | [Link](https://github.com/OpenM3D/M3DBench) | A large-scale 3D instruction tuning dataset |
| **ViP-LLaVA-Instruct** | [Making Large Multimodal Models Understand Arbitrary Visual Prompts](https://arxiv.org/pdf/2312.00784.pdf) | [Link](https://huggingface.co/datasets/mucai/ViP-LLaVA-Instruct) |  A mixture of LLaVA-1.5 instruction data and the region-level visual prompting data |
| **LVIS-Instruct4V** | [To See is to Believe: Prompting GPT-4V for Better Visual Instruction Tuning](https://arxiv.org/pdf/2311.07574.pdf) | [Link](https://huggingface.co/datasets/X2FD/LVIS-Instruct4V) | A visual instruction dataset via self-instruction from GPT-4V |
| **ComVint** | [What Makes for Good Visual Instructions? Synthesizing Complex Visual Reasoning Instructions for Visual Instruction Tuning](https://arxiv.org/pdf/2311.01487.pdf) | [Link](https://github.com/RUCAIBox/ComVint#comvint-data) | A synthetic instruction dataset for complex visual reasoning |
| **SparklesDialogue** | [✨Sparkles: Unlocking Chats Across Multiple Images for Multimodal Instruction-Following Models](https://arxiv.org/pdf/2308.16463.pdf) | [Link](https://github.com/HYPJUDY/Sparkles#sparklesdialogue) | A machine-generated dialogue dataset tailored for word-level interleaved multi-image and text interactions to augment the conversational competence of instruction-following LLMs across multiple images and dialogue turns. |
| **StableLLaVA** | [StableLLaVA: Enhanced Visual Instruction Tuning with Synthesized Image-Dialogue Data](https://arxiv.org/pdf/2308.10253v1.pdf) | [Link](https://github.com/icoz69/StableLLAVA) | A cheap and effective approach to collect visual instruction tuning data |
| **M-HalDetect** | [Detecting and Preventing Hallucinations in Large Vision Language Models](https://arxiv.org/pdf/2308.06394.pdf) | [Coming soon]() | A dataset used to train and benchmark models for hallucination detection and prevention | 
| **MGVLID** | [ChatSpot: Bootstrapping Multimodal LLMs via Precise Referring Instruction Tuning](https://arxiv.org/pdf/2307.09474.pdf) | - | A high-quality instruction-tuning dataset including image-text and region-text pairs |
| **BuboGPT** | [BuboGPT: Enabling Visual Grounding in Multi-Modal LLMs](https://arxiv.org/pdf/2307.08581.pdf) | [Link](https://huggingface.co/datasets/magicr/BuboGPT) | A high-quality instruction-tuning dataset including audio-text audio caption data and audio-image-text localization data |
| **SVIT** | [SVIT: Scaling up Visual Instruction Tuning](https://arxiv.org/pdf/2307.04087.pdf) | [Link](https://huggingface.co/datasets/BAAI/SVIT) | A large-scale dataset with 4.2M informative visual instruction tuning data, including conversations, detailed descriptions, complex reasoning and referring QAs |
| **mPLUG-DocOwl** | [mPLUG-DocOwl: Modularized Multimodal Large Language Model for Document Understanding](https://arxiv.org/pdf/2307.02499.pdf) | [Link](https://github.com/X-PLUG/mPLUG-DocOwl/tree/main/DocLLM) | An instruction tuning dataset featuring a wide range of visual-text understanding tasks including OCR-free document understanding | 
| **PF-1M** | [Visual Instruction Tuning with Polite Flamingo](https://arxiv.org/pdf/2307.01003.pdf) | [Link](https://huggingface.co/datasets/chendelong/PF-1M/tree/main) | A collection of 37 vision-language datasets with responses rewritten by Polite Flamingo. | 
| **ChartLlama** | [ChartLlama: A Multimodal LLM for Chart Understanding and Generation](https://arxiv.org/pdf/2311.16483.pdf) | [Link](https://huggingface.co/datasets/listen2you002/ChartLlama-Dataset) | A multi-modal instruction-tuning dataset for chart understanding and generation |
| **LLaVAR** | [LLaVAR: Enhanced Visual Instruction Tuning for Text-Rich Image Understanding](https://arxiv.org/pdf/2306.17107.pdf) | [Link](https://llavar.github.io/#data) | A visual instruction-tuning dataset for Text-rich Image Understanding | 
| **MotionGPT** | [MotionGPT: Human Motion as a Foreign Language](https://arxiv.org/pdf/2306.14795.pdf) | [Link](https://github.com/OpenMotionLab/MotionGPT) | A instruction-tuning dataset including multiple human motion-related tasks |
| **LRV-Instruction** | [Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning](https://arxiv.org/pdf/2306.14565.pdf) | [Link](https://github.com/FuxiaoLiu/LRV-Instruction#visual-instruction-data-lrv-instruction) | Visual instruction tuning dataset for addressing hallucination issue | 
| **Macaw-LLM** | [Macaw-LLM: Multi-Modal Language Modeling with Image, Audio, Video, and Text Integration](https://arxiv.org/pdf/2306.09093.pdf) | [Link](https://github.com/lyuchenyang/Macaw-LLM/tree/main/data) | A large-scale multi-modal instruction dataset in terms of multi-turn dialogue | 
| **LAMM-Dataset** | [LAMM: Language-Assisted Multi-Modal Instruction-Tuning Dataset, Framework, and Benchmark](https://arxiv.org/pdf/2306.06687.pdf) | [Link](https://github.com/OpenLAMM/LAMM#lamm-dataset) | A comprehensive multi-modal instruction tuning dataset |
| **Video-ChatGPT** | [Video-ChatGPT: Towards Detailed Video Understanding via Large Vision and Language Models](https://arxiv.org/pdf/2306.05424.pdf) | [Link](https://github.com/mbzuai-oryx/Video-ChatGPT#video-instruction-dataset-open_file_folder) | 100K high-quality video instruction dataset | 
| **MIMIC-IT** | [MIMIC-IT: Multi-Modal In-Context Instruction Tuning](https://arxiv.org/pdf/2306.05425.pdf) | [Link](https://github.com/Luodian/Otter/blob/main/mimic-it/README.md) | Multimodal in-context instruction tuning |
| **M<sup>3</sup>IT** | [M<sup>3</sup>IT: A Large-Scale Dataset towards Multi-Modal Multilingual Instruction Tuning](https://arxiv.org/pdf/2306.04387.pdf) | [Link](https://huggingface.co/datasets/MMInstruction/M3IT) | Large-scale, broad-coverage multimodal instruction tuning dataset | 
| **LLaVA-Med** | [LLaVA-Med: Training a Large Language-and-Vision Assistant for Biomedicine in One Day](https://arxiv.org/pdf/2306.00890.pdf) | [Coming soon](https://github.com/microsoft/LLaVA-Med#llava-med-dataset) | A large-scale, broad-coverage biomedical instruction-following dataset |
| **GPT4Tools** | [GPT4Tools: Teaching Large Language Model to Use Tools via Self-instruction](https://arxiv.org/pdf/2305.18752.pdf) | [Link](https://github.com/StevenGrove/GPT4Tools#dataset) | Tool-related instruction datasets |
| **MULTIS** | [ChatBridge: Bridging Modalities with Large Language Model as a Language Catalyst](https://arxiv.org/pdf/2305.16103.pdf) | [Coming soon](https://iva-chatbridge.github.io/) | Multimodal instruction tuning dataset covering 16 multimodal tasks |
| **DetGPT** | [DetGPT: Detect What You Need via Reasoning](https://arxiv.org/pdf/2305.14167.pdf) | [Link](https://github.com/OptimalScale/DetGPT/tree/main/dataset) |  Instruction-tuning dataset with 5000 images and around 30000 query-answer pairs|
| **PMC-VQA** | [PMC-VQA: Visual Instruction Tuning for Medical Visual Question Answering](https://arxiv.org/pdf/2305.10415.pdf) | [Coming soon](https://xiaoman-zhang.github.io/PMC-VQA/) | Large-scale medical visual question-answering dataset |
| **VideoChat** | [VideoChat: Chat-Centric Video Understanding](https://arxiv.org/pdf/2305.06355.pdf) | [Link](https://github.com/OpenGVLab/InternVideo/tree/main/Data/instruction_data) | Video-centric multimodal instruction dataset |
| **X-LLM** | [X-LLM: Bootstrapping Advanced Large Language Models by Treating Multi-Modalities as Foreign Languages](https://arxiv.org/pdf/2305.04160.pdf) | [Link](https://github.com/phellonchen/X-LLM) | Chinese multimodal instruction dataset |
| **LMEye** | [LMEye: An Interactive Perception Network for Large Language Models](https://arxiv.org/pdf/2305.03701.pdf) | [Link](https://huggingface.co/datasets/YunxinLi/Multimodal_Insturction_Data_V2) | A multi-modal instruction-tuning dataset |
| **cc-sbu-align** | [MiniGPT-4: Enhancing Vision-Language Understanding with Advanced Large Language Models](https://arxiv.org/pdf/2304.10592.pdf) | [Link](https://huggingface.co/datasets/Vision-CAIR/cc_sbu_align) | Multimodal aligned dataset for improving model's usability and generation's fluency |
| **LLaVA-Instruct-150K** | [Visual Instruction Tuning](https://arxiv.org/pdf/2304.08485.pdf) | [Link](https://huggingface.co/datasets/liuhaotian/LLaVA-Instruct-150K) | Multimodal instruction-following data generated by GPT|
| **MultiInstruct** | [MultiInstruct: Improving Multi-Modal Zero-Shot Learning via Instruction Tuning](https://arxiv.org/pdf/2212.10773.pdf) | [Link](https://github.com/VT-NLP/MultiInstruct) | The first multimodal instruction tuning benchmark dataset |

## Datasets of In-Context Learning
| Name | Paper | Link | Notes |
|:-----|:-----:|:----:|:-----:|
| **MIC** | [MMICL: Empowering Vision-language Model with Multi-Modal In-Context Learning](https://arxiv.org/pdf/2309.07915.pdf) | [Link](https://huggingface.co/datasets/BleachNick/MIC_full) | A manually constructed instruction tuning dataset including interleaved text-image inputs, inter-related multiple image inputs, and multimodal in-context learning inputs. |
| **MIMIC-IT** | [MIMIC-IT: Multi-Modal In-Context Instruction Tuning](https://arxiv.org/pdf/2306.05425.pdf) | [Link](https://github.com/Luodian/Otter/blob/main/mimic-it/README.md) | Multimodal in-context instruction dataset|

## Datasets of Multimodal Chain-of-Thought
| Name | Paper | Link | Notes |
|:-----|:-----:|:----:|:-----:|
| **EMER** | [Explainable Multimodal Emotion Reasoning](https://arxiv.org/pdf/2306.15401.pdf) | [Coming soon](https://github.com/zeroQiaoba/Explainable-Multimodal-Emotion-Reasoning) | A benchmark dataset for explainable emotion reasoning task |
| **EgoCOT** | [EmbodiedGPT: Vision-Language Pre-Training via Embodied Chain of Thought](https://arxiv.org/pdf/2305.15021.pdf) | [Coming soon](https://github.com/EmbodiedGPT/EmbodiedGPT_Pytorch) | Large-scale embodied planning dataset |
| **VIP** | [Let’s Think Frame by Frame: Evaluating Video Chain of Thought with Video Infilling and Prediction](https://arxiv.org/pdf/2305.13903.pdf) | [Coming soon]() | An inference-time dataset that can be used to evaluate VideoCOT |
| **ScienceQA** | [Learn to Explain: Multimodal Reasoning via Thought Chains for Science Question Answering](https://proceedings.neurips.cc/paper_files/paper/2022/file/11332b6b6cf4485b84afadb1352d3a9a-Paper-Conference.pdf) | [Link](https://github.com/lupantech/ScienceQA#ghost-download-the-dataset) | Large-scale multi-choice dataset, featuring multimodal science questions and diverse domains | 

## Datasets of Multimodal RLHF
| Name | Paper | Link | Notes |
|:-----|:-----:|:----:|:-----:|
| **VLFeedback** | [Silkie: Preference Distillation for Large Visual Language Models](https://arxiv.org/pdf/2312.10665.pdf) | [Link](https://huggingface.co/datasets/MMInstruction/VLFeedback) | A vision-language feedback dataset annotated by AI |

## Benchmarks for Evaluation
| Name | Paper | Link | Notes |
|:-----|:-----:|:----:|:-----:|
| **CMMMU** | [CMMMU: A Chinese Massive Multi-discipline Multimodal Understanding Benchmark](https://arxiv.org/pdf/2401.11944.pdf) | [Link](https://github.com/CMMMU-Benchmark/CMMMU) | A Chinese benchmark involving reasoning and knowledge across multiple disciplines |
| **MMCBench** | [Benchmarking Large Multimodal Models against Common Corruptions](https://arxiv.org/pdf/2401.11943.pdf) | [Link](https://github.com/sail-sg/MMCBench) | A benchmark for examining self-consistency under common corruptions |
| **MMVP** | [Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs](https://arxiv.org/pdf/2401.06209.pdf) | [Link](https://github.com/tsb0601/MMVP) | A benchmark for assessing visual capabilities |
| **TimeIT** | [TimeChat: A Time-sensitive Multimodal Large Language Model for Long Video Understanding](https://arxiv.org/pdf/2312.02051.pdf) | [Link](https://huggingface.co/datasets/ShuhuaiRen/TimeIT) | A video instruction-tuning dataset with timestamp annotations, covering diverse time-sensitive video-understanding tasks. |
| **ViP-Bench** | [Making Large Multimodal Models Understand Arbitrary Visual Prompts](https://arxiv.org/pdf/2312.00784.pdf) | [Link](https://huggingface.co/datasets/mucai/ViP-Bench) | A benchmark for visual prompts |
| **M3DBench** | [M3DBench: Let's Instruct Large Models with Multi-modal 3D Prompts](https://arxiv.org/pdf/2312.10763.pdf) | [Link](https://github.com/OpenM3D/M3DBench) | A 3D-centric benchmark |
| **Video-Bench** | [Video-Bench: A Comprehensive Benchmark and Toolkit for Evaluating Video-based Large Language Models](https://arxiv.org/pdf/2311.16103.pdf) | [Link](https://github.com/PKU-YuanGroup/Video-Bench) | A benchmark for video-MLLM evaluation |
| **MLLM-Bench** | [MLLM-Bench, Evaluating Multi-modal LLMs using GPT-4V](https://arxiv.org/pdf/2311.13951.pdf) | [Link](https://github.com/FreedomIntelligence/MLLM-Bench) | GPT-4V evaluation with per-sample criteria |
| **BenchLMM** | [BenchLMM: Benchmarking Cross-style Visual Capability of Large Multimodal Models](https://arxiv.org/pdf/2312.02896.pdf) | [Link](https://huggingface.co/datasets/AIFEG/BenchLMM) | A benchmark for assessment of the robustness against different image styles |
| **MMC-Benchmark** | [MMC: Advancing Multimodal Chart Understanding with Large-scale Instruction Tuning](https://arxiv.org/pdf/2311.10774.pdf) | [Link](https://github.com/FuxiaoLiu/MMC) | A comprehensive human-annotated benchmark with distinct tasks evaluating reasoning capabilities over charts |
| **MVBench** | [MVBench: A Comprehensive Multi-modal Video Understanding Benchmark](https://arxiv.org/pdf/2311.17005.pdf) | [Link](https://github.com/OpenGVLab/Ask-Anything/blob/main/video_chat2/MVBENCH.md) | A comprehensive multimodal benchmark for video understanding |
| **Bingo** | [Holistic Analysis of Hallucination in GPT-4V(ision): Bias and Interference Challenges](https://arxiv.org/pdf/2311.03287.pdf) | [Link](https://github.com/gzcch/Bingo) | A benchmark for hallucination evaluation that focuses on two common types |
| **MagnifierBench** | [OtterHD: A High-Resolution Multi-modality Model](https://arxiv.org/pdf/2311.04219.pdf) | [Link](https://huggingface.co/datasets/Otter-AI/MagnifierBench) | A benchmark designed to probe models' ability of fine-grained perception |
| **HallusionBench** | [HallusionBench: You See What You Think? Or You Think What You See? An Image-Context Reasoning Benchmark Challenging for GPT-4V(ision), LLaVA-1.5, and Other Multi-modality Models](https://arxiv.org/pdf/2310.14566.pdf) | [Link](https://github.com/tianyi-lab/HallusionBench) |An image-context reasoning benchmark for evaluation of hallucination |
| **PCA-EVAL** | [Towards End-to-End Embodied Decision Making via Multi-modal Large Language Model: Explorations with GPT4-Vision and Beyond](https://arxiv.org/pdf/2310.02071.pdf) | [Link](https://github.com/pkunlp-icler/PCA-EVAL) | A benchmark for evaluating multi-domain embodied decision-making. |
| **MMHal-Bench** | [Aligning Large Multimodal Models with Factually Augmented RLHF](https://arxiv.org/pdf/2309.14525.pdf) | [Link](https://huggingface.co/datasets/Shengcao1006/MMHal-Bench) | A benchmark for hallucination evaluation |
| **MathVista** | [MathVista: Evaluating Math Reasoning in Visual Contexts with GPT-4V, Bard, and Other Large Multimodal Models](https://arxiv.org/pdf/2310.02255.pdf) | [Link](https://huggingface.co/datasets/AI4Math/MathVista) | A benchmark that challenges both visual and math reasoning capabilities |
| **SparklesEval** | [✨Sparkles: Unlocking Chats Across Multiple Images for Multimodal Instruction-Following Models](https://arxiv.org/pdf/2308.16463.pdf) | [Link](https://github.com/HYPJUDY/Sparkles#sparkleseval) | A GPT-assisted benchmark for quantitatively assessing a model's conversational competence across multiple images and dialogue turns based on three distinct criteria. |
| **ISEKAI** | [Link-Context Learning for Multimodal LLMs](https://arxiv.org/pdf/2308.07891.pdf) | [Link](https://huggingface.co/ISEKAI-Portal) | A benchmark comprising exclusively of unseen generated image-label pairs designed for link-context learning |
| **M-HalDetect** | [Detecting and Preventing Hallucinations in Large Vision Language Models](https://arxiv.org/pdf/2308.06394.pdf) | [Coming soon]() | A dataset used to train and benchmark models for hallucination detection and prevention | 
| **I4** | [Empowering Vision-Language Models to Follow Interleaved Vision-Language Instructions](https://arxiv.org/pdf/2308.04152.pdf) | [Link](https://github.com/DCDmllm/Cheetah) | A benchmark to comprehensively evaluate the instruction following ability on complicated interleaved vision-language instructions | 
| **SciGraphQA** | [SciGraphQA: A Large-Scale Synthetic Multi-Turn Question-Answering Dataset for Scientific Graphs](https://arxiv.org/pdf/2308.03349.pdf) | [Link](https://github.com/findalexli/SciGraphQA#data) | A large-scale chart-visual question-answering dataset |
| **MM-Vet**| [MM-Vet: Evaluating Large Multimodal Models for Integrated Capabilities](https://arxiv.org/pdf/2308.02490.pdf) | [Link](https://github.com/yuweihao/MM-Vet) | An evaluation benchmark that examines large multimodal models on complicated multimodal tasks |
| **SEED-Bench** | [SEED-Bench: Benchmarking Multimodal LLMs with Generative Comprehension](https://arxiv.org/pdf/2307.16125.pdf) | [Link](https://github.com/AILab-CVC/SEED-Bench) | A benchmark for evaluation of generative comprehension in MLLMs | 
| **MMBench** | [MMBench: Is Your Multi-modal Model an All-around Player?](https://arxiv.org/pdf/2307.06281.pdf) | [Link](https://github.com/open-compass/MMBench) | A systematically-designed objective benchmark for robustly evaluating the various abilities of vision-language models|
| **Lynx** | [What Matters in Training a GPT4-Style Language Model with Multimodal Inputs?](https://arxiv.org/pdf/2307.02469.pdf) | [Link](https://github.com/bytedance/lynx-llm#prepare-data) |  A comprehensive evaluation benchmark including both image and video tasks |
| **GAVIE** | [Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning](https://arxiv.org/pdf/2306.14565.pdf) | [Link](https://github.com/FuxiaoLiu/LRV-Instruction#evaluationgavie) | A benchmark to evaluate the hallucination and instruction following ability | 
| **MME** | [MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models](https://arxiv.org/pdf/2306.13394.pdf) | [Link](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation) | A comprehensive MLLM Evaluation benchmark |
| **LVLM-eHub** | [LVLM-eHub: A Comprehensive Evaluation Benchmark for Large Vision-Language Models](https://arxiv.org/pdf/2306.09265.pdf) | [Link](https://github.com/OpenGVLab/Multi-Modality-Arena) | An evaluation platform for MLLMs |
| **LAMM-Benchmark** | [LAMM: Language-Assisted Multi-Modal Instruction-Tuning Dataset, Framework, and Benchmark](https://arxiv.org/pdf/2306.06687.pdf) | [Link](https://github.com/OpenLAMM/LAMM#lamm-benchmark) | A benchmark for evaluating  the quantitative performance of MLLMs on various2D/3D vision tasks |
| **M3Exam** | [M3Exam: A Multilingual, Multimodal, Multilevel Benchmark for Examining Large Language Models](https://arxiv.org/pdf/2306.05179.pdf) | [Link](https://github.com/DAMO-NLP-SG/M3Exam) |  A multilingual, multimodal, multilevel benchmark for evaluating MLLM |
| **OwlEval** | [mPLUG-Owl: Modularization Empowers Large Language Models with Multimodality](https://arxiv.org/pdf/2304.14178.pdf) | [Link](https://github.com/X-PLUG/mPLUG-Owl/tree/main/OwlEval) | Dataset for evaluation on multiple capabilities |

## Others
| Name | Paper | Link | Notes |
|:-----|:-----:|:----:|:-----:|
| **IMAD** | [IMAD: IMage-Augmented multi-modal Dialogue](https://arxiv.org/pdf/2305.10512.pdf) | [Link](https://github.com/VityaVitalich/IMAD) | Multimodal dialogue dataset|
| **Video-ChatGPT** | [Video-ChatGPT: Towards Detailed Video Understanding via Large Vision and Language Models](https://arxiv.org/pdf/2306.05424.pdf) | [Link](https://github.com/mbzuai-oryx/Video-ChatGPT#quantitative-evaluation-bar_chart) | A quantitative evaluation framework for video-based dialogue models |
| **CLEVR-ATVC** | [Accountable Textual-Visual Chat Learns to Reject Human Instructions in Image Re-creation](https://arxiv.org/pdf/2303.05983.pdf) | [Link](https://drive.google.com/drive/folders/1TqBzkyqxOSg1hgCXF8JjpYIAuRV-uVft) | A synthetic multimodal fine-tuning dataset for learning to reject instructions |
| **Fruit-ATVC** | [Accountable Textual-Visual Chat Learns to Reject Human Instructions in Image Re-creation](https://arxiv.org/pdf/2303.05983.pdf) | [Link](https://drive.google.com/drive/folders/1Saaia2rRRb1nz5sKdmpzYdS4jHiMDaP0) | A manually pictured multimodal fine-tuning dataset for learning to reject instructions |
| **InfoSeek** | [Can Pre-trained Vision and Language Models Answer Visual Information-Seeking Questions?](https://arxiv.org/pdf/2302.11713.pdf) | [Link](https://open-vision-language.github.io/infoseek/) | A VQA dataset that focuses on asking information-seeking questions |
| **OVEN** | [Open-domain Visual Entity Recognition: Towards Recognizing Millions of Wikipedia Entities](https://arxiv.org/pdf/2302.11154.pdf) | [Link](https://open-vision-language.github.io/oven/) | A dataset that focuses on recognizing the Visual Entity on the Wikipedia, from images in the wild |
