# ML Model For Titanic Dataset
This is a simple model used to differentiate between passengers who survived and who didn't.

## Dataset
The dataset itself is present in .csv format in ```/csvs/titanic```. The training set and the outputs
are also in this folder.

## Model 
The model is very simple. It is a sequential model containinig 3 dense layers with softmax as activation function. And for as the loss function, binary crossentropy is used.

## Outputs
After training and testing the model, outputs are saved in ```csvs/titanic``` and ```images/titanic```. The former includes the ```output.csv``` where the 
latter has a ```.png``` file showing accuracy loss.
