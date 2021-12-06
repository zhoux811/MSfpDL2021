## what does the separate files do: (by order of use)


#### rename_files.py
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
rename the raw resource files scrapped from webpage into organized format.

#### rename_to_resnet_format_DONTRUN.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
(helper) rename the above files into format that training model reads. embed label in file name.

#### AutoFilterRaw_test.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
display pre-trained model's classification result to find patterns.

#### AutoFilterRaw_ResNet50_top2.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
filter the data using a pre-trained model based on confidence ranking.

#### resnetSaveData.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
convert the bulk files into binary format for loading into trainer.

#### 3classes_2chkpts_to_model.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
#### 4class_graph.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;


#### REsNetTrain_4classesTesla_directOutputModel.py
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
#### Resnet50Train_3classes_DLSelect.py
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
#### Resnet50Train_3classes_ManSelect.py
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
#### Resnet50Train_4classesTeslaFewShot_DLSelect.py
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
#### Resnet50Train_4classesTeslaFewShot_ManSelect.py
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
#### 3class_graph.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
load all the checkpoints generated when train the 3 classes model

#### resnetTrain.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;




#### load_model_predict_compare.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
apply the two trained model, display statistical predicted and validation results.







