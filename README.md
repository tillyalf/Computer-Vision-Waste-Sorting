# Computer-Vision-Waste-Sorting

Across recent years, global waste is continuing to increase at a catastrophic and harmful rate. Poor waste management, one of the key contributors to this problem, leads to destructive environmental and health impacts. Convolutional Neural Networks (CNN) and deep learning are being used increasingly to combat this issue through more effective automated waste classification approaches. The repo investigates how different changes to preprocessing, augmentation, regularization, dataset generation and hyperparameter selection can improve CNN convergence, therefore reducing overfitting and improving classification of waste. Throughout this research a CNN was developed in Google Colab using a dataset containing 13,348 images from 10 different classes of waste. Through a range of experiments into overfitting, regulation, augmentation and scaling, different models were evaluated on their accuracy and loss rates for the training, validation and test sets. With key experiments being repeated multiple times. The initial model, investigating overfitting, produced a very high generalization gap of 76.7%, through implementing all the positive adjustments, the generalization gap was reduced to 20.0%. The final produced model achieved a 51% validation accuracy on clean data and a 45.3% test accuracy on unseen augmented data. Increasing the dataset diversity and the range of generalization techniques caused the most influence, future work investigating larger datasets, architectures, and resources would be beneficial in discovering the impact of increased architectural complexity.

A provided simple CNN architecture featuring 3 convolution layers and 2 hidden dense layers was provided for the further development of this project. Although the three-layered architectural structure could have been expanded for increased depth, it was kept as is to provide more focus on hyperparameters whilst adhering to computational constraints. 











