# 🚀 Quick Setup Guide - Deploy Your Website in 5 Minutes

## Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. Name it `agarwal-enterprises` (or any name)
3. Make it **Public**
4. Click **Create Repository**

---

## Step 2: Upload Files

You need these 3 files:
- ✅ `index.html` - Main website
- ✅ `products.json` - All 741 products with prices
- ✅ `price_update_template.csv` - Example for price updates

**Upload method 1 - GitHub Web:**
1. Open your new repository
2. Click **Add file → Upload files**
3. Drag and drop the 3 files
4. Click **Commit changes**

**Upload method 2 - Git Command:**
```bash
git clone https://github.com/YOUR_USERNAME/agarwal-enterprises.git
cd agarwal-enterprises
# Copy the 3 files here
git add .
git commit -m "Initial commit - Add website"
git push origin main
```

---

## Step 3: Enable GitHub Pages

1. Go to your repository
2. Click **Settings** (top menu)
3. Click **Pages** (left sidebar)
4. Under "Build and deployment":
   - Source: Select **Deploy from a branch**
   - Branch: Select **main** and **/(root)**
5. Click **Save**
6. Wait 1-2 minutes for deployment

---

## Step 4: Get Your Website URL

Your site will be live at:
```
https://YOUR_USERNAME.github.io/agarwal-enterprises
```

**Example:**
- If username is `priyanka-agarwal`
- URL will be: `https://priyanka-agarwal.github.io/agarwal-enterprises`

---

## Step 5: Share & Test

1. Open the URL in your browser
2. Test on mobile (most important!)
3. Try adding products to cart
4. Test WhatsApp order button
5. Share with customers!

---

## Daily Price Updates

### Every day, to update prices:

1. **Create CSV file** with new prices:
   - Excel: Create columns `name`, `mrp`, `cost`
   - Add your products and prices
   - Save as CSV

2. **Open website**

3. **Click "⚙️ Update Prices"** button

4. **Upload CSV file**

5. **Done!** Prices updated instantly ✅

---

## Example CSV Format

Create this in Excel/Google Sheets:

| name | mrp | cost | profit_margin |
|------|-----|------|---------------|
| CHANA DAL 500 GM | 65 | 45.50 | 30 |
| TURMERIC POWDER 200 GM | 82 | 57.40 | 30 |
| RICE BRAN OIL 1L | 180 | 126 | 30 |
| VERMICELLI 400 GM | 45 | 31.50 | 30 |

---

## Customization

### Change Your WhatsApp Number

Edit `index-full.html` or `index.html`:

Find this line (around line 700):
```javascript
window.open(`https://wa.me/919057529646?text=${encoded}`, '_blank');
```

Replace `919057529646` with your WhatsApp number (with country code):
```javascript
window.open(`https://wa.me/91XXXXXXXXXX?text=${encoded}`, '_blank');
```

### Change Business Name

Find this section:
```javascript
<h1>🌿 Agarwal Enterprises</h1>
<p>Fresh Products Delivered Daily to Your Doorstep</p>
```

Replace with your business name.

---

## File Descriptions

| File | Purpose |
|------|---------|
| `index.html` | Main website (simpler, starts with sample products) |
| `index-full.html` | Full version (loads all 741 products from products.json) |
| `products.json` | All 741 products with categories and pricing |
| `price_update_template.csv` | Template for creating price updates |
| `README.md` | Detailed documentation |

**Use `index.html` OR `index-full.html`, not both.**

**Recommendation:** Use `index-full.html` and rename it to `index.html`

---

## Troubleshooting

**Q: Website not loading?**
- Wait 5 minutes after uploading
- Check repository settings (Pages should be enabled)
- Clear browser cache (Ctrl+Shift+Delete)

**Q: Products not showing?**
- Make sure `products.json` is uploaded
- Check browser console (F12) for errors
- If using `index.html`, products are hardcoded (should always show)

**Q: CSV upload not working?**
- Check column names match: `name, mrp, cost`
- Product names must match exactly (case-sensitive)
- Try a different browser

**Q: WhatsApp not opening?**
- Install WhatsApp on your device
- Check WhatsApp number is correct (include country code)
- Make sure you're using HTTPS (not HTTP)

---

## Colors Included

Your website uses a beautiful **Green Theme**:

| Color | Usage |
|-------|-------|
| 🟢 `#10B981` | Primary buttons, highlights |
| 🟢 `#059669` | Dark green, hover states |
| 🟢 `#D1FAE5` | Light green backgrounds |
| 🟢 `#F0FDF4` | Pale green, page background |

---

## Features Summary

✅ **All 741 Products** - From your closing stock  
✅ **Green Theme** - Fresh, professional, modern  
✅ **Search & Filter** - Find products instantly  
✅ **Daily Price Updates** - CSV upload system  
✅ **Shopping Cart** - Add & manage items  
✅ **WhatsApp Orders** - Direct integration  
✅ **Mobile Responsive** - Works on all devices  
✅ **Cost Tracking** - See profit margins  
✅ **Stock Display** - Show available quantity  
✅ **No Backend** - Runs 100% in browser  

---

## Support

If you need help:

1. **Check README.md** - Detailed documentation
2. **Check browser console** - F12 → Console tab
3. **Test in different browser** - Chrome, Firefox, Safari
4. **Clear cache** - Ctrl+Shift+Delete

---

## Next Steps

After deployment:

1. ✅ Share URL with customers
2. ✅ Update prices daily via CSV
3. ✅ Monitor WhatsApp orders
4. ✅ Adjust prices based on demand
5. ✅ Add new products to products.json

---

## You're All Set! 🎉

Your e-commerce platform is ready to serve customers with:
- 741 products
- Green theme
- Daily price updates
- WhatsApp integration

**Start accepting orders today!** 💚

---

For any questions, refer to **README.md** for detailed documentation.
