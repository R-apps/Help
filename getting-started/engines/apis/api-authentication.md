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

# API Authentication

After you publish your API, you can secure its integrity by authenticating it using any of these methods:

* **HTTP Basic Auth**\
  A method of authenticating clients where the server checks their username and password against a database of authorized users.
* **OAuth**\
  An open authentication that uses authorization tokens to prove consumers’ identity. This method allows your consumers to access your information without requiring them to provide their passwords.
* **Access Token**\
  A Token-based authentication allows you to include an access token for each API call. These tokens help you uniquely identify the API consumers and grant them access to information.
* **None**\
  No authentication. Anyone can consume your API without having to authenticate.

Let’s see how to authenticate an API. Open the API and go to its **Properties** in the right pane. Here,

* Select your API type (REST/SOAP)
* Choose the authentication type that you require for your API.
* Choose the HTTP method that specifies the desired action that a resource can perform.
* Enter the valid API URL (An HTTP request or an end-point URL where the user can communicate with the API).
* Select the request (**Accepts**) and response (**Produces**) parameter type (JSON/XML).
* Select the log level.

**What are Log Levels, and how do they help?**

The levels of logging classify various log events from each other based on their severity. Log levels help you regularly monitor your API for issues. Here’s the list of available log levels with quick info on how they help you:

* **Solution Level –** This log level captures every action/event.
* **Off** – This level doesn’t log anything. It just turns off the logging.
* **Error** – This level shows the issues preventing your app from functioning effectively. These are mostly runtime errors or unexpected conditions.
* **Warn** – This log level flags any issues that might occur unexpectedly or possibly happen at any time. A few times, these may prevent some processes from operating.
* **Info** – Logs every event, describing what occurred. In normal operations, you don’t need to deal with these logs.
* **Debug** – The logs at this level give detailed information. These help to diagnose and troubleshoot any issue.

{% hint style="info" %}
**Tip:** Unless you require a particular log level, we recommend using the 'Solution Level' log for private APIs and 'Debug' for public APIs.
{% endhint %}
