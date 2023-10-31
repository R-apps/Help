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

# Optimizing Complex Workflows

Is your flow too complex to handle? Optimize it using Link Throwing and Link Catching Intermediate Events. They provide the capability to connect two sections of a process. A link event in a flow can “throw” an event that can be “caught” by a catch event. Link Events allow you to pause your flow and check results at that point rather than executing your entire workflow.

Let’s optimize a flow.

* Insert “Intermediate” tools between sections of a process in your flow.
* Change the type of the tool to “LinkThrow” or “LinkCatch”.
* Next, create an event to link them. To create,
  * Click![](https://reasyapps.com/forum/wp-content/uploads/2022/07/Configure.png)in the canvas toolbar, in the Configuration Manager, switch to the **Event Manager** tab, and click **Create event**.
  * Give the event a unique name, select its type, assign a code, and define its scope, whether it can be used only in the current process or in the current application.
  * Add to save the event.
* Then, go to the “LinkThrow” element configuration and select the event. Repeat the same for the “LinkCatch” element to link the flow.
