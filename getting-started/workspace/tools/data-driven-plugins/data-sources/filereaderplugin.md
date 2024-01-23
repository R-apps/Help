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

# FileReaderPlugin

The "FileReader" plugin allows your app to read files and extract data from them. It is your go-to tool to effortlessly read and process files within your app. Integrate the File Reader into automated workflows to dynamically load content or documents based on user-uploaded files; and process them without manual intervention.&#x20;

{% hint style="info" %}
**Pro Tip:** Ensure that your users are aware of the accepted file formats to streamline the reading process.
{% endhint %}

#### How to Use?

Drop the File Reader plugin into your API flow. Open its configuration and specify the file type. Here's the summary of each file type to help you understand what it is and when to use it:&#x20;

* **CSVFileReader**: This reader type reads Comma-Separated Values (CSV) files and tabular data with rows and columns. Choose this reader if your app requires data analysis, CSV data migration to databases, or report generation.
* **ExcelFileReader**: This helps read Microsoft Excel files (XLS) effortlessly. It's adept at handling spreadsheet data with multiple sheets and formatting. Use this reader to import data from Excel files.
* **JSONFileReader**: This reader type reads JavaScript Object Notation (JSON) files, a lightweight data interchange format used for data storage and exchange between systems. Use it in APIs that utilize JSON for data exchange.
* **XMLFileReader**: This reader type helps in handling eXtensible Markup Language (XML) files, a format used to store and transport structured data. Use it in web services that utilize XML for data exchange or configuration.

For static file header(s), specify them, including their data types and whether or not they are required. Specify the attribute that holds the file in the Input Configuration tab. Extract to configure the attributes that hold the defined headers in the Output Configuration tab.
