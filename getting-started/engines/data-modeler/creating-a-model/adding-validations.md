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

# Adding Validations&#x20;

Before getting into it, let’s understand why we need to validate the data. Data validation is essential to help us get accurate results and ensure data integrity. Incorporating validations is always a good practice to cleanse data; so that we’ll not run into issues when we use it in the applications.

Now that we know how a validation helps, we’ll first see adding a basic validation.

### Basic Validation&#x20;

Say your app has a date field that should be in a specific range. If it’s out of range, you should display a message. To set this validation, select “daterange” from the validation type. Then define the range and set the message you wish to display. This is the default message that comes with the validation type you select; however, you always have the option to customize it. After you add a validation, make sure it is enabled.

Moreover, you’ll see different validation types for each data type. These are the validation types available for the “Date” data type. If you select a different data type, say “Integer”, you’ll see a different set of validation types. In case you don’t find the required validation, you can add one by providing a name, a regex, a default error message, a default placeholder, and the applicable data type. This is your newly added validation.

### Conditional-based Validation&#x20;

First, turn this ON to add conditions. Assume that this attribute should fetch an employee’s on-boarded date. If the record is not available, it should display a message. Let’s see how to add this validation rule. Give a name to the condition, select the attribute that holds the employee’s onboarding date, and then select the "is null" expression. As you set the rule, you’ll get the expression here. Then, set a message to be displayed if this condition is true. It’s that simple!

In case you don’t get the expression, click \<icon>. Moreover, you can copy and use this expression too if you're good at writing queries.

To add multiple rules, select the logical AND or logical OR operator and Click Add Rule.&#x20;

* Use the AND operator if the data has to satisfy two or more rules like this, or
* Use the OR operator if the data has to satisfy either or any one of the rules, and
* Use both operators in combination when you’ve multiple rules to satisfy.

To append another rule to the existing one, select the logical AND operator and define a rule that an employee’s onboarding date should not exceed the organization's establishment date. If the data satisfies both conditions, it should display a message.

What about adding extra conditions to be met? In such cases, you can add conditions as a group. Let’s see how it is done. Click Add Group and add the conditions in it. The conditions that you place under a group will be placed in brackets as you see here. This even helps you to prioritize which conditions must be satisfied first.

Likewise, you can include as many rules as you require to validate your data.

It’s not that you must display a validation message for every rule you define. It's your choice to determine what it should do upon satisfying the conditions, whether to validate, perform a computation, or set a value to be stored in it. Select the action type and add it.&#x20;

This is how you can add conditions to validate your data.

### Import Validations

When you have the option to add validation rules straight away in the platform, you may wonder why you need to add them outside of Reasy and then import them here.

Well, let me explain this with a use case.

Assume you're working in a collaborative environment and need multiple validation rules for a few fields. Also, we’re aware that when one of the team players is working on a module, the other team players who are working on the same app will have only view access to that module.

So, to let you work concurrently, Reasy has an option to import validations.

They are exported as an Excel file, which you can share with your team to work on. Now, you and your team can add validation rules together. You can add them directly to the platform, while the rest can add them to the Excel file they have been provided with.

The validation rules added by your team can then be imported.

This saves you time by letting you work collaboratively.
