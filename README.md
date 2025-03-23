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
If the user enters:

Total Chit Value: ₹1,00,000

Bid Amount: ₹80,000

Total Participants: 20

Current Month: 5

The calculator displays:

Amount to be Paid: ₹20,000

Commission: ₹4,000

Base Installment: ₹5,000

Profit Per Person: ₹3,800

Next Installment: ₹1,200

Remaining Months: 15

🔗 Conclusion:
This Chit Fund Calculator is a handy tool for quick calculations and financial planning in chit funds. It is a great example of blending web development skills with real-world finance concepts.
