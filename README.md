# PhysRepair

## Agentic Physics-Grounded Video Generation via Memory-Augmented In-Context Reasoning

**Code coming soon.** This repository currently provides paper information. The implementation has not been released yet.

[Project Page](https://xxkkxxx.github.io/PhysRepair/) · [Paper PDF](https://xxkkxxx.github.io/PhysRepair/assets/PhysRepair-paper.pdf)

**Xikang Guan<sup>1,†</sup>, Shaocong Yang<sup>1,†</sup>, Yanqi Bao<sup>2,‡</sup>, Can Wang<sup>3</sup>, Zheng Gu<sup>4</sup>, Zhengqing Chen<sup>2</sup>, Kai Chen<sup>5</sup>, Jing Huo<sup>1,*</sup>, Yang Gao<sup>6</sup>**

<sup>1</sup> School of Computer Science, Nanjing University  
<sup>2</sup> Horizon Robotics  
<sup>3</sup> School of Computing and Data Science, The University of Hong Kong  
<sup>4</sup> College of Computer Science and Software Engineering, Shenzhen University  
<sup>5</sup> State Key Laboratory for Novel Software Technology, Nanjing University  
<sup>6</sup> School of Intelligence Science and Technology, Nanjing University

<sup>†</sup> Equal contribution · <sup>‡</sup> Project leader · <sup>*</sup> Corresponding author

## Abstract

Physical plausibility is essential for realistic video generation. Existing methods impose physical guidance before synthesis via simulations or refined prompts, but this can limit dynamic diversity, miss errors that emerge only after generation, and require repeated regeneration when inconsistencies remain. We therefore study a *generate–diagnose–repair* paradigm that preserves the original generation capability and selectively repairs physical inconsistencies afterward, raising two key questions: what to repair, and how to repair? To address them, we introduce **PhysRepair**, an agentic video generation framework that combines causal reasoning over the observed physical failure with prior repair experience to enable localized and adaptive correction. Specifically, **Spatiotemporal Causal Constraints** identify the first invalid physical state and its causally affected states, producing a repair specification that guides physically plausible local regeneration while preserving unaffected content. **Experience-augmented In-context Learning** combines the ongoing repair context with relevant experience from previous repairs, allowing the agent to adapt its repair decisions across diverse physical failures and accumulate completed trajectories for future cases. Experiments on Physics-IQ Verified across solid mechanics, fluid dynamics, optics, thermodynamics, and magnetism demonstrate that PhysRepair consistently improves the physical plausibility of generated videos over existing methods.

## Citation

```bibtex
@misc{guan2026physrepair,
  title = {Agentic Physics-Grounded Video Generation via Memory-Augmented In-Context Reasoning},
  author = {Guan, Xikang and Yang, Shaocong and Bao, Yanqi and Wang, Can and Gu, Zheng and Chen, Zhengqing and Chen, Kai and Huo, Jing and Gao, Yang},
  year = {2026},
  note = {Manuscript},
  url = {https://xxkkxxx.github.io/PhysRepair/assets/PhysRepair-paper.pdf}
}
```
