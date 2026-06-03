# 📦 Daily Stock & Price Update Guide

## ✅ What You Can Now Update

Your CSV file can now update **both prices AND quantities**:
- ✅ MRP (selling price)
- ✅ Cost (your cost price)
- ✅ Stock (quantity available)
- ✅ Profit Margin (optional)

---

## 📝 CSV Format

### Required Columns:
```
name, mrp, cost, stock, profit_margin
```

### Example CSV:

```csv
name,mrp,cost,stock,profit_margin
PAT NUTRELA ORG OMEGA 3 6 7 9,551,385.70,55,30
PAPAD KALI MIRCH - T,55,38.50,16,30
CHANA DAL 500 GM (R1),65,45.50,6,30
MOONG SABUT 500 GM (R1),80,56,8,30
RICE BRAN OIL 1 LTR (B) - T,180,126,15,30
VIRGIN COCONUT OIL 500 ML (B) - T,365,255.50,20,30
VERMICELLI ROASTED 400 GM - T,45,31.50,25,30
SESAME OIL 1 L (B)-T,260,182,12,30
```

---

## 🎯 Step-by-Step: Update Prices & Stock

### Option 1: Using Excel

**1. Open Excel (or Google Sheets)**

**2. Create Your Data:**
```
Column A: Product Name (must match exactly)
Column B: MRP (new selling price)
Column C: Cost (your cost)
Column D: Stock (new quantity)
Column E: Profit Margin (optional)
```

**3. Example Data:**
| name | mrp | cost | stock | profit_margin |
|------|-----|------|-------|---------------|
| CHANA DAL 500 GM (R1) | 68 | 47.60 | 10 | 30 |
| TURMERIC POWDER 200 GM | 85 | 59.50 | 20 | 30 |
| VERMICELLI 400 GM | 48 | 33.60 | 35 | 30 |

**4. Save as CSV:**
- File → Save As
- Format: CSV (Comma Separated Values)
- Name: `daily_update.csv`

### Option 2: Using Google Sheets

**1. Open Google Sheets**

**2. Create Headers:**
```
A1: name
B1: mrp
C1: cost
D1: stock
E1: profit_margin
```

**3. Add Your Data:**
```
Row 2: CHANA DAL 500 GM (R1), 68, 47.60, 10, 30
Row 3: TURMERIC POWDER 200 GM, 85, 59.50, 20, 30
```

**4. Download as CSV:**
- File → Download → Comma Separated Values (.csv)

---

## 🚀 Upload to Website

### 1. Open Your Website
```
https://your-github-username.github.io/agarwal-enterprises
```

### 2. Click "⚙️ Update Prices" Button
You'll see the admin panel

### 3. Click "Upload CSV with Price & Stock Updates"

### 4. Select Your CSV File
Choose the file you created

### 5. Success!
✅ System will confirm how many products were updated

---

## 📋 Important Notes

### Product Name Matching
- **Names MUST match exactly** (case-sensitive)
- Example: If your database has `CHANA DAL 500 GM (R1)`, your CSV must have exactly that
- Even extra spaces will cause non-matching

### Optional Columns
You DON'T have to update all columns:
- ✅ Update only prices (leave stock blank)
- ✅ Update only stock (leave mrp blank)
- ✅ Update both at once
- ✅ Update profit margin

### Example: Update Only Stock (Keep Prices Same)
```csv
name,mrp,cost,stock
CHANA DAL 500 GM (R1),,, 25
TURMERIC POWDER 200 GM,,, 40
VERMICELLI 400 GM,,, 50
```

### Example: Update Only Prices (Keep Stock Same)
```csv
name,mrp,cost,stock
CHANA DAL 500 GM (R1),70,49,
TURMERIC POWDER 200 GM,90,63,
VERMICELLI 400 GM,50,35,
```

---

## 💡 Daily Workflow Example

### Monday Morning:
1. Check inventory (count physical stock)
2. Check prices (any market changes?)
3. Create Excel file with updates:
   - Products with new prices
   - Products with new stock levels

### Monday Afternoon:
1. Open website
2. Click "⚙️ Update Prices" 
3. Upload CSV
4. Refresh website to see changes
5. Share updated link with customers

### Daily:
- Repeat steps 1-5 as needed
- Update prices based on demand/supply
- Update quantities after each sale

---

## 📊 Real-World Example

### Scenario: Monday Morning Update

**Your Inventory Check:**
- CHANA DAL: Old price ₹65, new price ₹68, in stock 10 units
- TURMERIC: Old price ₹82, new price ₹90, in stock 20 units
- RICE OIL: Old price ₹180, in stock 15 units (price unchanged)

**Your CSV File:**
```csv
name,mrp,cost,stock
CHANA DAL 500 GM (R1),68,47.60,10
TURMERIC POWDER 200 GM,90,63,20
RICE BRAN OIL 1 LTR (B) - T,180,126,15
```

**Result:**
- ✅ CHANA DAL: Price updated to ₹68, stock set to 10
- ✅ TURMERIC: Price updated to ₹90, stock set to 20
- ✅ RICE OIL: Stock confirmed at 15 (price unchanged)

---

