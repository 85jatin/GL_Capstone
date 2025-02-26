# GL_Capstone
Data science research to build mobile application that captures cricket shots played by batsmen to provide real-time performance insights

Refer proposal document for more details: https://github.com/85jatin/GL_Capstone/blob/master/PROPOSAL.md

# List of experiment results:
## 1 Base VGG16
VGG16_DL, 174 shots, 10991 frames
### 68% accuracy at predicting Direction
https://github.com/85jatin/GL_Capstone/blob/master/Test_Validation_VGG-16%20pre-trained%20model%20implementation.ipynb
## 2 Base MobileNet
MobileNet_DL, 174 shots, 10991 frames
### 64% accuracy at predicting Direction
https://github.com/85jatin/GL_Capstone/blob/master/Test_Validation_MobileNet%20pre-trained%20model%20implementation.ipynb
## 3 Exp_1 MobileNet 
MobileNet_DL, 174 shots, 2809 frames (tailing 25% from all vidoes)
### 80% accuracy at predicting Direction
https://github.com/85jatin/GL_Capstone/blob/master/Exp_2_Test_Validation_MobileNet%20pre-trained%20model%20implementation_last_25%25_frames.ipynb
## 4 Exp_2 MobileNet 
MobileNet_DL, 174 shots, 2679 frames (tailing 25% from all vidoes, background substraction)
### 80% accuracy at predicting Direction 
https://github.com/85jatin/GL_Capstone/blob/master/Exp_3_Test_Validation_MobileNet%20pre-trained%20model%20implementation_50%25frames_backgroundSub.ipynb
## 5 Exp_4 InceptionResnetV2
InceptionResnetV2_DL, 174 shots, 2596 frames (tailing 25% from all videos, background substraction)
NOTE: Problem statement reframed (binary classification - OffSide/Legside; Straight class dropped)
### 87% accuracy at binary Direction class inferences
https://github.com/85jatin/GL_Capstone/blob/master/Exp_4_Test_Validation_InceptionResnetV2%20pre-trained%20model%20implementation_25%25frames_backgroundSub_binary.ipynb
