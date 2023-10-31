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

# Creating Custom Components

While Reasy offers an extensive collection of UI tools to accommodate most business use cases, it also empowers you with the capability to create custom plugins, simplifying your app development journey. You can conveniently manage all your custom plugins by navigating to **Account Information** > **Manage Plugins**.

{% hint style="info" %}
**Note:** Custom plugins are merely UI tools.
{% endhint %}

![](<../../../.gitbook/assets/Manage Plugins.png>)

### Creating a custom plugin

A plugin is a JavaScript (JS) object that possesses a name and contains actions. These actions contain methods that are triggered based on specific events. Developing custom plugins is a simple process, requiring minimum coding expertise.

Follow these steps to create one,

* Click **Create Plugin.**&#x20;
* Give your plugin a name and provide a brief description of its purpose.
* Select the plugin type, and there you go.

<div align="left">

<figure><img src="../../../.gitbook/assets/Create Plugin.png" alt="" width="563"><figcaption></figcaption></figure>

</div>

This downloads a zip file to your default local storage. Inside this zip file, you will find a file named "plugin.json", which contains basic information about your plugin and a unique identifier tagged to it.&#x20;

<div align="left">

<figure><img src="../../../.gitbook/assets/Plugin - zipped file.png" alt="" width="563"><figcaption></figcaption></figure>

</div>

The core JavaScript file for creating plugins is "plugin.js," where you define your logic. Within the JS file, access the "plugin.js" file to define all the necessary logic required for rendering the plugin, handling data, and more. After you define your logic, save the file.

You may also refer to the document in the extracted zip file, for guidance on each step and the purpose of each method, including what inputs are required.

{% hint style="info" %}
**Note:** If you have added CSS properties inside the CSS folder and attempt to access them in the properties panel, it may not work as expected. Because the properties panel resides within a parent iframe, while the page designer frame is within a child iframe, all JavaScript and CSS files are loaded within the child iframe.
{% endhint %}

Now, the plugin is ready for use. Install it on the platform to use it within your app. Similarly, you can create additional custom plugins required for your app and install all of them collectively.

### Installing a Custom Plugin

* Click **Install Plugin** and upload that zip file. If you intend to install multiple plugins, ensure they are all zipped into a single file.
* In the **Plugin Installation Wizard**, you will find a list of plugins listed along with their installation status. Select the plugins you wish to install and proceed with the installation.

{% hint style="info" %}
**Note**: If you attempt to install a plugin that was installed previously, its status will show as "Already installed". You can, however, reinstall it, which will overwrite the existing plugin. This feature is handy for inheriting any changes to the installed custom plugins.
{% endhint %}

Upon successful installation, the status of the plugin(s) will be marked as "Installed successfully." The installed plugin(s) will be listed in your plugin dashboard, and you'll also have the option to download a report summarizing the installation status of all plugins.

### Managing Custom Plugins

A plugin can be managed only by the user who installed it.

<div align="left">

<figure><img src="../../../.gitbook/assets/Plugin dashboard.png" alt=""><figcaption></figcaption></figure>

</div>

* **Enabling or Disabling a Plugin**: Once a plugin is installed, it is enabled by default and accessible under "Custom" in the Toolbox. However, you can disable it by clicking<img src="../../../.gitbook/assets/Disable plugin.png" alt="" data-size="original">, to restrict using it further. Disabling a plugin will no longer appear in your Toolbox.
* **Sharing a Plugin**: Click![](<../../../.gitbook/assets/share plugin.png>) to share the plugin with users in your domain. Once shared, the plugin will be marked as "shared" and will be available in your users' Toolbox under "Custom" tools. To revoke access, simply unshare it by clicking![](<../../../.gitbook/assets/Unshare Plugin.png>). Plugins not shared are considered "Private."
* **Exporting a Plugin**: Click![](<../../../.gitbook/assets/Export Plugin.png>)to download the plugin to share it offline. Users you share it with will need to install it to use it.&#x20;
* **Deleting a Plugin**: Click![](<../../../.gitbook/assets/Delete Plugin.png>)to delete the plugin permanently. After deletion, it will no longer be available in your dashboard.

You can search for a plugin by its name. You can even filter the plugins in your dashboard to view them at your convenience.
