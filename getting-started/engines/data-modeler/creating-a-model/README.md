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

# Creating a Model

The **Data Modeler** engine in Reasy helps you define the structure of your data. This article details the process of creating a data model from scratch.

Start by creating a model. To create,

* Open the **Data Modeler** engine and click '![](<../../../../.gitbook/assets/Create (6).png>)' in the Navigation Explorer.
* Give a name to the data model, and there you go.

Now, create entities (tables) to store your data. Also, if you have any pre-built entities, you can [import](https://reasyapps.com/forum/?ht\_kb=build-a-data-model#importentities) them here, based on your needs.

### Create Entities <a href="#create-entities" id="create-entities"></a>

<details>

<summary>Understand Virtual and Physical Entities</summary>

When you create an entity, it is stored as a template and referred to as a **Virtual Entity**. As these entities are just templates and not saved in any database, you cannot perform CRUD operations in real time. To do so, you’ll have to persist your entities associated with your app before you launch it; to make them accessible. By persisting, you’ll save your data to Reasy’s database which is called **Physical Entity**.

You can easily differentiate virtual and physical entities by the icons appended to entities in the Navigation Explorer.



</details>

To create an entity,

* Right-click the model and select **Add Entity**.
* Give the entity a name.

You can save them as physical entities by enabling “Save as Physical Entity”. You also have an option for adding more entities. Check the option (![](<../../../../.gitbook/assets/image (3).png>)) before you an entity, it will save you from repeating the same process for creating another entity.

Alternatively, you can add an entity by clicking ‘+’, next to the model you created. Entities get vadded with default names: entity1, entity2, and so on; so it's a good practice to rename them as you add them.

Moreover, you are facilitated with a few prebuilt entities such as products, orders, students, and more. To import them, right-click and select **Prebuilt Entities,** then choose the entity(s) you wish to import.

Likewise, create/import the entities required for your app data.

Next, add attributes to the entity created.

### Add Attributes <a href="#add-attributes" id="add-attributes"></a>

Attributes are the columns in your. Every entity that you create will have a few attributes such as, "CreatedDate", "ModifiedDate", and "UniqueId" with appropriate data types.

To add an attribute,

* Right-click the entity and select **Add Attribute**.
* Give it a unique name and select the data type.
* If it’s a key attribute, mark it as a key attribute.
* If it’s used for computations, mark it as a computation attribute, and provide a default, minimum, and maximum values. And, define the computation formula.
* Add validations to the user inputs; that you may require to validate the entries as they come in.\
  To add condition-based validations, turn on the option, and add conditions. You get the expression as you start setting the validation rules. Once done, test these validations using **Test** to see how those work.

{% hint style="info" %}
**Tip**: Alternatively, you can add attributes by clicking ‘+’ next to **Attributes** in an entity on the canvas.
{% endhint %}

{% hint style="info" %}
**Note**: Do not enter any spaces between the characters when you name an attribute.\
An attribute can be set either as a “Key Attribute” or as a “Computation Attribute.”
{% endhint %}

When you add an attribute, the services needed to perform CRUD operations on that attribute will get created by default. However, you can edit them if they aren’t the key attributes. Aside from these, you can [add services](https://reasyapps.com/forum/?ht\_kb=build-a-data-model#addservices) as and when you need them.

Likewise, add all the attributes that you need in your entity.

{% hint style="info" %}
**Note**: Do not add any spaces between the characters when you name a model.
{% endhint %}
