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

# App Management

The dashboard serves as a centralized hub for managing all your apps. You can easily access and view your app's information, customize its settings, deploy, export, share, and perform various other tasks. The availability of these options may vary depending on the logged-in user's role permissions.

This article provides you with a comprehensive process of managing apps, covering the entire journey from creation to deployment.

### Import an App

The **Import** feature allows you to reuse an app’s existing configurations and resources. If you have an existing app that is close to your new app’s requirements, you can import it and modify it the way you want. This will save you time and effort when creating a similar app from scratch.

To import an app,

* Click <img src="../.gitbook/assets/Create new app.png" alt="" data-size="line">and select **Import**.
* Select the app in “.sol” format and click **Next**.
* Continue to **Next** to see if you need to configure anything in any resource to import the app. When finished, click **Finish**.

Now, the imported app is available on your dashboard. You can then customize it as you need.

### Restore an App

This feature lets you restore a safely deleted app from the **App Store**. When collaborating within a shared workspace, you can also view the apps safely deleted by your team. If an app has multiple versions available in the App Store, you can restore the exact version you want.

To restore an app,

* Click <img src="../.gitbook/assets/Create new app.png" alt="" data-size="line">and select **Store**.
* Select the app and click **Restore**.

The platform restores the app and adds it to your dashboard. You can then customize it as you need.

### **View App Details**

Hover over![](<../.gitbook/assets/App Info.png>), the app tile to reveal the app’s basic information which includes the date, creator's name, context path, version, and other relevant details.

<div align="left" data-full-width="false"><figure><img src="../.gitbook/assets/App Info - Dashboard.png" alt="" width="257"><figcaption></figcaption></figure></div>

### **Pin your App**

When you have many apps on your dashboard, you may use this feature to move your app to the top of your list. It helps you access your app easily and quickly.

To have an app within easy reach, click![](../.gitbook/assets/Pin.png) on its app tile. When you pin another app, it unpins automatically.

### **Set your App Preferences**

Set your app preferences before going live. To set, click![](<../.gitbook/assets/App settings Icon.png>) on the app tile, you will see the following settings:&#x20;

#### General:

* **App Name**: Use this setting to change your app name.
* **URL:** Use this option to copy your app URL.&#x20;
* **Validation Icon**: While Reasy offers a default validation icon (<img src="../.gitbook/assets/Validation Icon.png" alt="" data-size="line">), you can still add your own. \
  Click '+' to add an icon of your choice.
* **Preloader:** Select a preloader[^1] from the provided options or click '+' to add one (GIF).

![](<../.gitbook/assets/App Settings - General (1).png>)

#### Configuration:

* **Display Date Format:** Specify the date format here
* **Currency:** Select the currency type to be used in your app. To display values as monetary figures,  enable **Currency Symbol**.
* To show toaster (pop-up) notifications with text messages after user actions like form submission, updates, or errors, enable **Toaster Message Text**.

![](<../.gitbook/assets/App settings - Configuration.png>)

#### Data Limit:

Set a Session expiration session time, which is the amount of time a user can be inactive before the session ends.

![](<../.gitbook/assets/App Settings - Data limit.png>)

#### Log Details:

* **Log Level**: Select a log level (session-specific logging) to manage your app's logging behavior (Info/Error/Debug). Select "Off" to disable logs generation.
  * **Info** _(default)_ – Logs general events, warnings, and errors.
  * **Error** – Only logs errors and exceptions.
  * **Debug** – Logs everything, including detailed internal data (for troubleshooting).
* **Users Log Enabled**: Use this field to specify which users’ actions should be logged. \
  Only actions performed by the specified user(s) will be included in user-specific logs.\
  Example: Monitor actions of admins, testers, or specific roles for auditing or debugging.

![](<../.gitbook/assets/App Settings - Log details.png>)

### **Compare App Versions**

This feature helps you compare multiple versions of your app and see how it has changed over time. This helps your manager or the lead keep track of app changes.

Let’s see how.

* Click![](<../.gitbook/assets/More actions (7).png>) on the app tile and select **App Compare**.
* Select the versions and **Compare** them.

A comparison is displayed, showing the number of different resources.

### **Deploy your App**

This feature helps you roll out an app from one environment to anothe&#x72;**.** When you deploy an app, you're installing it in a target environment, whether it is for testing, production, or another environment; with all the necessary dependencies and configurations. It's how you make your app available to others.

