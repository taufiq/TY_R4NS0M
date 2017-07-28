# TY_R4NS0M
Simulates a ransomware at a very basic level. Encrypts your file and the symmetric key is sent to a server, retrieves it after you run.
## READ this
Do not be afraid, this just encrypts all text files in the same directory as the python file. So all your data is safe, (or is it?).
Just clone this file, don't move anything that's in the git folder once its on your computer and follow the instructions. Watch as all the text files that contain "secrets" get instantaneously encrypted!

# How to run
## Important NOTE: Works on MAC OS and (POSSIBLY) Linux, use terminal to run all these commands
### Setup
If you would like to use the python3 version:
```
git clone https://github.com/taufiqmmhd/TY_R4NS0M.git
pip3 install pycrypto
pip3 install seccure
pip3 install requests
```

If you would like to use the python2 version:
```
git clone https://github.com/taufiqmmhd/TY_R4NS0M.git
pip install pycrypto
pip install seccure
pip install requests
```

If you face modulerrors even after installing the above mentioned modules, pip install those missing modules mentioned.

### Running
Go to the respective directory which you want to run the code in.
If you are using a python3 version please go to Python3_TY_R4nS0M,
if you are using a python2 version please go to Python2_TY_R4nS0M

Once you are in the directory of the folder you chose.
Type in:
```
//If folder is for python3version
python3 encrypt.py
```
else
```
python encrypt.py
```

## What now?
That's pretty much it, there's be a console input window running while it encrypt all  your files. Three options are given. Pay first before you decrypt! Server checks if you have paid before you can get the symmetric key to decrypt all your secrets! (Payments fake btw)
