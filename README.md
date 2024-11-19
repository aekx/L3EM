# Towards Emotion-enriched Text-to-Motion Generation via LLM-guided Limb-level Emotion Manipulating
<p align="center">
  <img src="assets/figure1.jpg" alt="introduction of EMTG" width="700">
</p>

The official implementation of the paper ["Towards Emotion-enriched Text-to-Motion Generation via LLM-guided Limb-level Emotion Manipulating"](https://dl.acm.org/doi/pdf/10.1145/3664647.3681487) in ACM MM 2024.

## Abstract
In the literature, existing studies on text-to-motion generation (TMG) routinely focus on exploring the objective alignment of text and motion, which largely ignore the subjective emotion information, especially the limb-level emotion information. With this in mind, this paper proposes a new Emotion-enriched Text-to-Motion Generation (ETMG) task, aiming to generate motions with the subjective emotion information. Further, this paper believes that injecting emotions into limbs (named intra-limb emotion injection) and ensuring the coordination and coherence of emotional motions after injecting emotion information (named inter-limb emotion disturbance) is rather important and challenging in this ETMG task. To this end, this paper proposes an LLM-guided Limb-level Emotion Manipulating (L3EM) approach to ETMG. Specifically, this approach designs an LLM-guided intra-limb emotion modeling block to inject emotion into limbs, followed by a graph-structured inter-limb relation modeling block to ensure the coordination and coherence of emotional motions. Particularly, this paper constructs a coarse-grained Emotional Text-to-Motion (EmotionalT2M) dataset and a fine-grained Limb-level Emotional Text-to-Motion (Limb-ET2M) dataset to justify the effectiveness of the proposed L3EM approach. Detailed evaluation demonstrates the significant advantage of our L3EM approach to ETMG over the state-of-the-art baselines. This justifies the importance of the limb-level emotion information for ETMG and the effectiveness of our L3EM approach in coherently manipulating such information.

## Data Preparation
Download data files from google drive


## Pipeline Overview
<p align="center">
  <img src="assets/figure1.jpg" alt="introduction of EMTG" width="700">
</p>
