**How to run the model on TinyML kit?** \
Link for Video Demo https://youtu.be/gmPGQqUhgyw

Download  room_classification.ino , room_classification.h\
Put them in a folder named room_classification\
Double click on room_classification.ino to open it using ArduioIDE.\
Connect TinyML kit with pc.\
Upload sketch.\
(Optional) Download Display_images&Results.py and run in on PC to see the image captured along with Prediction and confidence scores.

**How to train the model and get room_cassification.h?** \
Download Folders bedroom_class_lift_train, bedroom_class_lift_train, Training_CNN_model.ipynb\
Install necessary python libraries. We used python Python 3.9.18, Tensorflow 2.12.0, Keras 2.12.0\
Run Training_CNN_model.ipynb


**How to create a dataset to make my own Image classifier?** \
Download CaptureImage.ino, build_dataset.py\
Upload CaptureImage.ino to TinyML kit\
Run build_dataset.py to see the captured images, give labels and save them.\
