##  Smart Attendance Management system using Face👦🏻👧 Recognition 
Face Recognition Based Smart Attendance System. It is not only mark your attendance but also send notification via mail & sms. It also contain pre-defined instruction chatbot. UI is build using Tkinter which is very popular Framework of Python used to build Desktop applications.

Requirements
----------------------------------
1) Libraries
-pip install tkinter#
-pip install opencv
-pip install mysql
-pip install csv
-pip install cv2
-pip install pyttsx3
-pip install datetime
-pip install pytz
-pip install twilio
-pip install smtp
-----------------------------------
2) Python Version 3.11 (Python 3.11.5)
-----------------------------------
3) Software Used
-Pycharm IDE
-Mysql WorkBench (For Building the database).
-Twilio Account
-----------------------------------
4) Hardware Requirements
-camera
-storage
-processor
-----------------------------------

## Project Structure

- After run you need to give your face data to system so enter your ID and name in box than click on Take Images button.
- It will collect 100 images of your faces, it save a images in data folder
- After that we need to train a model(for train a model click on Train Image button.
- It will take 1 minute for training(for 5 person data).
- After training click on Face Detector ,it can fill attendace by your face using our trained model (model will save in TrainingImageLabel )
- it will create .csv file of attendance according to time & name.
- You can store data in database (mysql workbench),change the DB name according to your needs.

### Screenshots

### Basic UI
![Screenshot 2023-09-18 150812](https://github.com/user-attachments/assets/153ccf66-e16e-4db1-a8de-6f102b8037ee)

### Student details
![Screenshot 2023-09-18 150942](https://github.com/user-attachments/assets/2e7f3835-b4fa-45f3-a5ec-953102a5e291)

### Training Portal
![Screenshot 2023-09-18 151442](https://github.com/user-attachments/assets/7eec5239-4019-4df0-b357-38baffde26be)

### When it's Recognise me
![Screenshot 2023-09-18 151735](https://github.com/user-attachments/assets/c50fc047-23b8-475e-b6aa-7e134aac8417)


### Record attendace
![Screenshot 2023-09-18 151815](https://github.com/user-attachments/assets/a3637ada-38e0-404e-be1a-310ad84371fc)


### Notification Portal
![Screenshot 2023-09-18 151505](https://github.com/user-attachments/assets/e9e211e5-2fb6-45b8-a2a2-79e65167539b)


### Data Stored
![Screenshot 2023-09-18 151041](https://github.com/user-attachments/assets/2f7415d2-9d86-45f7-bf31-f2929b8efe0f)

### How it works? See:)
https://github.com/user-attachments/assets/8e227e92-7c40-4744-83d7-91a6b6da8406




### Notes
- It will require high processing power(I have 8 GB RAM & 2 GB GC)
- If you think it will recognise person just like humans,than leave it ,its not possible.
- Noisy image can reduce your accuracy so quality of images matter.

## Just follow☝️ me and Star⭐ my repository 
