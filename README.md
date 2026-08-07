# ATPPred: Prediction of Plant ATP-Binding Proteins Using ESM2 and 1D Convolution

## Introduction

Plant ATP-binding proteins play a central role in various physiological processes, including growth and development, energy metabolism, signal transduction, and environmental adaptation. Accurately identifying these proteins from sequences is crucial for understanding plant physiology and advancing agricultural biotechnology. In this study, we propose ATPPred, a novel computational tool combining the protein large language model Evolutionary Scale Modeling 2 with a convolutional neural network for high-precision prediction. The tool leverages ESM2 to extract global features and further refines feature representation through convolutional layers. Comprehensive performance metrics, systematic robustness evaluations across various sequence similarity thresholds, and rigorous cross-dataset benchmarking demonstrate its outstanding prediction capability and superiority over existing methods. In summary, ATPPred provides a reliable sequence-based approach that serves as a useful auxiliary tool for the preliminary screening and prioritization of candidate plant ATP-binding proteins.

### Highlights:
- **Construction of an innovative dual-module fusion architecture that first utilizes ESM2 to extract sequence representations, and subsequently applies a 1D CNN to further extract feature information.**
- **Verification of the model's exceptional robustness and dynamic adaptability through comprehensive ablation studies, multi-round negative sampling, and varying sequence similarity thresholds.**
- **Achievement of superior performance in independent benchmark testing, outperforming existing baseline models.**

### Environment Specification:
- Python 3.8.20
- torch==2.4.1
- torchvision==0.20.0
- torchaudio==2.4.1
- transformers==4.45.2
- scikit-learn==1.3.0
- numpy==1.24.3
- joblib==1.4.2
- biopython==1.78