## To create a virtual environment for a Non-IDE python project in windows, for example `C:\pythonProject`
* Open `Windows PowerShell`
* Navigate to the project directory
```bash
cd C:\pythonProject
```
* Create a virtual environment using the global python interpreter, for example `Python 3.11` and `venv` package
```bash
[C:\pythonProject]$ py -3.11 -m venv venv
```
* Now you can run your code, for example `main.py` file, using the local interpreter and install packages local to your project
```bash
[C:\pythonProject]$ venv\Scripts\python main.py
```
