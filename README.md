In this mini-project, my focus is on developing an advanced image classification system using ensemble training. This marks the second iteration of creating an image classifier, and the primary goal remains unchanged – evaluating the model's effectiveness in recognizing individuals of the same racial background.

The project aims to elevate a Convolutional Neural Network (CNN) through ensemble training, taking inspiration from the ensemble trees concept in XGBoost. This strategy involves merging two or more models, each with varying accuracy, to construct a composite model with enhanced performance. While there's no assurance of surpassing every individual model in the ensemble, the goal is to harness the strengths of each architecture, resulting in a model with commendable metric evaluation and versatile task performance.

In the previous iteration, I developed a basic image classifier that fell short in performance due to the simplicity of the CNN architecture and the limitations of a small dataset comprising only 530 images. In this paper, I will make a comparative performance analysis of the previous simple CNN, a CNN trained on DenseNet169, a CNN trained on ResNet152, a CNN trained on VGG19, and the ensemble model. The models use a larger dataset of 2,000 images and have a more intricate architecture.
