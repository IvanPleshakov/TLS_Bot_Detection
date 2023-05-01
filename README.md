# TLS_Bot_Detection
## Nuclear IT hack 1st place solution🥇 (VK Group case: bot detection using Transport Layer Security protocol)

### Data
![image](https://user-images.githubusercontent.com/90785471/235430404-b87d7112-7478-43b9-bc1d-d3e6dc416d77.png)

* Train - 47947 samples, Test - 14389 samples
* ua: user agent
* ciphers: TLS ciphers arranged in descending order of priority
* curves: TLS curves arranged in descending order of priority
* label: 1 - bot (40041 samples), 0 - user (7906 samples)

### Score (ROC-AUC)
* Cross Validation - 0.93
* Test - 0.865

### Model
*picture*
* Encoder - TransformerEncoder
* Head - Linear

### Tokenizer
* BPE Tokenizer

### Loss
* BCE Loss

### Optimizer
* Madgrad

### Scheduler
* ExponentialLR

### Tricks
* Stratified KFold
* Positional encoding
* PyTorch Lightning
