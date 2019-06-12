Install Homebrew - a package manager to install and manage development software you'll use.

In Google Chrome, navigate to http://brew.sh/

Copy the text underneath the "Install Homebrew" header.



In iTerm2 paste the text copied from the Homebrew website at the arrow command prompt and press Enter.

If you are prompted to install Command Line Developer Tools select the Install button and accept the license agreement.


At the prompt "Press RETURN to continue or any other key to abort" press Return/Enter.

When prompted, type in the password that you use to login to your computer.

{% hint style='tip' %} It may look like you’re not typing anything in but this is because it doesn’t want to display your password on the screen for security. Just type your full password and press Enter. {% endhint %}

The process will run for a few minutes until it completes. When finished type brew -v. This should display the version number of Homebrew that you have installed. Your screen should look similar to the following:


Install Git

In iTerm2, type brew install git and press enter.

When the process completes, type git --version at the arrow prompt to ensure Git was properly installed. If it is properly installed you should see something like git version 2.8.3 returned.

Now we need to configure our Git version control so that you can use it with GitHub later

At the prompt (the green arrow) set your user name by running the command git config --global user.name "Your Name" replacing the text Your Name with your own full name, keeping the quotation marks.

Next, set your user email address by running the command git config --global user.email youremail@example.com replacing youremail@example.com with your own email address.