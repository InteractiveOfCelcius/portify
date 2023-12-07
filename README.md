# portify
Portify is a utility to execute python code into our API.  
Our API has a lot of functions such as `API.moveFile` or `API.IsAdmin()` etc...
## Its features:
This are not all the functions, there is more, but I am lazy to add them.
```md
# API Functions:
  - API.apiDisplay()
  - API.IsAdmin()
  - API.executePowershell()
  - API.moveFile()
  - API.getSystemPath()
  - API.getFolderEnv()
# API Net:
  - APINet.downloadFile()
  - APINet.request()
# API Settings
  - Settings.loadSettings()
  - Settings.createSettings() : Not used for scripts, only used exclusive for portify
  - Settings.setSettings() : Very dangerous, it can modify the settings for portify
```
## Why should I use it?
You can use it for making daily tasks, or making other things that you would like to do.
## Its commands:
```md
# Commands:
  - portify -p 'ScriptNameHere' : You can execute a script by using this command, its required to have a BaseURL.
  - portify -b : You can modify the BaseURL, a base URL is a server that hosts the scripts, its very simple you can host it its very easy to do.
  - portify -d : You can enable debug mode
  - portify -v : Get the version of portify
  - portify -s : Get the portify settings
```
