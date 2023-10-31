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

# Design Properties

All the styling properties are accessible through the **Design** tab in the Property Editor. These CSS (Cascading Style Sheets) properties provide complete control over the element’s appearance, including color, font, size, text, spacing, position, background images, and more. You can easily access these properties by double-clicking the element on the Canvas.

Before we delve into it, let’s understand the types of CSS:

* **Internal CSS,** also known as **Inline CSS**. When you double-click and style an element, the settings apply only to that specific element. This is referred to as inline CSS. However, if you have used an element repeatedly on your screen and wish to apply the same settings to all of them at once, you may consider using external CSS.
* **External CSS,** also known as **Global CSS**. This simplifies your job; you may configure it once and apply it to all. Assume you've utilized a textbox for fields like Name, Email, Contact No., and so on. Rather than setting CSS for each element individually, you can set it once and apply it to all. Global CSS can be added in three different methods:
  1. The first method is by selecting![](<../../../.gitbook/assets/image (21).png>)on the element in the toolbox palette, which reveals its properties. Make the necessary settings and click **Apply Changes**. These settings will apply to that element wherever throughout the screen.&#x20;
  2. The second method involves using the “Add Class” function. Define the class in the style sheet, and add those class names in the **Add Class** section. This allows you to create global CSS.
  3. The third method is by defining the CSS in the style sheet itself or by importing CSS.

Using any of these methods, you can efficiently manage and apply CSS to your elements.

Here is a brief overview of the design properties that are common to each element.

> **Padding:** Use padding to add space between the content and border in the textbox
>
> **Margin:** Use margins to create space around elements, outside of borders
>
> **Width:** Each element occupies 12 columns of a layout or a container. To resize it, set the number of columns it should be positioned in to resize it.
>
> **Height:** Specify the element’s height in percentage or pixels.
>
> **Typography:** Set the font style, font size, alignment, and style to add CSS to your element.
>
> **Add Class**: The space here allows you to add custom stylings to apply it to your UI element. To have your custom settings, first specify them as classes in the style sheet, and then add the names of those classes here so you may apply them to your element.
>
> **Background color:** The color chosen here will be applied to the whole textbox, omitting the icon section.
>
> **Icon BG Color**: The color chosen here will be applied to the textbox's icon section.
