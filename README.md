#  How to create service account with mobile phone using termux

||Preview|Info|
|--|--|--|
|Part 1|[![](https://telegra.ph/file/d168f00348123336b8870.png)](https://youtu.be/GCIp656t1pw)|<ul><li>Create Project id</li><li>Must subscribe </li><li>Direct download link added</li><li>Watch now</li></ul>|

||Preview|Info|
|--|--|--|
|Part 2|[![](https://telegra.ph/file/932b5ac5fd9df50b4b454.png)](https://youtu.be/_8WuH0h0-88)|<ul><li>Full video with source links</li><li>Must subscribe </li><li>Direct download link added</li><li>Watch now</li></ul>

||Preview|Info|
|--|--|--|
|download apk|[![](https://telegra.ph/file/3845b4cf2a564eed510a7.png)](https://new6.gdtot.cfd/file/101739646)|<ul><li>First install termux on your phone</li><li>and You can download Termux here </li><li>By one click</li><li>Click on image to download</li></ul>

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
cd storage 
```

```
cd shared
```
```
cd Gujjuopgohil-tg
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




