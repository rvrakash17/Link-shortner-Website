# Link Shortener Website

A simple and interactive web application for shortening URLs. Users can input a long URL, and the application will provide a shortened version using the [SHRTCO API](https://shrtco.de/).

## Features

- **URL Shortening:** Shortens long URLs into short, easy-to-share links.
- **Copy to Clipboard:** Allows users to copy the shortened URL to their clipboard.
- **Responsive Design:** Works across different devices and screen sizes.

## Technologies Used

- **HTML:** Structure and markup of the web page.
- **CSS:** Styling and layout of the page.
- **JavaScript:** Functionality for URL shortening and clipboard operations.
- **SHRTCO API:** API service for shortening URLs.

## Installation

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/rvrakash17/Link-shortner-Website.git
   cd Link-shortner-Website
   ```

2. **Project Structure:**
   Ensure your project directory contains the following files:
   - `index.html` (HTML file for the structure)
   - `style.css` (CSS file for styling)
   - `app.js` (JavaScript file for functionality)

3. **Open the Project:**
   Open `index.html` in a web browser to view and use the link shortener.

## Usage

1. **Shortening a URL:**
   - Enter the long URL into the input field.
   - Click the "Shorten it!" button to get the shortened URL.
   - The shortened URL will be displayed, and you can copy it to your clipboard.

2. **Copy to Clipboard:**
   - Click the "Copy" button next to the shortened URL to copy it to your clipboard.

## Code Explanation

### HTML Structure

- **Header:**
  - Navigation menu with links to "RVR Groups" and "Link shortener."

- **Main Section:**
  - Input form for shortening URLs.
  - A section to display the shortened URL results.

### CSS Styling

- **Global Styles:**
  - Resets margin and padding, sets box-sizing to border-box.
  - Applies the Poppins font and adjusts body margins.

- **Header Styles:**
  - Flexbox layout for header navigation with spacing and alignment.

- **Form Styles:**
  - Styles for the input field and button within the form.
  - Background color, padding, and border-radius for input and button.

- **Result Styles:**
  - Displays the shortened URLs in a list format.
  - Styles for the "Copy" button.

### JavaScript Functionality

- **Select Elements:**
  - A utility function to select DOM elements.

- **Form Submission:**
  - Handles form submission to prevent default behavior.
  - Calls `shortenUrl()` with the user-provided URL.

- **Shorten URL Function:**
  - Sends a request to the SHRTCO API to shorten the URL.
  - Updates the DOM with the shortened URL and a "Copy" button.
  - Adds an event listener to the "Copy" button to copy the URL to the clipboard.

## Author

- **Akash R**
