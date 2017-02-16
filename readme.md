## LiveU Portal written in AngularJS

### Steps for Configuring LiveU Application

Step 1:
Install Github [If not installed in System]. Connect to “solo_app” repository using valid Github credentials.

Step 2:
Install IIS [If not installed in System]

Step 3:
Host LiveU Application in IIS locally

Step 4:
After hosting the application, If screen shows the complete blank page and browser’s developer tool gives JavaScript loading error under “Console” tab, then it is confirmed that, required components are not installed in your system.

We have to install following components using Command Prompt or Git Bash:

1. Install Node.js in your system:  
 1. Download Node.js installation package from following URL: https://nodejs.org/. We need to install Node.js as supportive package to install Bower library and components. 
 1. Double click on installation package & complete all the step-by-step instruction to install the Node.js package successfully.

1. Install Bower Library:   
 1. After successfully installing Node.js package, go to command prompt or git bash to install Bower library.
 1. Navigate to your project’s root folder where all the project files are placed. 
	`For ex.:	d:\liveu\solo_app\liveuweb\`
 1. Run following command to start the Bower library installation:
	`npm install –g bower`
 1. On successful installation, no error message will be displayed. In case of any error, specific error message will be displayed on the screen.

1. Install Bower Packages:  
 1. Run following command to start the Bower packages installation:
	`bower install`
 1. On successful installation, a new folder - bower_components will be added into project source.

1. Your web application is ready to test and you can start reviewing in the browser using your local URL.

