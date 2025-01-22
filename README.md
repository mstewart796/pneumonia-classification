# Pneumonia Detection CNN

This project uses a Convolutional Neural Network (CNN) to detect pneumonia from chest X-ray images. **Note:** The current results are based on an initial round of training and will be improved with further fine-tuning and training.

### Current Training Results:
- **Validation Accuracy**: 72.02%
- **Validation Precision**: 44.12%
- **Validation Recall**: 90.58%
- **Confusion Matrix**:
  ```
  [[1385,  694],
   [  57,  548]]
  ```

### Results Summary:
- **High Recall (90.58%)**: The model is effective at identifying most positive cases of pneumonia. This is critical in medical diagnostics, where failing to detect a condition can have serious consequences.
- **Lower Precision (44.12%)**: The model has a relatively high false-positive rate, indicating that it incorrectly classifies some healthy cases as pneumonia.
- **Overall Accuracy (72.02%)**: While the model performs moderately well, the accuracy reflects room for improvement in balancing false positives and negatives.

### Significance:
The high recall indicates the model's potential in medical applications where detecting pneumonia is prioritized. However, the lower precision highlights the need for further fine-tuning to reduce the false-positive rate, which can help avoid unnecessary interventions for healthy individuals. These results are a starting point, and further training will aim to improve both precision and accuracy while maintaining strong recall.

Further updates to the notebook and README, including more detailed comments and explanations, will follow as the model is improved.
