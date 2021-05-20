# Auto Slot book for COVISHIELD/ COVAXIN vaccine

## Screenshots
- **Entering mobil number initially**
![Enter your details](Screenshots/vaccine1.PNG)

- **Searching the location of yours**
![Searching your location](Screenshots/vaccine2.PNG)

- **Confirmation of your details**
![Confirm details](Screenshots/vaccine3.PNG)

- **Scanning for the available slots in given centers**
![Scan availble slots](Screenshots/vaccine4.PNG)

- **Re-scanning as timeout for account's session**
![Re-scanning for timeout](Screenshots/vaccine5.PNG)

- **If details saved, it'll take data from there**
![Data usage](Screenshots/vaccine6.PNG)

- **Booking successful message**
![Booking successful message](Screenshots/vaccine7.PNG)

## What's the use | What's this

- Are you not getting slot for your vaccination?  
- Are your logging every day to book slot for vaccine?  
- Are you 18+ but not getting single open slot?  
- Are you a programmer or have some knowledge of python?  
- Are you a registered 'cowin.gov.in' user?

> Then you're in correct place.  
> This project will automatically book a slot for vaccine available in your area.  
> This script will ask whether you need to auto book your slot or not  
> You can even save the input you've given
> Completely dependent upon the registration part you've done already
> Will ask for OTP needed for logging you in
> Your data is saved in your system only

## Library Requirements

- requests
- tabulate
- inputimeout
- svglib
- reportlab
- pyinstaller
- pysimplegui  
<br>
 - [x] Install [python 3.9](https://www.python.org/ftp/python/3.9.5/python-3.9.5-amd64.exe) and [PyCharm](https://www.jetbrains.com/pycharm/download/download-thanks.html?platform=windows&code=PCC) first

## How to install libraries

> Easy steps to install above required libraries in PyCharm

- Step 1: Click CTRL+ALT+S
- Step 2: Click on Project >> Python Interpreter
- Step 3: Click on + button
- Step 4: Search each one of them and Click Install
- Step 5: After all are installed, Click on 'X' and then 'OK' button
- Step 6: Click on :arrow_forward: button

## What inputs will it ask

- ```Your phone number``` (eg. 9346892074)
- ```OTP you got in that number``` (eg. 539035)
- ```For whom to book slot``` (eg. 1)
- ```Preference for the vaccine type``` (eg. 1)
- ```How do you want to search for center``` (eg. 2)
- ```Your Pincode, if selected 2 above``` (eg. 831001)
- ```Your State``` (eg. 4) - Index number mentioned there
- ```Your District``` (eg. 12) - Index number mentioned there
- ```Filtering centers with availability``` (eg. 1)
- ```How often to refresh the calendar``` (eg. 10)
- ```Search for next seven day starting from``` (eg. 1)
- ```Vaccine fee type preference``` (eg. 1)
- ```Do you want to auto-book``` (eg. yes-please)
- ```Do you like to save in json file``` (eg. y)
- ```Proceed with above details``` (eg. y)

## Cons

- **Only valid for almost 15-16 minutes only**. The code will give a beep sound and stop. You need to re-run the code and give OTP.
- Any wrong input will be declared as **wrong input** and **program will terminate**. So, read the steps carefully.

## How to run it
> - Just extract it in a folder  
> - Open in PyCharm  
> - Install libraries  
> - Hit :arrow_forward:  
> - Give necessary inputs


