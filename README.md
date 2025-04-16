# Publications

## 1. *PeerGuard_Defending Multi-Agent Systems Against Backdoor Attacks Through Mutual Reasoning*, 2025
**Intro:**
PeerGuard is a novel defense strategy designed to protect multi-agent systems (MAS) from backdoor attacks, leveraging the **reasoning capabilities** of large language models (LLMs). Unlike existing defenses that focus on single-model threats, PeerGuard introduces a mutual reasoning mechanism: agents critically examine each other's reasoning steps and final outputs to identify **inconsistencies** indicative of backdoor manipulation.

**Key Contributions:**

✳️ PeerGuard Framework: A collaborative defense method where agents inspect reasoning logic to detect malicious behavior;

🔌 Plug-and-play Integration: Seamlessly integrates into popular MAS frameworks such as AutoGen and CAMEL;

📈 Strong Performance: Achieves >96% TPR and <10% FPR across benchmarks (MMLU, CSQA, ARC) using GPT-4o and Llama3-70B;

🌐 Generalization: Extends from 2-agent systems to multi-agent settings with consistent high detection rates.



## 2. *Graduate Thesis:Multi-Modal Perception for Robots in Business Scenarios*, 2023
**Intro:** 
This thesis presents a multi-modal perception system designed for robots in business scenarios. It focuses on two key challenges:
* **Class-Incremental Learning:** A novel two-stage training strategy is proposed that leverages knowledge distillation and sample replay. With only 3% of the old data, the model is able to learn new object categories (e.g., lampposts) without catastrophic forgetting of existing ones.

* **Multi-Sensor 3D Object Detection:** The system fuses RGB images and LiDAR point clouds into a unified Bird's Eye View (BEV) representation. By combining BEVFormer and BEVFusion, the model utilizes both temporal awareness and cross-modality spatial interaction through a Transformer-based architecture.

**Experiments**
* **Result**: On the nuScenes dataset, the proposed model achieves 48.3% mAP, surpassing baseline by 3.8%.

* **Analysis & Limitations**: The thesis also analyzes common data quality issues (e.g., small objects, overexposed images) and discusses why earlier simulated data approaches failed to generalize.





## 3. *Understanding the Evaluation Abilities of External Cluster Validity Indices to Internal Ones*, 2020
**Intro:** This paper tackles the problem of evaluating the effectiveness of internal Cluster Validity Indices (CVIs). Existing methods, including NC-based and external CVI-based approaches, often fail under various data scenarios. To address this, the authors propose a novel method named CAMER (CVI Ability MEasurement via Ranking consistency), which quantitatively measures the evaluation ability of external CVIs through rank consistency metrics like Kendall’s Tau and Spearman's Footrule. 

**Key contributions:**

* Introduced the CAMER framework to quantitatively assess how well external CVIs evaluate internal CVIs.
* Explored seven widely-used external CVIs across six synthetic datasets with diverse characteristics (e.g., spherical, noisy, skewed).
* Validated the results on four real-world datasets to confirm the robustness of CAMER.
* Summarized external CVIs’ evaluation strengths under different scenarios, providing a practical guideline for selecting evaluation metrics.




