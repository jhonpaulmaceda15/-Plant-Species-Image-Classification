# Plant-Species-Image-Classification

https://drive.google.com/drive/folders/1ZOD_qtYLYwuXhBNROY57byFMYc4NGYhA?usp=sharing

### Reflection Questions

## How did the number of images per class affect your model’s accuracy?
The number of images per class strongly influenced accuracy. Classes with more images performed better because the model learned from greater variations in size, color, lighting, and angle. Classes with fewer images were often misclassified due to limited examples, creating class imbalance and bias toward larger classes.

## Which plant species were most commonly misclassified and why?
Species with similar leaf shapes, textures, colors, or vein patterns were frequently misclassified. Since deep learning models depend on visual features, similar-looking plants can easily confuse them. Poor lighting, cluttered backgrounds, and overlapping leaves also reduced accuracy.

### How did changing the epochs, batch size, or learning rate affect the training results?

Epochs: More epochs improved accuracy at first, but too many caused overfitting and weaker performance on new images.

Batch size: Smaller batches provided more stable learning but took longer to train, while larger batches trained faster but sometimes reduced accuracy.

Learning rate: A high learning rate missed optimal solutions, while a very low rate slowed training. A balanced rate gave the best results.

## What challenges did you encounter during dataset collection and labeling?
Challenges included limited images for some species, inconsistent lighting and backgrounds, unclear labels, and visually similar plants. These issues introduced noise and affected performance.

## If you were to improve your model, what specific changes would you make and why?
I would collect more images for underrepresented species, apply data augmentation, improve labeling accuracy, fine-tune hyperparameters, and use a pre-trained CNN such as MobileNet or ResNet. These steps would improve learning, generalization, and overall accuracy.
