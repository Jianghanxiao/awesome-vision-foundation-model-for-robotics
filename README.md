# 🚀 **Awesome Vision Foundation Models for Robotics**
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> ✨ A curated list of **Vision Foundation Models (VFMs)** that empower **robot learning** and **robot perception** with strong **zero-shot generalization**.

---

## 🎯 **Why This List?**
Robotics research keeps evolving — and so do vision foundation models trained on **huge datasets** with **broad generalization** skills.  
But… 🤯 finding the right model for **your specific robotic task** is hard.

So this repo serves as:

✅ A **dictionary** of VFMs for robotics  
✅ A **quick lookup** for papers & code  
✅ A **task-driven map** for integration into pipelines  
✅ A community-driven reference to stay **up-to-date**

---

## 🧩 **What Counts as a Vision Foundation Model?**
A model that:

- ✅ Supports **vision tasks**
- ✅ Shows **zero-shot / few-shot** generalization
- ✅ Has **practical value** for robot perception & interaction 🤖

> If there is **no code** → 🚫 **not included**.

> 💡 Broad definition: If it advances **robot vision** with **practical benefit**, it’s welcome here.

---

## 📚 **Taxonomy of VFMs in Robotics**

| Category | Example Capabilities | Typical Robotics Use |
|---------|---------------------|---------------------|
| 🧱 Visual Latent Representation | Semantic embeddings, open-vocab features | Object understanding, task instruction grounding |
| 🔍 Detection | object detection | Target localization, open-set recognition |
| ✂️ Segmentation | Instance segmentation, part segmentation, universal mask prediction | Grasping, affordance extraction, occlusion handling |
| 🔗 Correspondence | Keypoint matching, patch/feature correspondences | Multi-view alignment, object registration |
| 🧭 Tracking | Object/point trajectory, video mask tracking | Visual servoing, dynamic obstacle avoidance, motion prediction |
| 🌀 Depth Estimation | Monocular/multi-view depth, metric-free or metric depth | Navigation, coarse obstacle avoidance, 3D scene understanding |
| 🏗️ 3D Reconstruction | Point cloud / mesh generation from sparse views or streaming  | Digital twins, SLAM, simulation pipelines |

> 🔨 Entries will include: **paper + code link + robotics applicability**

### 🌌 2D/3D Generation & VLMs (Recommended Awesome Lists)
These are outside the current scope of VFMs for robotics, but useful references (in the future, we can try to incorporate the useful ones for robotics, welcome contributions from the community):

* [Awesome Text-to-Image](https://github.com/Yutong-Zhou-cv/Awesome-Text-to-Image)  
* [Awesome Video Diffusion](https://github.com/showlab/Awesome-Video-Diffusion)  
* [Awesome 3D Generation](https://github.com/justimyhxu/awesome-3D-generation)  
* [Awesome 3D Diffusion](https://github.com/cwchenwang/awesome-3d-diffusion)  
* [Awesome VLLMs](https://github.com/JackYFL/awesome-VLLMs)  

---

## 🤝 **Contributions**
PRs and suggestions are highly welcome! 🚀

✅ Add new papers with usable code  
✅ Suggest new categories  
✅ Improve robotics applicability notes
✅ Include Input / Output / Visualization for each model

Please use this template when adding:
```
### Model/Paper Name — [Year]
* Paper: link
* Code: github-repo-link [must have code]
* Input: image / video / text / RGBD / multi-view / prompts / ...
* Output: boxes / masks / embeddings / depth / point cloud / ...
* Visualization: one example figure illustrating input and output
* Robotics applicability: 1–2 lines (best to have)
* Integration notes: any requirement or typical use
```

📩 Let’s build the **go-to hub** for VFMs in robotics.

---

If you’re working on **robot vision** or **robot learning**,  
⭐ **Star** this repo & help the community grow!

---
---
---
## 🧱 Visual Latent Representation

## 🔍 Detection

## ✂️ Segmentation


## 🔗 Correspondence 

## 🧭 Tracking

## 🌀 Depth Estimation

## 🏗️ 3D Reconstruction 