# Create a Registration Form

## Introduction
Now that you're familiar with HTML Form elements and styling those using CSS, let's put those skills into practice. In this exercise, you'll create an interactive registration form for a website.

While registration forms are simple in their essence, they will reinforce what we've learned so far and give you additional practise to master HTML Form Elements.

## Getting Started
Follow the instructions below to get started:

1. Fork this Repository
2. Clone the Repository to your computer
3. Open the Repository in VS Code
4. Start the Live Server in VS Code 
5. Follow instructions 

## Instructions
Follow the instructions listed below.

### 1. Setting Up Your HTML Document
Start by creating a fresh HTML document. Ensure to include a <!DOCTYPE html> declaration at the top of your document, and opening and closing <html>, <head>, and <body> tags for proper HTML structure.

Next create a new CSS file called styles.css and link the file correctly using the <link> Element inside the <head> section. 

### 2. Constructing the Form
Next, you will need to create a ﻿<form>  element within your HTML document's <body>. The form element will house all the controls required for data entry.

### 3. Creating Form Controls
The form controls you will need to establish within your form include:
Two text input controls for the user's first and last name.
An email input control for the user's email address.
A password input control for creating user's password.
Finally, a submit button for sending the data to the server.
For all these input controls, except the submit button, remember to create a corresponding <label> to improve your form's accessibility.

### 4. Adding Placeholder Text
Insert some placeholder text into each of your input controls. This text gives users a clear indication of what data they need to provide in each field.

### 5. Styling The Form
With your form set up and functioning, you can proceed to the styling phase. Incorporate the following styles into your form:
Set a singular font-family across your entire webpage.
Align your form to the center of the page and set a specific width.
Apply appealing styles to your input and textarea elements, including color, border, etc.
Adjust the font size and style for your form labels.
Decorate the on-focus status for your input elements.
Personalize the design of your submit button.
Ensure to test your form's responsiveness. It should be fully functional with nicely transitioned styles when interacted with.

### 6. Testing the Form
The final stage involves testing your accumulated work. Your form should be clickable for users to select input boxes and interact freely with form controls. Use your Keyboard and make sure that it's navigable without using the mouse at all.

## Submission

When you're finished, run the following commands:

git add .
git commit -m "done"
git push origin main

Create a Pull Request and Submit your assignment.

## Let's Chat About Your Questions...

<details close>
<summary>How Do I Start Building My Form?</summary>

If you're unsure where to start with your form, begin by constructing the basic HTML structure. Add elements and attributes gradually, concentrating on the form content first. The styling part comes later with CSS.
</details>

<details close>
<summary>Any Suggestions For the Visual Appeal of My Form?</summary>

You know that they say... the sky is the limit! Or... try the Internet! You will likely find dozens of inspiration online. But remember, it's more imporant to get a functioning registration form, rather than the most beautiful one. 

Don't take too much time on finding inspiration.
</details>

<details close>
<summary>How Can I Ensure My Form is Accessible?</summary>

For accessibility, make sure each of your input fields has an associated <label>. This helps screen readers identify what each field is for. Also, ensure your color contrast is high enough for visually impaired users to read your text.
</details>

<details close>
<summary>How Can I Center My Form on the Page?</summary>

To center your form on the page, you can use CSS. If your form's width is defined, use `margin: auto;` to automatically adjust both the left and right margins and help center the form.
</details>

<details close>
<summary>How Do I Add Placeholder Text to Input Fields?</summary>

To add placeholder text to input fields, use the `placeholder` attribute in your <input> tags. For example, `<input type="text" placeholder="Enter your first name">` displays "Enter your first name" in the text box until the user starts typing.
</details>

Remember, each challenge is a stepping stone towards your growth! If you're still stuck, don't hesitate to seek additional help.