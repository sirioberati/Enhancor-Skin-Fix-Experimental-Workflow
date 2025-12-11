# Enhancor Skin Fix Workflow

> **Created by:** Enhancor Team  
> **Version:** 01 – Skin Fixing

## 📥 Access Models & Workflow

| Resource | Link |
| :--- | :---: |
| **Models + Workflow** | [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Download-blue)](https://huggingface.co/Sirioberati/enhancor_skin_fix/tree/main) |

This workflow demonstrates the structure and logic behind the **Enhancor Skin Fix system**. It is a technical template created to showcase how a natural skin-reconstruction pipeline can be built in ComfyUI.

## Purpose
Enhances AI-generated or plastic-looking skin into natural, authentic texture using masked sampling, guided CFG, controlled denoise, and upscale refinement.

---

## Visual Guide and Logic

### System Logic
Understanding the core pipeline and logic behind the full-fledged workflow.

| Overall Logic | LoRA Training Pipeline |
| :---: | :---: |
| ![Overall Logic](Overall%20Logic%20for%20a%20full%20fledged%20workflow.jpeg) | ![LoRA Training](LoRA%20Training%20Pipeline.jpeg) |

### ComfyUI Workflow
Deep dive into the node structure and segmentation strategy.

| Workflow Overview | Segmentation Strategy |
| :---: | :---: |
| ![Workflow Overview](Workflow%20Overview.png) | ![Portrait Segmentation](Workflow%20Portrait%20segmentation.jpeg) |

### Results
Before and After demonstration of the skin enhancement.

![Results](Workflow%20Results.png)

---

## Recommended User Settings

| Parameter | Recommended Range | Notes |
| :--- | :--- | :--- |
| **Denoise** | `0.30` – `0.35` | Controls how much of the original image is modified. |
| **CFG** | `0.7` – `2.0` | Lower CFG often yields more natural texture blending. |
| **Steps** | `30` | Optimal for detail resolving without over-baking. |

> *These parameters produce the best balance of realistic texture, preserved freckles, and stable identity retention.*

---

## Copyright © 2025 Enhancor
All workflow logic, structure, and configurations are the property of Enhancor.  
**Redistribution, resale, or commercial deployment is prohibited without authorization.**
