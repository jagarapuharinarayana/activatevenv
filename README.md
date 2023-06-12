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
CD /D "D:\menv\Scripts"
call activate.bat
CD /D "D:\"
jupyter notebook

