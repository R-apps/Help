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

# Consuming REST APIs

This article explains how to consume a REST API.

### Configure REST API

To consume, click '![](<../../../.gitbook/assets/Create (5).png>)' in the Navigation Explorer and select **Consume REST API**. Then,

* Select the method and enter the endpoint URL.
* In the “General” tab: enter the API name, select an entity to map to it, choose the content type (parameter type: JSON/XML), and select the authorization type.
* In the “Data” tab: select the required input and output attributes. If your API deals with only one record, you can restrict it to a single row.
* Next, if there are any custom headers to employ, add them under the "Custom Headers" tab, by entering the key-value pairs.
* Then, enter the sample request and response in the respective tabs. Further, you can quickly eliminate the empty objects by enabling the "Remove empty tags" option.&#x20;

Check "Allow query parameters", to allow users to sort and filter data by appending them to the end of the URL, and then **Create**.

This creates an API. You can access it from the mapped entity in the Navigation Explorer. Open it to view its flow on the canvas. Now, you can modify the API as needed.

### Import API <a href="#import-api" id="import-api"></a>

To import an API, switch to the **Import** tab and choose the file in JSON, YML, or YAML format. Alternatively, you can manually enter the code using the **Raw Text** option.

Then, select the objects and methods before you import. The imported APIIt's that simple to import an API.
