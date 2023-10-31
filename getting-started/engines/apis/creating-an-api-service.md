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

# Creating an API Service

### Create API Service <a href="#create-an-api-service" id="create-an-api-service"></a>

To create,

* Open the **APIs** engine, click'![](<../../../.gitbook/assets/Create (4).png>)', and select **Create API**.
* Give your API a unique name and select the entity you want to map to it.
* Next, select the input and output parameters (attributes).

That creates your API.

When you create an API, the services required to perform CRUD (Create, Read, Update, Delete) activities are automatically added to assist you in handling data.

After you create an API service, build a flow for it.

### Implement API Logic <a href="#build-api-flow" id="build-api-flow"></a>

Every API comes with a default flow attached to it. Double-clicking the API opens it on the canvas. You can customize it to meet your specific API requirements or create a new flow from scratch. Be sure to include "Start" and "End" nodes in your flow in both cases.

The three methods to build a flow for your API:

1. [Creating the flow from scratch](creating-an-api-service.md#method-1)
2. [Using Flow templates](creating-an-api-service.md#method-2)
3. [Importing an API flow](creating-an-api-service.md#method-3)

#### **Method 1: Building from scratch**

Use the flow elements available in the Toolbox to build an API flow.&#x20;

Begin by adding a **Start** node. Then, search for the elements required for your API and drag them onto the canvas. After you add all the necessary tools to your flow, complete it with an **End** node. Then, configure[ ](api-configuration.md)the flow elements as you want them to behave.

Alternatively, you can use the quick access tools to ease your work. These tools include options to configure and change the plugin type. To access the quick-access toolbar, click on an element in the canvas, hover your mouse over the arrow, and you'll find quick actions to add activities and configure them.

<div align="left">

<figure><img src="../../../.gitbook/assets/Quick-access toolbar for plugins.png" alt=""><figcaption></figcaption></figure>

</div>

While building a flow for your API, you may be required to group the elements, duplicate them, and so on. All such actions that you can take on them are available in the canvas toolbar.

* To group the flow elements, select them on the canvas and click![](https://reasyapps.com/forum/wp-content/uploads/2022/07/Group-1.png).
* To create a copy of an element or a group, select it on the canvas and click![](https://reasyapps.com/forum/wp-content/uploads/2022/07/Duplicate.png).
* If you wish to save any customized element, select it on the canvas and click![](https://reasyapps.com/forum/wp-content/uploads/2022/07/Save-for-later.png).
* Should you wish to rearrange your flow, click![](https://reasyapps.com/forum/wp-content/uploads/2022/07/Beautify-1.png). Click **Rearrange** to start the beautification process, and keep clicking **Next** until the process reaches 100%.

#### **Method 2:**

Another way to build an API flow is by using templates. Click![](<../../../.gitbook/assets/More actions.png>)in the canvas toolbar, and select **Sample Templates**. Choose one from various templates available for different flow patterns, and import it to utilize. You can alter it to suit your needs. Be sure to save it if you have made any changes to it.

#### **Method 3:**

The last method is to import an existing flow for your API. Right-click your API and select **Import Flow**. Select the “.apiflow” file and import it. You can alter it to suit your needs.

After you finish building a flow for your API, **save** it.

### Configure Flow Plugins <a href="#pluginconfig" id="pluginconfig"></a>

Configure the plugins in your API flow to define what they should do. To configure, click![](<../../../.gitbook/assets/Plugin settings.png>)from the the quick-access toolbar. Configure the plugin and save your configurations. For instance, if your flow involves a "File Download" plugin, you need to configure in what format the file should be downloaded, file type, file name, and its data type.

<div align="left">

<figure><img src="../../../.gitbook/assets/Plugin Configuration.png" alt=""><figcaption></figcaption></figure>

</div>

Similarly, configure all the plugins in your flow. Finally, save your flow.&#x20;

### Validate API Flow <a href="#validate-api-flow" id="validate-api-flow"></a>

Validating the flow helps you ensure there are no errors or faulty connections.

Once your flow is ready, validate it by clicking<img src="../../../.gitbook/assets/Validate.png" alt="" data-size="line">in the canvas toolbar. As you initiate the validation, the platform flags any missing or faulty connections and highlights the plugins that are unconfigured.

### Test API

As a final step, click![](../../../.gitbook/assets/playback.png), to playback test your API to ensure it works as expected. Logs generated here help you debug and resolve them.&#x20;

{% hint style="info" %}
**Best Practices:**

1. Choose the right entity when creating an API, as you cannot change it later.
2. Rename each element before configuring it when adding one to the flow.
3. Make sure to configure all the plugins in your flow before validating it.
{% endhint %}

Now, your API is ready to use within the app. To make it available for other apps to consume, publish it. [click here](publishing-api.md), to refer to the publishing process.
