## Install Git on Mac

We will use the Homebrew Package Manager we installed in the Node & npm section to install Git. 

1. To begin, type the following command in your terminal:

```bash
brew install git
```

2. When the process completes, open your **Terminal** and type:

```bash
git --version
```

to ensure Git was properly installed. 

If it is properly installed you should see something like 

```bash
git version 2.8.3
```
returned in the terminal.

## Verify Install and Initialize User Settings 

Next, we need to configure our Git version control so that you can use it with your GitHub account.

1. Open the **Terminal** and set your user name by running the following command and pressing `Return/Enter`:

```bash
git config --global user.name "Your Name"
```
* Replace the text "Your Name" with your own full name, keeping the quotation marks. i.e. "Gloria Higley"

2. Next, set your user email address by running the following command and pressing `Return/Enter`

```bash
git config --global user.email youremail@example.com 
```
* Replace youremail@example.com with your own email address.



