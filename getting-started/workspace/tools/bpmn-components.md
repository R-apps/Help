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

# BPMN Components

BPMN (Business Process Modeling Notation) elements are the standard notations that help you create process maps to visualize your business processes. Illustrate the logic behind a workflow from start to finish, permitting anyone to understand the sequence of events, information, and activity that flows through a chain of automated tasks. Determine how processes perform under varying scenarios and optimize repetitive and predictable processes.

All the flow objects, connecting objects, swimlanes, and data are available here.&#x20;

These flow elements are the components or building blocks that allow you to design and define the logic, behavior, and functionality of an application or process. These elements help you create workflows to automate your business processes by visually connecting and configuring them.

## **Flow Objects**

Flow objects are the building blocks, which include events, activities, artifact groups, and gateways, to help you define a flow and the behavior of a business process.

### Activity

Activities represent work performed within a business process and are depicted as rounded rectangles with names. These notations help illustrate the work being done in a process.

E.g., tasks, sub-process, etc.

### Gateways

Gateways, in diamond shapes, control how a business process flows by making decisions based on internal or external conditions. These notations help you separate and recombine flows based on certain conditions.\
E.g., an exclusive tool that can be transformed into event-based, parallel, inclusive, etc. in its settings.

### Events

Events represent occurrences that can affect a business process and can be internal or external. They are shown as circles with icons to indicate the type of trigger. These notations serve as a trigger.\
E.g., initiating a starting point, intermediate step, or end point of a process.&#x20;

### Artifact Group

Groups help you visually organize your tasks and activities without affecting the process.\
E.g., Artifact Group

### **Connecting Objects**

These include sequence flows, message flows, and associations, which connect the flow objects and represent the order and direction of the process flow.

E.g., Transition, which can be transformed into a message flow in the component settings.

## **Swimlanes**

Swimlanes are typically used to separate different functions or roles within a process, making it easier to understand the flow of work and the responsibilities of each team or individual. They are often depicted as horizontal or vertical rows on a diagram, with each row representing a specific role, department, or team involved in the process. Swimlanes are depicted with “Pools” and “Lanes” to refer to different levels of organization within the process. A pool is the highest level of organization in a swimlane diagram, representing the entire process being mapped out, whereas a lane is a subset of the pool that represents a specific role or department within the process.

E.g., Swimlane, Swimlane Vertical.

## **Expanded Subprocess Loop**

A sub-process is a graphical object within a process flow that can be “opened up” to show another process (either embedded or independent). It comes with a ‘+’ sign in the lower center of the shape, indicating that the activity is a sub-process and has a lower level of detail. It offers you the opportunity to provide more detailed information about a particular step or task within a process.
