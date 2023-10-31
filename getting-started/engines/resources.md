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

# Resources

The **Resources** engine helps you create, configure, and manage the sources for the API, Email, data, and other plugins. Using sources outside of plugins reduces the effort required to configure the source each time a plugin is used. A one-time configuration is all you need. If you use the source repeatedly, you can make a change once, and it will apply to all.

As each source has different configurations, let’s see how to create a data source.

* Go to the **Resources** engine and click **Create new source**.
* Give it a name and select the source type as “Data Source”. Here, we’re choosing the “Oracle” database.
* Enter the URL (to identify and connect to the specified database), username, and password to access it.
* In the **Advanced Settings**, you can set the following:
  * Maximum connection pool size (Maximum number of connections supported by your database)
  * Minimum idle connection (No. of active connections that can remain idle)
  * Connection timeout (The time frame to establish the connection)
  * Idle timeout specifies the time that a connection remains idle in the pool)
  * Max lifetime (Maximum time that a connection is allowed to stay in the pool)
* As a last step, test the connection and save it.

As well, you can create as many sources as you need. All the sources you create will appear here.

* To view, click![](https://reasyapps.com/forum/wp-content/uploads/2022/07/View.png).
* To edit, click![](https://reasyapps.com/forum/wp-content/uploads/2022/07/Edit.png). Modify and update it.
* To delete, click![](https://reasyapps.com/forum/wp-content/uploads/2022/07/Delete-policy.png).
* To refresh it, click![](https://reasyapps.com/forum/wp-content/uploads/2022/07/Reset-source.png). Refreshing the source updates the data selected from a database location if it has changed.

If you’ve multiple sources, you can test them all at once, regardless of the source type. Click **Test all sources**; the platform tests their connectivity and gives you the report as you see here.

Also, you can audit the source configurations to check how they work.&#x20;
