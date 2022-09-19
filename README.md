# Wi-fi-Activity-recognition-Survey
This project is "only" for TONIC laboratory member who is interested in Wi-Fi sensing.This is a detailed guidance of running the code given by the author of survey paper-><a href="https://doi.org/10.1109/MCOM.2017.1700082">A Survey on Behavior Recognition Using WiFi Channel State Information</a>.  
Furthermore, this page foucus on running the code fluently rather than comprehensively explaining the code and data.

<br/>

## We use 

GPU: NVIDIA RTX 3070  
OS: Ubuntu 18.04.6 LTS  
Package Managemenhttps://github.com/ermongroup/Wifi_Activity_Recognitiont: Anaconda3 (Highly recommend**)
 

## Prerequisite

python = 3.6.5  
tensorflow = 2.8.2  
tensorflow-addons = 0.17.1 (Use "pip install")    
cudnn = 8.2.1  
cudatoolkit = 11.3.1  
scikit-learn = 0.19.1   
numpy = 1.14.3    
matplotlib = 2.2.2  
pandas = 0.23.0  

<br/>

## How to  run
0. Download dataset from [here](https://drive.google.com/drive/folders/1c_DIC1q9Zn3UKKn6XrX47IuNkrOUkhjO?usp=sharing)  
 -> **Notice: Dataset size is ~4GB**  

1. "git clone" this repository.  
 
2. Run the cross_vali_data_convert_merge.py  
 -> This script makes csv files(input features & label) of each activity in "input_files" folder.　　

3. Run the cross_vali_recurrent_network_wifi_activity.py 
 -> This script makes learning curve images & confusion matrix in a new folder.　　

## Other information
Plese check [here](https://github.com/ermongroup/Wifi_Activity_Recognition)

