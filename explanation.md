## Project Description
Creating automated workflow(Customer care auto-ticketing) by use of attended automation once triggered.

## Creation of folders
Requests Folder & Processed Folder for the spreadsheets.

## There are 3 xaml files used to create automation, as below
### Main.xaml
The main workflow which will invoke other workflows and orchestrate the automation.

### ReadRequest.xaml
Picks read the ticket data from the excel createdfor the next workflow to process.

### SaaSAutomation.xaml
Zoho application is used  to read data from Request file and creat ticket.

## Process:
Utilize UiPath to execute the Main, ReadRequest, and SaaSAutomation XAML files. Initiate the process by clicking the run button. Upon prompting, select "OK" and initiate the automation by pressing ALT+S. The automation will conclude automatically upon activation of the designated hotkey.ie. Ctl + c