## 🔍 Troubleshooting

### "Products not updating?"
**Solution:** Check if product names match exactly
```
Database: CHANA DAL 500 GM (R1)
CSV:      CHANA DAL 500 GM (R1)  ✅ Matches

Database: CHANA DAL 500 GM (R1)
CSV:      CHANA DAL 500 GM      ❌ Doesn't match (missing R1)
```

### "Stock showing as 0?"
**Solution:** Make sure you included the stock number
```csv
name,mrp,cost,stock
CHANA DAL 500 GM (R1),68,47.60,10  ✅ Stock: 10
CHANA DAL 500 GM (R1),68,47.60,    ❌ Stock: blank
```

### "CSV won't upload?"
**Solution:** 
- Make sure it's actually saved as .CSV (not .XLS or .XLSX)
- Try Excel → Save As → CSV (Comma delimited) (.csv)
- Check file size (should be small, under 1MB)

### "Changed wrong product?"
**Solution:**
- Double-check names before uploading
- Take screenshot of CSV before uploading
- Can upload again with correct data (overwrites old data)

---

## 💾 Best Practices

### 1. Keep Backup
Save a copy of your weekly updates:
```
2024-Jan-01_prices.csv
2024-Jan-08_prices.csv
2024-Jan-15_prices.csv
```

### 2. Template Method
Create a master Excel file:
- Copy all product names once
- Reuse it each day (just change prices/stock)
- Much faster than recreating every day

### 3. Batch Updates
Update multiple products at once instead of one-by-one

### 4. Consistency
- Update at the same time daily
- Keeps customers expecting fresh prices
- Builds trust

### 5. Verify After Upload
- Click "⚙️ Update Prices" again
- Scroll through and verify changes
- Makes sure update was successful

---

## 🎓 Example Templates

### Template 1: Minimal Update (Just New Prices)
```csv
name,mrp,cost,stock
CHANA DAL 500 GM (R1),68,47.60,
TURMERIC POWDER 200 GM,90,63,
RICE BRAN OIL 1 LTR (B) - T,185,129.50,
```

### Template 2: Full Update (Everything)
```csv
name,mrp,cost,stock,profit_margin
CHANA DAL 500 GM (R1),68,47.60,10,30
TURMERIC POWDER 200 GM,90,63,20,30
RICE BRAN OIL 1 LTR (B) - T,185,129.50,15,30
VERMICELLI 400 GM,50,35,25,30
```

### Template 3: Bulk Stock Update
```csv
name,mrp,cost,stock
PAT NUTRELA ORG OMEGA 3 6 7 9,,, 40
PAPAD KALI MIRCH - T,,, 20
CHANA DAL 500 GM (R1),,, 15
MOONG SABUT 500 GM (R1),,, 8
RICE BRAN OIL 1 LTR (B) - T,,, 12
```

---

## 📱 Mobile-Friendly Updates

You can even update on your phone:
1. Create CSV in Google Sheets on your phone
2. Download as CSV
3. Open website on phone
4. Click "⚙️ Update Prices"
5. Upload CSV from phone
6. Done!

---

## ⏰ Recommended Update Schedule

### Daily (Morning):
- Update stock levels
- Adjust prices based on stock
- Share with customers

### Weekly (Sunday):
- Review performance
- Plan for week ahead
- Adjust bulk prices

### Seasonal (Monthly):
- Major price changes
- Seasonal product swaps
- Promotion planning

---

## 🎯 Pro Tips

**Tip 1:** Use Excel's auto-fill
- Enter price formula once
- Copy down to fill others
- Saves time for bulk updates

**Tip 2:** Color-code changes
- Highlight cells with changes
- Take screenshot before upload
- Reference if needed

**Tip 3:** Keep product names consistent
- Same naming = easier matching
- Copy-paste from website once
- Reuse in all future CSVs

**Tip 4:** Update during low-traffic time
- Update early morning or late night
- Customers won't see partial updates
- Ensures consistency

---

## 📊 What Gets Updated

✅ **Updates Instantly:**
- Product prices (MRP)
- Stock quantities
- Cost prices
- Profit margins

✅ **Updates for Next Customer:**
- Stock availability status
- "Add" button enable/disable (if out of stock)

❌ **Won't Update (Past Orders):**
- Previous customer orders
- Order history
- Old cart data

---

## 🔒 Data Safety

- ✅ All updates saved locally
- ✅ No cloud storage
- ✅ No data sent to servers
- ✅ Your data is secure
- ✅ Updates persist across refreshes

---

## 🎉 You're Ready!

Now you can:
- ✅ Update prices daily
- ✅ Update stock quantities
- ✅ Update profit margins
- ✅ All from a simple CSV file
- ✅ In seconds!

**Start updating your products today!** 📈

---

## 📞 Quick Reference

| Task | Steps |
|------|-------|
| Update Prices | Create CSV → Upload → Done |
| Update Stock | Create CSV → Upload → Done |
| Update Both | Create CSV with both columns → Upload → Done |
| Check Updates | Click "⚙️ Update Prices" → View table |
| Find Product Name | Click "⚙️ Update Prices" → Search table |

---

**Happy Updating!** 💚
