# MVTec Anomaly Detection

Unsupervised anomaly detection on the MVTec dataset using pretrained CNN
features, autoencoders, and patch-based methods.

## Overview
This project studies how different anomaly detection strategies behave
across industrial object categories with varying texture complexity.

## Methods
- ResNet18 / WideResNet50 (ImageNet pretrained)
- Feature-level Autoencoders
- Patch-based Autoencoders
- PatchCore-style kNN anomaly scoring
- ROC–AUC evaluation

## Results
| Category   | ROC–AUC |
|------------|---------|
| Bottle     | ~0.92   |
| Metal Nut  | ~0.65   |
| Zipper     | ~0.58   |

## Key Insights
- Smooth objects are easier to model with reconstruction-based methods
- Texture-heavy objects remain challenging
- Feature representation matters more than model complexity

## Author
Arkaprava Roy
