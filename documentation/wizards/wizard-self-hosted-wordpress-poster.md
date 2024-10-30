---
cover: ../../.gitbook/assets/shw-header.jpg
coverY: 0
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Wizard: Self-Hosted WordPress Poster

Self-Hosted WordPress Poster is a  **utility wizard** designed to help you quickly create posts on your self-hosted WordPress websites. It eliminates the need for setting up time-consuming campaigns, allowing you to effortlessly publish content on your websites.

To run this wizard navigate:

**Main menu > Wizards**

From Wizards screen select "**Self-Hosted WordPress Poster**" wizard and click on "**Initialize**" button to launch it.

<figure><img src="../../.gitbook/assets/shw poster 1.jpg" alt=""><figcaption></figcaption></figure>

***

### How to Use Self-Hosted Wordpress Poster

This Wizard is broken into two steps:

<figure><img src="../../.gitbook/assets/shw poster 2.jpg" alt=""><figcaption></figcaption></figure>

1\) General Settings

2\) Post Settings

Let's go and set each available option on this wizard.

***

### Step 1 - General Settings

### Campaign Folder <a href="#campaign-folder" id="campaign-folder"></a>

<figure><img src="../../.gitbook/assets/shw poster 3.jpg" alt=""><figcaption></figcaption></figure>

In this option you select where you want the wizard to store generated campaign. The default option is "**Auto generate**" which generates a new folder automatically.

If you want the wizard to store the new campaign into a specific folder you can select "**Select a Folder**" radio button and use the drop-down menu to select a specific folder.

<figure><img src="../../.gitbook/assets/ccp-3.jpg" alt=""><figcaption></figcaption></figure>

### Name Prefix

<figure><img src="../../.gitbook/assets/shw poster 4.jpg" alt=""><figcaption></figcaption></figure>

**Name prefix** gives a prefix on generated campaign name to help you identify it later. Name prefix is optional but it is recommended if you want to keep your campaigns better organized.

### Indexer

<figure><img src="../../.gitbook/assets/shw poster 5.jpg" alt=""><figcaption></figcaption></figure>

This is the same option that you can find also in other SEO Neo sections (for example when you create a new campaign). You can select an indexer to use for your Self-Hosted WordPress posts.

