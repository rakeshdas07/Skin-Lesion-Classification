# Knowledge Distillation for Skin Classification 

I am experimenting with **Knowledge Distillation (KD)** to improve skin lesion classification.  
So far, I have tried the following models:

- ✅ ConvNeXt-L  
- ✅ EfficientNetV2-L  
- ✅ Vanilla CNN  

---

## 📊 Results

Here are the results for the models I tried (two screenshots per model showing training/validation curves and metrics):

### ConvNeXt-L
![ConvNeXt-L Accuracy](images/convnext_l_acc.png)  
![ConvNeXt-L Loss](images/convnext_l_loss.png)

### EfficientNetV2-L
![EfficientNetV2-L Accuracy](images/efficientnetv2_l_acc.png)  
![EfficientNetV2-L Loss](images/efficientnetv2_l_loss.png)

### Vanilla CNN
![Vanilla CNN Accuracy](images/vanilla_cnn_acc.png)  
![Vanilla CNN Loss](images/vanilla_cnn_loss.png)

---

## 🔜 Next Steps
- Finalize the **parent (teacher) model** for KD.  
- Try out different **student models** to find the one that performs best.  
- Add more experiments with balanced accuracy and F1-score.  
- Optimize for deployment in resource-constrained settings.  
