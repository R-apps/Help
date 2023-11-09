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

# Responsive Grid System

Reasy's layout patterns use a 12-column flexible grid system for seamless adaptation to various screen sizes, from desktops to small mobile devices. This ensures a responsive and mobile-friendly user experience. This framework divides the screen width into 12 equal columns, offering you the flexibility to create responsive and adaptive layouts.&#x20;

Each element dragged onto the canvas occupies 12 columns, spanning across the screen.

This infographic illustrates the essentials of a 12-column grid layout.

<figure><img src="../../../.gitbook/assets/12-column grid - Anatomy.png" alt=""><figcaption></figcaption></figure>

* **Section**: This serves as a container for the component(s).
* **Section Controls**: These are the actions to manage and control the arrangement of sections on a screen.
  * **Add**: Adds a new section to the bottom of it.
  * **Delete**: Deletes the specified section
  * **Move Up**: The entire section shifts up by one section
  * **Move Down**: The entire section shifts down by one section
* **Column Count**: This count tells us the number of columns occupied by a section.
* **Columns**: These are the 12 available columns.

{% hint style="info" %}
1. &#x20;To view the grids on the canvas, click![](<../../../.gitbook/assets/image (5).png>)on the canvas toolbar.
2. Sections are crucial in building your app's interface. So, ensure that your components are exactly placed in order to efficiently manage and position the sections and elements within them.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

### Layout Columns: Resizing and Dividing&#x20;

You can seamlessly rearrange, resize, and stack the elements.&#x20;

When you don't require all 12 columns, resize and group the components together to create wider columns. To resize a component on the canvas, click and hold its section to expand or reduce it, making it fit within the desired number of columns.&#x20;

For instance, if you want to place two components side by side, you can fit each of them into 6 columns, or you can use one component with 4 columns and the other with 8 columns, essentially creating a two-column layout. Similarly, for three components in a row, you can fit each of them into 4 columns, resulting in a three-column layout. If you have a single component that only spans 4 columns, resize it to fit those 4 columns and place the next component in a separate section.

So, it all depends on how you require it for your app's interface. However, make sure that the grid columns total up to twelve for a row.

{% hint style="info" %}
Only the components within a section will be auto arranged.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

If you are working with a container or card that spans only fewer columns, say 6 columns, the container within itself will still function as a 12-column responsive grid. This will help to ensure that your content is displayed properly and looks great on all devices.

{% hint style="info" %}
**Note:** Depending on the screen size, the columns will re-arrange themselves: On a large screen, the content might look better structured in three columns, but on a mobile screen, the content elements might look better piled on top of each other. So, it is recommended that you test your screen on multiple devices before launching your app.
{% endhint %}

By leveraging this 12-column grid, you can create visually appealing and user-friendly websites that cater to a wide range of devices.
