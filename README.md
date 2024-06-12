Udemy Advisor Bot
Udemy Advisor Bot is a web application that helps users find the best Udemy courses for the skill they want to learn. Users can input the skill they are interested in, and the application will fetch and display the top Udemy courses for that skill using the Eden AI API.

Features
User-friendly interface for entering the desired skill.
Fetches course suggestions from Udemy using the Eden AI API.
Displays suggestions in a formatted and readable manner.
Responsive design that works on both desktop and mobile devices.
Technologies Used
HTML
CSS
JavaScript
Eden AI API
Installation
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/yourusername/udemy-advisor-bot.git
Navigate to the project directory:
bash
Copy code
cd udemy-advisor-bot
Open index.html in your preferred web browser.
Usage
Enter the skill you want to learn in the input field.
Click the "Get Suggestions" button.
Wait for the suggestions to load. The suggestions will be displayed in the output section.
Code Structure
index.html: The main HTML file that structures the web page.
styles.css: The CSS file that styles the web page.
script.js: The JavaScript file that handles the API requests and DOM manipulation.
API
This project uses the Eden AI API to fetch course suggestions. The API key is included in the JavaScript code.

javascript
Copy code
const apiKey = 'YOUR_API_KEY_HERE';
Replace 'YOUR_API_KEY_HERE' with your actual API key.

File Descriptions
index.html
Contains the HTML structure for the page.
Includes the input field for entering the skill, a button to fetch suggestions, and a section to display the output.
styles.css
Styles the web page, including the header, input container, output container, and footer.
Includes responsive design for different screen sizes.
script.js
Handles the API requests to Eden AI.
Fetches course suggestions based on the user's input.
Formats and displays the fetched suggestions.
Customization
Update the apiKey variable in script.js with your own Eden AI API key.
Modify the styles in styles.css to match your desired look and feel.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
Developed by Tapoprasad Tripathy.
Uses Eden AI API for fetching Udemy course suggestions.

If you have any questions or suggestions, feel free to contact me at tapoprasad@gmail.com
