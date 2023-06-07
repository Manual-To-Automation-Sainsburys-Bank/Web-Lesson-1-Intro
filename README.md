<p float="left">
  <img src="https://d98b8t1nnulk5.cloudfront.net/production/images/layout/logo-header.png?1469004780" width="400" height="100" title="BS_Logo">
  <img src="https://cdn.cookielaw.org/logos/af33d682-b608-4a02-a87c-726c5880e254/44ba34d9-63c1-451e-a22d-ba28af064ea1/19ef061a-823e-4179-ae5c-43b2c60fe360/New_SB_Logo_r240g108b0.png" width="400" height="100" title="Percy.IO2">
</p>

# Sainsburys Bank - Web - Lesson 1 - Writing Your First Test

This repository contains a simple Selenium based test that performs a search on Duck Duck Go and outputs the title of the Web page after the search has been completed. There is only one test file and 2 dependecies.

It is designed as a very entry level idea of how to interact with a website using Automation.

## Necessary Tools

There are a few things that you will need before you can get started.

* NodeJS - use [this](https://nodejs.org/en/download) guide for both Windows and Mac. 
* Git for pulling down the code - follow [this](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) guide for installing Git on all platforms. There are other useful guides on the website mentioned previously. Start [here](https://github.com/git-guides) anad follow through to the various links to learn more about Git. It will be very useful on your automation journey. If you have any issues with tokens or user credentials, let me know as this can trip a lot of people up.
* Visual Studio Code - You can download it [here](https://code.visualstudio.com/download). This is the best free tool for writing JS code at the moment and the one that will be used for demos during the lessons.
* ChromeDriver - this is the web driver that will be used to open Chrome and do the test locally. You can download it from [here](https://chromedriver.chromium.org/downloads). Remember to grab the version that matches your installed browser. Other webdrivers are available also. You can get Firefox [here](https://github.com/mozilla/geckodriver/releases), Edge driver [here](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/), and Safari driver [here](https://developer.apple.com/documentation/webkit/testing_with_webdriver_in_safari).

## How To Run

Follow the below steps to run the script on your machine:

Clone this repository:

```sh
git clone https://github.com/Manual-To-Automation-Sainsburys-Bank/Web-Lesson-1-Intro.git
```

Move into the directory:

```sh
cd Web-Lesson-1-Intro
```

Type the following command:

```sh
npm run test
```

There are obviously many ways to grab this repository and this is just one way. Some of the others are:

 - GitHub Desktop application
 - Download the Zip file of the repository
 - Clone it through Visual Studio Code
