# Angular CLI

![Angular CLI logo](../.gitbook/assets/cli.png)

An advantage of Angular is its powerful **C**ommand **L**ine **I**nterface \(**CLI**\). This is a special tool we can use to quickly create an Angular application. The Angular CLI will scaffold the framework for a web application so we can be up and running in no time!

## Install Angular CLI

In the terminal, run the following command:

{% code-tabs %}
{% code-tabs-item title="command line" %}
```bash
npm install --global @angular/cli
```
{% endcode-tabs-item %}
{% endcode-tabs %}

To verify your installation, check the Angular CLI version by typing:

{% code-tabs %}
{% code-tabs-item title="command line" %}
```bash
ng version
```
{% endcode-tabs-item %}
{% endcode-tabs %}

If you see output with a version number, your Angular CLI installation is successful.

![Angular CLI successful installation](../.gitbook/assets/angular-cli.png)


## Create the application project

Next we'll create a new Angular project, called `todo-list` using the Angular CLI. This is the web application we'll work on during the workshop.

Make sure your terminal is still inside the `nggirls-workshop` folder. 

{% hint style="info" %}
Your terminal displays your current path above or as part of the command prompt. You can also run the `pwd` command to see your working directory. If you see `nggirls-workshop` in your path, you're good to go!

![](../.gitbook/assets/nggirls-workshop-folder.png)
{% endhint %}


Then run the following command to create the Angular project:

{% code-tabs %}
{% code-tabs-item title="command line" %}
```bash
ng new todo-list
```
{% endcode-tabs-item %}
{% endcode-tabs %}


Angular CLI will ask a couple of questions to help create a new application. Answer the questions as shown below: 

1. Would you like to add Angular routing? (y/N): N 
2. Which stylesheet format would you like to use? (Use arrow keys): CSS (Press `Enter` to select CSS)

This can take a while, since many packages are being downloaded from the web and installed.

Now change your working directory to the new folder that Angular CLI created for this project by running:

{% code-tabs %}
{% code-tabs-item title="command line" %}
```bash
cd todo-list
```
{% endcode-tabs-item %}
{% endcode-tabs %}


## Open the project in Visual Studio Code

We want to open the project in your IDE. We can use the toolbar inside VS Code or the command line.

Open VS Code in this folder using the command line by running:

{% code-tabs %}
{% code-tabs-item title="command line" %}
```bash
code .
```
{% endcode-tabs-item %}
{% endcode-tabs %}


You can also open the project folder using the toolbar by selecting **File** ![](../.gitbook/assets/arrow-right.svg) **Open Folder...** and navigating to the `~/nggirls-workshop/todo-list` folder.

Close your terminal window.

## Serve the application

We'll now switch over to using the integrated terminal in Visual Studio Code.

{% hint style="info" %}
For the workshop you will use the terminal in VS Code. Having your IDE and terminals together in one application will make it easier to follow the tutorial without having to juggle between so many different application windows.
{% endhint %}

In VS Code, open a terminal window by selecting **Terminal** ![](../.gitbook/assets/arrow-right.svg) **New Terminal**.

{% hint style="info" %}
Visual Studio Code should automatically open the terminal to your project location (`~/nggirls-workshop/todo-list`). If it doesn't, navigate there by running the command `cd ~/nggirls-workshop/todo-list`.
{% endhint %}


In the terminal inside VS Code, run the following command to serve your application. This process continues in a "stuck" state until you tell it to stop.

{% code-tabs %}
{% code-tabs-item title="command line" %}
```bash
ng serve -o
```
{% endcode-tabs-item %}
{% endcode-tabs %}

The flag `-o` is a short for `--open`, which will open your default browser to where the application is running: `localhost:4200​`. 

{% hint style="danger" %}
If the application doesn't open in Google Chrome, copy the URL of the application, open a new Chrome tab, and paste in the application URL. You will have to repeat this at the workshop when starting up your project.
{% endhint %}

You should see a page like this:

![Angular Start Screen](../.gitbook/assets/angular_start_screen.png)

Yay! You know have a running Angular application! As long as you're working on the application you should keep the terminal where you run it open. Any change you make in the project code will be reflected immediately in the web browser.

You can open another terminal to perform tasks in parallel.
To stop the app from running and exit "stuck" state, press `CTRL` + `c` in the terminal.


## **Congratulations!**

You've reach the end of the installation worksheet. You have installed all of the tools you will need to build your first Angular application!

Give yourself a pat on the back! We look forward to seeing you back here tomorrow to continue working on your to-do list app.

![](https://media.giphy.com/media/FPbwPhVh4YJlNYerJP/giphy.gif)

