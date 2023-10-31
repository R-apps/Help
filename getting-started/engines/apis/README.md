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

# APIs

API (Application Programming Interface) services let apps connect and interact seamlessly, enabling data exchange between them. APIs often serve as a link between your app's frontend and backend. APIs work on a Request-Response model, in which the client sends a request and the server responds with a response.

APIs are used to retrieve data, send data, perform specific actions, or integrate third-party services.

APIs typically use well-known protocols (SOAP or REST), which define communication standards, processes, and data formats. REST APIs provide much greater flexibility, permitting data to be sent in a variety of formats, including JSON, HTML, Python, and Media, than the SOAP protocol's structured XML data format. The REST protocol is used for all APIs you build in Reasy. However, in light of the diverse app needs, Reasy provides you with the option to select the suitable protocol when publishing it for consumption by external applications.

In Reasy, APIs are referred to as “Public” and “Private”, where

* The **Private** APIs act as microservices and are accessible within the app.
* The **Public** APIs act as web services and allow external applications to consume them.

APIs remain “Private” until you publish them. Once published, they become “Public”. When we create APIs, they’re assigned a status icon. Each represents a different status.&#x20;

Here’s a quick look:

<table data-header-hidden data-full-width="false"><thead><tr><th width="101"></th><th></th></tr></thead><tbody><tr><td><img src="../../../.gitbook/assets/Private API without flow.png" alt=""></td><td>Private API without dataflow</td></tr><tr><td><img src="../../../.gitbook/assets/Private API with flow.png" alt=""></td><td>Private API with dataflow</td></tr><tr><td><img src="../../../.gitbook/assets/Deactivated API.png" alt=""></td><td>Published but not activated</td></tr><tr><td><img src="../../../.gitbook/assets/Published API.png" alt=""></td><td>Published and Activated</td></tr></tbody></table>

The **APIs** engine provides access to the default CRUD (Create, Read, Update, Delete) services established for each entity in your data model. These services let you manage your data efficiently and effortlessly; all you have to do is configure them, and you are ready to go.

{% hint style="info" %}
These default APIs are not allowed to change their flow or properties. You can, however, duplicate them to make them perform as needed for your app.
{% endhint %}
