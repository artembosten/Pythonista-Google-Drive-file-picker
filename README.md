# Pythonista-Google-Drive-file-picker
File picker dialog for Pythonista.  List/choose files and directories from your Drive

HOW TO USE:

You need StaSh in Pythonista  
In StaSh run:  
pip install PyDrive  

Code:  

from pydrive.auth import GoogleAuth  
from pydrive.drive import GoogleDrive  
import driveFilePicker as dFP #this file  

gauth = GoogleAuth()  
gauth.LocalWebserverAuth() # Creates local webserver and auto handles authentication  

drive = GoogleDrive(gauth)  

Pass this drive instance to the PICK method in driveFilePicker.py  

Example implementation: https://github.com/artembosten/iOS-Youtube-DL-to-Google-Drive  
