# Project-Building-an-E-Commerce-Clothing-Classifier-Model
Using Deep Learning to automatically classify new product listings for a clothing retail store.

In this project, I solved a business problem for a clothing retailer by building a Deep Learning model that automatically categorizes new product listings into distinct garment types such as shirts, trousers, shoes, etc.
It is useful in business because:
1, It makes it easier for customers to find what they're looking for, saving both* the business and the customers valuable time and money.
2, It assists in inventory management by quickly sorting items, reducing costs on manpower and fast-tracking operations.

The model is trained on the FashionMNIST dataset class which has 60,000 training images and 10,000 test images. It is a Convolutional Neural Network that I initially trained to run for 50 epochs, but because of an early stopping function I applied, the model was able to achieve its best value at 15 epochs and didn't need to run all the way to 50. This early stopping mechanism monitors validation loss and stops training if it doesn’t improve for a certain number of epochs (the "patience" argument, which I set to 5).
This helps optimize the number of training epochs and prevent overfitting. The model achieved an accuracy of apprx 90%.

#### I am not able to upload the dataset here yet, but it can always be downloaded from other sources.
