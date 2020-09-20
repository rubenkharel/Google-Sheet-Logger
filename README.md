# googlesheetlogger README

GoogleSheetLogger was built for one and only and specefic purpose of doing github's README automation. It extracts your workspace information and which is later used by Github to display the data in Github README. You can see the demo below or if you are viewing this readme from vscode. Check https://github.com/rubenkharel/rubenkharel to see how it looks like.

## Features

Reads your vscode workspace informations and push it to google sheet.

For example if you are editing a index.html file in MyProject folder. 
The extension reads the information and sends it to your Google Sheet.


## Requirements
INSTRUCTIONS WILL BE UPDATED WITH GIFs AND VIDEOS TO MAKE IT CLEAR. 

**Steps**:
1. Create Google Service Account
2. Get Google service's email, apiKey, and .p12 file.
3. Create a Google Sheet document
4. Extract the google sheet document's ID

Now You have 4(or 5) things at total.
1. Google Service Email
2. Google Service .p12 file
3. Google Sheet ID and Name.
4. Google Service API Key ( Not for extension but for Github Action )

After gaining all these files and Info, Go to extension settings and fill up the informations.
For the file: First rename it to mykey.p12 You need to find the vscode instillation directory and paste the file inside the extension's folder. 

In **windows** it is located in : `C:/users/yourUserName/.vscode/extensions/rubenkharel.googlesheet.....` <br />
In **WSL** it is in: `/home/yourUserName/.vscode-server/extension/rubenkharel.googlesheet......`

I guess you you are good to go form here... 

Instruction is difficult I guess. So I will be updating the readMe soon.

## Extension Settings

This extension contributes the following settings:

* `email.googleServiceAccountEmail`: The Google service email you are provided while creating Google service account.
* `keyFile.p12`: Specifies the folder path containing the mykey.p12 file you downloaded from google service. Follow the tutorial from the Github repo if you get any issues.
* `sheetID.locatedInGoogleSheetUrl` : Sheet ID of the sheet you are going to be using as a bridge. It is located in the url of the sheet you will be using.
* `sheetName.theNameOfTheSheet` : Found on google sheet document's right-bottom corner. Let it be default I would say.

## Known Issues

Just create an issue if you find any. Or if need help create an issue.

## Release Notes

Initial... 

### 0.0.1

Well, this is all I got right now. Its just a noob version, Might update after few months when I got some real skills...

-----------------------------------------------------------------------------------------------------------

**Enjoy!**
