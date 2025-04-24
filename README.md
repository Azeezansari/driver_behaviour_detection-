# driver_behaviour_detection-
Real-time driver behavior detection using deep learning models like AlexNet, ResNet34, and VGGNet.
# Driver Behavior Detection (Deep Learning)

This project uses CNN-based models (AlexNet, ResNet34, and VGGNet) to classify driver behavior from images into one of five categories:
- Safe Driving
- Talking on the Phone
- Texting
- Turning
- Other Activities

## 🔍 Summary
We trained and evaluated three deep learning models using a balanced dataset with over 10,000 images. The best performing model was **AlexNet** with a validation accuracy of over 98%.

## 📁 Files
- `group5_submission.ipynb`: Full implementation of data preprocessing, modeling, training, and evaluation.

## 📊 Model Comparison
| Model    | Train Accuracy | Validation Accuracy |
|----------|----------------|---------------------|
| AlexNet  | 98.81%         | 98.14%              |
| ResNet34 | 98.46%         | 96.85%              |
| VGGNet   | 98.47%         | 61.32%              |

## 🚀 Getting Started
Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook to reproduce results.

## 🛠 Tools Used
- Python
- TensorFlow / Keras
- NumPy, Matplotlib
- OpenCV
