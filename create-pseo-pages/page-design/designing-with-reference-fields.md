# Designing with Reference Fields

Reference fields allow you to bring information from one CMS collection into another.

{% hint style="info" %}
If your collection items don’t include reference fields, make sure you’ve set them up correctly. See [_Creating Reference and Multi-Reference fields_](../connecting-webflow/creating-reference-and-multi-reference-fields.md) for more information.
{% endhint %}

In Webflow, there are two types of reference fields:

* Single reference fields
* Multi-reference fields

Single reference fields are configured to link a single item from another collection. For example, if your blog collection is configured to reference a single author, you can select one name from the list of available authors.

They’re the simplest in theory and to work with in practice.

When you add an element to your page, click on the settings to add dynamic CMS content.

<figure><img src="../../.gitbook/assets/Screenshot 2024-04-11 at 5.53.16 PM.png" alt=""><figcaption></figcaption></figure>

Single reference fields are available immediately. Select the field you want to add to the page, and the CMS will automatically determine which referenced item it should use to obtain the information.
