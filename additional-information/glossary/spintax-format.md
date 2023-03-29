# Spintax format

**Spintax** (abbreviated for Spin Syntax)or **spun** format, is a list of text phrases, sentences and synonyms separated by the pipe character ( **|** ). Each group of keywords is enclosed inside curly brackets ( **{ }** ). When used on a software that supports **spintax,** the spintax parser picks a random keyword or sentence from the available choices and generates unique sentences for each iteration.

### **Spintax example (1)**

**Spintax Input**: {Hi|Hello|Good Morning}

* Hi
* Hello
* Good Morning

### **Spintax example (2)**

**Spintax Input:** {New|Old|Used} car

The above spintax text, can produce the following different variations of text:

* New car
* Old car
* Used car

{% hint style="info" %}
There are no limits on the number of spintax parts that you use. You can also used nested spintax format. Nested spintax is using brackets within brackets. This creates more variations for output.
{% endhint %}

### **Nested spintax example**

**Spintax Input:** My {first|super|great} {blog|post}

Possible variations of text:

* My first blog
* My first post
* My super blog
* My super post
* My great blog
* My great post
