# LockSmith Pro - Professional Locksmith Website

A comprehensive, modern locksmith service website built with HTML, Tailwind CSS, and JavaScript. Features emergency services, booking system, user/admin dashboards, and complete service management.

## 🚀 Features

### Main Website
- **Two Home Pages**: Emergency focus and professional services
- **Complete Service Pages**: Residential, commercial, automotive, smart locks
- **Online Booking System**: Service scheduling with photo upload
- **Contact & Support**: Multi-channel contact options
- **Customer Reviews**: Testimonial management
- **Service Areas**: Geographic coverage with maps
- **Pricing**: Transparent service rates
- **FAQ**: Common questions and answers
- **Blog**: Security tips and guides

### User Dashboard
- **Appointment Management**: View and schedule services
- **Service History**: Complete booking records
- **Technician Tracking**: Real-time service tracking
- **Profile Settings**: Personal information management
- **Billing**: Payment history and invoices

### Admin Dashboard
- **Booking Manager**: Complete appointment control
- **Technician Management**: Staff scheduling and assignment
- **Service Area Control**: Geographic management
- **Review Management**: Customer feedback moderation
- **Pricing Editor**: Service rate management
- **Reports**: Analytics and insights

## 🎨 Design System

### Color Scheme
- **Primary**: Jet Black (#0F0F0F)
- **Secondary**: Metallic Gold (#C9A227)
- **Background**: Soft Ivory (#FAF7F2)
- **Text**: Deep Black (#1A1A1A)
- **Accent**: Dark Bronze (#5C4A1D)

### Technologies Used
- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first styling
- **Font Awesome**: Icons
- **AOS**: Scroll animations
- **Swiper**: Carousels and sliders
- **Google Maps**: Location services

## 📁 Project Structure

```
Locksmith Service/
├── index.html              # Home Page 1 - Emergency Focus
├── home2.html              # Home Page 2 - Professional Services
├── services.html           # Complete Services Listing
├── book.html               # Online Booking System
├── contact.html            # Contact & Support
├── dashboard.html          # User Dashboard
├── admin.html              # Admin Dashboard
├── css/
│   └── styles.css          # Custom Styles
├── js/                     # JavaScript files (if needed)
├── images/                 # Image assets
└── README.md               # This file
```

## 🛠️ Installation & Setup

1. **Clone or Download** the project files
2. **Navigate** to the project directory
3. **Open** `index.html` in your web browser

### Local Development
For local development with live reload:
```bash
# Using Python
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 📱 Responsive Design

The website is fully responsive and works seamlessly on:
- **Desktop** (1200px+)
- **Tablet** (768px - 1199px)
- **Mobile** (320px - 767px)

## 🔧 Customization

### Branding
- Update company name in navigation and footer
- Replace contact information
- Update logo and brand assets

### Colors
Modify the CSS variables in `css/styles.css`:
```css
:root {
    --primary-color: #0F0F0F;
    --secondary-color: #C9A227;
    --background-color: #FAF7F2;
    --text-color: #1A1A1A;
    --accent-color: #5C4A1D;
}
```

### Services
Update service offerings in:
- `services.html` - Main services page
- `index.html` - Homepage services
- `home2.html` - Professional services

## 🚀 Deployment

### Static Hosting
Deploy to any static hosting service:
- **Netlify**
- **Vercel**
- **GitHub Pages**
- **Firebase Hosting**
- **AWS S3**

### Server Setup
For production with backend integration:
1. Set up a web server (Apache/Nginx)
2. Configure SSL certificate
3. Connect to backend API
4. Set up database for bookings/users

## 🔐 Security Features

- **Input Validation**: Form validation on all inputs
- **XSS Protection**: Sanitized user inputs
- **CSRF Protection**: Form tokens (when backend integrated)
- **Secure Headers**: Proper security headers
- **HTTPS Ready**: SSL-ready configuration

## 📊 Analytics Integration

Add your analytics tracking in the `<head>` section:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

For support or questions:
- **Email**: info@locksmithpro.com
- **Phone**: 1-800-LOCKSMITH
- **Website**: [LockSmith Pro](https://locksmithpro.com)

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🎯 Browser Support

- **Chrome** 60+
- **Firefox** 55+
- **Safari** 12+
- **Edge** 79+
- **Mobile Safari** 12+
- **Chrome Mobile** 60+

## 🔄 Updates

### Version 1.0.0 (Current)
- ✅ Complete website implementation
- ✅ User and admin dashboards
- ✅ Responsive design
- ✅ Modern animations
- ✅ SEO optimized

### Planned Features
- 🔄 Backend API integration
- 🔄 Payment processing
- 🔄 SMS notifications
- 🔄 Live chat support
- 🔄 Mobile app integration

---

**Built with ❤️ for professional locksmith services**
