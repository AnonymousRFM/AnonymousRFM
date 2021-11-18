# RFM
Train the model by  
```bash
python train_old.py --gpu 0  
```
The training may take around 18 GB of memory of GPU. Due to the order of the output, it should be trained under a single GPU. 

So, if you using more than one GPU, you can refer to line 254~257 in train_old.py to change the order of the output.
