# Computer-Vision-Waste-Sorting

Convolutional Neural Networks (CNN) and deep learning are being used increasingly to combat poor waste management through more effective automated waste classification approaches. The repo investigates how different changes to preprocessing, augmentation, regularization, dataset generation and hyperparameter selection can improve CNN convergence, therefore reducing overfitting and improving classification of waste. Throughout this research a CNN was developed in Google Colab using a dataset containing 13,348 images from 10 different classes of waste. Through a range of experiments into overfitting, regulation, augmentation and scaling, different models were evaluated on their accuracy and loss rates for the training, validation and test sets. With key experiments being repeated multiple times. The initial model, investigating overfitting, produced a very high generalization gap of 76.7%, through implementing all the positive adjustments, the generalization gap was reduced to 20.0%. The final produced model achieved a 51% validation accuracy on clean data and a 45.3% test accuracy on unseen augmented data. Increasing the dataset diversity and the range of generalization techniques caused the most influence, future work investigating larger datasets, architectures, and resources would be beneficial in discovering the impact of increased architectural complexity.

A provided simple CNN architecture featuring 3 convolution layers and 2 hidden dense layers was provided for the further development of this project. Although the three-layered architectural structure could have been expanded for increased depth, it was kept as is to provide more focus on hyperparameters whilst adhering to computational constraints. 

"Results.md" displays the different experimentation that was executed in order to find the best performing model.

Although it would have been beneficial to implement more changes to final model as it performed quite well, it took 30 minutes to run and therefore this would have been very resource consuming to conduct. Additionally, as both curves were beginning to plateau, it indicated that the model is not overfitting and has rather learned all it can with the architecture and dataset provided.

This final model produced a validation accuracy of 51.0% and a test accuracy of 45.3% on the augmented unseen data (n=3). This is significant improved from the first subsection in which validation accuracy was only 20%. This system successfully demonstrates productive learning with scores beyond random guessing across ten classes. 












