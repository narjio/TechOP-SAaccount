#  How to create service account with mobile phone using termux
- YouTube Link: [Service Accounts Tutorial](https://youtu.be/HzpOwbMHoAY)
- [x] First install termux on your phone and You can download Termux here by click below link
- [![](https://telegra.ph/file/f43e8994a05e1031513c6.png)version 0.117](https://drive.google.com/uc?id=1vi4EoX7m_6rS1WNW17Lur1J0f1Zt1j8o&export=download)

After complete installation process, run below cmd on termux.
```
termux-setup-storage
```
```
pkg install python3
```
```
pkg update python3
```
```
pkg install git
```
```
git clone https://github.com/narjio/TechOP-SAaccount && cd TechOP-SAaccount
```
```
pip3 install -r requirements.txt
```
optional 👇 if not working leave as it is use next commnads
```
pip install --upgrade pip
```
use below commands 👇
```
pwd
```
```
cd
```
```
cd storage
```
```
cd downloads
```
REMOVE THIS -> "PASTE YOUR COPIED PWD PATH" AND PASTE YOUR PATH DONT USE "" OPERATOR 
```
cp -r credentials.json "PASTE YOUR COPIED PWD PATH"
```
```
cd
```
```
cd TechOP-SAaccount
```
```
ls
```
```
python3 gen_sa_accounts.py
```
go to url and login with same account which you created console.cloud.google.com , drive api credentials 
NOTE - USE ONLY YOURS RECIVED URL 

NOTE - below line remove PROJECT ID title and paste your PROJECT ID DONT REMOVE $ symbol
```
python3 gen_sa_accounts.py --enable-services $PROJECT ID
```
NOTE - below line remove PROJECT ID title and paste your PROJECT ID DONT REMOVE $ symbol
```
python3 gen_sa_accounts.py --create-sas PROJECT ID
```

