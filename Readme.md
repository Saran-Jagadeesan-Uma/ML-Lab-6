# TensorBoard Lab - Optimizer Comparison on MNIST

## Project Overview
This lab compares three different optimizers (SGD, Adam, RMSprop) on MNIST digit classification using TensorBoard for visualization and analysis.

## What's Different from Other Labs
- **Dataset**: MNIST digits (different from Fashion-MNIST in other labs)
- **Focus**: Optimizer comparison (instead of basic logging or hyperparameter tuning)
- **Custom Features**: Prediction visualizations, custom metrics (generalization gap, loss ratio)
- **Architecture**: Simple Dense network for fast training

## Key Features
- Compare 3 optimizers side-by-side
- Custom callback for prediction visualization during training
- Custom metrics logging (generalization gap, loss ratio)
- Image logging to TensorBoard
- Histogram and graph visualization
- Fast training (~2 minutes total)

## TensorBoard Capabilities Demonstrated
1. Scalar logging (loss, accuracy)
2. Image logging (samples, predictions)
3. Graph visualization (model architecture)
4. Histogram logging (weight distributions)
5. Custom metrics
6. Multi-experiment comparison

## How to Run
1. Install required packages:
```bash
   pip install tensorflow matplotlib pandas
```

2. Run the notebook cells sequentially

3. Launch TensorBoard to view results:
```bash
   %tensorboard --logdir logs
```

## Expected Results
- **Adam**: Fastest convergence, smooth learning curves
- **RMSprop**: Good performance, adaptive learning rate
- **SGD**: Slower but stable convergence

## Technologies Used
- TensorFlow/Keras (deep learning framework)
- TensorBoard (visualization)
- NumPy (numerical computing)
- Matplotlib (plotting)
- Pandas (data analysis)