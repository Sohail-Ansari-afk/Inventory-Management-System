# 📦 Inventory Management System (Tkinter GUI)

A beginner-friendly desktop app to manage inventory using Python's `tkinter`. Track items, update stocks, search inventory, and export to CSV — all through a clean GUI! 🎯

---

## 🖥️ Features

✅ Add new items  
✅ Update existing item quantity or price  
✅ Delete items  
✅ Search inventory  
✅ Export inventory data to CSV  
✅ Tabular display using `ttk.Treeview`

---

## 🛠️ Requirements

- Python 3.x
- Standard libraries only (`tkinter`, `csv`) — no installation needed! 🎉

---

## ▶️ How to Run

1. 🧾 Download the script: `inventory management system.py`

2. 💻 Open a terminal and navigate to the file’s location.

3. 🏃‍♂️ Run the app:

   ```bash
   python "inventory management system.py"
````

4. 🖱️ The GUI window will open and you can begin managing inventory right away.

---

## 🧪 Usage Steps

### ➕ Add an Item

* Enter **Item Name**, **Quantity**, and **Price**
* Click **"Add Item"**
* The item appears in the table 📋

### ✏️ Update an Item

* Enter the **existing Item Name**
* Modify Quantity or Price
* Click **"Update Item"**

### 🗑️ Delete an Item

* Enter the **Item Name**
* Click **"Delete Item"**

### 🔍 Search for an Item

* Enter the **Item Name**
* Click **"Search Item"**
* Quantity and Price will auto-fill the fields

### 📤 Export to CSV

* Click **"Export CSV"**
* Creates a file `inventory_export.csv` with all data including totals

---

## 📂 Example Output (CSV)

| Item     | Quantity | Price | Total  |
| -------- | -------- | ----- | ------ |
| Monitor  | 10       | 120.5 | 1205.0 |
| Keyboard | 5        | 45.99 | 229.95 |

---

## 🧑‍💻 Author

Crafted with ❤️ using `tkinter` and a pinch of Python.

---

## 🧹 Notes

* All data is stored in memory only 🧠 (no persistent database).
* Make sure to **export** if you want to save your data.

---

Happy Inventorying! 📦📊🧾


