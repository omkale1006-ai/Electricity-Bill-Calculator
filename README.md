⚡ Electricity Bill Calculator - Python Project
Welcome to the Electricity Bill Calculator – a simple Python project that lets users calculate electricity bills based on unit usage with defined slab rates. It’s a beginner-friendly project perfect for understanding conditional logic, input validation, and real-world utility billing.

📋 Features
Accepts user input for electricity units.

Implements real-world slab rules:

✅ First 100 units: No charge

✅ Next 100 units (101–200): ₹5 per unit

✅ Beyond 200 units: ₹10 per unit

Displays a detailed breakdown of the bill.

Handles invalid inputs gracefully.

🚀 Technologies Used
Component	Technology
Programming	Python 3
I/O Operations	input() / print()
Error Handling	try-except block

🧠 How It Works
python
Copy
Edit
if units <= 100:
    amount = 0
elif units <= 200:
    amount = (units - 100) * 5
else:
    amount = (100 * 5) + ((units - 200) * 10)
🧪 Example Usage
bash
Copy
Edit
🔢 Enter the number of units used: 250
🧮 Calculating your bill...

💰 Chargeable Units: 100 units @ ₹5 = ₹500
💰 Extra Units: 50 units @ ₹10 = ₹500
💰 Total Bill Amount: ₹1000
📦 How to Run
Clone or download this repository.

Open the file in any Python environment or IDE.

Run the Python script:

bash
Copy
Edit
python electricity_bill_calculator.py
Enter your unit usage and get your bill instantly.

🎯 Why This Project?
This mini project is great for:

Python beginners

College assignments

Practicing if-elif conditions

Real-world billing logic simulation

✍️ Author
Made with 💡 by Om Nagnath Kale
