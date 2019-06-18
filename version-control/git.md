# Git

Git is a tool that helps you manage versions of your code and work in collaboration with team members. There is a lot to know about it, but in this tutorial we will cover only basic usage.

## Install Git

Click on the arrow (^) below to expand the section for your operating system.

{% include "./git-windows.md" %}

{% include "./git-mac.md" %}

## Verify Install and Initialize User Settings (for both Windows and Mac)


Next, we need to configure our Git version control so that you can use it with your GitHub account.

Back in your terminal, set your user name by running the command:

```bash
git config --global user.name "Your Name"
```
and replacing the text Your Name with your own full name, keeping the quotation marks.

Next, set your user email address by running the command:

```bash
git config --global user.email youremail@example.com 
```
and replacing youremail@example.com with your own email address.

