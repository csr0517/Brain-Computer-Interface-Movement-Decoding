# Brain-Computer Interface Movement Decoding

This project implements a Support Vector Machine (SVM) classifier for decoding movement intentions from EEG data, specifically distinguishing between actual and imagined movements of left or right arms. The system utilizes advanced dimensionality reduction techniques and provides decision statistics for enhanced classification reliability.

## Overview

The project aims to bridge the gap between human brain activity and external devices by accurately interpreting EEG signals, with potential applications in assistive technologies and rehabilitation engineering.

### Key Features

- Implementation of SVM classifier with decision statistics
- Robust two-level cross-validation approach
- Integration of Linear Discriminant Analysis (LDA) for optimal feature reduction
- Comprehensive evaluation using ROC curves and accuracy metrics
- Support for both overt and imagined movement classification

## Technical Details

### Data Characteristics
- 120 features per data sample
- 204 samples per movement type
- Binary classification: imagined vs. overt movements

### Performance Metrics
- Average accuracy: 80.62%
- High ROC AUC scores across test sets
- Robust performance in cross-validation scenarios

### Prerequisites

Required Python libraries:
- pandas: Data manipulation and analysis
- numpy: Scientific computing
- scikit-learn: Machine learning models and preprocessing
- matplotlib: Visualization
- warnings: Warning management

## Implementation Highlights

### Preprocessing Pipeline
1. Initial data loading and validation
2. Dimensionality reduction using LDA
3. Feature space optimization
4. SVM model training with optimal parameters

### Model Configuration
- Optimal regularization parameter (α): 10000
- Linear kernel implementation
- Two-level cross-validation for robust evaluation

## Results

The system achieves:
- High classification accuracy (>80%)
- Reliable discrimination between movement types
- Robust performance across different data splits
- Effective handling of high-dimensional EEG data

## Future Directions

Potential areas for enhancement:
- Implementation of adaptive algorithms for real-time analysis
- Integration with real-time BCI systems
- Expansion to include more diverse movement types
- Investigation of deep learning approaches
- Cross-disciplinary collaboration opportunities

## References

Key resources and documentation:
- scikit-learn documentation
- Research papers on BCI and movement decoding
- EEG signal processing literature
