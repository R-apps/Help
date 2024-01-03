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

# Data Sources

Data sources are used to indicate where the input data for a process comes from, what action it must perform, and where the output data goes. Reasy offers you the opportunity to transform a data source from one type to another with the click of a button.

Here are the data sources that Reasy offers:

### SQLPlugin

The "SQLPlugin" is your go-to plugin that makes handling data a breeze. It is your gateway to handling data dynamically without needing complex coding.&#x20;

You can fetch and display specific data from your database effortlessly. You can update your app's content in real-time based on changes in data. It's great when you want specific information without having to go through the entire dataset.

#### How to Use?

* Simply drag and drop the SQL plugin into your app's interface.
* Configure the plugin by specifying the data source. Fetch the tables (entities) and columns (attributes).
* Select the query type, and then use our easy-to-use query builder to write the query you need without having to deal with complicated code.&#x20;
* Validate your query and save your configuration.&#x20;

It's that simple.

#### Query Building

Here's a glance at SQL commands for CRUD operations:

* `SELECT`extracts data from the database
* `UPDATE`updates data in the database
* `DELETE`deletes data from the database
* `INSERT INTO`inserts new data into the database

{% hint style="info" %}
Utilize the "Ctrl+Spacebar" hotkey to retrieve a list of these SQL commands, then choose the desired one.
{% endhint %}

Sample query to insert data into an entity:

```sql
insert into entity_1 (CreatedDate,ModifiedDate,CreatedBy) values(?,?,?)
```

Similarly, you construct the queries using our handy list of SQL commands.

## SessionPlugin

The "Session Plugin" allows you to memorize the users' sessions and effortlessly manage and manipulate data within your application. You can dynamically control your app's behavior based on user interactions and system events. These parameters can be usernames, passwords, tokens, or other sensitive information.&#x20;

As users interact with your application, the plugin silently stores and manages essential data, ensuring a smooth and personalized user experience.&#x20;

#### How to Use?

Simply drag and access the plugin interface, where you can define and assign parameters based on your application's requirements. Configure the plugin and save your configurations.&#x20;

Let's glance at which utility to understand when and where to use.&#x20;

**Session Exist:** Use this utility to keep track of logged-in users' details, maintaining their session data to provide a personalized experience without constant re-authentication.&#x20;

**Set parameters:** Use the "Set Parameters" utility by defining the parameter name and setting its value based on user input or system events.&#x20;

**Get Parameters:** Use the "Get Parameters" utility to retrieve and utilize these values across various sections of your application, by defining the parameter name and setting its value.&#x20;

**Get UserName:** Use this utility to retrieve the logged-in user's username.&#x20;

**Get UserId:** Use this utility to retrieve the logged-in user's User ID.&#x20;

{% hint style="info" %}
**Note:**&#x20;

\-When you are dealing with the "Set Parameters" utility, specify the data type, value type, and value in the "Input configuration" tab.

\-When you are dealing with the "Get" utility, specify the data type and its scope of use (local/global) in the "Output Configuration" tab.
{% endhint %}

### MakeServerURL

The MakeServerURL plugin is perfect for making dynamic server URLs. You don't have to manually change the URL anymore. You can simply use the MakeServerURL plugin to handle it for you. You can use the MakeServerURL plugin to handle it easily. It allows you to change server URLs on the go, making your app adaptable to different environments. It's perfect when you choose to use a URL to view or download a file.

#### How to Use?

Just drag and drop the MakeServerURL plugin into your app's workflow. Choose the source file and configure the rules to generate a dynamic URL in the plugin settings. The plugin creates a server URL based on your settings, so your users can easily access the correct destination.

### PrivatePDM

<>

### Logout

The "Logout" plugin lets users end their session. You can use it to let your users log out manually or automatically when their session times out or when they're done using your application, like after submitting a form or updating information.

#### How to Use?

Just drag and drop the plugin into your app's interface. Customize the settings to define when and how a specific user can log out. You can even define success and failure actions and make the result appear locally or globally. This allows you to offer a personalized experience based on your application's requirements.

### MethodInvoker

The "MethodInvoker" plugin makes it easy for you to invoke/call methods on objects and classes in your app, and work with data in real time. You can pick a method, enter parameter values, and run it. This plugin makes complex tasks easier without any coding. It can run specific methods easily with just a few clicks.&#x20;

You can use it to call an API and get data for your app. The plugin is great for APIs that don't have good documentation. It lets you try out different methods and parameters.

#### How to Use?

Simply drag and drop the plugin onto your app's canvas. Select the entity and the method to invoke in your app's workflow. Configure the necessary parameters and there you go.

### UMPlugin

The "UM" plugin comes with a range of services to let you manage users, their accounts, and their information within your app. It's perfect for apps requiring user registration and profile creation, such as social platforms, forums, or membership-based sites.&#x20;

#### How to Use?

Drag and drop to include the plugin in your API, select the required service, and configure the necessary parameters. You can even choose to display the fetched details locally or globally.

{% hint style="info" %}
**Note:** \
**-** When you are attempting to fetch or update users' information, you will need to select the parameters to fetch and configure them in the Output configuration tab.\
\- When you are attempting to perform actions such as 'Lock User', 'Deactivate User', 'Delete User', and 'Change Password', you need to configure the necessary parameters in the Input configuration tab.
{% endhint %}

### APIConsumer

The APIConsumer core plugin helps you connect and use external services or data in your app. This plugin helps you easily integrate services such as payment gateways, social media platforms, and data providers into your applications. It supports both REST and SOAP API formats.

#### How to Use?

Simply drag and access the plugin interface, then enter the API URL you want to use. Provide the format, URL, methods, and content type. You can include service headers like fixed headers, dynamic headers, or response headers. Add request and response templates and save the API settings. Further, you can choose to display and use the response code locally or globally.

### EmailReaderPlugin

### FileReaderPlugin

### PropertyReader

### FileDownloadPlugin

### FileWriterPlugin

### JsonUtils

### JoinPlugin

### FileWriterService

### DateUtils

### EmailSending

### EncryptDecrypt

### StringUtils

### FileUtils

