# TLS_Bot_Detection
## Nuclear IT hack 1st place solution🥇 (VK Group case: bot detection using Transport Layer Security protocol)

### Data
* Train - 47947 samples, Test - 14389 samples
* User Agent:
* Ciphers:
* Curves:
* Label: 1 - bot (40041 samples), 0 - user (7906 samples)

### Score (ROC-AUC)
* Cross Validation - 0.93
* Test - 0.865

### Model
*picture*
* Encoder - Attention layers
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
