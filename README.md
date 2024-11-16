# 论文整理

---

## 医疗视觉语言模型
| 时间       | 机构                    | 论文名                                                                                       |
|------------|-------------------------|---------------------------------------------------------------------------------------------|
| 2023.5     | Lehigh University       | BiomedGPT: A generalist vision–language foundation model for diverse biomedical tasks       |
| 2023.5     | 上海AI Lab              | PMC-VQA: Visual instruction tuning for medical visual question answering                    |
| 2023.6     | 微软                    | LLaVA-Med: Training a Large Language-and-Vision Assistant for Biomedicine in One Day        |
| 2023.7     | 谷歌                    | Towards Generalist Biomedical AI                                                           |
| 2023.7     | 斯坦福                   | MED-FLAMINGO: A MULTIMODAL MEDICAL FEWSHOT LEARNER                                          |
| 2023.6     | 清华深圳                 | OphGLM: Training an Ophthalmology Large Language-and-Vision Assistant based on Instructions and Dialogue |
| 2023.8     | 上交                    | Towards Generalist Foundation Model for Radiology by Leveraging Web-scale 2D&3D Medical Data |
| 2024.7     | 多伦多大学               | LiteGPT: Large Vision-Language Model for Joint Chest X-ray Localization and Classification Task |
| 2024.7     | University of California | Prompting Medical Large Vision-Language Models to Diagnose Pathologies by Visual Question Answering |
| 2024.3     | 北京人工智能研究院       | M3D: Advancing 3D Medical Image Analysis with Multi-Modal Large Language Models             |
| 2023.12    | 华盛顿大学               | Quilt-LLaVA: Visual Instruction Tuning by Extracting Localized Narratives from Open-Source Histopathology Videos |
| 2024.7     | 上海AI Lab              | Cost-effective Instruction Learning for Pathology Vision and Language Analysis              |
| 2024.8     | 重邮                    | PA-LLaVA: A Large Language-Vision Assistant for Human Pathology Image Understanding         |
| 2024.6     | 斯坦福                   | Biomedical Visual Instruction Tuning with Clinician Preference Alignment                    |
| 2024.6     | 港中文                   | HuatuoGPT-Vision, Towards Injecting Medical Visual Knowledge into Multimodal LLMs at Scale  |
| 2024.6     | 某公司                   | Advancing High Resolution Vision-Language Models in Biomedicine                             |
| 2024.6     | Salesforce              | STLLaVA-Med: Self-Training Large Language and Vision Assistant for Medical                  |
| 2024.4     | 浙大                    | Med-MoE: Mixture of Domain-Specific Experts for Lightweight Medical Vision-Language Models  |
| 2024.1     | 哈工                    | PeFoMed: Parameter Efficient Fine-tuning of Multimodal Large Language Models for Medical Imaging |


## RAG+MedVLM

| 时间      | 机构               | 论文名                                                                                       |
|---------|------------------|---------------------------------------------------------------------------------------------|
| 2023    | 阿里               | RAMM: Retrieval-augmented biomedical visual question answering with multi-modal pre-training |
| 2024    | Aalto University | Improving medical multi-modal contrastive learning with expert annotations                  |
| 2024    | 上海大学             | Memory-based cross-modal semantic alignment network for radiology report generation         |
| 2024.4  | 香港科技大学           | MedDR: Diagnosis-guided bootstrapping for large-scale medical vision-language learning      |
| 2024    | CMU              | Fact-aware multimodal retrieval augmentation for accurate medical radiology report generation |
| 2024.7  | UNC-ChapelHill   | RULE: Reliable multimodal RAG for factuality in medical vision language models              |
| 2024.10 | UNC-ChapelHill   | MMed-RAG: Versatile Multimodal RAG System for Medical Vision Language Models |


