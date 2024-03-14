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

# JsonUtils

The "JsonUtils" plugin is a handy plugin that simplifies manipulating the JSON data with its variety of services. It is often used in API response processing, dynamic data modification, and extracting specific information from complex JSON structures.

This plugin offers a variety of services to let you effortlessly [parse ](#user-content-fn-1)[^1]or [stringify ](#user-content-fn-2)[^2]JSON, compare JSONs, convert JSON format, and more. Let's go over each service that this plugin offers.

### JSON to-JSON

This service enables you to manipulate JSON data quickly and effortlessly. You can remove unnecessary data from a JSON file by adding the necessary filter conditions and even replacing keys to match your interface or specific requirements. You can also delete all other keys by clicking "Remove other keys."&#x20;

This JSON-to-JSON conversion is useful for APIs or microservices that accept or return JSON data in a specific format.

### JSON to XML

This service converts JSON data into the Extensible Markup Language (XML) format. It converts JSON objects, arrays, and values into their corresponding XML elements, attributes, and text nodes, with the specified parent name. In addition, you can replace the keys with the required values and remove the unnecessary ones.

It is beneficial when you need to exchange data with systems or services that rely on XML-based communication protocols, such as SOAP (Simple Object Access Protocol) or older web services.

### XML to JSON

This service converts XML data into JSON format. It parses the XML document and creates a corresponding JSON object, facilitating data exchange and integration with systems that expect JSON input. You can also choose to replace the keys with the required values and remove the unnecessary ones while converting.

### XML to XML

This service enables you to manipulate XML data quickly and effortlessly. You can also choose to modify the XML structure by replacing the keys with the required values and removing the unnecessary ones while converting.

Converting XML data structure into a different XML schema required by a downstream system or application.

### Merge Objects

This service merges two or more JSON objects into a single one. You can specify the number of objects to merge, choose the output format (XML), decide whether to allow duplicate values, define output keys, set filtering conditions, and replace keys with specified values while removing unnecessary ones. Based on your selections, the service merges the objects accordingly.

This service helps in merging JSON objects with varying structures into a standardized format, simplifying data processing.

### Merge Arrays

This service works similarly to merging objects, with the exception that it merges arrays of objects instead. This service merges two or more JSON arrays into a single one. It concatenates array elements while preserving their order. You can specify the number of objects to merge, select an output format (XML), allow duplicate values, define output keys, set filtering conditions, replace keys with specified values while removing unnecessary ones, and sort the keys in ascending or descending order.

### Merge Arrays by Index

This service merges two arrays by index, combining elements at corresponding positions in the arrays. It creates a new array where each element is the result of merging the elements from the same index in the input arrays.



## How to Use

Add the plugin to your API flow and select the utility based on the operation you want to make on JSON data. Set up the plugin by configuring input and output parameters based on your data processing needs.

[^1]: Converting the data in a String to JSON

[^2]: Converting the JSON objects into a String
