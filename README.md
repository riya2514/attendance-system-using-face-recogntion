# attendance-system-using-face-recogntion
This repository contains code for facial recognition using openCV and python with a tkinter gui interface. To run the code open train.py file

Technology used : -openCV (Opensource Computer Vision - version : 4.2.0.34) -tkinter GUI interface
software :Python (3.7), Pycharm IDE.

we're working on Face recognition based Attendance Management System by using OpenCV(Python), Tkinter. One can mark thier attendance by simply facing towards the camer

Working :

When we run train.py a window is opened on command prompt and it'll ask for Id and Name. After entering we have to click Take Images button. By clicking "Take Images", web camera is opened and it start taking image sample of person.This Id and Name is stored in folder StudentDetails and file name is StudentDetails.csv. It takes 60 images as sample and store them in folder TrainingImage.After completion it notify that iamges are saved. After taking image sample, we have to click Train Image button.
Now it will take few seconds to train machine for the images that are taken by clicking "Take Image" button and creates a Trainner.yml file and store in TrainingImageLabel folder.Here make a new folder "TrainingImageLabel" after clonning the project where your yml file will be saved.
Now all initial setups are done. By clicking Track Image button, camera of running machine is opened again. If face is recognised by system then Id and Name of person is shown on Image. Press "a" for closing this window. After quitting, attendance of person will be stored in Attendance box present below on the window and also in the attendance folder as csv file with name, id, date and time. Also  create a folder with name attendance and make attendance.csv file so that new entries could be saved there after clonning the project.

Made by: Riya Sinha & Shrinkhala singh
