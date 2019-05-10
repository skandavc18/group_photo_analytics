# emotion_analytics
emotion analytics

This project was done for University Exhibition.A web interface was developed for this.

The problem was basically to do analytics on a group image. This has tremendous applications in the field of analytics.
The problem was divided into 4 tasks

1. Extract the faces. 
2. Recognition of faces. If the face is there in Database, do nothing. Else add to Database along with other relevent info like   age,gender,etc from the user.
3. Recognize emotions on each face using the CNN model
4. Plot graphs of emotions, age, gender,etc (if there in database )

So the add_imgdb.py,recognition.py,recog_extract.py,face_detect_extract.py are for adding images to database, recognize faces, extract faces and detect faces respectively. Graph.py is used to plot various graphs. 

The emotion_analysis.py file is the one which loads the model and analyzes the emotions and plots the emotion graph. 
The emotion_model_train.py trains a CNN which inturn is used to detect emotions in the face.

To start training the model, run the command python emotion_model_train.py .

A model.h5 file is created. This model is loaded by the emotion_analysis.py to do the analysis part
