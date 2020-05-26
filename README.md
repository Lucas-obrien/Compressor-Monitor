# Compressor-Monitor
This repository is dedicated to the development of an application that analyses screenshots for number data and triggers an alert if the compressor is below a limit (to be decided by Jim later on).

The objectives are:

1. Acquire the selenium and ocr packages
2. proof of messaging concept by having a message sent to a whatsapp account
3. proof of ocr package by having a test image processed and the temp pressure and maybe the indicators extracted
4. Create a function that automatically extracts the ocr data and exports it to a master excel file (creates a new row and adds date, time, pressure, temp, whether its tripped an alert, and whether an alert message has been sent)
5. create a function that looks at the last row of the excel file and if it has an alert flag but hasnt sent a message yet it will automatically send a message to the set up whatsapp account and raise a message sent flag
6. create a function that will clear the alert message flags when the pressure returns to a good level
7. create a function that checks the days date and the most recent files date and if they are different it creates a new excel file and sets that as the main excel file to ad data too and check.
4. create a script that automatically checks for new files in the compressor folder every 10 seconds and processes them if it detects them.
