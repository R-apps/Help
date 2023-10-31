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

# Manage API Services

This article tells you how to manage an API service.

### Search API Services

Search for an API service by its name if you have multiple. The platform returns the search results as you type.

### Filter API Services

Filter your API services for a classified view by clicking![](https://reasyapps.com/forum/wp-content/uploads/2022/06/Filter-API.png). Also, you can view:

* The entities mapped to the APIs in your app
* The screens to which the APIs are bound
* The user(s) who created these APIs
* The Modified date

### Export API Flow

To export an API’s flow, right-click and select **Export flow**. You get the flow in your local storage in “.apiflow” format.

### Create a copy of an API Service

To duplicate an API service with desired configurations, right-click it and select **Duplicate**. You get a copy of that API.

### Set API Expiry Time

For the public APIs, you can set the expiry time to make an API available only for a certain period. To do so, right-click the API and select **Set Expiry Time** to set the date and time.

### Delete an API Service

If the API services are no longer in use, you can delete them.

To delete an API, right-click it and select **Delete.** If that API is bound to your app’s screens, the platform forbids the action and shows you the screens to which the service is bound.

### Download API Document <a href="#download-api-document" id="download-api-document"></a>

API documents provide intermediary applications with a smooth developer experience. It’s a primary resource that explains what is possible with your API and how to get started.

To download, open the API, click![](<../../../.gitbook/assets/More actions (4).png>)in the canvas toolbar, and then select **Download Doc as PDF**. A PDF document will be downloaded to your default downloads directory in local storage. \
To download the API in XML format, select **Download WSDL**.

{% hint style="info" %}
**Note:**

1\. The default CRUD services created for the entities are forbidden to edit or rename. However, you can alter their flow.\
2\. As you publish an API, it gets activated. To deactivate it, right-click and select **Deactivate**. To reactivate it, select **Activate**.\
3\. You can set an expiry time only for public APIs.
{% endhint %}
