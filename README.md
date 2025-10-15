# 👗 Neha Fashion & Boutique Website

A modern, responsive e-commerce website for ethnic wear and designer clothing.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Product Categories**: 
  - Kashmiri Suits
  - Long Frocks
  - Designer Suits
  - Lehengas
- **Shopping Cart**: Add items, manage quantities, and checkout
- **Hero Slider**: Automatic image carousel on homepage
- **Contact Form**: Easy customer communication
- **WhatsApp Integration**: Direct chat button
- **Social Media Links**: Facebook, Instagram, Twitter
- **Newsletter Subscription**: Email collection
- **Share Functionality**: Share products and website
- **Smooth Animations**: Modern UI transitions
- **Local Storage**: Cart persists across sessions

## 📁 Project Structure

```
nehafashion/
│
├── index.html              # Main HTML file
├── css/
│   └── style.css          # All styling
├── js/
│   └── script.js          # All functionality
├── images/
│   ├── logo1.png          # Website logo
│   ├── slider1.jpg        # Hero slider image 1
│   ├── slider-2.jpg       # Hero slider image 2
│   └── ourcollection1.png # Product images
│
├── README.md              # This file
└── DOMAIN_AND_HOSTING_GUIDE.md  # Deployment guide
```

## 🚀 Quick Start

### Local Development

1. **Open the website**:
   - Simply open `index.html` in your web browser
   - Or use a local server (recommended):
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve
     ```

2. **View in browser**:
   - Navigate to `http://localhost:8000`

### Customization

#### Update Products

Edit `js/script.js` - modify the `productsData` array:

```javascript
{
    id: 'product1',
    category: 'kashmire',
    title: "Your Product Name",
    price: 3499,
    sizes: ["S", "M", "L", "XL"],
    img: "images/your-image.jpg"
}
```

#### Update Contact Information

Edit `index.html`:
- Line 16-17: Phone and email in header
- Line 467: WhatsApp number
- Lines 267-283: Contact section details

#### Update Colors

Edit `css/style.css` - modify CSS variables:

```css
:root {
    --primary-color: #d4145a;    /* Main brand color */
    --secondary-color: #ff6b9d;  /* Accent color */
    --dark-color: #2c2c2c;       /* Dark text/backgrounds */
}
```

#### Add Product Images

1. Add images to `images/` folder
2. Update image paths in `productsData` array
3. Recommended image size: 800x800px

## 🎨 Color Scheme

- **Primary**: #d4145a (Pink)
- **Secondary**: #ff6b9d (Light Pink)
- **Dark**: #2c2c2c (Charcoal)
- **Light**: #f8f9fa (Off-white)

## 📱 Responsive Breakpoints

- **Desktop**: > 768px
- **Tablet**: 481px - 768px
- **Mobile**: < 480px

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6)**: Interactive functionality
- **Font Awesome**: Icons
- **Local Storage**: Cart persistence

## 📦 Dependencies

### External Libraries (CDN)

- Font Awesome 6.4.0 (Icons)

No build process or package manager required!

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🔧 Configuration

### WhatsApp Integration

Update the WhatsApp number in `index.html` (line 467):

```html
<a href="https://wa.me/919876543210" class="whatsapp-float">
```

Replace `919876543210` with your number (country code + number, no spaces or +)

### Social Media Links

Update links in `index.html` (lines 19-22 and footer):

```html
<a href="https://facebook.com/yourpage">
<a href="https://instagram.com/yourpage">
```

## 📈 SEO Optimization

The website includes:
- Meta descriptions
- Semantic HTML
- Alt tags for images
- Responsive design
- Fast loading times

### To improve SEO:
1. Add unique meta descriptions for each page
2. Use Google Search Console
3. Create sitemap.xml
4. Add robots.txt
5. Optimize images (compress)

## 🚀 Deployment

See `DOMAIN_AND_HOSTING_GUIDE.md` for detailed deployment instructions.

### Quick Deploy Options:

1. **Netlify** (Recommended - FREE):
   - Drag and drop the entire folder
   - Instant deployment
   - Free SSL certificate

2. **GitHub Pages** (FREE):
   - Push to GitHub repository
   - Enable Pages in settings

3. **Traditional Hosting**:
   - Upload via FTP or cPanel
   - Point domain to hosting

## 📧 Email Configuration

Update email addresses in:
- Header contact info
- Contact section
- Footer

## 🔒 Security

- Use HTTPS (SSL certificate)
- Validate form inputs
- Sanitize user data
- Keep dependencies updated

## 🐛 Troubleshooting

### Images not loading:
- Check image paths in `productsData`
- Ensure images exist in `images/` folder
- Check file extensions (case-sensitive)

### Cart not working:
- Check browser console for errors (F12)
- Ensure JavaScript is enabled
- Clear browser cache and localStorage

### Mobile menu not working:
- Check JavaScript is loaded
- Verify nav-toggle ID matches

## 📝 Future Enhancements

Potential features to add:
- [ ] Backend integration (Node.js/PHP)
- [ ] Database for products (MongoDB/MySQL)
- [ ] User authentication
- [ ] Payment gateway (Razorpay/Stripe)
- [ ] Order management system
- [ ] Product reviews and ratings
- [ ] Wishlist functionality
- [ ] Size guide
- [ ] Product zoom
- [ ] Filter and sort products
- [ ] Search functionality

## 📄 License

This project is free to use for personal and commercial purposes.

## 👥 Support

For questions or issues:
- Check `DOMAIN_AND_HOSTING_GUIDE.md`
- Review browser console (F12) for errors
- Verify all file paths are correct

## 🎉 Credits

- **Design**: Custom design for Neha Fashion & Boutique
- **Icons**: Font Awesome
- **Fonts**: System fonts (Segoe UI)

---

**Made with ❤️ for Neha Fashion & Boutique**

*Last Updated: 2024*
