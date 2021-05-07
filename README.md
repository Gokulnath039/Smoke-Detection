Smoke-Detection 


A wide range of Custom functions for YOLOV4 and Scaled-YOLOV4 are implemented by using Pytorch 


Demo For Smoke detection using Scaled YOLOV4 

Getting Started 

Conda(Recommended)


#Pytorch

   conda create --name Scaled-YOLOV4
   conda activate Scaled-YOLOV4-cpu
   
 Pip
   
  pip install -r requirements.txt
  
Nvidia Driver (For GPU, if you are not using Conda Environment and haven't set up CUDA yet)

Make sure to use CUDA Toolkit version 10.1 as it is the proper version for the  Pytorch version used in this repository. https://developer.nvidia.com/cuda-10.1-download-archive-update2

Download my weigth key for Smoke detection 
Use my  google drive link which given below:

      https://drive.google.com/drive/folders/1IqegxIsV2iHQZeVNPgO4KKQwSEhmQmea?usp=sharing
      
Download and paste the weigth file in weigth key folder 



After download and paste the weigth.Your are run to Object detection model in our machine by follow the command below:

  python detect.py --weights . (Weigths_path) /best_yolov4-csp-results.pt --img 416 --conf 0.4 --source .. (img_path)

Wow! you done a smaoke detection 
