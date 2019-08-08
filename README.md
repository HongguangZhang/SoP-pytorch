# To train the model with following command.

python main_pretrain_SoP.py --pretrained -b 32 [path to ImageNet dataset]

-b: batch size, adjust according to the GPU memory
check other options in main_pretrain_SoP.py

# To modify the output of Resnet50.
1. open 'resnet_models.py'
2. go to line 184-199
3. comment and uncomment lines to modify the output from Resnet50 
