# HugoSites
Hugo sites For Employees

*Prerequisites:*
- Hugo
- Git
- Access to Github
- Access to Azure Portal

## Install Hugo on Microsoft:
*Prequisites:*
- Powershell
- scoop

## Steps
- Run Powershell
- install scoop 
`Invoke-Expression (New-Object System.Net.WebClient).DownloadString('https://get.scoop.sh')`
- install hugo 
`scoop install hugo-extended`

## How to Create your own Hugo template
Now we installed Hugo we can start building our own version of the Devon templated Hugo site. We start with creating a directory and change to the directory where we can hold our version. when that is done let us initiate it as a git repository.

`git init`

Now we have to pull the latest version from GitHub.

`git pull https://github.com/DevOnGlobal/HugoSites.git`

Create in the root folder a new directory with your name and copy the content ofone of the existing folder or from the template folder to start fresh. Now we can run the test enviroment and change the yaml files to create our personal Hugo site. Whe we copied the files move to your directory and start hugo server.

`hugo server --theme toha --watch` 

This will run a test version of your site on localhost:1313!

