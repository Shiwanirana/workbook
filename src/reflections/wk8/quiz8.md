# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
Package.json file contains npm packages and various metadata relevant to the project. Basically it gives information to npm which then handles the project and its dependencies. 
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
At top level, as it is the first file to be read.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
vue files are pre-compiled, but 'npm i' can be the one. 
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
AuthConfig.js and .env 
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
1. By command line --> heroku logs    //by default it retrieves 100 logs
2. Directly going to the heroku.com and then log in and then navigate to the app you want to see and then on top right click more and select 'view logs'
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
1. Login to heroku, install heroku-cli (if not installed)
2. initiate git repository('deploy to heroku' is done )
3. commit changes and push to heroku.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branching is mainly useful when a team project is going on. It helps the teams to work in parallel, and maintains stability when the changes are made to the code.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Code review should happen after the testing but before the merging to the repository's main branch. 
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merging
```
