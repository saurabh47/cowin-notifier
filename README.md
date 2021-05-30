# cowin-notifier
## What this repository does
![image](https://github.com/saurabh47/cowin-notifier/blob/main/cowin-notifier-working.png)
## Installation
```
pip3 install requests pygame gspread
```

## Inital Setup
1. Update your pincode on line number 16 of script.py
2. Create Google sheet & add your API credentials in `cowin-sheet-cred.json` <br /> To genrate Sheet API credentails refer this video https://www.youtube.com/watch?v=ct0xvw_Z0tU&t=617s
3. Install IFTTT App on your android or ios device <br /> https://ifttt.com/
4. Create IFTTT Applet to get notification on your device. <br /> Follow below steps 
  <img src="./screenshots/step1.jpeg" alt="step1" width="200"/>
  <img src="./screenshots/step2.jpeg" alt="step2" width="200"/>
  <img src="./screenshots/step3.jpeg" alt="step3" width="200"/>
  <img src="./screenshots/step4.jpeg" alt="step4" width="200"/>
  <img src="./screenshots/step5.jpeg" alt="step5" width="200"/>
  <img src="./screenshots/step6.jpeg" alt="step6" width="200"/>
  <img src="./screenshots/step7.jpeg" alt="step7" width="200"/>
  
## Run the script in Background
```
nohup python3 -u script.py &
```
