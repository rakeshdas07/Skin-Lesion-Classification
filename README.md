# Knowledge Distillation for Skin Classification 

I am experimenting with **Knowledge Distillation (KD)** to improve skin lesion classification.  
So far, I have tried the following models:

- ✅ ConvNeXt-L  
- ✅ EfficientNetV2-L  
- ✅ Vanilla CNN  

---

## 📊 Results

Here are the results for the models I tried :

### ConvNeXt-L
![ConvNeXt-L Accuracy Graph](Results/ConvNextL_AccuracyGraph.png)  
![ConvNeXt-L Test Classification Report](Results/ConvNextL_TestClassificationReport.png)
![ConvNeXt-L Confusion Matrix](Results/ConvNextL_TestConfusionMatrix.png)


### EfficientNetV2-L
![EfficientNetV2-L Accuracy Graph](Results/EffiV2L_AccuracyGraph.png)  
![EfficientNetV2-L Test Classification Report](Results/EffiV2L_TestClassificationReport.png)
![EfficientNetV2-L Confusion Matrix](Results/EffiV2L_TestConfusionMatrix.png)

### Vanilla CNN
![Vanilla CNN Accuracy Graph](Results/VanillaCNN_AccuracyGraph.png)  
![Vanilla CNN Loss Graph](Results/VanillaCNN_LossGraph.png)
![Vanilla CNN Classification Report](Results/VanillaCNN_ClassificationReport.png)


---

## 🔜 Next Steps
- Finalize the **parent (teacher) model** for KD.  
- Try out different **student models** to find the one that performs best.  
- Add more experiments with balanced accuracy and F1-score.  
- Optimize for deployment in resource-constrained settings.  
