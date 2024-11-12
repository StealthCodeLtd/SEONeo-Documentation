# Adding content

When you create a new content bucket, it's content is empty. In order to fill it with content, you will need to edit the bucket, by clicking "**Edit**" on hover button.

<figure><img src="../../.gitbook/assets/content bucket edit.jpg" alt=""><figcaption></figcaption></figure>

There are three different ways to add content:

**1) Import**

You can import content from file(s) or other content bucket that already includes content.

**2) Generate**

You can generate content using our free built-in builders, or 3rd party APIs.

**3) Add**

You can add content manually.

<figure><img src="../../.gitbook/assets/content bucket menu.jpg" alt=""><figcaption><p>Use import, Generate and Add to insert content into content bucket.</p></figcaption></figure>

***

### Adding different content types

Each content bucket can have multiple content entries from different [**content type**](broken-reference). You can navigate on different content categories and add content on each category separately.

<figure><img src="../../.gitbook/assets/content types.jpg" alt=""><figcaption><p>Navigate between content types using tabs.</p></figcaption></figure>

In the following example we will add a new article inside our content bucket.

1\) Click "**Article**" on content type tab.

<figure><img src="../../.gitbook/assets/articles tab.jpg" alt=""><figcaption></figcaption></figure>

2\) Click "**Add Article**" to open article form.

<figure><img src="../../.gitbook/assets/articles - add article.jpg" alt=""><figcaption></figcaption></figure>

3\) Insert all required text on article editor and click "**Save**". Each content type has it's own editor depending on required data. In this example we add an article so we see the full article editor.

<figure><img src="../../.gitbook/assets/article html editor.jpg" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Different content types require different data entry. Refer to [**content types**](broken-reference) for more information.
{% endhint %}

***

### Article Editor

Article editor is where you can create and edit articles that which are stored inside content buckets. Other content types like short descriptions, bios etc. have only a simple text form but articles can include rich content and formatted text.

{% hint style="info" %}
Where you write article title and article body, it is preferred to use [**spintax format**](../../additional-information/glossary/spintax-format.md), which makes you title to include different variations. If you don't use spintax format, your article will get posted as it is.
{% endhint %}

Below we can see the basic section of article editor.

<figure><img src="../../.gitbook/assets/article html editor - sections.jpg" alt=""><figcaption></figcaption></figure>

#### 1) Article Title

This is where you put your article title. You can also insert default spun title by clicking "**Default Value**".

#### 2) Short Codes

Short codes are special tags that you insert inside article body. These tags sets specific positions/placements where next keyword will be placed.&#x20;

{% hint style="info" %}
If the next keyword type on the campaign  is not the same as short code keyword type, the short code gets ignored.
{% endhint %}

Except from keyword types, short codes can also be image, video, or embedded code.

If you don't include any short code, keywords will be places at random positions (defined from your campaign campaign settings). If you include short codes, you set specific positions inside article body where you want keywords to appear.

{% hint style="info" %}
Using "**any keyword**" will randomly select an available keyword from your campaign.
{% endhint %}

#### 3) Article HTML Body

This is where you write your article body. You can enter text and HTML code. The default value in the window is **\<p> \</p>**, because at least a paragraph is needed. Even if you delete \<p> tags in the article editor, SEO Neo will add it on the fly.

#### 4) Spin

You can spin your article using one of the available spinners. Spinning your article will take your article text and create a new one in [**spintax format**](../../additional-information/glossary/spintax-format.md).  This is highly recommended because it creates different variations from the same article.

To spin your article, select one of the available spinners and then click "**Spin**".

<figure><img src="../../.gitbook/assets/spinner combobox.jpg" alt=""><figcaption><p>Click on menu to select a spinner.</p></figcaption></figure>

