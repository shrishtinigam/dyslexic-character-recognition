# dyslexic-character-recognition

### Introduction
In this paper, we implement a CNN model to recognize and rectify incorrectly written characters, in order to aid children with dysgraphia as a result of dyslexia. Dysgraphia is a language disorder that is defined as a difficulty or inability to coherently communicate through writing. The proposed work attempts to implement a CNN classification model that categorizes a character as correctly written or incorrectly written, and if it is incorrectly written, identifies the character it was supposed to be. Our goal is to aid children with writing difficulties to practice their writing with the model helping them correct their mistakes. Compared to the conventional testing procedures that take in a lot of time in screening, an automated detection mechanism would take lesser time and produce reliable results while analyzing the writing aspect. 

### Dataset
Dataset was collected from 3 sources where uppercase letter is from NIST Special Database 19 while lowercase letter is from Kaggle Dataset  and some datasets for testing is from dyslexic kids of Seberang Jaya primary school, Penang, Malaysia. This dataset contains a total of 78275 for normal class while for reversal is 52196 and for corrected is 8029.

### Proposed Methodology
In our work, we show a comparative analysis between various perceptron and CNN based learning methods to recognize reversed characters. We first apply a CNN model for the binary classification of reversed characters and regular characters as below. Label 0 is assigned to Normal characters, and Label 1 is assigned to reversed characters. Next, we use a Multi-Layer Perceptron to recognize the reversed and normal characters. 0-25 Labels are assigned to normal characters. 26-51 labels are assigned to reversed characters. Some reversal mistakes are common, for example, vertical flip of asymmetrical letters like B, K, F etc. Some letters however, are symmetrical, like A, O etc., and thus have no reversal character equivalents. Such letters, in total are – A, H, M, O, V, W, X, Y. This dataset is applied to the rest of the methodologies as well. 

### Results
Maximum accuracy reached was 90.4% by the Character Recognition K-Fold Cross Validation Larger CNN model. Comparision between all the models implemented is shown below.

![image](https://github.com/shrishtinigam/dyslexic-character-recognition/assets/72018363/0f274770-8962-4f07-a81c-55d5736e6ae9)

Comparision to various other existing models is shown in the following table. As shown, our model shows comparative accuracy. 

![image](https://github.com/shrishtinigam/dyslexic-character-recognition/assets/72018363/34fd18af-6c41-446d-82ce-5eb0c000354d)

