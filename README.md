# Custom Form Styling

This project contains a simple yet elegant form styling built with CSS. It aims to create a clean and user-friendly interface, ideal for gathering user input such as text, email, phone number, and more. The design uses a lavender-colored background with a white form container to ensure that the form stands out.

## Features

- **Responsive Layout:** The form adjusts automatically to different screen sizes, ensuring a good user experience across devices.
- **Custom Colors:** The form's primary color scheme features lavender (`#F2E6F9`) and purple accents (`#7F03C2`).
- **Clean and Minimalist Design:** The form is styled with a minimalistic approach, ensuring ease of use and readability.
- **Interactive Elements:** Hover effects on buttons and form inputs provide visual feedback to the user.

## Some Images:
<img width="450px;" src="https://github.com/Deepthipriyanka004/Neuro-Nexos/blob/master/Screenshot%202025-05-03%20133956.png"/>
<img width="450px;" src="https://github.com/Deepthipriyanka004/Neuro-Nexos/blob/master/Screenshot%202025-05-03%20134011.png"/>


## Files

- **CSS:** The main styling file.
  - `body`: The background color and layout properties.
  - `.form-container`: The container for the form with padding, shadow, and rounded corners.
  - `h2`: Styling for the header inside the form.
  - `label`: Styling for labels.
  - `input` and `textarea`: Input fields and textarea with padding, borders, and responsive design.
  - `.submit-btn`: Submit button with hover effect for interactivity.

## How to Use

1. Clone the repository or copy the CSS code into your project.
2. Link the CSS file in the `<head>` section of your HTML document.
3. Create a form in HTML that includes various input fields like text, email, and select, as well as the submit button.
4. Optionally, adjust the styling to fit your project’s needs (e.g., change colors, fonts, or spacing).

### Example HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Styled Form</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="form-container">
    <h2>Contact Us</h2>
    <form>
      <label for="name">Full Name</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email Address</label>
      <input type="email" id="email" name="email" required>

      <label for="phone">Phone Number</label>
      <input type="tel" id="phone" name="phone" required>

      <label for="message">Message</label>
      <textarea id="message" name="message" rows="4" required></textarea>

      <label>Preferred Contact Method</label>
      <div class="radio-group">
        <label>
          <input type="radio" name="contact-method" value="email" checked> Email
        </label>
        <label>
          <input type="radio" name="contact-method" value="phone"> Phone
        </label>
      </div>

      <button type="submit" class="submit-btn">Submit</button>
    </form>
  </div>
</body>
</html>


# **Installation**
Download or clone the repository.

Include the styles.css file in your project.

#Customization
Feel free to modify the following properties in the CSS file to suit your design preferences:

Colors: Change the background color, input borders, and button colors.

Fonts: Modify the font-family property for a different typographic style.

Spacing: Adjust padding, margin, or form container width for your desired layout.

## 𝗟𝗶𝗰𝗲𝗻𝗰𝗲
This project is licensed under the MIT License - see the LICENSE file for details.
