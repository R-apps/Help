---
description: Smart way of creating a data structure
---

# Importing a Data Model

Instead of creating entities from scratch, you can quickly import one from external sources. \
To import a model, create a model and open it on the canvas. Next, click![](https://reasyapps.com/forum/wp-content/uploads/2022/06/Import-model.png)in the canvas toolbar, and select the source from which you wish to import. You can import a model from:

* [Model file](importing-a-data-model.md#import-model-from-model-file)
* [XLS file](importing-a-data-model.md#import-model-from-xls-file)
* [Structure from XLS file](importing-a-data-model.md#import-model-structure-from-xls-file)
* [Database](importing-a-data-model.md#import-model-from-database)

### **Import Model from Model File**

Choose the model file in “.pdm” format or drag it here.

Then, select the entities and mark key attributes; and enable “Save as Physical Entities”, to save them to Reasy's database.

<img src="../../../.gitbook/assets/import model from model.png" alt="" data-size="original">

### **Import Model from XLS File**

This feature helps when working collaboratively.\
Let’s understand it with a use case. If you’re working on a data model and a peer attempts to modify it, s/he is not permitted to do so. You can facilitate your peer work on it by exporting it into an Excel file and sharing it. Then, your peer can make the necessary changes and import them, as shown below.

To import a model into an Excel, choose the Excel file and click **Next**. Then, select the columns (attributes) and their data types. Additionally, you can specify the key attribute as well.\
– To import the model along with the data, enable “Import With Data”.\
– To save them as physical entities, enable “Save as Physical Entities”.

### **Import Model from Database**

Select the datasource and choose the tables (entities). Then, select the attributes that you require.

{% hint style="info" %}
**Note**: If you import an existing entity or a different one of the same name, it merges with the existing entity by adding additional fields, if any.
{% endhint %}
