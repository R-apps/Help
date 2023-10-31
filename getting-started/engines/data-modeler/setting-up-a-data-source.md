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

# Setting up a Data Source

This article explains the process of connecting to an external database.

Reasy utilizes a PostgreSQL database, to help you place your structure and the data in it. To make your data available in your own database, set up a data source to create a connection that connects your app to the database you want to access.&#x20;

Reasy supports all database types, including Oracle, SQL, HSQL, and others.&#x20;

Here's how you can set up a data source:

* Access the **Resources** engine and select Creating a new source.&#x20;
* Give the resource a unique name to identify and a brief description to reveal its details.&#x20;
* Select the source type as “Data Source” and then select your database type.&#x20;
* Enter the database URL, username, and password.

Additionally, you can configure connection parameters under "Advanced Settings" such as:

* The maximum number of concurrent connections that can be made to the database (Max connection pool size)
* The minimum number of idle connections
* Connection timeout, idle timeout, and max lifetime

That’s it. Select this data source to connect to your database. After you connect to your database and opt to save your entities as physical entities, they get stored in your own database.

What if you need to encrypt sensitive information? The solution lies in employing column-level encryption, which ensures the security of your confidential data and mitigates the risk of data breaches. This encryption can be applied to all or selected columns within the database. To enable encryption, simply turn ON the corresponding option. Double-click on the table and drag the column(s) where you wish to apply encryption.
