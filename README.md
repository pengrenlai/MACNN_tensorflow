# MACNN_tensorflow
TensorFlow-based implementation of "Multi-stage Attention Convolutional Neural Networks for HEVC In-Loop Filtering" by Peng-Ren,Lai

The model is trained and tested on images compressed by HM16.7

# Architecture
The architecture of our MACNN is illustrated below. Green denotes our revised inception block, yellow denotes self-attention block, ⊕ denotes element-wise addition, and ⊗ denotes concatenation.
![architecture](MACNN_architecture.PNG)

# Results
![visual result](visual_result.PNG)
