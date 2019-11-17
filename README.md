# User_Verification_with_face_unlock
 This is a beta version of an user verification application for windows.  Ver-1.0


#Verify the user post login on Windows

Windows Anniversary Update on July 9th was a major developemnt for many windows features including security. An additional feature can now be added to your laptop/personal computer with the help of UV (User Verification). User Verification is a basic windows based application that is still in development. Currenlty this application can be downloaded freely and used freely. The application requires Python installed on the machine.

######
#Idea

* When you switch on your PC/Laptop and the device asks for a password, how many times do your friends or potential threats open it up with the knowledge of your password? Well, not anymore! The User Verification application launches a face recognition check upon logging on to windows to ensure if it is the intended user. If not windows will be locked and returned to the lock screen once again. The facial recognition of any number of users can be trained on the model provided in this package and the application responds to all of the trained faces positively.

# Scope for future developments
 * I intend to wrap the application in a exe file with a nice user interface and some custom features. Keeping it simple and more user friendly, I also intend to work on making this a stand alone application without having to follow any installation hussles. Whilst Improving the accuracy of face recognition on one side, I'm also planning to develop this application to support more features like unlocking the machine itself. Just like in mobile phones the application once installed will work in the background immediately when the computer reaches lock screen and tries to recognise users instead of asking a password. Any suggestion, ideas and support is deeply appreciated.
 
 # Installation
 
 *Firstly you need to run 'create_face_datasets.py' using the 'execute.bat' file provided. Note: do edit the file prior with python.exe location on your computer and the location of create_face_datasets.py location.
 
 *Once the above step is initiated please wait for few minutes while the webcam quickly clicks images of your face and saves it to a folder 'training' in your working directory. (A total of 100 pictures will be clicked in about 50 secs)
 
 *second step is to initiate 'training_model.py' file, by replacing 'create_face_datasets.py' file in the 'execute.bat' file and run it. Note: Do open the .py file with python idle or pycharm adn edit the location of files to the ones on your computer or it will throw an error
 
 *Open the 'lock_unloack_face_recognition.py' and edit the locations jsut like in the above steps and save the file. Also remember to update the 'execute.bat' file one last time and replace the 'training_model.py' with 'lock_unlock_face_recognition.py'.
 
 *Ready to go. Search for 'Task Scheduler' on the windows start menu and open it with 'run as administrator' option.
 
 *Under the action tab click on -> 'Create Take' -> enter a name for your application ('user_verification') -> select the triggers tab on the right -> and select 'new'. Under 'Begin the task' drop down choose 'On Workstation Unlock' and select 'specific user' and click ok.
 
 *Goto the next tab 'Actions' and click on 'New' -> under Program/Script -> click browse and select the 'execute.bat' file and click ok, on the task scheduler screen click ok once again and close the task scheduler application.
 
 *Now hit ctrl+L to lock your computer then enter our password to unloack asusual. The application will launch itself and recognizes your face, if it is you no action is taken. If someone else enters the password and opens the computer upon recognition the computer will be locked again and the user is sent to lock screen again.
 
 
 
 
 
 #######
# Requirements
 
 0. Python(https://www.python.org/ftp/python/3.6.3/python-3.6.3-amd64.exe) installed with with the following packages
 1. Numpy
 2. Opencv
 3. Pillow (PIL)
 4. Pyautogui
 5. Windows Task Scheduler
 
 
 #########
 #Looking forword to working on further developments on this application, all contributions are welcome.
 
 
 # KnownStranger03
      |
         |
            |
               |
                  |
                     |
                        |
                           |
                              |
                                 |
                                    |
                                       |
                                          # User Verification - ver 1.0
                                                                         |
                                                                            |
                                                                               |
                                                                                  |
                                                                                     |
                                                                                        |
                                                                                           |
                                                                                              |
                                                                                                 |
                                                                                                    |
                                                                                                       |
                                                                                                           |
                                                                                                              |
                                                                                                                 |
#                                                                                                                      Krishna Prasad
     
  
 
    
        
           
              
 
 *
