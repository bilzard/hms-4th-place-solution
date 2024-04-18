# HMS - Harmful Brain Activity Classification
I have prepared code that works in the kaggle notebook environment.  

## preprocess
generate csv.  
https://www.kaggle.com/code/yujiariyasu/preprocess-train-csv

## data creation
generate spectrograms.  
https://www.kaggle.com/code/yujiariyasu/fmax30-sec30-8feats-0
https://www.kaggle.com/code/yujiariyasu/fmax90-sec10-8feats-0
https://www.kaggle.com/code/yujiariyasu/fmax60-sec40-16feats-0
https://www.kaggle.com/code/yujiariyasu/fmax30-sec50-16feats-0
https://www.kaggle.com/code/yujiariyasu/fmax30-sec30-8feats-1
https://www.kaggle.com/code/yujiariyasu/fmax90-sec10-8feats-1
https://www.kaggle.com/code/yujiariyasu/fmax60-sec40-16feats-1
https://www.kaggle.com/code/yujiariyasu/fmax30-sec50-16feats-1
https://www.kaggle.com/code/yujiariyasu/fmax30-sec30-8feats-2
https://www.kaggle.com/code/yujiariyasu/fmax90-sec10-8feats-2
https://www.kaggle.com/code/yujiariyasu/fmax60-sec40-16feats-2
https://www.kaggle.com/code/yujiariyasu/fmax30-sec50-16feats-2
https://www.kaggle.com/code/yujiariyasu/fmax30-sec30-8feats-3
https://www.kaggle.com/code/yujiariyasu/fmax90-sec10-8feats-3
https://www.kaggle.com/code/yujiariyasu/fmax60-sec40-16feats-3
https://www.kaggle.com/code/yujiariyasu/fmax30-sec50-16feats-3
https://www.kaggle.com/code/yujiariyasu/fmax30-sec30-8feats-4
https://www.kaggle.com/code/yujiariyasu/fmax90-sec10-8feats-4
https://www.kaggle.com/code/yujiariyasu/fmax60-sec40-16feats-4
https://www.kaggle.com/code/yujiariyasu/fmax30-sec50-16feats-4

## pretrain
pretrain 4 models.  
https://www.kaggle.com/code/yujiariyasu/pretrain-by-all-data

## train
finetune 4 models.  
https://www.kaggle.com/code/yujiariyasu/train-by-clean-data

## ensemble
stacking with 8 models predictions from all team members.  
https://www.kaggle.com/code/yujiariyasu/hms-stacking

## CSV & Weights
The following is the finished product.  

#### pretrained model weights for finetune:  
https://www.kaggle.com/datasets/yujiariyasu/first-fmax30-30sec-8ims-bandpass-spe-and-eeg  
https://www.kaggle.com/datasets/yujiariyasu/first-fmax90-10sec-8ims-bandpass-spe-and-eeg  
https://www.kaggle.com/datasets/yujiariyasu/hms-chris-fmax60-30sec-16ims-bandpass  
https://www.kaggle.com/datasets/yujiariyasu/first-fmax30-50sec-16ims-bandpass  

#### finetuned model weights for submit:  
The weights used for the final submission were created in kaggle notebook by all team members.  
Please see submission notebook for usage. https://www.kaggle.com/code/yujiariyasu/4th-place-solution  

https://www.kaggle.com/code/ren4yu/fork-of-fmax30-50sec  
https://www.kaggle.com/code/ren4yu/fork-of-fmax30-50sec-ccc5a6  
https://www.kaggle.com/code/yujiariyasu/fork-of-finetune-hms-chris-fmax30-30sec-8ims-bandp  
https://www.kaggle.com/code/tattaka/fold0-fmax30-50sec-9epochs-2stage-pretrain  
https://www.kaggle.com/code/tattaka/fold34-fmax30-50sec-9epochs-2stage-pretrai  
https://www.kaggle.com/code/tattaka/fold12-fmax30-50sec-9epochs-2stage-pretrain  
https://www.kaggle.com/code/yujiariyasu/fold0-fmax60-40sec-16ims-12epochs  
https://www.kaggle.com/code/ren4yu/fold012-fmax30-30sec-8ims-2stage-pretrain  
https://www.kaggle.com/code/ren4yu/fold012-fmax90-10sec-2stage-pretrain  
https://www.kaggle.com/code/tatamikenn/fold34-fmax90-10sec-2stage-pretrain  
https://www.kaggle.com/code/tatamikenn/fold34-fmax30-30sec-8ims-2stage-pretrain  
https://www.kaggle.com/code/tatamikenn/fold3-fmax60-40sec-16ims-12epochs-e60a77  
https://www.kaggle.com/code/tatamikenn/fold4-fmax60-40sec-16ims-12epochs-a8660e  
https://www.kaggle.com/code/tattaka/fold1-fmax60-40sec-16ims-12epochs  
https://www.kaggle.com/code/tattaka/fold2-fmax60-40sec-16ims-12epochs  
