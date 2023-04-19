# BhavcopyEasy
This tool allows users to combine multiple files into a commonly importable format for technical analysis softwares.
This tool does not download data.
 
## FAQ  

### How to use this?

#### Prerequisites
This application requires Dotnet 6 or above. Please download the dotnet framework runtime from [Microsoft Website](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) if you don't have it.
You only need .Net runtime (win x64 or win x86 according to your machine).

#### Steps (v0.1.1-alpha) -
1. Download data files to a folder. No need to extract the zip any longer. Preferably do not download in C:\\. If you only have C:, then create a folder on Desktop and put everything there.
2. Download released zip file and extract the contents to same folder as above.
3. Edit batch file using notepad, and update below fields carefully.

    Date - Date of the data files - YYYY/MM/DD

    CMFile - name of the bhavcopy zip file

    IndexFile - name of the index data file including extension

    Your final file content should look something like this,

        BhavcopyEasy.exe --Date "2023/04/19" --CMFile "cm19APR2023bhav.csv.zip" --IndexFile "ind_close_all_19042023.csv"

4. Save the file and run the batch file.

If everything is successful, it should create a .txt file in same folder.
If you see ErrorLog.txt file generated instead, please raise a bug and attach that file to bug.

### Notes
1. Only download from official releases from the repo -

    Being very honest about it, in its current state its extremely easy to wrap malware around it. Don't risk by downloading from unknown sources. Also always scan with antivirus before running to be safe.
2. Do not redistribute. Download only from the releases on repo.
3. No liability with the author. Run at your own risk. Author shall bear no responsibility for any damages or losses.
4. No warranty.
5. No modifications permitted.