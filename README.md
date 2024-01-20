# SmartMonitoringSystem-FaceSpeechRecognition app

This is Face Recogniton connected to a Database which gets the Face Name and Image Name from the Database and compares the Face in the live video with the images stored in the local storage using python.

Make sure imageFolderPath is correctly set to the images folder in the frontend application in both files facerec.py and capture.py.
To run the application, open the project in vscode and run :

- facerec.py script. It will detect targets and send an email to administrators and push an alert to the system.
- speechrec.py script. Talk out something , if the keyword is detected in the speech it will take a capture of the suspect and send an email to administrators and push an alert to the system.
  <img src="Database Driven Face Recognition using Python.jpg" class="img-responsive" alt=""> </div>