Moreover, deployment lets you test out new features without messing up your live app version. So, you can keep the app running smoothly while experimenting with new things on the side.   &#x20;

Here are a few instances when you might need to deploy your app.

1. &#x20;When you build an app and want your teams to test and validate its functional integrity and detect errors.&#x20;
2. &#x20;When your app requires approval at different stages before going live.
3. &#x20;When you add new features to your app and want to test them without affecting the live app, you can push the new features separately. This will ensure everything works smoothly.

To understand the deployment process, let's first understand environments.&#x20;

An **Environment** refers to a specific instance of a Reasy server where apps are developed, tested, deployed, and run. Each environment is a distinct computing infrastructure that includes hardware, software, network resources, and other dependencies to run the apps built on Reasy.

Typically, different environments are created to facilitate different stages of the SDLC. The most common environments include:

* _Development environment_ _(aka local environment):_ This is where developers create and manage the development branches of a particular app. It's an individual developer's local machine where new features or changes are implemented and debugged before being shared with others.
* _Testing environment:_ This environment is used for comprehensive software testing, including unit testing, integration testing, and system testing. It aims to identify and fix issues or bugs before software is released.
* _Staging (aka pre-prod) environment:_ This is a replica of the production environment where the software is tested in conditions that closely resemble the live environment. It allows for final testing and validation of the application before deployment.
* _Production environment:_ This is the live environment where the software is deployed and made available to end-users. It represents the actual system on which the software operates and serves its intended purpose.

However, you're not limited to these environments. You may also set up sandbox environments for experimenting and prototyping, disaster recovery environments for backup and business continuity purposes, and others; as required throughout your App Development Life Cycle.

Here’s how you can set up an environment.

#### **Environment Setup**

Reasy platform administrators will have the option to set up environments by linking Reasy instances and identify them with a specific name. All linking requests require authorization from the target environment and once approved the linked servers becomes available for application deployment.

Below are the steps to set up an environment,

* Go to **Dashboard**>**Platform** and click **Linked Servers**; this displays a list of servers that are already linked.
* To create a new environment, click **Link Server.** Give it a unique name, server ID, server key, and the machine’s IP address and port number.
* Click the **Link** after entering the necessary information, a link request is sent to the specified machine.&#x20;

Its status remains "Request Pending" until accepted. Once the request is accepted, the status changes to "Linked". The linked servers will then appear as environments where you can deploy your apps.

Now that we understand environments, let's look at the app deployment process. Deploying the app is a simple action of pushing the specific branch of the app to the target environment.

* Click![](<../.gitbook/assets/More actions (7).png>) on the app tile and select **Deploy**. The platform displays a list of available environments, also known as linked servers.
* Next, select the environments where you want to deploy your app and click **Send**. This will send a request to all the selected environments.

Administrators of the target environment have to approve the deployment requests and install the app.&#x20;

So, with just a few clicks, you can easily deploy your app to the desired environment(s) at once.&#x20;

Once your app is installed in the desired environments, it can be deployed to additional environments if required. So, how would you keep track of all the environments in which your app has been deployed? To help you with that, we have an option called "[Deployment tree](app-management.md#deployment-tree)", which visualizes its deployment flow.&#x20;

### **Deployment tree**

The deployment flow of an app is depicted here in a tree structure. Each environment is displayed as ' <img src="../.gitbook/assets/Environment icon.png" alt="" data-size="line">' with a color, indicating the deployment status.\
![](<../.gitbook/assets/Deploy - Reachable & Installed.png>) **Reachable and installed**; means the app is successfully deployed in the destination environment.\
![](<../.gitbook/assets/Deploy - Reachable but not installed.png>) **Reachable but not installed**; means the destination machine has received the app but not installed it.\
![](<../.gitbook/assets/Deploy - Not reachable.png>) **Not reachable;** means the app is pushed from the source environment but not received at the destination. You may check your logs if your app isn’t accessible.

To check your app’s deployment status, click![](<../.gitbook/assets/More actions (6).png>) on the app tile and select **Deployment tree**.

### **Branch & Checkout**

