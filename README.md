# Agarwal Enterprises - E-Commerce Website 🌿

A beautiful, mobile-friendly e-commerce platform with **daily price update system** and **green theme**.

---

## 🎨 Features

✅ **Green Color Theme** - Fresh, natural, organic aesthetic  
✅ **741 Products** - All your closing stock products integrated  
✅ **Search & Filter** - Find products by name or category  
✅ **Daily Price Updates** - Easy CSV upload system  
✅ **Shopping Cart** - Add products and manage quantities  
✅ **WhatsApp Orders** - Send orders directly via WhatsApp  
✅ **Mobile Responsive** - Works perfectly on all devices  
✅ **Local Data Storage** - Price changes saved on device  

---

## 📁 Files Included

1. **index.html** - Main website file (contains all code)
2. **products.json** - All 741 products with pricing and categories
3. **price_update_template.csv** - Template for daily price updates

---

## 🚀 How to Deploy

### Option 1: GitHub Pages (Free & Easy)

1. Create a new GitHub repository named `agarwal-enterprises`
2. Upload `index.html`, `products.json`, and `price_update_template.csv` to the repo
3. Go to Settings → Pages → Enable GitHub Pages
4. Your site will be live at: `https://yourusername.github.io/agarwal-enterprises`

### Option 2: Any Web Hosting

1. Upload `index.html` to your web hosting
2. Site will work immediately (no backend needed)

---

## 📝 How to Update Prices Daily

### Step 1: Create a CSV File
Create a spreadsheet with these columns:
```
name, mrp, cost, profit_margin
```

Example:
```
PAT NUTRELA ORG OMEGA 3 6 7 9, 551, 385.70, 30
PAPAD KALI MIRCH - T, 55, 38.50, 30
```

### Step 2: Update on Website
1. Click **"⚙️ Update Prices"** button on the website
2. Click **"Upload CSV with Price Updates"**
3. Select your CSV file
4. ✅ Prices are updated instantly!

### Step 3: Export Your Data
Use the included `price_update_template.csv` as a starting point. You can:
- Edit in Excel
- Edit in Google Sheets
- Edit in any CSV editor

---

## 🔧 Product Data Structure

Each product has:
```json
{
  "id": 1,
  "name": "Product Name",
  "category": "Category Name",
  "mrp": 551,
  "cost": 385.70,
  "profit_margin": 30,
  "stock": 55,
  "description": "Product details"
}
```

**Fields Explained:**
- `name` - Product name
- `category` - Product category (for filtering)
- `mrp` - Selling price (what customers pay)
- `cost` - Your cost price (for calculating profit)
- `profit_margin` - Percentage profit (30% = customer pays 30% more than cost)
- `stock` - Available quantity
- `description` - Product description

---

## 💡 Tips for Daily Updates

### Batch Price Changes
1. Export current prices from the website
2. Update multiple products in one CSV
3. Upload the CSV once to update all prices

### Creating the CSV File

**In Excel:**
1. Open Excel
2. Create columns: name, mrp, cost, profit_margin
3. Add your products
4. Save as CSV (File → Save As → Format: CSV)

**In Google Sheets:**
1. Create a spreadsheet
2. Add your data
3. Download as CSV (File → Download → CSV)

**Quick Example CSV:**
```
name,mrp,cost,profit_margin
CHANA DAL 500 GM,65,45.5,30
TURMERIC POWDER 200 GM,82,57.4,30
```

---

## 📊 All 741 Products Included

Products across 135 categories:
- **Groceries** - Oils, Pulses, Rice, Flour, Spices
- **Beauty & Personal Care** - Soaps, Creams, Oils, Toothpaste
- **Cleaning Products** - Detergent, Floor Cleaner, Dish Wash
- **Health & Medicines** - Supplements, Vitamins, Ayurvedic Products
- **And 131 more categories!**

---

## 🎯 How Customers Use It

1. **Browse** - Customers see all products with prices
2. **Search** - Find specific products instantly
3. **Add to Cart** - Click "Add +" to add products
4. **Checkout** - Enter delivery address
5. **Order** - Send order via WhatsApp
6. **Confirmation** - You receive order on WhatsApp

---

## 💚 Green Color Theme

Professional green palette:
- **Primary Green:** #10B981 (buttons, highlights)
- **Dark Green:** #059669 (hover states)
- **Light Green:** #D1FAE5 (backgrounds)
- **Pale Green:** #F0FDF4 (base background)

---

## 🔐 Data Privacy

✅ All data stored locally on user's device  
✅ No data sent to external servers  
✅ Works 100% offline after first load  
✅ Safe for customer information  

---

## ⚙️ Customization

### Change WhatsApp Number
Edit line in `index.html`:
```javascript
window.open(`https://wa.me/919057529646?text=${encoded}`, '_blank');
```

Replace `919057529646` with your WhatsApp number.

### Change Business Name
Edit the header in `index.html`:
```javascript
<h1>🌿 Agarwal Enterprises</h1>
<p>Fresh Products Delivered Daily to Your Doorstep</p>
```

### Add More Products
Edit `products.json` or use the CSV import feature.

---

## 🐛 Troubleshooting

**Q: CSV upload not working?**
- Make sure column headers match: `name, mrp, cost, profit_margin`
- Product names must match exactly (case-sensitive)

**Q: Prices not showing?**
- Try opening in a different browser
- Clear browser cache (Ctrl+Shift+Delete)
- Check browser console for errors (F12)

**Q: WhatsApp not opening?**
- Make sure you have WhatsApp installed
- Update your WhatsApp number in the code

---

## 📱 Mobile Optimization

The website is fully optimized for:
- ✅ iPhone & iPad
- ✅ Android phones
- ✅ Tablets
- ✅ Desktop computers

Perfect for customers to order from their phones!

---

## 📞 Support

For issues or questions:
1. Check this README first
2. Test in different browser
3. Clear browser cache
4. Make sure CSV format is correct

---

## 🎉 You're All Set!

Your e-commerce platform is ready to use with:
- ✅ 741 products
- ✅ Green theme
- ✅ Daily price updates
- ✅ WhatsApp integration

**Next Steps:**
1. Upload files to GitHub Pages or web hosting
2. Test on mobile
3. Share with customers
4. Update prices daily via CSV

Good luck with Agarwal Enterprises! 🌿💚
