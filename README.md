# IIT-Jodhpu--Challange
IIT-Jodhpur challange for Research Associate

Dataset Used: https://www.kaggle.com/c/logical-rythm-2k20-sports-image-classification/overview

For this challange i have run two model
1. ciustom efficienetB0
2. Fouryer Visual Transform



with Custom EfficientNet-bo we have got 97% on Train and 88% on Val
For Fouryer Visual Transformwe we got 87%  on train and 77% on val, 
All the logs are in the respective notebooks

With Fouryer Visual Trnasform we would get better accuracy, if we make network deeper,
due to computational efficiency i have onlu used three blocks from ViT and 2 two blcoks from FVT, so this intend the accuracy reaches to 77%

with the analysis I have run the Inference on Custom-EfficientNet-B0 and made the 'test_predection.csv'

`IIT_jodhpur_challange.ipynb` In this notebook we have run teh inference,
just upload the notebook to colab and run all code shell sequentially model will start training. All the dependeny have been taken care off.
'sports.h5' is trtained custom efficienet-B0 model for inference.

