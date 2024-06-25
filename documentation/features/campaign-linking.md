# Campaign Linking

{% embed url="https://www.youtube.com/watch?v=qUbD08zApnU" %}

**Campaign linking** is a feature that allows you to automate campaigns and schedule them to start when another another campaign finishes. This advance scheduling mechanism, helps you speed up your process of automating multiple campaigns and create long drip-feed strategies.

## Understanding Campaign Linking - Terms

In the image below we see a basic campaign linking example, to explain some terms.

<figure><img src="../../.gitbook/assets/link chain.jpg" alt=""><figcaption><p>Link Chain - terms diagram</p></figcaption></figure>

* When there are multiple campaign linked together, the whole link schematic is called **"link chain"**.
* When two campaigns are linked together, the top-tier campaign is called **"parent"** and the lower-tier is called a **"child"**. In the image above, campaign **A** is the **parent** of campaign **B** and campaign **B** is the parent of campaign **C**.
* The first campaign in the chain is called **"root parent"**.

{% hint style="info" %}
Each campaign in the chain **can only be linked with one parent** and **one child**.  A campaign **cannot have** multiple parents or multiple children.&#x20;
{% endhint %}

##

## Understanding Campaign Linking - Flow

Below is a real example of linked campaigns created inside SEO Neo:

<figure><img src="../../.gitbook/assets/link chain - example.JPG" alt=""><figcaption></figcaption></figure>

Each campaign can be linked with another campaign. In this example **Campaign A** is linked with **Campaign B** and **campaign B** is linked with **Campaign C**. Campaign A is called "**root parent**" as it is the master (first) parent of the whole link chain.

When you create a link chain you set the order you want the campaign to start. When the first campaign in the chain completes (stops running), it starts the second campaign in the chain. The process continues until all campaigns in the chain completes.

##

## How to Link Campaigns

To link a campaign with another campaign, you can select the campaign to link with in "Settings" step when you create or edit a campaign.

<figure><img src="../../.gitbook/assets/link chain - 1.jpg" alt=""><figcaption></figcaption></figure>

You can find "**Link Campaign**" in **Posting Options**. From there you can select Instant post, Posts per day, Days to run or **Link Campaign**.

Select Link Campaign and then select a parent campaign for you current campaign using the drop-down menu on the right.

<figure><img src="../../.gitbook/assets/link campaign 2.jpg" alt=""><figcaption><p>Link campaign in Posting options</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/link chain 3.jpg" alt=""><figcaption></figcaption></figure>

In this example we are editing **Campaign C** and we want to link it with **Campaign B**. Inside **Campaign C**, we select **Campaign B** (the parent) to create our link.

{% hint style="info" %}
You can **only** select campaigns that are **not currently running** and **don't have any other child**. Example: you can't link another campaign with **Campaign B**, because **Campaign B** is already linked with **Campaign A** and **Campaign C**. However you could link a new campaign with **Campaign C**.
{% endhint %}

##

## Using Quick Edit to Link Campaigns

Another way to link campaigns, is to use **Quick Edit**. This way you can links your campaigns faster without navigating all campaign creation steps 1-4.

<figure><img src="../../.gitbook/assets/link chain 4.jpg" alt=""><figcaption></figcaption></figure>

In this example we have 3 campaigns: **Campaign A** and **Campaign B** which are already linked together. Let's assume we want to create a link chain:\
**Campaign A** <- **Campaign B** <- **Campaign C**

We need to link **Campaign C** with **Campaign B.** We can use "**Quick Edit**" from hover buttons to quickly edit **Campaign C**.

<figure><img src="../../.gitbook/assets/link chain 5.jpg" alt=""><figcaption></figcaption></figure>

Selected "**Link campaign**", select the parent campaign you want to link current campaign with (select parent campaign). In this case we've selected **Campaign B**. Click '**Save**" to save your changes.

<figure><img src="../../.gitbook/assets/link chain 6.jpg" alt=""><figcaption></figcaption></figure>

Now **Campaign C** is linked with **Campaign B** and we have finished our link chain.

<figure><img src="../../.gitbook/assets/link chain 7.jpg" alt=""><figcaption></figcaption></figure>

On our example we have created a chain with three campaigns: **Campaign A**, **Campaign B** and **Campaign C**. When you start the first campaign in the campaign the order of campaign running will be as follows:\
**Campaign A** -> **Campaign B** -> **Campaign C**.



### Breaking Chain

At any time you can use **Edit** or **Quick Edit** to remove a campaign from a chain. Keep in mind that breaking a chain will respect the order of the chain. In our example, if we remove **Campaign C** from the chain, then we will have: a chain (**Campaign A** -> **Campaign B**) and a single campaign **Campaign C**.

<figure><img src="../../.gitbook/assets/breaking chain 1.JPG" alt=""><figcaption></figcaption></figure>

If we removed **Campaign B** from the chain, we would break the chain (because we only have three campaigns in our chain). This would make all campaigns unchained.

<figure><img src="../../.gitbook/assets/breaking chain 2.JPG" alt=""><figcaption></figcaption></figure>

