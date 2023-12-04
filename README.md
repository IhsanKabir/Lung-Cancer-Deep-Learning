# Utilizing Model Compression Techniques in Medical Imaging (Lung Cancer)

* The code is the official implementation of the work for 499A and 499B namely Senior Capstone Design A and B. The Project is entitled: "#### Utilizing Model Compression Techniques in Medical Imaging (Lung Cancer)
####"
* Contributors: AKM Ihsan Kabir
* Special Thanks to our Faculty: Nafisa Noor.

# Methodology
#### Medical Imaging is an emerging sector that involves deep learning to detect or classify objects significant to medical understanding and conclusions. Here we look into detecting lunger cancer tumours which either might be benign, or malignant or the lung image may be completely normal. However, such models are large in size which is no longer effective in small devices and consume substantial power or take time when inferencing. We propose model compression techniques such as knowledge distillation and quantization. Below is the table obtained for knowledge distillation on several convolutional neural networks.

# Deep Learning Training Pipeline followed:
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://github.com/IhsanKabir/Lung-Cancer-Deep-Learning/blob/main/Figures/Untitled%20Diagram.drawio.png)
Figure 1: The Figure illustrates the training pipeline followed for knowledge distillation. We used a previously trained model on Lung Cancer.


# We Present our Observations on Knowledge distillation using 4 different models
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://github.com/IhsanKabir/Lung-Cancer-Deep-Learning/blob/main/Figures/Table%20Git.jpg)
Table 1: Showcasing of models trained on the Lung Cancer detection data. The table shows 4 models: AlexNet, MobileNetv2, Our Model (for this experiment) and a ResNet18 model. The table shows that training with knowledge distillation is able to increase performance of a model significantly.

# Inference

We utilized Gradio to infer the resultant student models. Given an input of a Lung CT Scan our model is able to predict the type of tumor or the condition of the lung CT. Given below are the website and illustrations:

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://github.com/IhsanKabir/Lung-Cancer-Deep-Learning/blob/main/Figures/Benign%20Case%20Git.jpg)
Figure 2: A Benign Lung CT

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://github.com/IhsanKabir/Lung-Cancer-Deep-Learning/blob/main/Figures/Normal%20Case%20Git.jpg)
Figure 3: A Normal Lung CT

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://github.com/IhsanKabir/Lung-Cancer-Deep-Learning/blob/main/Figures/Malignant%20Case%20Git.jpg)
Figure 4: A malignant Lung CT

