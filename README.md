# Fashion MNIST Neural Network with Label Smoothing and Data Augmentation

This project implements a fully connected neural network in NumPy to classify Fashion MNIST images. It showcases:

✅ He initialization for stable training  
✅ ReLU and Softmax activations  
✅ Label smoothing to prevent overconfident predictions  
✅ Data augmentation (random flips and rotations) to improve generalization  
✅ L2 regularization  
✅ Mini-batch gradient descent  
✅ Automatic model checkpointing when test accuracy improves  

## Features

- **Architecture:** 2 hidden layers (300 neurons each) + output layer
- **Label Smoothing:** Softens targets to enhance calibration
- **Data Augmentation:** 
  - Random horizontal flips
  - Random rotations (-15° to +15°)
- **Regularization:** L2 penalty on weights
- **Training:** 600 epochs, tracks accuracy and cost

## Requirements

- Python 3
- NumPy
- Pandas
- scikit-learn
- OpenCV (cv2)
- Matplotlib

## How to Run

1. Place `fashion-mnist_train.csv` in your working directory.
2. Run the script in Kaggle, Colab, or locally.
3. Monitor training logs for accuracy and cost.
4. Best model weights are saved automatically when performance improves.

## License

MIT License


