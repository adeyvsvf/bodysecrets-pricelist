# Bodysecrets Price List Website

A professional, mobile-responsive website that displays product prices dynamically from a Google Sheet.

## Features

- 🔄 **Real-time data** - Automatically fetches current prices from Google Sheets
- 🔍 **Live search** - Filter products instantly as you type
- 📱 **Mobile-friendly** - Responsive design for all devices
- 💰 **Currency formatting** - Nigerian Naira (₦) with proper formatting
- 🎨 **Professional design** - Dark green theme with modern UI
- ⚡ **Fast loading** - Optimized for quick access
- 🔒 **No database needed** - Data stored securely in Google Sheets

## Setup

1. **Google Sheet Configuration:**
   - Publish your sheet to web: `File → Share → Publish to web`
   - Set sharing to public: `Share → Anyone with link → Viewer`
   - Ensure columns are: `PRODUCT NAME`, `SIZES`, `SELLING PRICE`

2. **Deployment:**
   - Upload `index.html` to any web hosting service
   - Or use drag-and-drop deployment (Netlify, Surge, etc.)

## File Structure

```
/Users/admin/BodysecretsPriceList/
├── index.html          # Main website file
└── README.md           # This documentation
```

## Google Sheet Integration

The website automatically connects to:
- **Sheet ID:** `1WC36RiBxwrBHa-qGPj60O-_GInXfISfA_0NmXRKv_p4`
- **Format:** CSV export via CORS proxy
- **Updates:** Real-time when page is refreshed

## Browser Support

- ✅ Chrome, Firefox, Safari, Edge
- ✅ Mobile browsers (iOS, Android)
- ✅ Tablets and desktop

## Updates

To update prices:
1. Edit your Google Sheet
2. Customers refresh the website
3. New prices appear automatically

---

**Built with:** Pure HTML, CSS, and JavaScript (no frameworks required)
