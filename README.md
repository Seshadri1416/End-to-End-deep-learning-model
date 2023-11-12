# End-to-End-deep-learning-model
Food security is a pressing global issue, demanding the assurance of safe and healthy crop production for both
consumers and farmers. Plant diseases are a significant contributor to crop losses. To address this challenge, a
rapid and accurate model for plant disease identification and distinction is essential. This project leverages deep
learning techniques and utilizes the Plant Village dataset as its data source.To extract crop characteristics, two
pre-trained models, EfficientNetB0 and DenseNet121, are employed. The features extracted from these models
are fused through concatenation, allowing the model to harness the rich feature data of the crops. This fusion
ensures that any loss of information during feature extraction is compensated for. This approach has demonstrated
superior results compared to other models.Data augmentation is employed to expand the dataset's breadth and
assist the model in acquiring a deeper understanding of complex information, all without increasing the quantity
of data. DenseNet, a convolutional neural network, exhibits a feed-forward structure, with each layer connected
to all subsequent layers, facilitating the concatenation of feature maps from preceding layers to form a layer's
input. EfficientNetB0, the foundational network in the EfficientNet family, is designed with minimal memory
and floating-point operations per second (FLOPS) requirements.The results obtained after implementing these
steps show that the classification accuracy surpasses that of the other models compared. Through this work, we
have gained substantial insights into the capabilities of EfficientNetB0 and DenseNet121 in addressing the critical
challenge of plant disease identification in the context of food security.
Keywords: Deep learning, Convolution Neural Network, Feature Fusion, Deep features, Plant disease.
