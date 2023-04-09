#  How to create service account with mobile phone using termux
- YouTube Link: [Service Accounts Tutorial](https://youtu.be/HzpOwbMHoAY)
- [x] First install termux on your phone and You can download Termux here by click below link
- [![](https://telegra.ph/file/86bdd0fcc9094cc5a84b3.png)version .118](https://new6.gdtot.cfd/file/101739646)

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
mkdir /sdcard/Gujjuopgohil-tg/ -p
```
```
cd /sdcard/Gujjuopgohil-tg
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
NOTE - below line remove PROJECT ID title and paste your PROJECT ID remove $ symbol as well
```
python3 gen_sa_accounts.py --enable-services $PROJECT ID
```
NOTE - below line remove PROJECT ID title and paste your PROJECT ID 
```
python3 gen_sa_accounts.py --create-sas PROJECT ID
```
NOTE - below line remove PROJECT ID title and paste your PROJECT ID remove $ symbol as well
```
python3 gen_sa_accounts.py --download-keys $PROJECT ID
```
```
ls
```
```
cd accounts
```
```
grep -oPh '"client_email": "\K[^"]+' *.json > emails.txt
```
```
ls
```
```
cd ..
```
```
python3 generate_drive_token.py
```
```
exit
```




