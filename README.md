# skinLesionClassifier
Skin cancer is the most common type of cancer. About 30% of new cases of cancer
in Canada are skin cancers. There are many types of skin cancer, but the most
deadly form (by far) is melanoma. Melanoma is very hard to stop once it has
spread to other parts of the body. Fortunately, early detection can improve
the chance of survival.

This is a classification model that uses the HAM10000 dataset to classify skin 
lesions as either melanoma or non-melanoma. It is trained on Google's Inception v3
Convolutional Neural Network (CNN) model.

The model was trained using Keras and has an accuracy score of around 86%.

### Usage
```sh
$ git clone https://github.com/karmdesai/skinLesionClassifier.git
$ cd skinLesionClassifier
$ python lesionPredictor.py 
```
Once the model has loaded, there will be a prompt asking for the file path of the 
image that you want to classify. Simply enter the entire file path and the model
will classify the lesion.

### What's Next
- [ ] Convert the model to TensorflowJS so that it can be used on the web
- [ ] Upgrade the model so that it can classify lesions into more types

### Acknowledgements
1. Inception v3 Model - [https://github.com/tensorflow/models/tree/master/research/inception]
2. Skin Lesions Classification Paper - [https://arxiv.org/pdf/1812.02316.pdf]
3. HAM10000 Dataset - [https://www.nature.com/articles/sdata2018161]