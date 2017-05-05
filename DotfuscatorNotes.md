This document contains notes we took while integrating Dotfuscator into 
the BugSweeper Xamarin app. You can step through this file's history in git
to see where we noted each point.

# Dotfuscator CLI path

We're using Dotfuscator Professional Edition 4.28.2:

`C:\Program Files (x86)\PreEmptive Solutions\Dotfuscator Professional Edition 4.28.2\dotfuscator.exe`

# Projects and configurations to protect

* `BugSweeper.UWP` project
  * *Release* configuration
  
# Protected projects and configurations

* `BugSweeper.Android` project
  * *Release* configuration
* `BugSweeper.iOS` project
  * *Release* configuration
  * *Ad-Hoc* configuration
  * *AppStore* configuration

# Targets file path

`C:\code\BugSweeper\PreEmptive.Dotfuscator.Xamarin.targets`

# Currently protecting

`BugSweeper.UWP` project

* Project directory: `C:\code\BugSweeper\BugSweeper\BugSweeper.UWP`
* Project file: `C:\code\BugSweeper\BugSweeper\BugSweeper.UWP\BugSweeper.UWP.csproj`
* Relative path to targets file: `..\..\PreEmptive.Dotfuscator.Xamarin.targets`