This feature enables you to version your app, with each version called a branch. A branch is a method to deviate from the main development process, and checkout lets you switch between them. It is typically used to build a new feature, solve a bug in a branch, or freeze an app with specified features. This process increments the version number for each new version of the app. The app's initial version is 1.0.0. When you create a branch, it becomes a new version starting from 1.0.1, then 1.0.2, and so on.

To version your app, click![](<../.gitbook/assets/More actions (7).png>) on the app tile, and select **Branch & Checkout**. View all versions of your app by using the **All branches** option.&#x20;

### **App to PWA**

This feature helps you upgrade an app to a Progressive Web App (PWA) to let you offer your users an app-like experience. By adding the app to their home screen, users can access it with a single tap, just like a native app.&#x20;

Converting a web app to a PWA offers enhanced user experience, offline accessibility, cross-platform compatibility, and improved performance.

To transform an app into a PWA,

* click ![](<../.gitbook/assets/More actions (6).png>)on the app tile, and select **Manage PWA Settings**.
* Turn on to enable PWA. Although the PWA appears in the name of your app, you can change it and add your brand logo.&#x20;
* To make the necessary settings,
  * Select "Offline Support" to set cache settings.
  * Turn on Notifications under "Permissions" to enable push notifications that convey reminders, updates, promotions, and more.
  * Select "Messages" to set the messages to display your users in different scenarios.
  * Enable the **Installation pop-up** to pop up users a message to install the app.
  * Select "Notification Settings" to set the notification position and background color.

After you finish PWA settings, click **Save**.&#x20;

### **Share your App**

This feature lets you share your app with others in your domain. It’s great for collaborating, dividing tasks, and building apps more efficiently as a team. By sharing, you and your team can collectively build the app, reducing complexity.

To share an app, click![](<../.gitbook/assets/More actions (6).png>) on the app tile, and go to **More Options** > **Share**. Select the user(s) and then grant them with the necessary permissions to control their access to your app. Grant the recipients with any of the following permission type:

* **Full-access:** Grants the same permissions you have.
* **Read-only:** Lets recipients view the app restricting editing access.
* **Custom:** Allows engine level control, which enables you to control recipients' access to each engine. To restrict access to engine(s), set their permission to "None".

These permissions help you ensure application's security and integrity.

<div align="left"><figure><img src="../.gitbook/assets/Share App - with permissions (1).png" alt="" width="563"><figcaption></figcaption></figure></div>

### **Store your App**

Regardless of whether you are developing apps to address pain points for clients or customers, or pursuing your own unique app ideas, this feature lets you store and reuse them in the future. This lets you preserve your apps, leveraging your previous app development efforts, retrieve, and modify them as needed, ensuring that your work remains organized and accessible.&#x20;

To add an app to the store, click![](<../.gitbook/assets/More actions (6).png>) on the app tile, and go to **More options** > **Add to store**. Then,

* Provide a name as to how you want to store your app,
* Select a category in which you want to keep,
* Detail your app and its features for easy recognition, and
* Add an image as a tag to make it easier to find.

{% hint style="info" %}
Use the **Manage** option to create a new category or to manage existing ones.
{% endhint %}

**Duplicate your App**

Create a duplicate of an app using this option. This option allows you to maintain your original app intact when you have multiple options to address an issue with minimal changes or when you wish to share a copy of your app with the team.&#x20;

To create a copy of your app, click![](<../.gitbook/assets/More actions (6).png>) and go to **More Options** > **Copy**. A copy of the app is added to your Dashboard.

**Export your App**

Exporting is the process of creating a package or file containing all of an application's necessary components and resources. It saves a copy of an app to your local storage, allowing you to access and use your app outside of the development environment. For example, you can share it offline with the teams to test it, or you can allow individuals to install it on their devices.

To get a copy of an app to your local storage, click![](<../.gitbook/assets/More actions (6).png>) and go to **More Options** > **Export**. Continue to click Next to see whether there is anything to configure in any resource. Finally, click **Finish**, and the app exports as a “.sol” file (a Reasy-compatible format).

**Test your App**

It's a good practice to test your app before you deploy it or share it with others. This **Test** option allows you to examine your app's behavior in real time.&#x20;

To test it and see how it works, click![](<../.gitbook/assets/More actions (6).png>) on the app tile, and go to **More Options**>**Test solution**. Make sure your app is active before testing it.

[^1]: A loading indicator that shows your users that the app's content is loading or processing.
