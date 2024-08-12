# -Medical-Image-Segmentation
Link to dataset：https://drive.google.com/file/d/1p33nsWQaiZMAgsruDoJLyatoq5XAH-TH/view
dataset structure：
Domian1: Drishti-GS dataset [101] including training[50] and testing[51]  
Domain2: RIM-ONE_r3 dataset [159] including training and[99] testing[60]  
Domain3: REFUGE training [400] MICCAI 2018 workshop including training and[320] testing[80]  
Domian4: REFUGE val [400] including training and[320] testing[80]  
dataset should be saved in the folder(Dataloaders)  
parametric：  
Epoch 100  
Batch Size 5  
Optimizer Adam(base_lr=0.001,betas=(0.9, 0.999))  
tqdm>=4.60.0  
tensorboardX>=2.1  
torch>=1.7.1  
torchvision>=0.8.2  
pytorch_metric_learning>=0.9.99  
numpy>=1.19.2
