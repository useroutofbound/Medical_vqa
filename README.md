# Medical Visual Question Answering (Med-VQA)

## Task
Develop a model that answers questions about medical images, such as radiological scans.

## Approach
1. **Multimodal Feature Extraction**
   - **Image Features**: Used a modified VGG19 model pre-trained on ImageNet.
   - **Question Features**: Employed NLP techniques with RNNs, LSTMs, or Transformers.

2. **Feature Fusion**
   - Combined visual and textual features using advanced fusion methods.

3. **Predictions**
   - Treated as a classification problem using metrics like F1 Score and Accuracy.

## Results
The model effectively extracted and fused features, providing accurate answers to medical questions based on visual inputs. Future work will address improvements in model architecture and dataset expansion.
