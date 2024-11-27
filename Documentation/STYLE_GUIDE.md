# Style Guide for Community Support Tracker


## Fonts
- **Primary Font**: Arial, sans-serif 
- **Secondary Font**: Georgia, serif 

## Colors
- **Primary Blue**: #007BFF (Use for buttons, navigation, and accents)
- **Dark Blue**: #0056B3 (Use for hover states)
- **Light Gray**: #F8F9FA (Background color)
- **Text Gray**: #212529 (Text color)
- **Cyan Accent**: #17A2B8 (Highlight elements like active links)
- **Error Red**: #DC3545 (For error messages)

## Buttons
- **Default**:
  - Background: #007BFF
  - Text: White
  - Border: 2px solid #0056B3
  - Border Radius: 5px
- **Hover**:
  - Background: #0056B3

## Navigation
- **Default**:
  - Background: #007BFF
  - Text: White
- **Hover**:
  - Text changes to #17A2B8 (Cyan Accent)

## Forms
- **Input Fields**:
  - Border: 1px solid #007BFF
  - Background: White
  - Text: #212529
  - Focus: Border changes to #0056B3
- **Error Messages**:
  - Color: #DC3545 (Red)

## Tables
- **Header**:
  - Background: #007BFF
  - Text: White
- **Rows**:
  - Odd: #F8F9FA (Light Gray)
  - Even: White
- **Hover**:
  - Background: #E9ECEF

## Spacing
- **Padding**:
  - Containers: 20px
  - Buttons: 10px 20px
- **Margin**:
  - Sections: 30px between each section

## Accessibility
- Use clear focus outlines for inputs and links.
- Ensure contrast between text and background colors.

## Media Queries
- Adjust font sizes and layouts for smaller screens.
- Use a collapsible menu for navigation on mobile devices.

---

### Example CSS (for Reference)

```css
/* General */
body {
    font-family: 'Roboto', sans-serif;
    color: #212529;
    background-color: #F8F9FA;
    margin: 0;
    padding: 0;
}

/* Header */
header {
    background-color: #007BFF;
    color: #FFFFFF;
    text-align: center;
    padding: 15px;
}

nav a {
    color: #FFFFFF;
    margin: 0 10px;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    color: #17A2B8;
}

/* Buttons */
button {
    background-color: #007BFF;
    color: #FFFFFF;
    border: 2px solid #0056B3;
    border-radius: 5px;
    padding: 10px 20px;
    cursor: pointer;
}

button:hover {
    background-color: #0056B3;
}

/* Forms */
input, textarea {
    border: 1px solid #007BFF;
    border-radius: 5px;
    padding: 10px;
    width: 100%;
}

input:focus, textarea:focus {
    border: 1px solid #0056B3;
    outline: none;
}

/* Footer */
footer {
    background-color: #F8F9FA;
    color: #212529;
    text-align: center;
    padding: 10px;
}
