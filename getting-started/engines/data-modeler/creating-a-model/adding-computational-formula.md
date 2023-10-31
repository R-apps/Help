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

# Adding Computational Formula

This article helps you understand adding a computation formula.

When you require dynamically calculated data, insert an expression in the attribute that calculates and holds the result. This is quite similar to arithmetic calculations using the BODMAS rule.

To understand more, let's look at an example of calculating employees' gross salaries:

Ex: Gross Salary = Net Salary - (Deductions + Taxes)

The Gross salary is calculated by subtracting taxes and deductions from the employee's net salary.

So, we require attributes holding Net salary, taxes, and deductions to be calculated. The movement data is available in these attributes; the "Gross Salary" attribute should calculate and display the derived result. Inserting an expression is as simple as inserting a formula in Excel. Edit the attribute to place a formula for this calculation. Here, short keys help you pick the attributes. Hitting **Control + Space** on your keyboard displays the attribute list, and **Control + M** displays the method list. As you see here, create an expression using the required attributes. If you want to enter the attributes manually, use this pattern: @{entityname.attributename}.
