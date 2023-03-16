# AutomationXSS


Automation Spray Blind XSS on Header



![image](https://user-images.githubusercontent.com/29269177/225630783-ad5795a0-c293-4c39-b626-e4a4d07a1ea3.png)



Usage :
ffuf -w url_target.txt:FUZZ1 -w headers.txt:FUZZ2 -u FUZZ1 -H "FUZZ2: <BlindXSS_Payload>"



Credit :
 - Emad Shanab
 - Kitsune
