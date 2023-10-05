# Uploading Cloud Blogs

When you click "**Upload**" button a pop-up menu appears showing all available cloud services that you [**have setup**](cloud-blogs-settings/).

<figure><img src="../../.gitbook/assets/cloud blogs - upload 1.jpg" alt=""><figcaption></figcaption></figure>

You can select one or multiple services you want to upload your blogs by using the checkboxes from the right side.

<figure><img src="../../.gitbook/assets/cloud blogs - upload 2.jpg" alt=""><figcaption></figcaption></figure>

### Upload Settings

When you select (check) a cloud service, the menu expands to show settings for selected service. Upload settings are different from service to service. For example on Azure you only have to select **Bucket** and **Directory** but on Bunny you also have to select **Pull zone.**

{% hint style="info" %}
For best compatibility, we recommend that you avoid using dots (.) in bucket names, except for buckets that are used only for static website hosting.&#x20;

If you include dots in a bucket's name, you can't use virtual-host-style addressing over HTTPS, unless you perform your own certificate validation. This is because the security certificates used for virtual hosting of buckets don't work for buckets with dots in their names.
{% endhint %}

<figure><img src="../../.gitbook/assets/cloud blogs - upload 3.jpg" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Different services have different ways to manage uploaded assets.&#x20;
{% endhint %}

When you select the cloud service(s) you want to upload your blogs, just click on "**Upload Blog**" button.
