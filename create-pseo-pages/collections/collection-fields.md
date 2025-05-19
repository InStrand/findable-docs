# Collection Fields

Collection fields define the types of content that go into your pages.

To configure your fields, select your collection, enter the Fields menu, and click ‘New field’.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdJr8ZSYhlVEcNm5aLkiy7DlQ6OEJRHugIZmoJXon24Bcix0EpN_tZjhclaXB_JugYmze9Vdo0YBEbY-hKHzZc0joamyqZZZ0zIonp0MrowyrHvSS-bAtX1EeVmOWwnXUdEl6yOAw?key=qZLMsj6pTYNc6US2FRF4Y9la" alt=""><figcaption></figcaption></figure>

There are different field types that take different inputs. Add all of the fields you need for your collection.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdQv_RUYwJ6zSTXdmkPTEXZy31zAP-QkX-CF1ne2lSh-3BWmSiwE5fwi1YsLKm9qWwYrCWaHHq4FEjpZ5qFFkygw_HU6b2CgbiHbO2X6qJkcRgKNCyoYnCC6XGtowd0dwjm7oRD?key=qZLMsj6pTYNc6US2FRF4Y9la" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
There are two protected fields used by Findable:

* `name`
* `slug`

`name` is the name of the item. Often this will be your page title, but it can be anything.

The `slug` is what appears in the URL when you’re on that item’s page.

Both of these fields can be edited within Findable, however they are automatically generated when you create a collection as they’re required items for the sync.
{% endhint %}

### Field Types

#### Text

Text, or plain text, is a simple textbox that takes a string of characters as an input. This is good for shorter content that doesn’t require any formatting, like captions, meta descriptions, and standalone headings.

#### Rich Text

Rich text allows you greater control over text formatting. This is useful for longer paragraphs, articles, and any other text that you’d like to style directly.

Within the Findable editor, you’ll be able to apply:

* Bold, italic, and underlining
* Heading levels from H1 to H6
* Ordered and unordered lists
* Blockquotes
* Code formatting
* Hyperlinks
* Embedded images

#### Number

Number fields take numeric inputs only. This can be used for phone numbers, pricing, ratings and more.

In general, if you plan to use number values for filtering or other calculations, a number field is your best choice. If you’d like to apply any formatting (for example, adding an area code in brackets to a phone number), you might choose to use a text field instead.

#### Date

Date fields allow you to select dates and times via a popup window. This is automatically converted into a format in the backend that websites commonly read, allowing you to display dates and times or apply filtering to your page.

#### Image

Image fields are perfect for banners, icons, and other image files that you might use on your page. Findable currently supports all image types available in Webflow, including GIF, JPEG, WEBP, AVIF, and SVG.

#### Relation

Relational fields are a power-up that allows you to create connections between items in different collections.

For example, a locations collection might include a relational field called venues that connects to a collection containing a list of bars in a city. For each location (a suburb), we can quickly assign which bars are in the area. When we go to design our page, the full list of bars in that area are automatically available to us with no additional filtering.
