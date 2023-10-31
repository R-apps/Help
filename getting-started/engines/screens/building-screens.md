---
description: Create Your App's UI Effortlessly
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Building Screens

This article emphasizes building a screen from scratch, although you have multiple options for constructing your app's interfaces.

### **Build screen from scratch**

To create a screen,

* Expand the desired layout in the Navigation Explorer, go to **Screens**, and click<img src="../../../.gitbook/assets/image (47).png" alt="" data-size="original">to create a new screen.
* Give the screen a name and open it on the canvas.
* Go to the Toolbox, find the required tools, and drag them onto the canvas, one by one. Here are a few tips and tricks that will help you build screens effortlessly.

{% hint style="info" %}
1. If you need to clone a component or a section, you can quickly do so by selecting it on the canvas and clicking![](../../../.gitbook/assets/Duplicate.png)in the canvas toolbar.
2. As this is a responsive grid, arrange your sections and elements thoughtfully to ensure an organized layout. For more assistance, [click here](responsive-grid-system.md).
3. If you prefer using the canvas grid, you can switch to grid view by clicking![](<../../../.gitbook/assets/Grid View.png>)in the canvas toolbar.
4. For apps with login screens, dashboards, or contact us forms, consider using pre-built screens. Later, customize them to fit your app's requirements. This saves you time in building them from scratch.
{% endhint %}

* After designing the screen, bind the components with data and configure their properties to define their behavior and appearance.&#x20;

{% hint style="info" %}
If a component on your screen is used multiple times, you can use global CSS settings to configure it once and apply the settings to all instances. This simplifies your work. For more details on how to do it, [click here ](../../workspace/property-editor/)to understand how to do it.
{% endhint %}

* When you finish, save it by clicking![](<../../../.gitbook/assets/image (12).png>). Then, click![](<../../../.gitbook/assets/image (40).png>)to preview it to see how it looks across different devices.

By following these steps, you can efficiently create a screen tailored to your app's needs, ensuring a seamless user experience across devices.

### Built-in Code

When you begin building a screen, Reasy creates code in both HTML and JavaScript using its built-in code generator. To view, switch to the **Code** tab. Furthermore, if you are a coding expert, you may make the necessary changes to the code.

## Best Practices <a href="#best-practices" id="best-practices"></a>

1. As everything in an app is data-driven, try structuring your data first and then building screens. It enables you to bind your screen elements to the appropriate attributes (data tables). Another advantage of doing so is that you can simply drag the attribute or entity onto the canvas to construct a screen element depending on the attribute's datatype, assuming it's an input element like a textbox.
2. Before designing a screen, give it a name so you can readily identify it.
3. Ensure that your screens display properly on Mobile and Tablet devices before you launch your app.
4. Although you can decide whether to display or hide the layout while building a screen, it's always a good idea to have it visible so you can preview your screen with the layout.