{% hint style="info" %}
It is **recommended** to use [**Omega Indexer**](https://www.omegaindexer.com/) or [**Colinkri**](https://www.colinkri.com/) if you want better results with indexing your posts.

If you need more information on how to setup an indexer [**read this section**](https://docs.seoneo.io/quick-start/creating-your-1st-campaign/before-creating-your-campaign/basic-settings#indexers) of our documentation.
{% endhint %}

### Select Self-Hosted WordPress

<figure><img src="../../.gitbook/assets/shw poster 6.jpg" alt=""><figcaption></figcaption></figure>

In this section you select which self-hosted WordPress you want to use to create your posts. You can filter-out your self-hosted WordPress websites by folder (using the left drop-down menu and selecting a folder).

{% hint style="info" %}
For more information on how to setup your self-hosted WordPress account into SEO Neo [**read this section**](../self-hosted-wordpress/) of the documentation.
{% endhint %}

### Self-Hosted WordPress Poster Schedule

<figure><img src="../../.gitbook/assets/shw poster 7.jpg" alt=""><figcaption></figcaption></figure>

This option is optional but is very useful. You can check "**Schedule Self-Hosted WordPress Poster**" option and select a date and time (by clicking on the box on the right side).

<figure><img src="../../.gitbook/assets/shw poster 8.jpg" alt=""><figcaption></figcaption></figure>

When you finish with General Settings click on "**Next**" button to navigate to the second step of the wizard.

***

### Step 2 - Post Settings

This step includes all the options to define your posts on your WordPress website (the one you selected on the previous step).

<figure><img src="../../.gitbook/assets/shw 2-1.jpg" alt=""><figcaption></figcaption></figure>

### Post Settings

<figure><img src="../../.gitbook/assets/shw 2-2.jpg" alt=""><figcaption></figcaption></figure>

**Posts per Day**: as the name suggests, defines the number of posts SEO Neo to perform per day. There is a limitation of _100 maximum posts_ per day.

**Internal Links:** sets the number of internal links you want to be created for your posts. Internal links are hyperlinks that connect one page on a website to another page within the same domain.

{% hint style="info" %}
Keep in mind that you need **OpenAI** **API key** to use **Internal Links** feature.
{% endhint %}

For more information on internal links you can read [**this section of our documentation**](https://docs.seoneo.io/documentation/features/internal-linking).

**Internal Links Relevance:** Self-Hosted WordPress has an additional setting for internal links. With this option you can set how internal links are generated. There are three different options:

<figure><img src="../../.gitbook/assets/shw internal links relevance.jpg" alt="" width="563"><figcaption></figcaption></figure>

| Option         | Info                                                                               |
| -------------- | ---------------------------------------------------------------------------------- |
| **random**     | random selection between (categories and tags)                                     |
| **categories** | internal links are generated from posts exclusive to the selected group categories |
| **tags**       | internal links are generated from posts exclusive to the selected group tags.      |



### Understanding Category Groups

This wizard helps you create posts on your self-hosted WordPress website. To help you with this task we created category groups. A category group is a group of posts settings that apply on different categories of your WordPress website. This means that you can create different posts with different settings on different categories.

{% hint style="info" %}
Keep in mind that you need **at least one category group**. Your website categories can be included **in only one** category group.
{% endhint %}

**Example:**

Let's assume we have three categories on our website: A, B, C

We can create a category group that posts on **A, B** and another category group that posts on **C**.

Creating a category group that posts on **A, B** and another category group that posts on **B,C** is not valid. This is because the second group includes a category (**B**) that is **already included** in first group.

<figure><img src="../../.gitbook/assets/shw category groups valid-invalid.jpg" alt="" width="375"><figcaption><p>Examples of category groups</p></figcaption></figure>



### Creating Category Groups

To create a new category group, click on "**Add Category Group**" button.

<figure><img src="../../.gitbook/assets/shw category group button.jpg" alt="" width="563"><figcaption></figcaption></figure>

A new window will appear where you can select on which categories on your website you want to post.

<figure><img src="../../.gitbook/assets/shw categories.jpg" alt="" width="563"><figcaption></figcaption></figure>

You can select multiple categories to post by using checkbox on the left.

<figure><img src="../../.gitbook/assets/shw categories 1.jpg" alt="" width="508"><figcaption></figcaption></figure>

You can also add a new category and click on "**Add**" button.&#x20;

<figure><img src="../../.gitbook/assets/shw - add categories 1.jpg" alt="" width="486"><figcaption></figcaption></figure>

The category will be added on the list where you can select it or remove it using the little "**x**" button.

<figure><img src="../../.gitbook/assets/shw - add categories.jpg" alt="" width="486"><figcaption></figcaption></figure>

When you finish selecting categories, click on "**Generate Category Group**" button. The category will be generated.&#x20;

You can use the "**trash**" button to remove generated categories or the "**down arrow**" to expand the category and change it's settings.

<figure><img src="../../.gitbook/assets/shw category.jpg" alt=""><figcaption></figcaption></figure>

From the expanded view, you can set **content bucket**, **total** number of **posts**, **tags** and **featured images** for your posts.

<figure><img src="../../.gitbook/assets/shw category settings 1.jpg" alt=""><figcaption></figcaption></figure>

When you finish with your settings you can add another category group. Just keep in mind that **you cannot** **select the same category** that have been used on a different group.

<figure><img src="../../.gitbook/assets/shw disabled category.jpg" alt="" width="563"><figcaption></figcaption></figure>

When you finish with all your category groups, click on "**Generate**" button and your are done! A new wizard campaign is created that will create all your posts based on all provided information in the Wizard.

<figure><img src="../../.gitbook/assets/shw generate.jpg" alt="" width="563"><figcaption></figcaption></figure>
