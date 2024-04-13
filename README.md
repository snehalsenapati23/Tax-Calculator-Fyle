
# Tax Calculator

This is a simple tax calculator web application built using HTML, CSS, and JavaScript. It allows users to calculate their overall income after tax deductions based on their gross annual income, extra income, applicable deductions, and age group.


# Deployed Link 
- https://tax-calculator-blush.vercel.app/

## Features

- Users can input their gross annual income, extra income, total deductions, and select their age group.
- Error icons are displayed next to input fields if the input is invalid, with tooltips providing error messages.
- Users can hover over question mark icons to see tooltips explaining each input field.
- Upon clicking the submit button, the application calculates the overall income after tax deductions and displays the result in a modal.
- The modal also provides a close button to dismiss it.

## Dependencies

- Bootstrap Icons: Used for icons in the application.
- Google Fonts (Roboto): Used for the font styles in the application.

## File Structure

- `index.html`: Contains the HTML structure of the tax calculator web application.
- `styles.css`: Contains the CSS styles for the application layout and design.
- `index.js`: Contains the JavaScript code for handling user inputs, calculating taxes, and displaying results.
- 
## Valid Input Test Case:

- ### Input:
Gross Annual Income: ₹ 500,000
Extra Income: ₹ 50,000
Deductions: ₹ 20,000
Age Group: < 40
- ### Expected Result: Overall income after tax deductions should be displayed in the modal.
- ### My output : ![image](https://github.com/snehalsenapati23/Tax-Calculator-Fyle/assets/78613699/bf541cf5-9bc4-4d9e-b17a-7bb8b42e0343)
![image](https://github.com/snehalsenapati23/Tax-Calculator-Fyle/assets/78613699/99cf6170-a90c-4582-9834-df9800043c6c)

## Invalid Input Test Case:

- ### Input:
Gross Annual Income: ABC (non-numeric input)
Extra Income: -₹ 10,000 (negative value)
Deductions: (blank)
Age Group: (not selected)
- ### Expected Result: Error icons should be displayed next to the respective input fields, with tooltips showing relevant error messages.
- ### My output: ![image](https://github.com/snehalsenapati23/Tax-Calculator-Fyle/assets/78613699/f1691bdf-b855-4746-946e-64a31248ee7c)


## Usage

1. Open `index.html` in a web browser.
2. Enter your gross annual income, extra income, total deductions, and select your age group.
3. If there are any errors in the input fields, error icons will be displayed with tooltips explaining the errors.
4. Click the submit button to calculate the overall income after tax deductions.
5. A modal will appear displaying the calculated result.
6. Click the close button in the modal to dismiss it.

## Development

If you want to modify or extend the functionality of the tax calculator application, you can follow these steps:

1. Modify the HTML (`index.html`) to adjust the layout or add new features.
2. Update the CSS (`styles.css`) to change the visual appearance of the application.
3. Modify the JavaScript (`index.js`) to add new functionality or enhance existing features.

## Future Enhancements

Here are some potential enhancements that could be implemented in future versions of the tax calculator:

- Support for multiple tax calculation methods based on different tax laws or regions.
- Integration with user authentication to store and retrieve user data securely.
- Addition of charts or graphs to visually represent tax data and trends.
- Implementation of client-side data validation to improve user experience and prevent errors.