## 胸片报告生成
| Paper Title                                                                             | Publication Year | Institution/Organization                          | Link                                                                                                      |
|-----------------------------------------------------------------------------------------|------------------|---------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| Generating Radiology Reports via Memory-driven Transformer                               | 2020             | arXiv                                             | [arxiv.org](https://arxiv.org/abs/2010.16056)                                                             |
| Cross-modal Memory Networks for Radiology Report Generation                             | 2022             | arXiv                                             | [arxiv.org](https://arxiv.org/abs/2204.13258)                                                             |
| Exploring and Distilling Posterior and Prior Knowledge for Radiology Report Generation   | 2021             | IEEE Conference on Computer Vision and Pattern Recognition (CVPR) | [cvf.com](http://openaccess.thecvf.com/content/CVPR2021/html/Liu_Exploring_and_Distilling_Posterior_and_Prior_Knowledge_for_Radiology_Report_CVPR_2021_paper.html) |
| AlignTransformer: Hierarchical Alignment of Visual Regions and Disease Tags for Medical Report Generation | 2021 | Springer Lecture Notes in Computer Science        | [springer.com](https://link.springer.com/chapter/10.1007/978-3-030-87199-4_7)                             |
| Contrastive Attention for Automatic Chest X-ray Report Generation                       | 2021             | arXiv                                             | [arxiv.org](https://arxiv.org/abs/2106.06965)                                                             |
| METransformer: Radiology Report Generation by Transformer with Multiple Learnable Expert Tokens | 2023 | IEEE Conference on Computer Vision and Pattern Recognition (CVPR) | [cvf.com](http://openaccess.thecvf.com/content/CVPR2023/html/Wang_METransformer_Radiology_Report_Generation_by_Transformer_With_Multiple_Learnable_Expert_CVPR_2023_paper.html) |
| MMTN: Multi-Modal Memory Transformer Network for Image-Report Consistent Medical Report Generation | 2023 | AAAI Conference on Artificial Intelligence        | [aaai.org](https://ojs.aaai.org/index.php/AAAI/article/view/25100)                                        |
| Dynamic Graph Enhanced Contrastive Learning for Chest X-ray Report Generation           | 2023             | IEEE Conference on Computer Vision and Pattern Recognition (CVPR) | [cvf.com](http://openaccess.thecvf.com/content/CVPR2023/html/Li_Dynamic_Graph_Enhanced_Contrastive_Learning_for_Chest_X-Ray_Report_Generation_CVPR_2023_paper.html) |
## 胸片报告生成
| 会议或期刊       | 论文名                   | 概述                                                                                       |
|------------|-------------------------|---------------------------------------------------------------------------------------------|
| ACMMM     | Medical Report Generation via Multimodal Spatio-Temporal Fusion       | 比较了过去和现在的患者图像，用特征归一化处理长尾问题       |
| AAAI      | PromptMRG: Diagnosis-Driven Prompts for Medical Report Generation  | 在诊断感知提示的指导下提高MRG的诊断准确性                    |
| lEEE     | Medical Report Generation Is A Multi-label Classification Problem   | 将MRG视为一个多标签分类问题，简化任务，减少对解码器的依赖，侧重准确分类关键字       |
|       | Large Language Models for Disease Diagnosis: A Scoping Review     | 各种评估方法            |
| ACL    | Fine-Grained Image-Text Alignment in Medical Imaging Enables Explainable Cyclic Image-Report Generation  | 预测病灶区域，并进行循环医疗报告生成   |
|       | Uncovering Knowledge Gaps in Radiology Report Generation Models through Knowledge Graphs  | 利用知识图谱评估医疗报告生成 |
| Artificial Intelligence In Medicine     | A label information fused medical image report generation framework  | MIX-MLP多标签分类网络、共注意机制、层次LSTM网络有效识别异常和多标签诊断分类 |
| IEEE     | ChatCAD+: Towards a Universal and ReliableInteractive CAD using LLMs  | 分层上下文学习和可靠的互动模块实现ChatCAD+系统 |
