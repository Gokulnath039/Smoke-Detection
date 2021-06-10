Smoke-Detection 


A wide range of Custom functions for YOLOV4 and Scaled-YOLOV4 are implemented by using Pytorch 


Demo For Smoke detection using Scaled YOLOV4 

 ![smoke](https://user-images.githubusercontent.com/67773609/117445624-8a777700-af58-11eb-935f-b6fcab2e45b7.png)


Getting Started !!

Conda(Recommended)

To create a virual envs in your machine by using the command below:

    conda create --name Scaled-YOLOV4
    conda activate Scaled-YOLOV4-cpu
    
 Pip
   
    pip install -r requirements.txt
  
Nvidia Driver (For GPU, if you are not using Conda Environment and haven't set up CUDA yet)

Make sure to use CUDA Toolkit version 10.1 as it is the proper version for the  Pytorch version used in this repository. https://developer.nvidia.com/cuda-10.1-download-archive-update2

Download weigth file in <a href="https://drive.google.com/drive/folders/1IqegxIsV2iHQZeVNPgO4KKQwSEhmQmea?usp=sharing">drive</a>  

      
Download and paste the weigth file in weigth key folder 

![weight](https://user-images.githubusercontent.com/67773609/117445941-ffe34780-af58-11eb-939f-07dc6ad88cd9.png)


After download and paste the weigth.Your are run to Object detection model in our machine by follow the command below:

  ![run ](https://user-images.githubusercontent.com/67773609/117446218-610b1b00-af59-11eb-9982-5ebabdb6b73f.png)

    python detect.py --weights . (Weigths_path) /best_yolov4-csp-results.pt --img 416 --conf 0.4 --source .. (img_path)


I take the open dataset for the training in roboflow

Dataset Link is given below:
   
    https://public.roboflow.com/object-detection/wildfire-smoke
    
wow! you Made it smoke detection on your machine 
