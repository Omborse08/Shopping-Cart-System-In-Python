# 🛒 Python Mini Shopping Cart System

## 📌 Overview
This is a simple **command-line shopping cart program** written in Python.  
It allows users to browse items from different categories, add them to their cart, calculate the final bill (including tax and optional coupon discount), and save the bill as a text file.

---

## 🚀 Features
- **Category Selection:** Fruits, Snacks, and Electronics.
- **Add to Cart:** Add items with custom quantity.
- **Checkout System:**
  - Displays cart details.
  - Calculates tax (10%).
  - Optional coupon discount (`SAVE10`).
  - Saves bill to `Bill.txt` with timestamp.
- **User-Friendly Navigation:** Uses `match-case` for cleaner menu handling.

---

## 📂 Project Structure
```
shopping_cart.py     # Main Python script
Bill.txt             # Generated bill file after checkout
```

---

## 💻 How to Run
1. Make sure you have **Python 3.10+** installed.
2. Save the code as `shopping_cart.py`.
3. Open a terminal and run:
   ```bash
   python shopping_cart.py
   ```
4. Follow the on-screen menu to shop and checkout.

---

## 🖼 Example Usage
```
1. Fruits
2. Snacks
3. Electronics
4. Checkout
5. Exit
>> 1
- apple ₹30
- banana ₹10
- mango ₹20
Enter Items To Add: apple
Enter Qty: 2
> apple Added To Cart
Do you want to add more (y/n): n
```

---

## 📜 Bill Example
```
Bill - (2025-08-09 22:15:42.652378)
Name: apple   Qty: 2   Price: 30
Tax (10%): 6.0
Discount: 10
Final Total: 56.0
```

---

## 🛠 Technologies Used
- **Python 3.10+** (`match-case` statement)
- **datetime** module for timestamping bills.

---

## 📌 Future Improvements
- Add item removal feature.
- Save and load cart from file.
- Add inventory stock tracking.
