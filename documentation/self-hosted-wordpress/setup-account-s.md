# Setup Account(s)

Before using Self-hosted Wordpress you will need to setup your account.

To do so, navigate to: **Accounts > "Self Hosted Wordpress"**.

From there you can add multiple accounts and organize them into folders.

<figure><img src="../../.gitbook/assets/frm 1.jpg" alt=""><figcaption></figcaption></figure>

To create an account, click "**Add Self Hosted Wordpress**" button.

<figure><img src="../../.gitbook/assets/frm 2.jpg" alt=""><figcaption></figcaption></figure>

A new pop-up window will appear where you will need to enter your **Domain**, your **Username** and **Password**.

<figure><img src="../../.gitbook/assets/frm 3.jpg" alt=""><figcaption></figcaption></figure>

When you finish click on "**Create**" button to create your account. You can also use hover over your created account and use the **test domain** button (a heart icon) to test your account credentials.

<figure><img src="../../.gitbook/assets/frm 4.jpg" alt=""><figcaption><p>Use "test domain" function from hover buttons to check your credentials</p></figcaption></figure>

## Which Password to use for your Self-hosted Wordpress Account ?

When you add a new **Self Hosted Wordpress** you need to enter domain, username and **password**. Although domain and username is standard for your Wordpress, this is not the case for the password.

There are two different scenarios / passwords you can use:

1. **Application Password** (generated within your Wordpress user account) - **recommended**
2. Your **account** password (which requires a plug-in) - **not** **recommended**.



## Using Application Password

To create an Application Password, from your Wordpress navigate: **Users > Profile.**

<figure><img src="../../.gitbook/assets/app password 1.jpg" alt=""><figcaption></figcaption></figure>

Write a name on "**New Application Password Name**" field.

<figure><img src="../../.gitbook/assets/app password 2.jpg" alt=""><figcaption></figcaption></figure>

Click on "**Add New Application Password**" button.

<figure><img src="../../.gitbook/assets/app password 3.jpg" alt=""><figcaption></figcaption></figure>

A new password has been generated. Copy that password and use it when you add a new Wordpress account on Self Hosted Wordpress.

<figure><img src="../../.gitbook/assets/app password 4.jpg" alt=""><figcaption></figcaption></figure>

###

## Your Account Password

If you want, you can also use your default Wordpress account password, without the need to create a new application password, but this method is not recommended.

If you want to use your account password, you will need to install **JSON Basic Authentication** **plug-in** for this method to work.

Download **JSON Basic Authentication** **plug-in** from the following link:

{% embed url="https://github.com/WP-API/Basic-Auth/archive/refs/heads/master.zip" %}

After downloading the plug-in, install it on your Wordpress site.

<figure><img src="../../.gitbook/assets/plugin 1.jpg" alt=""><figcaption></figcaption></figure>

When you install the plug-in you need to activate it. Go to "**Installed Plugins**" where you will see all installed plugins. From there, locate "**JSON Basic Authentication**" plug-in and click "**Activate**".

<figure><img src="../../.gitbook/assets/plugin 2.jpg" alt=""><figcaption></figcaption></figure>

You are now ready to use your own account password.

