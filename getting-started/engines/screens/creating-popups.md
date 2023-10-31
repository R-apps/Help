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

# Creating Popups

## What's a popup screen?

A popup screen, also known as a modal, appears on top of your app's primary content. They are displayed as an overlay until you take the action or dismiss it. As pop-ups improve the user experience, use them wisely for focused interactions and conveying critical messages.

Here are some examples that we have come across where popup screens are helpful:

* **Log in/Sign up forms**: Upon clicking the "Sign In" or "Sign Up" button, a pop-up appears, allowing us to enter our credentials or register without navigating to a different page.
* **Contact Forms**: Websites use pop-ups for contact forms instead of directing users to a separate contact page.
* **Confirmation and Dialog Boxes:** When users attempt to delete an item, a popup dialog prompts them to confirm the action.
* **Cookies Consent:** Websites use popups to seek user consent to use their cookies.
* **User Surveys and Feedback:** Websites present popup screens with short surveys or feedback forms, encouraging user participation.

{% hint style="info" %}
**Tip**: Use pop-ups judiciously, as too many or too invasive pop-ups might ruin the user experience.
{% endhint %}

### Creating a Popup

When you open the screen, click it in the Navigation Explorer to reveal its properties. Choose the Type "Popup" in the **Design** tab, to make it a popup screen. Now, you can style and resize it as needed. You may also add a header or footer to it.

Then, define its occurrence in the **Events & Actions** tab. A load event for the screen is available by default. You can edit it however you want or delete it if it is no longer needed. For more events involved in your screen, click '+' to configure them. To view the event setup, [click here](broken-reference).
