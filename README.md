# Updated JavaScript Form Validation Assignment with Suggestions for Improvement:

## General Instructions

- Develop a professional looking and attractive HTML form that employs JavaScript validation.
- Your HTML must be in file named `project_2.html`.
- Your CSS must be in a folder/file named `css/style.css`.
- Your JavaScript must be in a folder/file named `js/script.js`.
- Ensure accessibility using WAVE tests without errors, alerts or contrast issues.
- The use of the HTML `required` attribute is prohibited.
- You must provide a set of instructions for the user.

## Form Attributes and Values

The form must have the following attributes and values set:

- name = "order"
- id = "order"
- action = "https://ctec.clark.edu/~belgort/formprocessing/processform.php"
- method = "POST"

## Form Fields

- First Name: Text input, max 20 characters.
- Last Name: Text input, max 20 characters.
- Address: Text input, max 40 characters.
- City: Text input, max 30 characters.
- State: Select with all 50 states as options.
- Product: Select with 15 product options.
- Quantity: Numeric input, 5 characters.
- Contact: Radio buttons for phone contact preference. Include at least 4 different options for them to select one from.
- Terms and Conditions: Checkbox for acceptance.
- Interests: Checkboxes for interests selection. 0 or many options may be selected.
- Feedback: Textarea for input.

## Styling and Design

- Ensure the form looks professional and not amateurish.
- You are encouraged to use Bootstrap, plain old CSS, or Tailwind CSS for styling if desired.
- Your CSS must be in a folder named css.
- Enhance styling for mobile responsiveness.

## Form Validation Rules (JavaScript in `js/script.js`)

- All fields are required.
- Implement error messaging for each validation rule.
- Real-time validation for immediate feedback.
- Error bucket that appears above and below the form.
- Disable the submit button until all fields are filled out.
- Place focus on the first unfilled field.

## Assignment Submission

- Push code to GitHub and submit with the phrase "Ready to Grade" in Canvas.

## Grading Rubric

| Item                                                 | Full Marks | Partial Marks | No Marks |
|:-----------------------------------------------------|:-----------|:--------------|:---------|
| Form and field coding accuracy                       | 25         | 12.5          | 0        |
| Validation rules implemented correctly in JavaScript | 25         | 12.5          | 0        |
| Error bucket functionality                           | 25         | 12.5          | 0        |
| HTML/CSS/WAVE compliance                             | 25         | 12.5          | 0        |
| Professional styling with mobile responsiveness      | 50         | 25            | 0        |
