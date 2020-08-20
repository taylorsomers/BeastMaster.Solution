





<h1 align="center">
  <img width="900" height="450" src="https://coding-assets.s3-us-west-2.amazonaws.com/hero_images/beast_master_header.jpg">

  
**<h1 align = "center">Beast Master**


</h1>
     
<br>

<h4 align = "center">
  <a href="#requirements">Requirements</a> •
  <a href="#setup">Setup</a> •
  <a href="#protecting-your-data">Protecting Data</a> 
  <a href="#questions-and-concerns">Q's & C's</a> •
  <a href="#technologies-used">Technologies</a> •
  <a href="#known-bugs">Known Bugs</a> •  
  <a href="#contributors">Contributors</a> •
  <a href="#license">License</a></h4>

<br>

## **ABOUT**

* 
* 
* 
* 
* 
* 
* 
* 



## **REQUIREMENTS** 

* Install [Git v2.62.2+](https://git-scm.com/downloads/)
* Install [.NET version 3.1 SDK v2.2+](https://dotnet.microsoft.com/download/dotnet-core/2.2)
* Install [Visual Studio Code](https://code.visualstudio.com/)
* Install [MySql Workbench](https://www.mysql.com/products/workbench/)

<br>

## **PROTECTING YOUR DATA** 
(when modifying for personal use)

#### **Step 1: From within VSCode in the root project directory, we will create a .gitignore file**

# For ![l-top](https://github.com/ryanoasis/nerd-fonts/wiki/screenshots/v1.0.x/mac-pass-sm.png)
```js 
touch .gitignore 
```

# For ![l-top](https://github.com/ryanoasis/nerd-fonts/wiki/screenshots/v1.0.x/windows-pass-sm.png)

```js 
ni .gitignore 
```

#### Step 2: commit that .gitignore file (this prevents your sensitive information from being shown to others). **⚠️DO NOT PROCEED UNTIL YOU DO!⚠️**

![setup](https://coding-assets.s3-us-west-2.amazonaws.com/img/entity-readme-image.png "Set up instructions")

#### Step 3: **To commit your .gitignore file enter the following commands**

```js
git add .gitignore
```
```js
git commit -m "protect data"
```

#### Step 4: **Then, you need to update your username and password in the appsettings.json file.**

_by default these are set to user:root and an empty password. if you are unsure, refer to the settings for your MySqlWorkbench._

![appsettings](https://coding-assets.s3-us-west-2.amazonaws.com/img/app-settings.png)

## **SETUP**

copy this url to clone this project to your local system:
```html
https://github.com/tmemmerson/BeastMaster.Solution.git
```

<br>

Once copied, select "Clone Repository" from within VSCode & paste the copied link as shown in the image below.

![cloning](https://coding-assets.s3-us-west-2.amazonaws.com/img/clone-github2.gif "Cloning from Github within VSCode")

<br>

With the project open to the root directory, navigate to the production directory with the following commands in your terminal.
```js 
cd BeastMaster
```

```js 
dotnet restore 
```

```js 
dotnet build 
``` 

```js 
dotnet ef database update 
``` 

Your application is now built, as well as the requisite database for this application. Now we run the program with...
```js 
dotnet watch run 
``` 


<br>

## **TECHNOLOGIES USED**

_**Written in:** [Visual Studio Code](https://code.visualstudio.com/)_

_**Image work:** [Adobe Photoshop](https://www.adobe.com/products/photoshop.html/)_

_**Database Mgmt:** [MySql Workbench](https://www.mysql.com/products/workbench/)_


<br>

## **KNOWN BUGS**

_**None as of:** 8/20/2020_

<br>

## **CONTRIBUTORS**

| [<img src='https://coding-assets.s3-us-west-2.amazonaws.com/linked-in-images/sean-downs.jpeg' width='160px;'/><br /><sub><b>Sean Downs</b></sub>](https://www.linkedin.com/in/sean-downs/)<br />


| [<img src='https://coding-assets.s3-us-west-2.amazonaws.com/linked-in-images/taylor-somers.jpeg' width='160px;'/><br /><sub><b>Taylor Somers</b></sub>](https://www.linkedin.com/in/taylorsomers/)<br />


| [<img src='https://coding-assets.s3-us-west-2.amazonaws.com/linked-in-images/erich-richter.jpeg' width='160px;'/><br /><sub><b>Erich Richter</b></sub>](https://www.linkedin.com/in/erichjrichter/)<br />

| [<img src='https://coding-assets.s3-us-west-2.amazonaws.com/img/tristan_emmerson.jpg' width='160px;'/><br /><sub><b>Tristan Emmerson</b></sub>](https://www.linkedin.com/in/tristan-emmerson/)<br />


## **LICENSE**
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Copyright (c) 2020 **_Tristan Emmerson, Stickerslug Inc._**