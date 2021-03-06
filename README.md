# Attention: Incorrect virus detection
**Some stupid idiot seems to have abused PS2EXE to compile his computer virus script. As a result, a rapidly growing number of virus scanners recognize programs created with PS2EXE as malicious programs and delete them.**

**There is only one hope to save the PS2EXE project: Please send your (harmless) programs created with PS2EXE via the web forms from the virus scanners' vendors for reporting false positives (I've already done it with some of them, please use only the false positive page)!**

**If this is not successful, then I will have to quit PS2EXE as nobody can use it anymore.**

**Thank you for your support**

# Win-PS2EXE
Graphical front end to PS1-to-EXE-compiler PS2EXE.ps1

Author: Markus Scholtes

Version: 1.0.0.3

Date: 2019-12-16

With [PS2EXE.ps1](https://gallery.technet.microsoft.com/PS2EXE-GUI-Convert-e7cb69d5) originally created by Ingo Karstein you can compile Powershell scripts to real Windows executables. **Win-PS2EXE** is a small graphical front end to the script.

### Features and restrictions:
* **Win-PS2EXE** does not support all parameters of **PS2EXE.ps1**
* WPF application that compiles without Visual Studio or MSBuild on every Windows with .Net 3.5x or .Net 4.x
* only one source file
* drag'n'drop for file names
* separate .Net 4.x and .Net 3.5x versions (since .Net 3.5x do not allow uncompiled event handlers in XAML)

### Screenshot:
![Screenshot](Screenshot.jpg)

### How to compile:
Run **Compile.bat** (in a .Net 3.5x environment use the version in folder *DotNet3.5*).

### How to use:
Ensure **PS2EXE.ps1** is in the same directory as **Win-PS2EXE.exe**.

Start **Win-PS2EXE.exe** and fill in the desired fields (only *Source file* is mandatory).

Click **Compile**, a powershell window opens and your powershell script will be compiled to an executable.

### Changes:
1.0.0.3: file fields no longer run out

1.0.0.2: -noConfigFile is default now
