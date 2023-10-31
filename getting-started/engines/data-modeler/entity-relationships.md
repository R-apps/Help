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

# Entity Relationships

### **Introduction**

When dealing with information stored across different entities, establishing logical connections is essential. These relationships are the key to making sense of complex data structures and are the foundation for efficient data management. This article will guide you through the process of creating logical relationships to help you relate information stored in different entities.

Here are the four types of relationships:

#### **One-to-One Relationship**

In a one-to-one relationship, a single instance of one entity is associated with a single instance of another entity. For instance, consider the relationship between an employee and their Social Security Number (SSN). Each employee has one unique SSN, and each SSN is linked to only one employee.

One Employee <--> One SSN No.

#### **One-to-Many Relationship**

In a one-to-many relationship, a single instance of one entity is associated with multiple instances of another entity. For instance, a department can have numerous employees, but each employee belongs to only one department.

One Department <--> Many employees (e.g., Emp1, Emp2...)

#### **Many-to-One Relationship**

Conversely, a many-to-one relationship occurs when multiple instances of one entity are associated with a single instance of another entity. For instance, several employees can share the same job designation, but an individual employee cannot hold more than one job title simultaneously.

Many employees <--> One Designation

**Many-to-Many Relationship**

Finally, a many-to-many relationship arises when multiple instances of one entity are associated with multiple instances of another entity. For instance, many employees may work on one project, and conversely, one employee can contribute to multiple projects.

Employees <--> Projects

### **Establishing Entity Relationships**

To establish a relationship between any two entities, follow these steps:

* Navigate to the source entity in the Navigation Explorer and select "Add Relationship" from the right-click menu.
* Assign a name to the relationship.
* Choose the entity with which you want to establish the relationship and select the relationship type.

The relationship appears on the canvas as you create.&#x20;

Hovering over the relationship provides options to view, edit, or delete the relationship.

{% hint style="info" %}
**Tip**: Alternatively, you can add a relationship by choosing "Add Relationship" from an entity's more actions on the canvas.
{% endhint %}

By doing so, you may efficiently organize your relational data.
