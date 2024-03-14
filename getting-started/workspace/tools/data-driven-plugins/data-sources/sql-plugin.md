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

# SQL Plugin

The "SQLPlugin" is your go-to plugin for easy data management. It is your gateway to dynamically handling data without the need for complex coding. This plugin allows you to connect to a database and create, read, update, and delete specific data from your database in real time.

### How to Use?

* Simply drag and drop the SQL plugin into your app's interface.
* Configure the plugin by specifying the [data source](#user-content-fn-1)[^1]. Fetch the tables (entities) and columns (attributes).
* Select the query type, and then use our simple query builder to build the query you require without having to deal with complicated code.

{% hint style="info" %}
**Tip**: Before saving your configuration, validate the query for its accuracy.
{% endhint %}

It's that simple.

### Query Building

Here's a glance at SQL keywords for CRUD operations:

* `CREATE`creates a new entity in the database
* `SELECT`extracts data from the database
* `UPDATE`updates data in the database
* `DELETE`deletes data from the database
* `INSERT INTO`inserts new data into the database

{% hint style="info" %}
**Tip**: Utilize the hotkey "Ctrl+Spacebar" to retrieve a list of these SQL keywords, entities, and attributes to build queries quickly and effortlessly.
{% endhint %}

Here are the sample queries for CRUD operations:

{% code title="Query to create an entity:" %}
```sql
create enity_name (ProductId,ProductName,Category,PurchaseDate) values(?,?,?,?)
```
{% endcode %}

{% code title="Query to select data:" %}
```sql
select CreatedDate,ModifiedDate,CreatedBy,UniqueID from entity_1  where UniqueID=?
```
{% endcode %}

{% code title="Query to insert data:" %}
```sql
insert into entity_1 (CreatedDate,ModifiedDate,CreatedBy) values(?,?,?)
```
{% endcode %}

{% code title="Query to update data:" %}
```sql
update product_info set Category='Infrastructure'    
```
{% endcode %}

{% code title="Query to delete a record:" %}
```sql
delete from entity_1 where UniqueID=?
```
{% endcode %}

{% hint style="info" %}
**Hint**: When dealing with static data, enter the values; when dealing with dynamic data, insert '?' symbols equal to the number of attributes. When dealing with both static and dynamic data, specify values and use '?' in combination.
{% endhint %}

[^1]: Configure this data source in the **Resources** engine that connects to your target database.
