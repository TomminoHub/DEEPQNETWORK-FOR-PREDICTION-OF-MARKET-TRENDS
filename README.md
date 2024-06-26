# AI and Finance Project
It was tested with python 3.11.9 but it should work with python 3.8+, to install all the packages needed to run the notebook you can use the command:
```bash
pip install -r requirements.txt
```
We first trained an LSTM to get the Close price of the IVV for the next minute. You can find the code and the trained LSTM in the _lstm_ folder with the two .csv of the Close price prediction. \
You can find the rest of the code in the _project.ipynb_ notebook, if you want you can skip the training phase because in the folder there is the already trained model: _DQN_trained_model.pth_. \
You can also see the already run notebook in the _project.html_ file.

If you want to run everything by yourself, you need to first run the _lstm.ipynb_ notebook to generate the predictions of the Close price and then you can run the _project.ipynb_ to train and test the model.