SEO Neo includes a free spinner, but you can also use any 3rd-party supported spinner. To use a 3rd-party spinner, you will need to set your credentials (API keys etc.) from [**spinner settings**](../settings/third-party-api.md#spinner)**.**

<figure><img src="../../.gitbook/assets/spinners.jpg" alt=""><figcaption><p>Available spinners</p></figcaption></figure>

Below is an example of a basic article text that gets "spinned" using SEO Neo's built-in free spinner. As you can see, although the original text was very small and simple, after spinning, we got many different variations.

| Original article text                     | Spintax format generated from free spinner                                                                                                                                                                                        |
| ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| this is a very small text article example | this {is a very\|is an extremely\|is a really} {small\|little\|tiny\|modest\|smaller\|compact} {text\|textual content} {article\|post\|write-up\|report\|short article\|posting} {example\|instance\|illustration\|case in point} |

#### 5) Preview Article

When you want to check how your article will look like, you can see "**Article Preview**" window on the right section of the editor. This preview will also preview HTML code preview, so you can easily check your text and HTML. In order to update and preview any changes in the **Article HTML body**, you have to click on "**Update Preview**" button first.

<figure><img src="../../.gitbook/assets/article html editor - preview.jpg" alt=""><figcaption><p>Click "Update Review" button on the top right section to preview any changes</p></figcaption></figure>

{% hint style="info" %}
Whenever you make any changes, click "**Update Preview**" button to update and render the preview of the article.
{% endhint %}

### Adding Short Description

Adding a short description is the same like adding an article. The difference is that short description is just plain text and a title.

<figure><img src="../../.gitbook/assets/add short description.jpg" alt=""><figcaption></figcaption></figure>

Short descriptions don't have full article editor because the user is only required to add a description title and a small description (recommended 255 characters long).

<figure><img src="../../.gitbook/assets/short description.JPG" alt=""><figcaption></figcaption></figure>

### Adding Bio

Adding bio is the same like adding an article. The difference is that short description is just plain text and a title.

<figure><img src="../../.gitbook/assets/add bio.jpg" alt=""><figcaption></figcaption></figure>

Bios don't have full article editor because the user is only required to add a small bio title and a small bio text (recommended 255 characters long).

<figure><img src="../../.gitbook/assets/bio.JPG" alt=""><figcaption></figcaption></figure>

***

### Adding Rich Content

As the name implies, rich content includes rich content that can be included in your articles. Articles can include **images**, **videos** and **embeded code**.

You can add rich content by clicking "**Rich Content**" and then "**Add Rich Content**". A drop-menu will appear to select what type of rich content you want to add.

<figure><img src="../../.gitbook/assets/Add rich content.jpg" alt=""><figcaption><p>Select what type of rich content you want to add from drop-menu.</p></figcaption></figure>

After selecting rich content type, a form appears where you can enter URLs. You can enter multiple URLs (one per line) to save time.

Rich content is injected inside your article at a random position. If you want to specify a specific position within your article for your images, videos or your embedded code, you can change "**Position in Article**" option.

<figure><img src="../../.gitbook/assets/rich content position.jpg" alt=""><figcaption><p>You can choose top, bottom and random position.</p></figcaption></figure>

{% hint style="info" %}
It is highly recommended to include rich content on your content buckets. This increases SEO value of your posted articles, as search engines favor rich-content articles that include images, videos etc.
{% endhint %}

***

### Scraping Rich Content

If you don't any rich content URLs but you still need to find some for your content bucket, SEO Neo has a free built-in scraper.

To use the scraper:

1\) Click "**Scrape Rich Content**"

<figure><img src="../../.gitbook/assets/scrape rich content.jpg" alt=""><figcaption></figcaption></figure>

2\) Select what type of content you want to scrape "**images** or **videos**".

<figure><img src="../../.gitbook/assets/scrape type.jpg" alt=""><figcaption></figcaption></figure>

3\) Enter keyword you want SEO Neo to use to scrape content.

4\) Enter the number of URLs you want to scrape (maximum 20).

<figure><img src="../../.gitbook/assets/scrape images (1).JPG" alt=""><figcaption></figcaption></figure>

5\) Click "**Scrape Images/Videos**" and SEO Neo will fetch URLs for you, based on given keywords.

***

### Adding Blog Details

Blog details are include "**Blog Name**" and "**Blog Subdomain**" that will be used during blog creation.

Both blog name and blog subdomain support spintax format to include variations.

You can also click on "**Default Value**" to use built-in SEO Neo's default blog names and subdomains which come in spintax format.&#x20;

<figure><img src="../../.gitbook/assets/blog details.jpg" alt=""><figcaption><p>You can always use "Default Value" buttons to fetch pre-defined Blog Names or Blog Sub-domains</p></figcaption></figure>
