# chit-calculator

📊 Chit Fund Calculator

A simple web-based application to calculate and display various aspects of a chit fund. The calculator helps users understand the payable amount, commission, profit per person, next installment, and more.

🌟 Features:

User-Friendly Interface:

Neat and responsive design using HTML and CSS.

Clean input fields for user data entry.

Styled result display for better visibility.

Core Functionalities:


Amount to be Paid: The remaining amount after deducting the bid amount from the total chit value.

Commission Calculation: 4% of the total chit value, deducted before calculating the next installment.

Base Installment: Divides the total chit value by the number of participants.

Profit Per Person: Distributed equally among all participants from the bid amount minus commission.

Next Installment: The amount to be paid in the next month, considering the profit per person.

Remaining Months: Counts the months left in the chit duration.

Copy Functionality:


Users can copy specific chit details to the clipboard for easy reference.

The "Copy Details" button selectively copies essential fields like Base Installment, Profit Per Person, Next Installment, etc.

🛠️ How It Works:
The user inputs:

Total Chit Value (e.g., ₹1,00,000)

Bid Amount (e.g., ₹80,000)

Total Participants (e.g., 20)

Current Month (e.g., 5)

Clicking the "Calculate" button performs calculations and displays the results.

The "Copy Details" button copies selected chit details to the clipboard.

📁 Code Highlights:
HTML: Structure and input fields for user interaction.

CSS: Styled for a clean and modern look.

JavaScript: Handles calculations, validation, and clipboard functionality.

Input validation ensures valid and sensible values before processing.

Uses navigator.clipboard.writeText() for clipboard access.

💻 Example:
The Webpage
![image](https://github.com/user-attachments/assets/a6c92447-3011-48a3-abf8-3d96e12754c3)

The Working
![image](https://github.com/user-attachments/assets/62631230-e55f-4bd3-9aa9-40698acd45dd)

Details Copying Funtionality
![image](https://github.com/user-attachments/assets/5830afc7-f094-42b5-b379-0bdbc44ddf54)

🔗 Conclusion:
This Chit Fund Calculator is a handy tool for quick calculations and financial planning in chit funds. It is a great example of blending web development skills with real-world finance concepts.
