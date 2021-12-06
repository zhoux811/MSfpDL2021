# what does the separate files do: (by order of use)


### rename_files.py
  rename the raw resource files scrapped from webpage into organized format.

## rename_to_resnet_format_DONTRUN.ipynb
  (helper) rename the above files into format that training model reads. embed label in file name.

## AutoFilterRaw_test.ipynb
  display pre-trained model's classification result to find patterns.

## AutoFilterRaw_ResNet50_top2.ipynb
  filter the data using a pre-trained model based on confidence ranking.



## resnetSaveData.ipynb
   convert the bulk files into binary format for loading into trainer.




## 3classes_2chkpts_to_model.ipynb

## 4class_graph.ipynb



## REsNetTrain_4classesTesla_directOutputModel.py

## Resnet50Train_3classes_DLSelect.py

## Resnet50Train_3classes_ManSelect.py

## Resnet50Train_4classesTeslaFewShot_DLSelect.py

## Resnet50Train_4classesTeslaFewShot_ManSelect.py

### 3class_graph.ipynb
  load all the checkpoints generated when train the 3 classes model

## resnetTrain.ipynb





## load_model_predict_compare.ipynb
  apply the two trained model, display statistical predicted and validation results.







