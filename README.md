# WebProject1
Objective: Create a Random Password Generator that allows users to generate secure passwords using various character types (uppercase, lowercase, numbers, symbols), and provides a copy-to-clipboard feature with confirmation notification. This project helps reinforce string manipulation, DOM events, clipboard API, and notification design.
Objective:
Create a Random Password Generator that allows users to generate secure passwords using various character types (uppercase, lowercase, numbers, symbols), and provides a copy-to-clipboard feature with confirmation notification. This project helps reinforce string manipulation, DOM events, clipboard API, and notification design.

📷 Output:

A clean interface with password display, copy icon, and generate button.

✅ Requirements:
🔹 Features to Implement:
1. Password Display Area:
Read-only input field to display the generated password


Copy icon inside the input field to copy the password


2. Generate Password Button:
Button labeled "Generate Password"


On click, generates a random password from:


Uppercase letters (A-Z)


Lowercase letters (a-z)


Numbers (0-9)


Special characters (!@#$%^&* etc.)


3. Copy Functionality:
On clicking the copy icon:


The password is copied to clipboard


A visual notification appears (e.g., "Password Copied!")



🌟 Bonus Features (Advanced):
🔘 Checkbox to select character types: Uppercase, Lowercase, Numbers, Symbols


🔢 Password length selector (e.g., slider or number input)


🌓 Dark/Light mode toggle


🔄 Auto-regenerate after timer (for extra security)


📊 Password strength indicator (e.g., weak, medium, strong)



💻 Tech Stack:
HTML: Structure for title, input, buttons


CSS: Modern container styling, responsive layout, copy icon design


JavaScript: Generate password, copy to clipboard, show notification



✅ Design & UX Guidelines:
Keep a clean UI with good spacing


Use modern fonts and icons (e.g., Font Awesome for copy icon)


Ensure notification is visually distinct and fades after 2–3 seconds


Responsive for both desktop and mobile views


Password input should be read-only with visually obvious styling



🛠 Development Guidelines:
Use Math.random() and character sets to build password


Use navigator.clipboard.writeText() for copying


Use setTimeout() to auto-hide notifications


Encapsulate logic in functions like generatePassword(), copyPassword()


Add icons using <i class="fa fa-copy"> or SVG



⏳ Timeline:
Finish this assignment in 1.5 to 2 hours

📦 Deliverables:
✅ Live App URL (GitHub Pages / Netlify / Vercel)


✅ GitHub Repository with clean code and modular JS


✅ README.md including:


Overview of the app


Features implemented


Screenshots of the UI


How to run the app locally


Optional features included

Reference video Link:
https://1drv.ms/v/c/e9e8b87622fb1ae5/ERDwm_BPLT5JowQIw1v-_OwB7toNXqYpeAYJTdZd6OzWdw
