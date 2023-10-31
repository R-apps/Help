---
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: false
  outline:
    visible: true
  pagination:
    visible: true
---

# Events and Actions

An event, within the context of app development, refers to any user action or system occurrence that the application must recognize and respond to.&#x20;

When defining the properties of your screen components, you have the capability to manage how your application reacts to various user interactions.

Typical examples of events encompass:

1. **Mouse events**
2. **Keyboard events**
3. **Load events**
4. **Form events**

## Event Configuration

Event handling refers to the process of specifying how your application should react when a particular event takes place. Typically, this involves writing a piece of code or a function to be executed in response to the event. However, Reasy simplifies this process by allowing you to configure events visually.

For instance, let's take a look at the login screen with a 'Login' button. If we look at its properties, it has an on-click event configured. Clicking the event displays the event configuration. When the user clicks the Login button, it triggers an authentication process. Based on the outcome of this authentication, the application may either log the user in and direct them to a particular page or generate an error message.

<figure><img src="../../../.gitbook/assets/Login Event Flow.png" alt=""><figcaption></figcaption></figure>

In Reasy, this event handling can be managed effectively. You'll find a property labeled "Add/Edit Action" under General Properties, which enables you to define actions based on your components, such as buttons, hyperlinks, and others. Accessing it is simple: open the screen and click for screen-related events (load events, app events, etc.), or double-click the specific component within the screen for component-related events (button clicks, hyperlinks, etc.).

To create an event, click **Add/Edit Action**, and

* Select a trigger: Specify what action should initiate the event from "When".
* Assign a unique name to the event for easy identification. However, Reast suggests a suitable name based on the selected action type.
* If you want to control event access based on user roles, enable "Role-based Access.".

After adding the event, you'll be prompted to define its specifics. Depending on the selected action, you are provided with a visual flow to configure the event's response. Configure this flow to meet your requirements and save it.

For certain buttons 'Save,' 'Submit,' or 'Update,' you may require API services to insert or update data in the model. In such instances, you can easily navigate to the APIs engine and drag the relevant service into the event's flow.

Should you require more events, simply use the '+' option to add more. In this way, you can visually configure all the events necessary for your app with ease.&#x20;
