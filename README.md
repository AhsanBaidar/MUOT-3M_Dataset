# 🌊 MUOT-3M: A 3 Million Frame Multimodal Underwater Tracking Benchmark

Official repository for **MUOT-3M**\
📄 *MUOT-3M: A 3 Million Frames Multimodal Underwater Benchmark*

------------------------------------------------------------------------


------------------------------------------------------------------------

## 🚀 Overview

**MUOT-3M** is the first large-scale **multimodal underwater object
tracking benchmark**, designed to advance research in marine computer
vision, underwater robotics, and multimodal learning.

Unlike previous RGB-only underwater datasets, MUOT-3M provides
synchronized **RGB, Enhanced RGB, Depth, and Language modalities**,
enabling robust learning under severe underwater degradations.

------------------------------------------------------------------------

## 📊 Dataset Statistics

-   🎥 **3,030 underwater videos**
-   🖼 **3.01 million frames**
-   ⏱ **27.8 hours of footage**
-   🐠 **677 fine-grained classes**
-   🌎 **16 phyla**
-   🧬 **124 families**
-   🏷 **32 tracking attributes**
-   📦 Train/Test split: **70% / 30%**
-   🧠 Expert-validated annotations (marine biologist reviewed)

------------------------------------------------------------------------

## 🌊 Modalities

Each sequence includes synchronized:

-   RGB frames\
-   Enhanced RGB frames\
-   Estimated depth maps\
-   Segmentation masks\
-   Language descriptions\
-   Bounding box annotations

The dataset captures real-world underwater challenges:

-   Low visibility\
-   Turbidity & backscatter\
-   Color attenuation\
-   Camouflage\
-   Swarm distractors\
-   Dynamic illumination\
-   Motion blur

------------------------------------------------------------------------

## 📂 Dataset Access

The dataset is hosted on Hugging Face:

### 🤗 Download Links

-   🔹 **Full Dataset**\
    https://huggingface.co/datasets/AhsanBB/MUOT_3M-A_3_Million_Frame_Underwater_Object_Tracking_Dataset

------------------------------------------------------------------------

## 📈 Benchmark Comparison

MUOT-3M significantly exceeds existing underwater tracking datasets in:

-   Scale\
-   Class diversity\
-   Attribute coverage\
-   Multimodal design


------------------------------------------------------------------------

## 🧪 Annotation Protocol

-   Semi-supervised bounding box generation\
-   Manual frame-by-frame verification\
-   Expert validation\
-   Segmentation mask refinement\
-   Ecological taxonomy validation

All sequences were curated to ensure:

-   Continuous target visibility\
-   Natural underwater scenes\
-   High annotation consistency

------------------------------------------------------------------------

## 🎯 Applications

MUOT-3M supports research in:

-   Underwater object tracking\
-   Marine robotics\
-   Aquaculture monitoring\
-   Coral reef analysis\
-   Vision-language underwater models\
-   Multimodal representation learning

------------------------------------------------------------------------

## 📜 Citation

```
@article{bakht2026muot_3m,
  title={MUOT\_3M: A 3 Million Frame Multimodal Underwater Benchmark and the MUTrack Tracking Method},
  author={Bakht, Ahsan Baidar and Alansari, Mohamad and Din, Muhayy Ud and Naseer, Muzammal and Javed, Sajid and Hussain, Irfan and Matas, Jiri and Mahmood, Arif},
  journal={arXiv preprint arXiv:2602.18006},
  year={2026}
}
```
------------------------------------------------------------------------

## 📄 License

The dataset is released for research purposes under an open academic
license.\
Please check the Hugging Face page for full license details.

------------------------------------------------------------------------

**MUOT-3M establishes a new foundation for scalable multimodal
underwater tracking research.**
