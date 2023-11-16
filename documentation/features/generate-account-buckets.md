# Generate Account Buckets

From **update version 1.5.0** we have added "Generate Account Buckets" feature. Say goodbye to the tedious task of manually creating and assigning account buckets. 🛠️ SEO Neo's new feature makes your process smoother and faster.

This quality of life update can save you hours, especially with huge and complex campaigns where you have to create and assign account buckets to each link group.

## Why Generate Account Buckets Automatically

When you create your campaign, on **step 3 (Groups)** you need to assign Account Buckets for each link group.&#x20;

<figure><img src="../../.gitbook/assets/generate account buckets 1.png" alt=""><figcaption><p>Assigning an account bucket for each link group</p></figcaption></figure>

Some times this may be an issue because you need to create them before creating your campaigns. Even if you have pre-calculated the number of account buckets before creating your campaign, it is time consuming to assign them one-by-one to each group (especially on huge campaigns with dozens or link groups).

With this feature SEO Neo can **generate automatically** and assign account buckets for all your campaign's link groups.

## How to Use

To use this feature, click on "**Generate Account Buckets**" button located on Groups step inside campaign creation.

<figure><img src="../../.gitbook/assets/generate account buckets 2.jpg" alt=""><figcaption><p>Generate Account Buckets button</p></figcaption></figure>

A new pop-up window will appear with different options for generating your new account buckets.

The first group of options is about account bucket name generation. You can give a **prefix** on generated names, or can can even enable "**Include group type**" and "**Include tier**" to also include group type and tier level (number) on generated account bucket names.

<figure><img src="../../.gitbook/assets/generate account buckets 0.jpg" alt=""><figcaption><p>Options about name prefix</p></figcaption></figure>

The second group of options is about account buckets folder. You can either let SEO Neo to generate a new folder for your new buckets, or choose a specific folder (**Generate Folder**) where you want new presets to be stored (**Select Existing Folder**).

<figure><img src="../../.gitbook/assets/generated account presets 4.jpg" alt=""><figcaption><p>Folder options for new account buckets</p></figcaption></figure>

## Example

We have given the following options for generating new account buckets:

* **Name prefix:** "demo"
* **Include group type:** disabled
* **Include tier:** disabled
* **Folder option:** Generate Folder

<figure><img src="../../.gitbook/assets/generate account buckets 3.JPG" alt=""><figcaption></figcaption></figure>

With these options, SEO Neo **will generate 6 Account Buckets** using prefix "demo".&#x20;

<figure><img src="../../.gitbook/assets/generate account presets 6.jpg" alt=""><figcaption><p>Generated account buckets using prefix "demo"</p></figcaption></figure>

SEO Neo generated **six (6)** account buckets. The reason being, is selected diagram. SEO Neo analyzes selected diagram and generates accounts buckets accordingly.

<figure><img src="../../.gitbook/assets/generated account presets 7.jpg" alt=""><figcaption><p>Diagram selected for current example campaign</p></figcaption></figure>

Another thing to notice here, is that SEO Neo, generated a new folder to keep all new account buckets inside. Generated folder name format is:\
**\<campaign name> \_ \<prefix>**

<figure><img src="../../.gitbook/assets/generate account buckets 10.jpg" alt=""><figcaption><p>SEO Neo generated new account buckets folder</p></figcaption></figure>

### Using "Generate Account Buckets" with Sibling Groups

When your campaign contains sibling groups (please [**this section for more information**](sibling-groups.md) on **sibling groups**) if you will need to enable "**hide sibling groups**" option if you want SEO Neo to generate a single account bucket for each sibling group.

<figure><img src="../../.gitbook/assets/generate account buckets sibling.jpg" alt=""><figcaption><p>Hide sibling groups option</p></figcaption></figure>

In the example above, if you have "**hide sibling groups**" disabled, SEO Neo will generate **four (4)** new account buckets. If on the the other hand you have this option enabled, SEO Neo will generate **three (3)** new account buckets (this is because sibling groups usually share the same account bucket).

{% hint style="info" %}
"**Hide sibling groups**" effects how to setup your campaign link groups but also how SEO Neo features function. **Generate Account Buckets** is affected from this option. As a rule of thumb - when you have "hide sibling groups" enabled - SEO Neo will **count a sibling group as a single one**.
{% endhint %}
