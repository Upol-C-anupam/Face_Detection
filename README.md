# Face_Detection

1. Drew bounding box around the face using the library called "Labelme".
2. Data augmentation is done using albumentation library
3. I have used BINARYCROSSENTROPY  loss function as it is an classification problem and also have used Localization loss function as it is a boundary detection problem as well.
4. Used VGG16 model inside my model and added final two layers which were our classification and regression model.
