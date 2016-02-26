##Android Client for IdentityServer4

###Assumptions
1. You have published AuthorizationServer(IdentityServer4) and working fine (I used IIS)
2. You have published SampeApi(resource API) and working fine (I used IIS)
3. You have Android Studio
4. I have used Android Emulator to test this App

###Features
1. This sample is created using Resource Owner Flow
2. Accessing Token
3. Refreshing Token
4. Calling Service

###How to run?
1. Load project in Android Studio
2. set your deployed IP of AuthorizationServer and SampleApi in "yourpath...\IDSvr4AndroidClient\app\src\main\java\abubakar\IDSvr4ROClientDroid\constants.java"
3. run or debug app in emulator

###Screen Shots


####Startup screen
![Alt text](img1.png?raw=true "Startup screen")


####Access Token
![Alt text](img2.png?raw=true "Access Token")


####Refresh Token
![Alt text](img3.png?raw=true "Refresh Token")


####Calling Service
![Alt text](img4.png?raw=true "Calling Service")
