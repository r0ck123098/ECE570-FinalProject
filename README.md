# ECE570-FinalProject

For the model that I trained, you need to download it from the google drive.
this is the google drive link: https://drive.google.com/drive/folders/147NJfxJCJ7RkCEabP-zTO7GlbTitVMzt?usp=sharing
download the all 4 zip files and upload to the google drive using the left sidebar
![image](https://github.com/user-attachments/assets/63658396-52b9-4fb4-9fff-c63e79070d2c)
And then run the !mkdir folder_name
!mv [filename].zip
! cd folder_name
!unzip [filename].zip
! cd ..
if it make sure everything is in correct name, like the mlm model must be in the model of mlm_trained_model and mlm result must be in mlm_results. nsp model must be in the folder of nsp_trained_model and nsp results must be in nsp_results.
And also make sure there is no nested folder, each folder is in root and when u get into the folder u should directly see the safetensor and json files.
Important: remember to unzip the file and match the relative location in the code.
Also, if you wish to train by yourself instead of loading, uncomment the trainer.train() function so that you can have your own model (not recommended, it usually takes around 1 hr to 5 hrs)


You can also use the gdown, and here is the github link for it: https://github.com/wkentaro/gdown


