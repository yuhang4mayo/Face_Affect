# Face_Affect

## Problem Statement

Our project performs facial expression detection using video data. The goal is to extract meaningful frame-level information from videos and classify facial expressions accurately.

## Project Architecture

- Extract frames from video sources and convert images into tensors suitable for model input.
- Preprocess and normalize image tensors (resizing, normalization, augmentation as needed).
- Run frames through a machine learning model to detect and classify facial expressions.

## Design and Implementation

- Data ingestion: video → frame extraction → dataset of images/frames.
- Preprocessing pipeline: resizing, cropping, normalization, and optional augmentation.
- Model: train/evaluate a CNN or transformer-based architecture for expression classification.
- Evaluation: compute accuracy, precision, recall, and confusion matrices.

## Technical Issues

- GPU resource constraints may limit local training speed and batch sizes.
- Consider using cloud GPU instances or managed ML platforms for large-scale training and inference.

## Results & Conclusion

- Reported metrics: accuracy, precision, recall for the detection model.
- Perform subgroup analysis to identify performance differences across demographics or expression categories.

## Next Steps

- Fill in the `Design and Implementation` section with specific model architecture and training details.
- Research on Data sources online
- Add instructions for running experiments, dependencies, and sample data paths.

