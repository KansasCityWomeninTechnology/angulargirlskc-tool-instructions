## Install Git on Mac

We will use the Homebrew Package Manager we installed in the Node & npm section to install Git. 

To begin, type the following command in your terminal:

```bash
brew install git
```

When the process completes, open your **Terminal** and type the following to ensure Git properly installed.

```bash
git --version
```

If it is properly installed you should see something like this returned in the terminal.

```bash
git version 2.8.3
```

## Verify Install and Initialize User Settings 

Next, we need to configure our Git version control so that you can use it with your GitHub account.

Open **Terminal** and set your user name by running the following command and pressing `Return/Enter`:

```bash
git config --global user.name "Your Name"
```

{% hint style="warning" %}
Replace the text "Your Name" with your own full name, keeping the quotation marks. i.e. "Jane Doe"
{% endhint %}

Next, set your user email address by running the following command and pressing `Return/Enter`:

```bash
git config --global user.email youremail@example.com 
```

{% hint style="warning" %}
Replace youremail@example.com with your own email address.
{% endhint %}

