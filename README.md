# 🚀 Fly Finance FX Conversion Savings Calculator

A professional, interactive web-based calculator that helps exporters and service providers visualize potential savings when using Fly Finance for FX conversions compared to traditional banks.

## ✨ Features

- **Real-Time Calculations**: Instant comparison between traditional bank rates and Fly Finance rates
- **Historical FX Rates**: Support for multiple currencies with date-specific rates
- **PDF Export**: Download comparison reports as PDF documents
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Transparent Pricing**: Shows exactly how much markup each provider charges
- **Easy Embedding**: Can be embedded on any website using iframe

## 🎯 Supported Currencies

- GBP (British Pound)
- USD (US Dollar)
- EUR (Euro)
- AUD (Australian Dollar)
- CAD (Canadian Dollar)

## 📊 How It Works

1. **Select Currency**: Choose the currency you received FX in
2. **Enter FX Amount**: Input the amount you received in foreign currency
3. **Enter INR Received**: Enter the INR amount you were credited
4. **Select Date**: Choose the transaction date
5. **View Results**: See detailed comparison between bank rates and Fly Finance

## 🌐 Deployment

### GitHub Pages (Free Hosting)

1. **Create a new repository** named `fly-fx-calculator`
2. **Upload these files**:
   - `index.html`
   - `README.md`
   - `Fly-Logo.jpg`
   - `black-4x.jpg`
   - `.gitignore`

3. **Enable GitHub Pages**:
   - Go to Settings → Pages
   - Select `main` branch as source
   - Save

4. **Live URL**: `https://your-username.github.io/fly-fx-calculator`

### Custom Domain

If you want to use a custom domain (e.g., `calculator.flyfinance.com`):
1. Go to Settings → Pages → Custom domain
2. Enter your domain
3. Update your domain's DNS settings to point to GitHub Pages

## 🔗 Embedding the Calculator

You can embed this calculator on your website using an iframe:

```html
<iframe 
  src="https://risheedeshpande-ux.github.io/fly-fx-calculator" 
  width="100%" 
  height="1200" 
  frameborder="0" 
  allowfullscreen>
</iframe>
```

### Embedding Options

**Full Page:**
```html
<iframe src="https://risheedeshpande-ux.github.io/fly-fx-calculator" width="100%" height="100%" frameborder="0"></iframe>
```

**Responsive Iframe:**
```html
<div style="position: relative; width: 100%; padding-bottom: 150%; height: 0; overflow: hidden;">
  <iframe 
    src="https://risheedeshpande-ux.github.io/fly-fx-calculator" 
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: none;" 
    allowfullscreen>
  </iframe>
</div>
```

## 🎨 Customization

### Update Contact Information

In `index.html`, find and update:

```html
<!-- Email -->
<a href="mailto:tradefx@fly.finance">tradefx@fly.finance</a>

<!-- Phone -->
<a href="tel:+918108343511">+91 8108343511</a>

<!-- Google Form Link -->
<a href="https://forms.gle/YOUR_GOOGLE_FORM_ID">Start Onboarding</a>
```

### Update Logos

Replace these image files with your own:
- `Fly-Logo.jpg` - Main company logo
- `black-4x.jpg` - Secondary logo

### Update Exchange Rates

Edit the `historicalRates` object in the JavaScript section to add or update rates:

```javascript
const historicalRates = {
    'GBP': {
        '2025-10-10': 118.51,
        '2025-10-16': 117.70,
        // Add more dates...
    },
    // Add more currencies...
};
```

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🖨️ Print Features

- Clean PDF export without buttons
- Print-optimized styling
- Maintains exact colors and formatting
- Page-break prevention for cards

## 🔐 Privacy

- No data is stored on servers
- All calculations happen locally in the browser
- No tracking or cookies
- GDPR compliant

## 📞 Support

- **Email**: tradefx@fly.finance
- **Phone**: +91 8108343511

## 📄 License

This calculator is proprietary to Fly Finance. Unauthorized copying or modification is prohibited.

## 🚀 Version History

### v1.0 (November 2025)
- Initial release
- Support for GBP, USD, EUR, AUD, CAD
- PDF export functionality
- Responsive design
- GitHub Pages deployment

---

**Built with ❤️ by Fly Finance**
