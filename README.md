# activatevenv
it represents how to activate venv using batch file (commandprompt)
<br></br>
<br></br>
<br>@echo off</br>
<br>CD /D "D:\menv\Scripts"</br>
 <br>start activate.bat</br>
 <br>start jupyter notebook </br>
 
 # activatevenv change to rootdirectory
 @echo off
<br>CD /D "D:\menv\Scripts"</br>
<br>call activate.bat</br>
<br>CD /D "D:\"</br>
<br>jupyter notebook</br>

