# ECE570-FinalProject

For the model that I trained, you need to download it from the google drive. <br />
this is the google drive link: https://drive.google.com/drive/folders/147NJfxJCJ7RkCEabP-zTO7GlbTitVMzt?usp=sharing <br />
download the all 4 zip files and upload to the google drive using the left sidebar <br />

And then run the  <br />
!mkdir folder_name <br />
!unzip filename.zip -d folder_name <br />
if it make sure everything is in correct name, like the mlm model must be in the model of mlm_trained_model, nsp model must be in the folder of nsp_trained_model. <br />
results are unnecessary to be uploaded to the colab. <br />
And also make sure there is no nested folder, each folder is in root and when u get into the folder u should directly see the safetensor and json files. <br />
Important: remember to unzip the file and match the relative location in the code. <br />
Also, if you wish to train by yourself instead of loading, uncomment the trainer.train() function so that you can have your own model (not recommended, it usually takes around 1 hr to 5 hrs) <br />
Example Google colab directory: <br />
![image](https://github.com/user-attachments/assets/63658396-52b9-4fb4-9fff-c63e79070d2c)
![image](https://github.com/user-attachments/assets/f5e58093-6da1-4901-8026-bd8cd2d5daaf)



You can also use the gdown, and here is the github link for it: https://github.com/wkentaro/gdown


