Tutorials
---
https://golang.org/


Installation
---
https://www.python.org/downloads/

[global name 'execfile' is not defined] (https://code.google.com/p/googleappengine/issues/detail?id=8835)
uninstall python 3.3 and install 2.7  
`C:\Python27\python.exe`  

[‘python’ is not recognized as an internal or external command] (http://pythoncentral.io/add-python-to-path-python-is-not-recognized-as-an-internal-or-external-command/)  

`C:\Users\Jacob\AppData\Local\Programs\Python\Python35-32\python.exe`
[how-do-i-set-system-environment-variables-in-windows-10] (http://superuser.com/questions/949560/how-do-i-set-system-environment-variables-in-windows-10)


https://golang.org/dl/  


Google Gloud Platform
---
https://console.cloud.google.com/  
Creating a Project. 
Project ID: go-jacobhsu  

Google App Engine
---
https://cloud.google.com/appengine/docs/go/    


C:\Users\Jacob\go\go_appengine_sdk_windows_amd64-1.9.31\go_appengine
\demos\helloworld

app.yaml
```
application: go-jacobhsu 
version: 1
runtime: go
api_version: go1
```


# Deploy to App Engine

https://cloud.google.com/appengine/training/go-plus-appengine/deploy  

Deploy your application by running appcfg.py, which is located in the SDK directory, with the update command and your application directory as the last argument.  

`/path/to/google_appengine/appcfg.py update goplus`  

`$cd C:\Users\Jacob\go\go_appengine_sdk_windows_amd64-1.9.31\go_appengine`  
`$appcfg.py update D:\github\go-age`  


http://go-jacobhsu.appspot.com
