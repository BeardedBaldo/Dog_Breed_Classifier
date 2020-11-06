# Dog_Breed_Classifier
Pytorch implementation of a dog breed classifier. The notebook provided contains all the main processes involved including downloading the dataset, processing it, loading the pretrained models, 
training, testing and prediction. Its a simple implementation of transfer learning in pytorch. Final result: vgg19 model with batch normalization provided highest testing accuracy of ~75% with 15 epochs.

<b>Dataset used:</b> The <a href = "http://vision.stanford.edu/aditya86/StanfordDogs/">Stanford dogs dataset</a> was used for the purpose. Contains 20000 images of 120 breeds of dogs.
note: Sometimes the dataset link does not work as there possible issues with the server.

<b>Models used:</b> Resnet50, vgg11, vgg19, and inception. More models to be added in the future. 

<b>Next Steps/Fixes: </b> 
1) Improve model accuracy with more hyperparameter tuning(more epochs, lower learning rate, other optimizers/loss functions)
2) Add and test out more pretrained models (Alexnet, other variants of resnet, vgg etc.)
3) Include more breeds in the dataset (collect dataset via scrapping)
4) Deploy into a web app

