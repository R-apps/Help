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

# Session Plugin

The "Session Plugin" allows you to memorize the user's sessions and effortlessly manage and manipulate data within your application until the user logs out. Within the session, you can control your user's access to the app. These parameters can be usernames, passwords, tokens, or other information.&#x20;

As users interact with your application, the plugin silently stores and manages essential data, ensuring a smooth and personalized user experience.

### How to Use?

Simply drag and access the plugin interface, where you can define and assign parameters based on your application's requirements. Configure the plugin and save your configurations.

Let's glance at which utility (method) to understand when and where to use.&#x20;

**Session Exist:** Use this method to keep track of logged-in users' details, maintaining their session data to provide a personalized experience without constant re-authentication.&#x20;

**Set parameters:** Use this method to tell the plugin to store a specific parameter by defining the parameter name and value.&#x20;

**Get Parameters:** Use this method to retrieve the set parameters using the parameter name to utilize them across the APIs involved in your application.

**Get UserName:** Use this method to retrieve the logged-in user's username.&#x20;

**Get UserId:** Use this utility to retrieve the logged-in user's user ID.&#x20;

{% hint style="info" %}
**Note**: By default, the plugin memorizes the username and role ID parameters. Any additional parameters you want the plugin to remember can be specified using the SET method and retrieved using the GET method.
{% endhint %}

{% hint style="info" %}
**Pro Tip:**

\-When you are dealing with the "Set" methods, specify the data type, value type, and value in the Input Configuration tab.

\-When you are dealing with the "Get" method, specify the data type and its scope of use (local or global) in the Output Configuration tab. Usually, this parameter information can be used within the API.
{% endhint %}
