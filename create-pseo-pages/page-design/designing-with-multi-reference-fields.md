# Designing with Multi-reference Fields

Reference fields allow you to bring information from one CMS collection into another.

{% hint style="info" %}
If your collection items don’t include reference fields, make sure you’ve set them up correctly. See [Creating Reference and Multi-Reference fields](../connecting-webflow/creating-reference-and-multi-reference-fields.md) for more information.                        &#x20;
{% endhint %}

In Webflow, there are two types of reference fields:

* Single reference fields
* Multi-reference fields

Multi-reference fields are configured to link multiple items from another collection. For example, if a product falls within several categories defined in another CMS collection, you can select all of the applicable categories that apply to the item.

Multi-reference fields are easy to configure in the collection but require a few more steps in design.

Add a new Collection List element to use a multi-reference field on your page.

Select the reference collection from the drop-down list. Ensure you’re selecting the reference collection, not the original one.

<figure><img src="../../.gitbook/assets/Screenshot 2024-04-11 at 8.23.16 PM.png" alt=""><figcaption></figcaption></figure>

Place your element within the collection and style it as you usually would.

Click the settings to add a dynamic reference to the collection.

<figure><img src="../../.gitbook/assets/Screenshot 2024-04-11 at 8.23.43 PM.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
For more information on using multi-reference fields, [check out Webflow's documentation](https://university.webflow.com/lesson/multi-reference-field?topics=cms-dynamic-content).
{% endhint %}
