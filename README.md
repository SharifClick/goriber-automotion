# Windows projects shortcut

So you're a fullstack developer. You are working on a project has 4 different repoes. api, admin, customer app and sales.
api written in any language and frontends written in JS, so you have to run npm commands after project has open.
* Guess your project name is `awesome`
* Write a file name `awesome.bat` and save it on your desktop, copy below code to that file (modify as your need).

```
  @echo off
  start /b code "C:\your-project-lists\awesome-api"
  start /b code "C:\your-project-lists\awesome-admin" 
  start /b code "C:\your-project-lists\awesome-customer-app" 
  start /b code "C:\your-project-lists\awesome-sales-app" 
  start powershell -noexit -Command "cd 'C:\your-project-lists\awesome-admin'"; powershell -noexit -Command "npm start"
  start powershell -noexit -Command "cd 'C:\your-project-lists\awesome-customer-app'"; powershell -noexit -Command "npm start"
  start powershell -noexit -Command "cd 'C:\your-project-lists\awesome-sales-app'"; powershell -noexit -Command "npm start"
```


## Disclaimer: don’t say python can do that. The scripts are only for goribs
