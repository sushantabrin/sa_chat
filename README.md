# sa_chat

## Description
A group video calling application using the Agora Web SDK with Django backend

![Screenshot 2022-01-16 185152](https://user-images.githubusercontent.com/97043022/149661821-becf13a4-d03c-4a5b-81fa-58194c6000da.jpg)

# UPTO 10 MEMBERS IN SAME ROOM!


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

![Screenshot 2022-01-16 184416](https://user-images.githubusercontent.com/97043022/149661549-8c34b7ed-a993-4043-b723-2d8c720bbfbe.jpg)
![Screenshot 2022-01-16 184321](https://user-images.githubusercontent.com/97043022/149661557-e61e06f7-d0b4-4fb5-8eb4-4837f4214b31.jpg)

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

## Or you can just fork it.

![Screenshot (111)](https://user-images.githubusercontent.com/97043022/149660090-759537fa-3d92-4196-a24b-964817d96ddb.png)
