# CSE676_traffic_sign_detection

## Abstract

Traffic signs classification is the process of identifying which class a traffic sign belongs to. In this project, we will build a deep neural network to classify traffic signs into different categories, such as speed limits, no entry, traffic signals, turn left or right, children crossing, no passing of heavy vehicles, etc. We are able to read and understand the meanings of each sign which are of great significance to automatic vehicles.

## Directions to run the code
1. get *Model.zip* from https://drive.google.com/file/d/1oMLC1MYyn_CmrRzCiHV6P6YryJOIvL0a/view?usp=sharing, then unzip *Model.zip*
2. Install all the dependencies with requirments.txt file
    * We are using google colab
    * **Type** - !pip install -r requirements.txt
2. Go to the directory named *Codes* using `cd Codes`
3. Before running the next command, put the image/video file, in which you want to detect traffic signs  in the directory named *Test*
    * **Type** - `python detect.py --source ../Test/{name of your file}`
    * For example if image name is test.jpg then type ` python detect.py -- source ../Test/test.jpg`
6. For running on live camera feed 
    * **Type** - `python detect.py --source 0`
7. Outputs are saved in *Results folder*

## Authors
Cheng Qian, Emely Xu, Jiaheng Zhang, Jinyi Tao
University at Buffalo
