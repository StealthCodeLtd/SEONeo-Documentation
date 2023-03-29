# 🔑 Account Buckets

### What is an account bucket

An account bucket is a collection of accounts that SEO NEO creates and uses in order to run a campaign. Each account stores log-in information for each website. Each account bucket can have multiple accounts for different websites.

<figure><img src="../../.gitbook/assets/affiliate marketing copy.jpg" alt=""><figcaption><p>An account bucket is a collection of user accounts.</p></figcaption></figure>

### How the software uses Account Buckets

When a campaign runs the software follows the following steps in order:

1. Load a website
2. Create/register an account (if there isn't any)
3. Confirm account (if required through email)
4. Log-in using the created account
5. Create new post based on campaign settings (account buckets, etc.)

{% hint style="info" %}
In step (2) we see that the software creates an account for a specific website. After the account registration SEO NEO stores account credentials (user name and password) into the account bucket.
{% endhint %}

An account bucket can store multiple accounts for multiple websites. This means that if a user created an account bucket named "_my\_account\_bucket_" this bucket can contains hundreds of accounts created after a completed campaign.

### What's the point of multiple account presets?

So what's the point of having different account presets, if an account bucket can store unlimited accounts? The answer is very simple and can be better be explained with the following example.

SEO NEO has a simple rule with account buckets. If there is an account already created for a website, SEO NEO will not try to create a new one, but it will use that account to sign-in and create a post on that account. So lets review the campaign steps again, but this time we will assume that the user has has selected an old account bucket (that has been already been used on a campaign before).

1. Load a website
2. If there is an account preset, use credentials and sign-in
3. Create new post based on campaign settings (account buckets, etc.)

> SEO NEO _has a simple rule with account buckets. If there is an account already created for a website, the software will not try to create a new one_

So now we see that SEO NEO detected that we have a previous account preset located into the account bucket and just loaded, used its credentials and signed in.

Using the same accounts on a campaign, makes SEO NEO create another post on the same blog. If you use 10 different account buckets for 10 different link groups, the software will create 10 accounts and 10 different blogs. But if you use 1 account bucket for 10 different link groups, the software will sign-in into those accounts and will create posts on those blogs already existing.

> _Using the same accounts on a campaign, makes_ SEO NEO _create another post on the same blog_

### An example

The user selects an account bucket for the first time on a campaign. SEO NEO creates two blogs and a post for each blog.

<figure><img src="../../.gitbook/assets/account buckets ex1.jpg" alt=""><figcaption><p>Using account bucket 1st time</p></figcaption></figure>

The user uses the same account bucket on another campaign. SEO NEO creates a new post for Blog A and a new post for Blog B.&#x20;

<figure><img src="../../.gitbook/assets/account buckets ex2.jpg" alt=""><figcaption><p>Reusing the same account bucket</p></figcaption></figure>

### How accounts are used

When a campaign runs it the account assigned for a specific site from selected bucket. If there is more than one active accounts (for the same site) the software will randomly choose between these accounts.

{% hint style="info" %}
If you use the same account bucket on multiple campaigns that run at the same time may brings undesired results. If you choose to do so, keep in mind that you don't know which task is using this account.
{% endhint %}
