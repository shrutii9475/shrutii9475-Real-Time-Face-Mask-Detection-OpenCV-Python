# shrutii9475-Real-Time-Face-Mask-Detection-OpenCV-Python

In today’s world it has become mandatory for all the citizens to wear a face mask to protect themselves from COVID-19. This program can be helpful for all the shop owners, offices, banks, schools, colleges or any public place because if anyone is not wearing a mask then he or she must not be allowed in that area. So, to take care of this very prominent problem we don’t need any guard or person who keeps a watch on people. As, this is a communicable disease, we do not want any guard to risk their health for security purposes.  We can integrate a camera which continuously clicks pictures of humans and detect from their faces whether they are wearing a face mask or not.

1.	Create a dataset that will be used to train our model.
  The dataset consists of 2 parts:
    First a folder with images of people with no mask.
  	Second a folder with images of people with no mask

2.	Then convert images into array

3.  Training of the model:
     And then apply some algorithm on that array by Implementing a Python script to train a face mask detector on our dataset using Keras and TensorFlow. This Python script will train a model and review the results.
   
4.	Implement another Python script to Detect face masks in real-time video streams.
   
5.	Deployment of the model:
   	Lastly, we can review the Results of applying our real time face mask detection.


python libraries used are:
1. TENSORFLOW
2. NUMPY
3. IMUTILS
4. KERAS
5. OPENCV-PYTHON
6. SCIPY
7. MATPLOTLIB

   RESULT

   ![image](https://github.com/shrutii9475/shrutii9475-Real-Time-Face-Mask-Detection-OpenCV-Python/assets/99082768/282ae7b5-2d26-4b31-8787-bd685f0ddc8e)

Figure: Detecting no mask- The following Image is the live example of the working of this project. As the person is not wearing a mask, it detects the face in a red rectangle followed by a No Mask header.


  ![image](https://github.com/shrutii9475/shrutii9475-Real-Time-Face-Mask-Detection-OpenCV-Python/assets/99082768/1faddae0-903d-4320-87e6-b4ea3371b442)

Figure: Detecting mask- This image is showing a person wearing a mask, that’s why face is detected in green rectangle followed by Mask header.

