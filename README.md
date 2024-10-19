# 
There are three ways to deal with errors and exceptions in uipath
1) Using Continue on Exception tool in Debug tap.
   
<img src="https://github.com/user-attachments/assets/c0fca533-a80c-46e1-bf29-9e364620f5dc" width="400">


3) Using [Global Exception Handler](https://docs.uipath.com/studio/standalone/2023.4/user-guide/global-exception-handler)

4) Using [Try Catch](https://docs.uipath.com/activities/other/latest/workflow/try-catch)
In its body there are a three activities(Try, Catches, Finally)

![image](https://github.com/user-attachments/assets/c980fc33-d3f0-464d-b442-80c5bf7cbe5b)

It can be used by means of a shortcut on the keyboard (Ctrl+T)

In our project some mistakes will be on purpose made to see how will deal with them and what kind of exception will discover

# TECHNICAL REQUIREMENTS

1) Read Range Work BooK Activity

# PROCEDURES

In the first experiment, The Read range workbook will be entered and an Excel file name will be placed that is not included in the project file.

![image](https://github.com/user-attachments/assets/5e9fe409-e822-4937-8925-e66dd6bad745)

From the properties panel window, the output of the Data table type is stored

![image](https://github.com/user-attachments/assets/7e2734c8-caae-454b-b28f-394cc03ee0d2)

.


![image](https://github.com/user-attachments/assets/40aa9747-cc06-4e71-a3dc-a8ef66cbf441)

#Result

As a result, the message box will print the exception type

![image](https://github.com/user-attachments/assets/b0e18026-c2d1-4032-bea4-904688bc2a7a)

[Click here](https://drive.google.com/file/d/16EM6A0Z0Z60t9fCOAZfiwfkDX41XWFVX/view?usp=drive_link)









