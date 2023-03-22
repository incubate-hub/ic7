Anomaly-Detection-in-Networks-Using-Machine-Learning
The implementation phase consists of 5 steps, which are: 
1- Pre-processing 
2- Statistics 
3- Attack Filtering
4- Feature Selection
5- Machine Learning Implementation
1 - Pre-processing
This step consists of a single file (preprocessing.ipynb). For this program to work, the dataset (CIC-IDS2017) files must be in the "CSVs" folder in the same location as the program. The dataset files can be access here . (The reason that these files are given an external link is that the maximum limit of the file in the cseegit system is 10 MB)
As a result of executing this file, a file named "all_data.csv" is created. This file is a prerequisite for the other steps to work.

The most recent runtime of this file was recorded as 328 seconds. The technical specifications of the computer on which it is run are given below.

Central Processing Unit	:	Intel(R) Core(TM) i7-7500U CPU @ 2.70GHz 2.90 GHz
Random Access Memory	:	8 GB (7.74 GB usable)
Operating System	:	Windows 10 Pro 64-bit
Graphics Processing Unit	:	AMD Readon (TM) 530
Attack Filtering
This step consists of a single file (attack_filter.ipynb). This program uses the "all_data.csv" file to create attack files and then it saves them in the "./attacks/" location. The Dataset contains 12 attack types in total. Therefore, 12 CSV files are created for these attacks. Within each file are 30% attack and 70% benign registry.This step is the prerequisite for the fourth and fifth steps. The last run time of this file was recorded as 304 seconds.


