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

# FileWriterPlugin

The "FileWriter" plugin makes it easier to create and update files in your app. This plugin's intuitive interface makes file management a breeze. You can automate the process of generating new files on the fly, specifying formats and extensions according to your needs, and updating existing files. This plugin supports various file formats, including CSV, EXCEL, JSON, and XML, enabling versatile file handling.

You may consider using this plugin to:

* save form submissions directly into files for organized data management,&#x20;
* export dynamic data, such as reports or analytics, into user-readable files, and more

#### How to Use?

Drag the File Writer plugin into your API flow. Choose an output file format and select an option to add the content received from the user's input—select "New file" to generate a new file or "Existing file" to add the user's input to an existing file.&#x20;

{% hint style="info" %}
To add dynamic content to an existing Excel file, select "Custom Sheet" and provide the sheet name into which the data has to be appended.
{% endhint %}

Next, if you would likely use the default headers, enable the "Use default headers" option; otherwise, specify the file headers in sequence for custom headers. Additionally, you can set font styles for the header and body separately if the output format is Excel.
