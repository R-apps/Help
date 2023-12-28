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

The SQLPlugin is your go-to data-driven core plugin that makes handling data a breeze. It is your gateway to handling data dynamically, without needing complex coding.&#x20;

You can fetch and display specific data from your database effortlessly. You can update your app's content in real-time based on changes in data. It's great when you want specific information without having to go through the entire dataset.

#### How to Use?

* Simply Drag and Drop the SQLPlugin into your app's interface.
* Configure the plugin by specifying the data source. Fetch the tables (entities) and columns (attributes).
* Select the Query type, and then use our easy-to-use query builder to write the query you need, without having to deal with complicated code.&#x20;
* Validate your query and save your configuration.&#x20;

It's that simple.

#### Query Building

Here's a glance at SQL commands for CRUD operations:

* `SELECT` - extracts data from the database
* `UPDATE` - updates data in the database
* `DELETE` - deletes data from the database
* `INSERT INTO` - inserts new data into the database

{% hint style="info" %}
Utilize the "Ctrl+Spacebar" hotkey to retrieve a list of these SQL commands, then choose the desired one.
{% endhint %}

Sample query to insert data into an entity:

```
insert into entity_1 (CreatedDate,ModifiedDate,CreatedBy) values(?,?,?)
```

### SessionPlugin

### MakeServerURL

### PrivatePDM

### Logout

### MethodInvoker

### UMPlugin

### APIConsumer

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

