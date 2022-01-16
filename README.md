# sa_chat

## Description
A group video calling application using the Agora Web SDK with Django backend

![Screenshot (111)](https://user-images.githubusercontent.com/97043022/149660090-759537fa-3d92-4196-a24b-964817d96ddb.png)

## Want to try the source code? Follow these steps:

#### 1 - Clone Repo
```
git clone https://github.com/sushantabrin/sa_chat
```
#### 2 - Install Requirements
```
cd sa_chat
pip install - requirements.txt
```
#### 3 - Update Agora credentials
In order to use this project you will need to replace the gagora credentials in `views.py` and `streams.js`

##### views.py
```
def getToken(request):
    appId = "YOUR APP ID"
    appCertificate = "YOUR APPS CERTIFICATE"
    ......
```
##### streams.js
```
....
const APP_ID = 'YOUR APP ID'
....
```
#### 4 - Start server
```
python manage.py runserver
```
