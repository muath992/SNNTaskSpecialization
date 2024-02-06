# SNNTaskSpecialization


## Notes:
* The codes are self contained and should run when following the three steps below. 
* In the main file "example_cifar10_vgg9.py", make sure you change directories of the dataset and the location where you want to save the model.


## Steps to train a sub-SNN: 

1. Insall all the packages in the file "requirments.txt" into your virtual environment.

2. Run your virtual environment.

3. Run the python file for training
   * python "example_cifar10_vgg9.py" --scale-factor 8 --epochs 260  --reset-model 1  --subSNN-index 0
   * Tune the hyperparameters by passing the parser's parameters as shown in the example above.
  



   
