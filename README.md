## ✅ TODO List

### 🧪 Model Training Experiments

- [ ] Train model on **100k data**, unfreezing **only projection layers**
- [ ] Train projection layers **from scratch**
  - [ ] Try training **only text projection**
  - [ ] Try training **both text and image projections**
- [ ] Try alternative **text backbone**: [Modern Liberta (Goader)](https://huggingface.co/Goader/modern-liberta-large)
  - [ ] Train only new projection layers
  - [ ] Train both projection and text backbone

### 📊 Data Strategy

- [ ] Implement **smart sampling strategy**:
  - Sample **more** from Wiki and Multi30k
  - Sample **less** from LAION

### 📚 Literature Review

- [ ] Review and compare **modern CLIP fine-tuning papers**
- [ ] Create a **comparison table** of methods and results

---

## 🎯 Final Goal

- ✅ Run **all experiments** listed above
- ✅ Evaluate results on **five datasets**:
  - Our Wiki
  - Multi30k Eval
  - LAION
  - V-WSD
  - One image classification dataset
- ✅ Upload the **best model** to **Hugging Face** as:

> 🔥 *The best Ukrainian CLIP model*
