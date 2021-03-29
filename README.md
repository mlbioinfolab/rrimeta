Introduction
The objective of this study of residue-residue interactions is to introduce a generic computational model to exploit the synergy among various protein information. The computational model is based on meta learning. It has the flexibility to integrate various component prediction tools into a unique prediction system. 
For the purpose of demonstration, we provide the executable code of RRI-Meta and the data used in this study.


Availability
 The complete executable code and data are available on the Google Drive through this link (https://drive.google.com/drive/folders/17yOsZ3RSQxFPZcnZCEWORFm0pBbeABcY). For the purpose of a quick test drive of RRI-Meta, we have prepared the training and test data constructed 224 distinct protein complexes, and the reader can test-drive RRI-Meta directly on these preprocessed datasets.


Materials
Computer code:
1.	rri-meta.exe: executable code of RRI-Meta

Data folders/subfolders:
1.	main_folder: a folder that stores rri-meta.exe, residue pair data. After unzipping the zipped file downloaded from the Google Drive, the contents of a main folder, e.g. rri-meta, will look like what the snapshot below shows. 
![image](https://user-images.githubusercontent.com/46346202/112778806-ed334400-9077-11eb-9c12-a7870a9f389d.png)
 
 

2.	protein complex: a folder that stores the distinct PDB files and sequence files of protein complexes listed in docking benchmark 5.0 (DBD 5.0). The snapshot below shows the subfolders which stores sequence files and PDB files.
![image](https://user-images.githubusercontent.com/46346202/112778824-fa503300-9077-11eb-9cd2-28b47a40c7bf.png)

 

3.	data: a folder that stores the training data and the test data in their feature vector form, and other relevant information.


Instructions to use the meta classifiers to predict the residue-residue interactions

A. For a quick test drive of RRI-Meta, using code and data on GitHub:

1.	Create a main folder, e.g. rri-meta, on your PC (Windows system). From GitHub, download rri-meta.exe and place it in rri-meta. Download the datasets from Google Drive and place them in rri-meta on your PC. 
![image](https://user-images.githubusercontent.com/46346202/112778854-0b00a900-9078-11eb-8831-19d7a3ddab58.png)



2.	How to run RRI-Meta to train and test RRI prediction models in Windows Systems?
a)	To complete both training and testing in one step by running rri-meta.exe, type the following command in “Command Prompt”. Refer to the snapshot below.

Take 1A2K for example. Type the following.
rri-meta.exe 1A2K
![image](https://user-images.githubusercontent.com/46346202/112778874-1522a780-9078-11eb-84bf-83cb6d663869.png)

 

The prediction performances, e.g. Accuracy, MCC, AUCROC, are output on the screen. In addition, one result file is produced and stored in 1A2K.txt.


 




