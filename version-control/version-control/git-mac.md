# macOS & Linux

We will use the Homebrew Package Manager we installed in the Node & npm section to install Git.

To begin, run the following command in your terminal:

{% code-tabs %}
{% code-tabs-item title="command line" %}
```bash
brew install git
```
{% endcode-tabs-item %}
{% endcode-tabs %}

When the process completes, open your **Terminal** and type the following to ensure Git properly installed.

{% code-tabs %}
{% code-tabs-item title="command line" %}
```bash
git --version
```
{% endcode-tabs-item %}
{% endcode-tabs %}

If it is properly installed you should see something like this returned in the terminal.

![git version successful output](../../.gitbook/assets/git-version.png)

{% hint style="warning" %}
If you were not able to install Homebrew, install or update Git following the instructions for your OS on the [Git Downloads webpage](https://git-scm.com/downloads).
{% endhint %}

## Verify Install and Initialize User Settings

Next, we need to configure our Git version control so that you can use it with your GitHub account.

Open **Terminal** and set your user name by running the following command:

{% code-tabs %}
{% code-tabs-item title="command line" %}
```bash
git config --global user.name "Your Name"
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% hint style="warning" %}
Replace the text "Your Name" with your own full name, keeping the quotation marks. i.e. "Jane Doe"
{% endhint %}

Next, set your user email address by running the following command:

{% code-tabs %}
{% code-tabs-item title="command line" %}
```bash
git config --global user.email youremail@example.com
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% hint style="warning" %}
Replace youremail@example.com with your own email address.
{% endhint %}

Close **Terminal** window.

