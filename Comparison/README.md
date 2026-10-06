# CNN vs Vision Transformer Comparison

## 1. Performance Comparison

Metric| CNN| Vision Transformer
/n Best Validation Accuracy| 46.13%| 64.59%
/n Test Accuracy| 44.80%| 62.68%
/n Macro F1-Score| 42.22%| 59.64%
/n Weighted F1-Score| 43.49%| 62.33%
/n Parameters| 422,602| 545,546

The Vision Transformer (ViT) outperformed the CNN across all evaluated metrics. It achieved a 17.88 percentage-point improvement in test accuracy, along with higher Macro F1-Score and Weighted F1-Score.

---

## 2. Key Observations

- The CNN achieved 44.80% test accuracy, providing a reasonable baseline for galaxy morphology classification.
- The Vision Transformer achieved 62.68% test accuracy, showing substantially stronger classification performance.
- The ViT achieved a higher Macro F1-Score (59.64%) and Weighted F1-Score (62.33%), indicating better overall classification performance across the galaxy classes.
- The ViT achieved a higher best validation accuracy (64.59%) compared with the CNN (46.13%).
- The ViT uses 545,546 parameters, compared with 422,602 for the CNN, making it a somewhat larger model.
- Despite having more parameters, the ViT provided a substantial improvement in classification performance.

---

## 3. Overall Comparison

The results demonstrate that the Vision Transformer performed better than the CNN for this galaxy morphology classification task.

The higher test accuracy and F1-Scores indicate that the ViT was able to achieve better overall classification performance and generalization on the test set.

Although the CNN provided a useful baseline, the ViT showed a clear advantage across the evaluated performance metrics.

---

## 4. Final Conclusion

Overall, the Vision Transformer was the better-performing model in this experiment, achieving 62.68% test accuracy compared with 44.80% for the CNN.

Although the ViT required more parameters, its substantial improvement in accuracy and F1-Scores makes it the stronger model for the evaluated galaxy morphology classification task.
