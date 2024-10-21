# 4 - Settings

This is the last step / section of campaign creation. This is where you change settings for the campaign. Here you can set Captcha service, threads to be used, if you want the campaign post to get drip-feed and if you want to schedule the campaign to run in the future.

### Captcha Services

This is **the only required setting on this step**. Using captcha services to solve captchas on your campaigns is a requirements [**as mentioned on this section**](../before-creating-your-campaign/) of the documentation.

<figure><img src="../../../.gitbook/assets/settings - 1.jpg" alt=""><figcaption></figcaption></figure>

Here you need to select at least one **Primary Captcha** service. In our case we will use "Twocaptcha".

<figure><img src="../../../.gitbook/assets/settings - primary captcha.jpg" alt=""><figcaption><p>Recomended default captcha service is Twocaptcha</p></figcaption></figure>

{% hint style="info" %}
Secondary captcha service is not required but it increases success rate in case the first captcha service fails to solve a captcha.
{% endhint %}

At this point you can **finish and save** your campaign setup, but we will explain all the other settings that are not required by default.

If you want to finish and save your campaign, just click "**Save**" button on the lower right side of the window.

<figure><img src="../../../.gitbook/assets/settings - save.jpg" alt=""><figcaption><p>Saving your campaign is the last step on campaign creation!</p></figcaption></figure>

### Threads

Here you can change how many threads will be used on this campaign. On some sites SEO Neo uses HTTP requests to create posts, and other sites use browser. You can change threads usage independently for each method.

<figure><img src="../../../.gitbook/assets/settings - 2.jpg" alt=""><figcaption><p>SEO Neo's default campaign threads values.</p></figcaption></figure>

{% hint style="info" %}
There is no specific number of threads you can use for threads. The general rule of thumb is that the more powerful your machine, the more threads you can use.

Keep in mind that browser threads require much more resources than HTTP.
{% endhint %}

### Post Drip Feed

Default value is "**Instant Post**". This means that the software will start the post process the moment you start the campaign.

<figure><img src="../../../.gitbook/assets/settings - 3.jpg" alt=""><figcaption><p>Post Drip Feed has three different options</p></figcaption></figure>

{% hint style="info" %}
**Instant Post** doesn't mean that posts will occur blazing fast. It means it will make the posts as fast as possible including all automation and human simulation factors.
{% endhint %}

In case you want your campaign to execute in a more "human way" or you want to delay each post by a specific amount (based on your SEO strategy), you can select one of two Post Drip Feed options:

**Posts Per Day**: you set how many posts you want SEO Neo to post per day and the software will automatically calculate how to delay each post.

**Days To Run**: you set how many days (totally) you want the campaign to last and the software will automatically calculate how to delay each post.

{% hint style="info" %}
**Drip Feed** option introduces calculated delay between posts to mimic human behavior. \
\
Setting a smaller than required number doesn't make SEO Neo to create posts faster.\


**Example**: let's say you have a big campaign that would require 3 days to complete based on the size of your campaign and based on your machine specs. If you choose "**Day To Run** = 1" it will not force SEO Neo to create posts within one day.
{% endhint %}

### Campaign Schedule

If you want to schedule when your campaign starts (in the future) you can enable "**Schedule Campaign Start**" from check box and set date and time from calendar.\


<figure><img src="../../../.gitbook/assets/settings - schedule 1.jpg" alt=""><figcaption><p>Enable "Schedule Campaign Start: checkbox</p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/settings - schedule 2.jpg" alt=""><figcaption><p>Click on calendar to select date and time</p></figcaption></figure>
