Release Notes

Brainy Words 2000 Web Application

Version 1.0

**New Features**

- Added a welcome screen
- Added a street screen
  - Added ability to click and drag with mouse to scroll along street
  - Added 100s of clickable audio elements to the street
  - Added 33 storefront categories to enter from the street
- Added a category screen to view the subcategories or words contained within each category
- Added quizzes for the words in the categories and subcategories
- Added coins that are accumulated for correctly answering quiz questions
- Added a progress screen
  - Added statistics from the results of quizzes for the current browser session
  - Added the ability to send an email containing the user&#39;s progress statistics

**Bug Fixes (major issues encountered during development that were fixed)**

- Users would be taken back to the start of the street when exiting a storefront instead of being return to outside of that storefront
- Multiple audio files could be played at the same time if multiple words were clicked in quick succession
- Street screen was scaled too large to be properly viewed on mobile devices
- Street image file was too large to be downloaded over a network within a reasonable amount of time
- The number of coins earned during quizzes disappeared after exiting each quiz and did not persist throughout the whole game session
- The game was unable to load a subcategory that was contained within another subcategory

**Known Bugs**

- The Android version of Firefox is unable to properly load the entire street image. The portion of the street after storefront category 28 does not display properly.



Install Guide

Install Guide for Brainy Words 2000 Web Application

**Prerequisites**

- You must have Node.js and NPM installed. When you install Node.js, NPM will automatically be installed as well.
- To download the latest version of Node.js see [https://nodejs.org/](https://nodejs.org/)
  - Both the LTS (Long Term Support) and Current versions of Node.js should be compatible with the application. However, it is generally recommended that you use the LTS version.

**Dependencies**

- From your command line run the command &quot;npm install&quot; from within the root directory of the application (the folder containing _package.json_).
  - This command will install all packages that are needed to run the Node.js application.
  - The packages that will be installed are:
    - body-parser (v1.17.1)

-
  -
    -
      - [https://www.npmjs.com/package/body-parser/v/1.17.1](https://www.npmjs.com/package/body-parser/v/1.17.1)
    - express (4.15.2)
      - [https://www.npmjs.com/package/express/v/4.15.2](https://www.npmjs.com/package/express/v/4.15.2)
    - express-handlebars (v3.0.0)
      - [https://www.npmjs.com/package/express-handlebars/v/3.0.0](https://www.npmjs.com/package/express-handlebars/v/3.0.0)

**Download**

- You can download version 1.0 of the Brainy Words 2000 Web Application from [https://github.com/NoahBlume/brainyWords2000](https://github.com/NoahBlume/brainyWords2000)

**Build**

- No build is necessary for this app. Once you&#39;ve installed the necessary packages, you will be able to run the Node.js application.

**Installation**

- Simply copy the application files from the GitHub link to wherever you wish to store them on your computer.

**Running Application**

- Launch the command line, navigate the root application directory containing _app.js_, and type this command: node app.js
- The application should now be accessible from you browser at this address: _localhost:3000_
- While the above command will allow you to start the application on your computer, the links provided in the web server setup tutorials below will give more detailed instructions on how to set up a server that will automatically start the application whenever the server boots up.

**Troubleshooting**

- If you installed Node.js and the application is not able to run, in your command line enter the command: node -v
  - This will tell you what version of Node.js you have installed.
  - If Node.js is not installed or the version number is different from the version you downloaded from the link above, try installing Node.js again.
- If you are having trouble installing the packages with the command &quot;npm install&quot;, in your command line enter the command: npm -v
  - This will tell you what version of NPM you have installed.
  - If NPM was not installed, or if it was installed but its version number is lower than v6.4.1, you should try reinstalling Node.js or try installing NPM using the commands listed on this page: [https://www.npmjs.com/get-npm](https://www.npmjs.com/get-npm)
- If you are having trouble using the command line, this guide should be a good introduction: [https://tutorial.djangogirls.org/en/intro\_to\_command\_line/](https://tutorial.djangogirls.org/en/intro_to_command_line/)
  - The most relevant sections are:
    - Open the command-line interface [https://tutorial.djangogirls.org/en/intro\_to\_command\_line/#open-the-command-line-interface](https://tutorial.djangogirls.org/en/intro_to_command_line/#open-the-command-line-interface)
    - Change current directory [https://tutorial.djangogirls.org/en/intro\_to\_command\_line/#change-current-directory](https://tutorial.djangogirls.org/en/intro_to_command_line/#change-current-directory)

