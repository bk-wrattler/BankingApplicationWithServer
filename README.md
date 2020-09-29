# BankingApplicationWithServer
The ServerProgram can be imported into java using Intelij or Eclipse

Banking_app can be imported into android studio and run on an android device or emulator using android 8 + (api 26)

Make sure that all devices are on the same wifi network.

You will need to change one line in each program:

1. Go to the windows command prompt and type ipconfig (you can't use whatismyip.com that won't get the right ip) find the right network adapter and copy
the ip v4 address.

2. In ServerProgram go to src/ServerFiles/ServerThread.java and change the String variable on line 18 to be the ip address you copied

3. In banking_app go to app/java/com.example.banking_app/StartUpScreen go to line 35 and change the ip address in the setIpAddr method

Run the server program first, then the app (Don't worry if you do it the other way around, the app will correct itself)
