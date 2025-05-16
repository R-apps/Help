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

* To view, click <img src="../../.gitbook/assets/View resource.png" alt="" data-size="line">.
* To edit, click ![](<../../.gitbook/assets/Edit resource.png>) Modify and update it.
* To delete, click ![](<../../.gitbook/assets/Delete resource.png>).
* To refresh it, click ![](<../../.gitbook/assets/Refresh resource.png>). Refreshing the source updates the data selected from a database location if it has changed.

If you’ve multiple sources, you can test them all at once, regardless of the source type. Click **Test all sources**; the platform tests their connectivity and gives you the report as you see here.

Also, you can audit the source configurations to check how they work.&#x20;

### Cache Datasource

A high-speed temporary local storage that holds previously fetched data. It is especially helpful when retrieving data from large datasets. Instead of making repeated calls to an external API or database, the cache serves data from memory or local storage — making your app faster and more efficient.&#x20;

As it is significantly faster than querying a database, use it when you want to reduce latency and improve response times.&#x20;

To use it, you must connect to a cache datasource and enable it in your API call.

<div align="left"><figure><img src="../../.gitbook/assets/Cache in API.png" alt="" width="375"><figcaption></figcaption></figure></div>

Once enabled, it fetches data from the original datasource and stores it locally. Whenever a request is made, the app reads from the cache instead of fetching it from the connected datasource - reducing API hits and minimizing costs.

Currently, Reasy supports **Redis** and **Mongo** as cache database types.

Let us understand how to connect to a cache datasource.

* Create a resource and select "Data Cache Source" type.
* Select the cache database type (Redis/Mongo)
* Select **Cache Threshold Limit**. This value determines when the cache datasource should fetch data. \
  Example: If set to 1000, the cache will only be used when the dataset exceeds 1000 records.
* Select **Cache Default Record Count**. It's recommended to match this value with your front-end pagination setting (records per page).
* Enter the **Host** and **Port** details for the cache database. If using more than one cache datasource, click '+' to add additional connection details.
* Enter the **Database name**, **Username**, and **Password** information, to authenticate the connection.
* Provide any additional settings if required.
* Finally, click **Test Connection** to validate, then **Save** to establish connection.

Now, the cache datasource is ready to use.

