# GL_Capstone
Predict videos of cricket shots played by batsmen and predict outcomes

# Folder Structure (to run notebooks from scratch):
-> Capstone (Master folder)
  -> Trimmed_complete (Videos completed with trimming step)
  -> Trimmed_videos (Overall dataset of videos to be used for training)
  -> Yet_to_trim (Videos yet to trim)
  -> Batch_1 (One for each experiment/Iteration)
    -> Direction_Class (One for each classification usecase)
      -> A_OffSide (Tagged videos class 1)
      -> B_Legside (Tagged videos class 2)
      -> C_Straight (Tagged videos class 3)
      -> D_Leave (Tagged videos class 4)
      -> temp (Empty folder to store frames from test video)
      -> train_1 (Empty folder to store frames from training vidoes)
      -> List.csv (Dataframe with video location and respective classes)
      -> Preprocessing.ipynb (Preprocess vidoes to images)
      -> VGG-16 pre-trained model implementation.ipynb
      -> Test_Validation_VGG-16 pre-trained model implementation.ipynb
      -> MobileNet pre-trained model implementation.ipynb
      -> Test_Validation_MobileNet pre-trained model implementation.ipynb
