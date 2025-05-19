# Creating Reference and Multi-Reference Fields

A powerful feature of both Webflow and Findable is the ability to use Reference fields. These fields map items in different data collections together, allowing you to draw on the properties of a connected field in your CMS or Findable collections.

Webflow’s API currently has a few restrictions on programmatically creating reference fields. Their development team is aware of and working on this shortcoming, but in the meantime, syncing reference fields from your content store to Webflow requires a very small manual intervention.

The manual process should only take a few minutes.

{% hint style="success" %}
**TL;DR:** Add reference fields to your CMS collection and match the name to your content store.
{% endhint %}

First, set up your Findable collections and initiate your first sync.

You should now have CMS collections on your Webflow site that match what you’ve set up in Findable.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeTEXGY7m_MC2ayHfofmBX_MQqy8JjJGsl45REu6jM6oG8iJyfo27vbZrXWNdFrgDH5mYB2vvVK3Vw8mQRJfwESTdyTmjhNHajvdfQTyjR7xYK0MQ9NwNO7Zr_GQAXdGTc6FVk14Q?key=qZLMsj6pTYNc6US2FRF4Y9la" alt=""><figcaption></figcaption></figure>

Click into a collection and select an item. If you're publishing a reference field, you'll see a plain text field in there instead.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXd1mGrZjowetBXAAsvAfLsItxSBmkoh2vV_0d3ieWuv7g9hpihP4iF0tZfgQK1NiVIA7JdbvW6UHnvv0Sm7oGw_PXmNNUpH8196_kYWPhj177MR6Y4tcEmTHkotjLLTBFqIqOOChQ?key=qZLMsj6pTYNc6US2FRF4Y9la" alt=""><figcaption></figcaption></figure>

You can also see these in the collection settings.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfnyU4HCJA2sklsxFlbzjdRQR68uGNvrfiPqgmnnOJyIiqIbm8QgSo0yTu1qp4xqy17CLws9uub5ychoUbKvGw3AlxH9VDOyYe6khxXaCsK4ylYAw8P_qdzCIlUvnm5VYR1kvKu?key=qZLMsj6pTYNc6US2FRF4Y9la" alt=""><figcaption></figcaption></figure>

The field name instructs you on how to configure your reference fields.

* `Category` - the name of the collection you'll be referencing
* `(Multi-Reference)` - the type of reference field you'll need to create

To get started, click 'Add New Field'

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfnUasnnejOBWBqv5-YwDMmLVhj3S5GPJOKlCBa5QcUypaexKCBW_yPaL89TBWxnyzBRZtSIgQcIzhnTzbBtiMuw23MtPOWD7mMLgigVqB55rNBOlKdU8ymRDJysh3Yr-1Hu1MhJg?key=qZLMsj6pTYNc6US2FRF4Y9la" alt=""><figcaption></figcaption></figure>

Add the reference field type indicated by the placeholder (the part of the name in brackets).

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcfpEjFeoAZmijoqk5vjNRdAwvDbfZxDsKfr5O-Ys6wYioPFbl1UIBA6yCPbcv0s-2FBjNgx_-TjdRQx0bUdIGsJxqYXcR_ASaRJSCL_Lv13kjld15u5-iTJw_mxXSKZAcPDyUmIQ?key=qZLMsj6pTYNc6US2FRF4Y9la" alt=""><figcaption></figcaption></figure>

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfR8w3e42UnGDbNl5Rl1xVdWa6iEQaXGe3BDipfF0TUWKf9dkX8gCOpG_P0IgU32FR7uP6YaVqtZUJ5L06NRu5vBBc7k2dSREsDBEfebTdnAQWRj462Rsjig68oiakxMvy_0lSu?key=qZLMsj6pTYNc6US2FRF4Y9la" alt=""><figcaption></figcaption></figure>

Give the field a label (also indicated in the title) and connect it to the relevant collection.

Make sure you do this for all Findable collections in your CMS.

When Findable performs the next automatic sync, your references will be mapped dynamically into Webflow, giving you access to them within the parent collection.
