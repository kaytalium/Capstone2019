# Transico - (How to run this project) School Project not for Production
Please note that this is a markdown file as such you would need a markdown reader to have a better experience viewing this file. this file can be viewed in visual studio code and hit the preview, other than that [Click here]()


---
### Group 1: 
- Tajhna McCourtie
- Ovel Heslop
- Ruel Andrews
- Cordel Reid
- Paula Green


## Development Methology

Before we can run the applications we must first understand the methology used to create it. 

The Transico was developed in two parts the android mobile version and the web application version. Below each version list the technology used in its creation. 

---
#### Mobile Version Development Tool
---
- Android studio version 3.3.2 https://developer.android.com/studio

In order to run the code you must have the following installed:

- Android Studio (Watch this video to get started )

[![Android Studio Setup](android-studio-video1-cover.jpg)](https://www.youtube.com/watch?v=1-k5KMj8IJQ)

Once the program is installed and configured successfully you may open the `transico_mobile project` with android studio. in order to view the code you must create a virtual phone or as google calls it a emulator. 

The video below will show how to perform the setup. 

[![Emulator Setup](android-studio-video2-cover.jpg)](https://www.youtube.com/watch?v=5BdqfvRS_TY)

Once the emulator is up the application will launch. 

`**Please Note` 

The application database sets on the google cloud platform call firebase. as such to see live data you must be connected to the internet. 

--- 
 #### Web Version Developoment Tool
---
- Nodejs version 8.12.0 or higher https://nodejs.org/en/download/
- Visual Studio Code version 1.33.1 or higher https://code.visualstudio.com/download
- Git version 2.21.0 or later https://git-scm.com/downloads
- angularjs cli https://cli.angular.io/

Now that we have our tools install and configured 
you can open bash by right-click on the project folder and click from the popup `Git Bash Here` this will open what look like a command prompt window. 

```console
    heslop-capstone MINGW64 ~/Documents/group1-project/transico_web
    $ 
```

from here you will type code . and this will open visual studio code application and load up the project. 

```console
    heslop-capstone MINGW64 ~/Documents/group1-project/transico_web
    $ code .
```

Once vsCode is up and ready you can come back to the terminal to launch the application. 

```console
    heslop-capstone MINGW64 ~/Documents/group1-project/transico_web
    $ ng serve --open
```

the command above will create a webserver locally and then build the web application deployment code, move said code to the newly created server and then open a webpage to the application from your default browser. 

```**Please note```

For best performance please to view using a chrome browser if this is not your default browser by copy and pasting the url you got when the browser was launch. 

Thank you for your time 
Codezero Team

@ codezero.com all rights reversed.




