---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Publishing API

When your API service is ready for the external world to consume, publish it. By publishing, you make it available for external apps to take advantage of the functionalities you’re exposing with your API.

To publish an API, right-click it and select **Publish**. The API gets published. You can notice it by its status icon. Alternatively, if you have the API opened on Canvas, you may click![](../../../.gitbook/assets/Publish.png) in the Canvas toolbar to publish your API.

{% hint style="info" %}
**Note**: Make sure your API has a valid flow before you publish it.
{% endhint %}

Now, to add an extra layer of security, you can authenticate your API. To learn how, [click here](api-authentication.md).

#### Test  Public API <a href="#test-api" id="test-api"></a>

Then, you can test your API service to see how it responds to the sample requests.\
Follow these steps to test your API.

* Open the published API and click ![](<../../../.gitbook/assets/Test API.png>)in the canvas toolbar. This will display the API's information.
* Select the API service type (REST or SOAP)
* Add the content and accept types in “Service Headers”.  The default is "application/json". If that's not your API content type, you can add a header. To add, click **Add Header** and enter the key-value pairs.
* Now, create a sample request using the Request Template. If your API includes downloading a file, check the option “This service may download a file”. Similarly, create a Response template.&#x20;

Now, send a request, and you will get the response within the defined Response Template.
