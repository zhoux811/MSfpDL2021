## what does the separate files do: (by order of use)


#### (1) rename_files.py
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
rename the raw resource files scrapped from webpage into organized format.

#### (2) rename_to_resnet_format_DONTRUN.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
(helper) rename the above files into format that training model reads. embed label in file name.

#### (3) AutoFilterRaw_test.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
display pre-trained model's classification result to find patterns.

#### (4) AutoFilterRaw_ResNet50_top2.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
filter the data using a pre-trained model based on confidence ranking.

#### (5) resnetSaveData.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
convert the bulk files into binary format for loading into trainer.

#### (6) Resnet50Train_4classesTeslaFewShot_DLSelect.py & Resnet50Train_4classesTeslaFewShot_ManSelect.py
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
train model with filtered data. do not save checkpoints, save models

#### (7) REsNetTrain_4classesTesla_directOutputModel.py
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
same as (6), do not save checkpoints, save models.

#### (8) Resnet50Train_3classes_DLSelect.py & Resnet50Train_3classes_ManSelect.py
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
same as (6). save checkpoints. do not save models.

#### (9) 3class_graph.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
use the checkpoints from (8) as weight models, test performance and output results

#### (10) 4class_graph.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
same as (9)

#### (11) 3classes_2chkpts_to_model.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
load checkpoints, continue training, save model after.

#### (12) load_model_predict_compare.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
apply the two trained model, display statistical predicted and validation results.

