# Brain Tumor Classification using Quantum Transfer Learning
## Project Overview
This project focuses on classifying brain tumors using a combination of traditional feature extraction methods and quantum transfer learning techniques. We implemented models based on three selected journal papers and tested them on the Chen Medical dataset. Our approach involved utilizing six different traditional feature extractors and combining them with quantum circuit classifiers to improve classification performance.

## Literature Survey
We conducted a comprehensive literature survey to identify state-of-the-art methods in brain tumor classification. From this survey, we selected three journal papers that provided the foundation for our implementation. Although we don't have a record of the literature survey or the papers, the chosen models significantly influenced our work.

## Methodology
### Traditional Feature Extractors
We applied the following six traditional feature extractors to the Chen Medical dataset:

ResNet-50<br/>
ResNet-512<br/>
VGG-16<br/>
VGG-19<br/>
MobileNet<br/>
XceptionNet<br/>
InceptionNet<br/>
### Quantum Circuit Classifiers
For the quantum classification, we used two different quantum circuits:

#### Quantum Circuit 1:<br/>
Layers: AngleEmbedding layer, Basic Untangling layer, and PauliZ layer.<br/>
#### Quantum Circuit 2:<br/>
Layers: Hadamard gate, CNOT gate, and Ry gate.<br/>
Feature Extractor: ResNet-50 (benchmark FE)<br/>

## Implementation of Research Paper Models
We implemented the models from the three selected journal papers and evaluated their performance on the Chen Medical dataset. These implementations served as benchmarks for comparing the effectiveness of our proposed quantum transfer learning approach.

## Implementation
We implemented the models using Python and various deep learning and quantum computing libraries. The primary steps included:

Preprocessing the Chen Medical dataset.<br/>
Extracting features using the traditional feature extractors.<br/>
Feeding the extracted features into the quantum circuit classifiers.<br/>
Evaluating the performance of each model.<br/>

## Results
The results demonstrated that combining traditional feature extractors with quantum circuit classifiers can enhance the performance of brain tumor classification models. Detailed results and comparisons are available in the project repository.

## Acknowledgements
We would like to thank the authors of the three journal papers for their valuable contributions to this field. Special thanks to the developers of the libraries we used in this project.

