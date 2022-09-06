# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
All npm packages contain a file, usually in the project root, called package. json - this file holds various metadata relevant to the project. This file is used to give information to npm that allows it to identify the project as well as handle the project's dependencies.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
First, you will create a package.json file to store useful metadata about the project and help you manage the project's dependent Node.js .
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run build command in command line, and it will create dist folder in your project. Just upload content of this folder to your ftp and done.
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
The connection string is a list of key/value pairs that the Connection object will parse; it will use the information to find the Data Source, authenticate, and ..
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
You can view logs with the Heroku CLI, the dashboard, your logging add-on, or in your log drain. You can't view logs for apps in Shield spaces with Private Space Logging enabled
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Clone the repository from GitHub to your local device: git clone <YOUR HTTPS URL FROM GITHUB>
Make your changes, and commit them to GitHub: ...
Login to your Heroku account: ...
Set remote for your project: ...
Push to Heroku master to deploy updates:
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Version control branching allows teams to develop and deploy software. But to effectively manage projects with multiple developers and releases, you need a branching strategy. This organizes your branches and development resources, allowing you to release on time.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Code reviews should happen after automated checks (tests, style, other CI) have completed successfully, but before the code merges to the repository's mainline branch.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```

```
