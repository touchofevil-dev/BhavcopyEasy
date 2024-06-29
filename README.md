# BhavcopyEasy
This tool allows users to combine multiple files into a commonly importable format for technical analysis softwares.
This tool does not download data.
 
## FAQ  

### Usage
![App Screenshot](https://github.com/touchofevil-dev/BhavcopyEasy/blob/master/Images/BhavcopyEasy-Image.jpg)

1. If this is your first time using the app, click on settings button, else move to step 5.
2. Select folder in which you've both the data files (i.e. cash market and index).
3. Select folder in which you'd like to generate the file.
4. Save the settings.
5. Click on Generate file.
6. If it works, it will open the folder with data.
7. If you get any error, it would show on screen and generate an ErrorLog file. You can use the ErrorLog.txt file to raise an issue on this repo.


### How to Install?

#### Prerequisites
This application requires Dotnet 8 or above. Please download the dotnet framework runtime from [Microsoft Website](https://dotnet.microsoft.com/en-us/download/dotnet/8.0) if you don't have it.
You only need .Net runtime (win x64 or win x86 according to your machine).

### Installation
Download the .msix file from Releases and install. Fairly straight forward.

#### If Installation button is disabled
If the Install button is disabled, check the steps below to resolve the error.
1. Right click on the .msix file.
2. Select digital signatures tab.
3. Select signer with name touchofevil and click on Details
4. Click on View Certificate.
5. Click on Install Certificate.
6. Select Local Machine and click next. Provide admin permission, if needed.
7. Select Place certificate in following store and click on browse.
8. Scroll down and select 'Trusted People' and click Ok.
9. Click next and click on Finish.
10. You should get successful import dialog. Click on ok and close open windows if any.
11. Rerun the installer.

### Notes
1. Only download from official releases from the repo.
2. Do not redistribute. Download only from the releases on repo.
3. No liability with the author. Run at your own risk. Author shall bear no responsibility for any damages or losses.
4. No warranty.
5. No modifications permitted.   
