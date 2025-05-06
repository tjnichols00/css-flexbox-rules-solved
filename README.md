# Flexbox RULES

## Introduction

In this activity, you'll be designing the sign-in and sign-up forms to replicate the Authentication page mockup. After that, you'll be enhancing the styles of the stylish e-commerce page that displays products in three different views.

These tasks will turn you into a Flexbox expert! You'll gain the ability to construct about 95% of the layouts needed on various freelance platforms. This exercise promises to be a highly enjoyable way to refine your Flexbox skills!

Check out the pages images you'll be imitating:

- Authentication page: /assets/images/authentication-page-solved.png
- E-commerce page:
  - Grid view: /assets/images/e-commerce-page-grid-solved.png
  - Lines view: /assets/images/e-commerce-page-lines-solved.png
  - Lines-action view: /assets/images/e-commerce-page-lines-action-solved.png

Please, watch the [Flexbox Rules INTRO video](https://www.loom.com/share/6bf938c7e4234745970fd83181b585a9?sid=19a5fc8d-b8e0-4d7b-b705-2d638fd2ec63) before you start.

## Learning objectives

This assignment should prove that a student is able to:

- Create forms and multiple form elements
  - labels
  - input fields
  - multiple option input fields
  - single option input fields
  - dropdowns
  - submit buttons
- Utilize Flexbox to create layouts
  - align elements horizontally and vertically
  - center items
  - set single direction and two direction layouts
  - apply multiple layout styles to a single element through a service CSS class name
- Build the HTML structure to conform Flexbox relations concept.

## Standard requirements

- [X] Fork the project to your github account
- [X] Clone the project to your computer
- [X] Open the project in VSCode with `code <cloned_repo_folder_name>`
- [X] This Assignment is NOT tested. You can use all the desired creativity!
- [X] All the tasks of the "Specific requirements" section MUST be solved
- [X] The project's file/folder structure should NOT be edited!
- [X] The ecommerce-page.html file should NOT be edited!
- [X] The code of the index.html and styles.css should pass the W3C validation (Feel free to use either the "w3c web validator" VSCode extension or the "Online w3c Markup Validation Service")
- [X] The code MUST be formatted with Prettier.
- [X] Push the changes to the Github repo, when finished.
- [X] Submit a .txt file with the Github repo url.

You'll discover certain styles existing in the initial state of the CSS files. They're present for a purpose, but it's your call to determine whether you want to utilize them, remove them, or create some.

## Specific requirements

> Authentication page

Acceptance criteria:

- [X] The layout should closely resemble the mockup.
- [X] Avoid using margin and float CSS rules to define distance/space between elements or their alignment.
- [X] Positioning (utilizing the position CSS property) is prohibited.
- [X] Edit the following files:
  - [X] html: `/pages/authentication-form.html`
  - [X] css: `/css/authentication-form.css`

Create the form HTML elements to imitate the mockup:

- [X] Wrap each group of a label and input elements with a container representing a row.
- [X] Maintain a 6px distance between the label and the input.
- [X] Keep a 30px distance between each row.
- [X] Bolden label text when paired with a text or text-like input field.
- [X] Avoid bold formatting for labels paired with checkboxes and radios.
- [X] Utilize a paragraph element if the label element can't be used.
- [X] Ensure inputs span the full width available within the parent.
- [X] Set the height of inputs with text-like values to 30px.
- [X] Set the height of dropdown elements to 30px.

For the "Sign In form":

- [X] The form should have a border of 1px width and solid style.
- [X] The login input element.
  - [X] Should require a value.
  - [X] Should include a placeholder.
  - [X] The value should be validated as an email by the default browser mechanism.
- [X] The password input element.
  - [X] Should require a value.
  - [X] Should include a placeholder.
  - [X] The value should be validated to contain a minimum of 8 characters and a maximum of 20 by the default browser mechanism.
  - [X] Should hide symbols during typing.
- [X] The "Sign in" button should submit the form to initiate field validation using the default browser mechanism.

For the "Sign Up Form"

- [X] The name input element
  - [X] Should require a value.
  - [X] Should include a placeholder.
- [X] The email input element
  - [X] Should require a value.
  - [X] The value should be validated as an email by the default browser mechanism.
  - [X] Should include a placeholder.
- [X] The password input element
  - [X] Should require a value.
  - [X] The value should be validated to contain a minimum of 8 characters and a maximum of 20 by the default browser mechanism.
  - [X] Should hide symbols during typing.
- [X] The confirm password input element
  - [X] Should require a value.
  - [X] The value should be validated to contain a minimum of 8 characters and a maximum of 20 by the default browser mechanism.
  - [X] Should hide symbols during typing.
- [X] The phone number input
  - [X] Should require a value
  - [X] The value should be validated to follow a template of telephone number strictly.
- [X] The avatar input
  - [X] Should be represented by a "Choose file" button allowing the user to select a file from their computer when clicked.
- [X] The state dropdown list
  - [X] Should be a dropdown list with a default option "Select your state" selected by default and three options with random state names (Iowa, etc.).
  - [X] The default option should be unavailable to be selected.
- [X] The city dropdown list
  - [X] Should be a dropdown list with a default option "Select your city" selected by default and three options with random city names (Dallas, etc.).
  - [X] The default option should be unavailable to be selected.
- [X] The Gender single-option group
  - [X] Clicking the label should activate the corresponding radio button.
  - [X] The "Other" option should be active (enabled) by default.
- [X] The "Sign in" button should submit the form to trigger field validation using the default browser mechanism.

> E-commerce page

Acceptance criteria:

- [X] Edit the following files:
  - [X] css: `/css/ecommerce-page.css`
- [X] Ensure the layout closely mirrors the mockup.
- [X] Refrain from using the margin CSS rule to specify distances between elements.
- [X] Positioning is prohibited.
- [X] When switching between views, display a different product list view.
- [X] The HTML file should remain unchanged; no updates or modifications are allowed.
- [X] The permitted list of CSS rules to add to the styles file is as follows:
  - `border-*`
  - `padding-*`
  - width
  - `*-width`
  - height
  - `*-height`
  - display
  - flex-direction
  - flex-wrap
  - justify-content
  - align-items
  - gap
  - color
