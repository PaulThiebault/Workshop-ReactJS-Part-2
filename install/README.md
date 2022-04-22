# Install <img src="../.assets/react-icon.png" width=20>

## Step 1: Installing NPM

To install npm on Ubuntu or Linux, invoke the command below:
```shell
$ sudo apt install npm
```

Once the installation is complete, you can verify the version of npm installed using the command:
```shell
$ npm --version

8.5.5  [Output]
```

The installation of npm also installs node.js and you can confirm the version of node installed using the command:
```shell
$ node --version

v17.9.0  [Output]
```

**If you have a problem with the version of Node click [here](Problems.md#problems)**

## Step 2: Installing create-react-app Utility

**create-react-app** is a utility that enables you to set up all the tools required to create a React Application. It saves you a great deal of time and energy setting everything from scratch and gives you the head start needed.

To install the tool, run the following npm command:
```shell
$ sudo npm -g install create-react-app
```

Once installed, you can confirm the version of installed by running:
```shell
$ create-react-app --version

5.0.1  [Output]
```

## Step 3: Create & Launch Your First React Application

Creating a React application is quite simple. We are going to create a react app called workshop-reactjs-app as follows:
```shell
$ create-react-app workshop-reactjs-app
```

*This takes roughly 3-5 minutes to install all the packages, libraries, and tools needed by the application.*

If the creation of the application was successful, you will get the notification below giving the basic commands that you can run to start managing the application.

To run the application, navigate into the app directory
```shell
$ cd workshop-reactjs-app
```

Then run the command:
```shell
$ npm start
```

If it says **Happy hacking!**,Fire up your browser and browse your server’s IP address:

`http://localhost:3000/`

## Installation is done! :relaxed:

---

<div align="center">

<a href="https://github.com/juniorconseiltaker" target="_blank"><img src="../.assets/taker-icon.png" width="50"></a>

</div>