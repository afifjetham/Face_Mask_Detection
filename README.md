# Face_Mask_Detection
**Description:**

Face Mask Detection is one of the useful and high in demand usecase in recent times due to the Covid-19 disaster.

Recently it has been made mandatory for public to wear a mask continously. Places such as Airports, Hospitals, Malls, etc doesn't allows one to enter if found without the Mask. And also there are countries where wearing mask had been made compulsory and fine has been imposed if found without the Mask.

As it was difficult to keep a track of such scenario. This Image Recognition software came into picture which made it easier to detect whether a person is wearing a mask or not.

**About Dataset:**

The Dataset contains images of people wearing masks and people not wearing masks. The database contains 10,000 colored images in the training folder, 800 images in the validation folder, and 992 images in the test folder.
I am unable to upload the dataset due to large file size. You can find many such datasets on Kaggle or can ask me for the same by connecting with me.

**Task:**

Your task is to create a CNN model for identifying whether a person in the image is wearing a mask or not.

Please perform the following tasks:

- Download the database, You can download it from Kaggle.
- Create test, train, and validation directory variables
- Create train and validation data generator with target size (128,128)
- Train a CNN model
- Train a model with VGG19 model
- Use callbacks to save your model at every step
- Training may take several hours, so use 5 to 10 epochs only.
