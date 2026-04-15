# 🧾 Tax Invoice Generator - Water Innovation Systems

A simple, professional **web-based Tax Invoice Generator** designed for business use.  
This tool allows you to create, calculate, and print GST-compliant invoices easily.

---

## 🚀 Features

- ✅ Clean and professional invoice layout
- ✅ Dynamic item entry (Add unlimited products/services)
- ✅ Automatic calculation:
  - Total Before Tax
  - CGST @ 9%
  - SGST @ 9%
  - Total GST
  - Grand Total
- ✅ Vendor / Buyer details input section
- ✅ Invoice details section (Invoice No, Date, E-way bill, etc.)
- ✅ Print-ready format
- ✅ Company logo support
- ✅ Lightweight (No external libraries required)


## ⚙️ How to Use

1. Open `index.html` in any modern web browser.
2. Enter invoice details:
   - Invoice Number
   - Date
   - Buyer details
   - Payment details
3. Add items using **"Add Item"** button.
4. Enter:
   - Quantity
   - Rate
5. Click **"Calculate"** to auto-generate totals.
6. Click **"Print"** to print or save as PDF.

---

## 🧮 Tax Calculation Logic

- CGST = 9% of Subtotal  
- SGST = 9% of Subtotal  
- Total GST = CGST + SGST  
- Grand Total = Subtotal + GST  


Replace the logo path in HTML:

html

<img src="logo.png" class="logo">
