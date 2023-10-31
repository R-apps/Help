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

# Exporting a Data Model

This article explains the benefits and process of exporting a data model.

* **Collaborative Work**: Exporting the model allows easy sharing with your team, enabling timely feedback and collaboration.
* **Reusability**: The exported model can be reused across multiple projects or applications.
* **Data Integrity and Backup:** Exporting serves as a backup mechanism, ensuring data integrity. In case of any unexpected issues, you can restore a model quickly and effortlessly.
* **Version Control**: Each exported model represents a specific version or iteration of the data model. This makes it easier to track changes, compare different versions, and maintain a comprehensive record of the data model's evolution over time.

Here are the various formats to which you can export your model:

### **Model to Model File:**

This format is ideal for exporting unstructured data. When you choose this option, the selected entities are saved as a package with the ".pdm" extension. While we understand that unstructured data is often presented in JSON or XML formats, we use the PDM format to ensure compatibility with Reasy.

### **Export Data**:

Use this option to export both the model and its data.

### **Model to Database:**

Use this option to export a model to your preferred external database. Before proceeding, ensure that you have a compatible data source to connect to your database. The model will export the chosen entities directly to your designated database.

### Export Validation Rules

Beyond just exporting a model, you can also export the "Validation rules" within it. By default, all entities are selected. However, if you want to export only the entities that have validation rules, simply uncheck all entities and choose the ones you require. Once you've made your selection, proceed with the export process. It will generate an Excel file containing the exported rules.
