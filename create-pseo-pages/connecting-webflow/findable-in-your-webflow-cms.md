# Findable in your Webflow CMS

Once you initiate your first sync, Findable will begin adding content to your CMS. This includes new collections and items. These will be visible immediately after the sync completes.

<div data-full-width="false"><figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdrmV_Z3qHbf9Vf9F-5drIapoEvI0LQqpwclne1a6tnIXMKdS1fKJY3RqPSdVX4nz5rZFdnkJLKUGmNEGC1vvOV8cHYlqvm9-VQQMp3inIF_MXArOo827bTJhrN11I-zyMzL84eMg?key=qZLMsj6pTYNc6US2FRF4Y9la" alt=""><figcaption></figcaption></figure></div>

Each collection in Findable will create a corresponding CMS collection. The names of these collections will match what you set up in Findable.

Each collection will contain the published items from that collection in Findable. A corresponding item will be created in your CMS on the next sync whenever you add a new item to Findable.

Likewise, deleting or unpublishing an item from Findable will remove the corresponding item from the CMS.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcGNBNboxMZ1b5tba_38K40FliqjhQhI4V3DKc5mvrrd7BHaWYqkzU0KPPpA7nUQ1vkhT7As2FxGIuyRGF_q5DRMT1rvVn_DN5amlinHWVvRz2ubsvQyYfTQ5x2V9EuwaupcST3VA?key=qZLMsj6pTYNc6US2FRF4Y9la" alt=""><figcaption></figcaption></figure>

Each item gets its fields from your Findable collection.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcss41KrN_Ib4u6HhRqhjoCYF73ijjLC0HrUp_rt6oc9_3CPNLXb-LcCgviKb0kQe3MAw3UPz4qpHZUm3lTtVRBPZK8G6K3l3hgwIhLScHcfyFL3GPkJgtlessFkedT2NZCCP3w?key=qZLMsj6pTYNc6US2FRF4Y9la" alt=""><figcaption></figcaption></figure>

When you change data in Findable, it will update the CMS on the next sync.

{% hint style="warning" %}
If you’d like to update the content in your CMS, make the changes in Findable, not the CMS. Any changes made within the CMS will be overwritten during the next sync.
{% endhint %}

Webflow’s API limitations mean that Findable cannot create reference fields automatically. When you perform the first sync, you’ll need to make these manually. Read the [Creating Reference and Multi-Reference fields](creating-reference-and-multi-reference-fields.md) section for more information.
