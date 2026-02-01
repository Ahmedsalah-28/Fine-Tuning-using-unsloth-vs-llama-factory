# Fine-Tuning Comparison with LoRA

This repository demonstrates Fine-Tuning of pre-trained language models using **LoRA** with two different frameworks: **Unsloth** and **LLaMA-Factory**. The goal is to compare speed, flexibility, and performance using the **same model, dataset, and hyperparameters** for a fair evaluation.

---

## What is Fine-Tuning?

Fine-Tuning is the process of taking a pre-trained model and training it further on a dataset closer to your specific task.  
- ✅ Guides the model for better performance in a specific scenario  
- ❌ No need to train from scratch  
- ❌ You don’t change everything in the model  

Fine-Tuning is the difference between:  
> “A model that knows a bit of everything”  
> and  
> “A model that performs best in a specific scenario”

---

## Why Two Implementations?

To better understand the effects of Fine-Tuning, the application was implemented in **two different ways**. This approach allowed us to:  
- Learn to work with multiple frameworks  
- Compare trade-offs between speed and flexibility  
- Make informed engineering decisions rather than just following tutorials  

**Both implementations use:**  
- LoRA  
- The same dataset  
- Same hyperparameters  
- Same base model  

The only difference is the framework.

---

## Implementations

### 1. Unsloth
- Focused on **speed** and low VRAM usage  
- Training time is much shorter  
- Ideal for quick experiments and learning  
- See Fine-Tuning effects quickly  

### 2. LLaMA-Factory
- Flexible and highly customizable framework  
- Better for organized, scalable experiments  
- Suitable for advanced workflows and configurations  

---

## Key Takeaways

- There’s no absolute “best” framework  
- Choose **Unsloth** for quick experiments, low resources, and learning  
- Choose **LLaMA-Factory** for flexibility, advanced settings, and scalable workflows  
- Fine-Tuning is not just a tool, it’s an **engineering decision** depending on your goal, resources, and use case

---




