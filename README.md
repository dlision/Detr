Firstly we have clone the github reposity as given below  
```
git clone https://github.com/facebookresearch/detr.git
```
To install dependencies is to run the requirement.txt as 
```
pip install -r requirements.txt
```
then to run the inference on the specific model use this file and pass the following arguments.

detr_inference.ipynb

 specifyb the model name in a variable like detr_resnet101 or detr_resnet50 
```
model_name =  {specify the model name}
```
 And then set the path of test images 
 Path= {specify the path of images}
 after that set the out path as 
 output_path={specify the ouput path}
