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

# PrivatePDM

The "PrivatePDM" plugin lets you add a new attribute that is needed by the API but not defined in the database. This is a transient attribute and is not saved in the database. As an example, you could use private PDM to make an attribute that stores the job ID (a temporary value) of a job process.

### How to Use?

Drag the PrivatePDM plugin into your API flow. Click **Add New Field** to define the attribute name and datatype.
