# Mask_NoMask_Detection

It is very very for everbody to follow the rules set by the government. One of which is wearing mask in public places. This inspired me to try building a model to detecting mask on the faces and classify accordingly based on whether a person is wearing a mask or not. 

# Logic 

This could be set up at an entrance of any public area using Raspberry Pi and camera. When a person is wearing the mask, he/she should be allowed or given access to move into public area and if not then they need to wear the mask inorder to entry the area. 

Since I could not get live video, I have created a video from set of images (Mask/No Mask) and provided this video as input to test my model. I have used OpenCV to stream the video, training the Neural Network to classify mask/no mask and used an excellent pre-trained face-recognition model MTCNN to detect the faces in the frame. Once the face is detection, the trained model will be classifying whether the person is wearing the mask or not.

# Output

[![Download to watch full video output]()](Mask_No_Mask_Detection.mp4)
