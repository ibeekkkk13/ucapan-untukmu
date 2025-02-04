# Morning Greeting Program - HTML

## Description
This simple HTML program provides an interactive greeting to users, offering motivational words to brighten their morning. The design includes a button that reveals an uplifting message when clicked.

## Features
- Full-screen responsive layout with vibrant gradient background.
- A motivational message that appears upon clicking the button.
- Clean and modern styling with button hover effects.

## Usage Instructions
1. Open the HTML file in any modern web browser.
2. You will see a greeting "Selamat Pagi!" and a prompt to click a button.
3. Click the "Klik untuk Semangat!" button.
4. The motivational message will appear below the button.

## File Structure
```
index.html  - Main program file
```

## Code Breakdown
### HTML Structure
- A `<div>` container wraps the title, button, and message elements.
- The button triggers a simple JavaScript function to display the hidden message.

### Styling
- Flexbox is used for centering elements on the screen.
- Linear gradient background enhances the visual appearance.
- Buttons have hover effects for better user interaction.

### JavaScript Functionality
```javascript
function showMessage() {
  document.getElementById('message').style.display = 'block';
}
```
This function unhides the motivational message when the button is clicked.

## Compatibility
- Compatible with all major modern browsers, including Chrome, Firefox, Edge, and Safari.

## Customization
- Modify the message inside `<div id="message">` to fit your preference.
- Update color schemes in the CSS section to match your brand.

## Author
Created as a friendly motivational tool using simple web technologies.
