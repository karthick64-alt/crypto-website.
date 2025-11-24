# Cryptocurrency Website - Complete Project

A comprehensive, client-ready cryptocurrency website built with HTML, CSS, JavaScript, and Bootstrap 5.

## 🚀 Features

### Main Pages
1. **Home Page 1** (`index.html`) - General Crypto Landing Page
   - Hero banner with animated crypto icons
   - Live crypto prices display
   - Core features section
   - Why choose us section
   - Use cases (Trading, Investing, Staking, NFT)
   - Partners & integrations
   - Testimonials
   - Newsletter subscription

2. **Home Page 2** (`index2.html`) - Niche-Specific Crypto Layout
   - Full-screen hero with animated globe
   - Token utility section
   - Development roadmap timeline
   - Whitepaper CTA
   - Community stats (Telegram, Twitter, Discord)
   - NFT features
   - Security certifications

3. **About Us** (`about.html`)
   - Company overview
   - Mission & vision
   - Problem we solve
   - Team section with profiles
   - Advisors & partners
   - Journey timeline
   - Testimonials

4. **Services** (`services.html`)
   - Grid/List view toggle
   - 10 comprehensive services:
     - Crypto Trading Platform
     - Wallet Services
     - Blockchain Development
     - Smart Contract Development
     - Crypto Payment Gateway
     - Token Launchpad
     - NFT Marketplace
     - Staking & Yield Farming
     - Portfolio Management
     - Web3 Consulting

5. **Service Details** (`service-details.html`)
   - Service overview
   - Key features
   - Supported blockchains
   - Security standards
   - User benefits
   - Pricing table (Free, Pro, Enterprise)
   - FAQs section

6. **Blog Listing** (`blog.html`)
   - Blog posts grid
   - Category filters (Trading, Blockchain, DeFi, NFT)
   - Search functionality
   - Pagination

7. **Blog Details** (`blog-details.html`)
   - Full blog article
   - Author details
   - Publish date
   - Sidebar with:
     - Recent posts
     - Categories
     - Popular topics
   - Tags section
   - Social share buttons
   - Comments area

8. **Contact Us** (`contact.html`)
   - Contact form
   - Email support
   - Phone number
   - Business address
   - Social links
   - Google Maps integration
   - Quick links

9. **Login** (`login.html`)
   - Email/password authentication
   - Social login options (Google, GitHub)
   - Remember me functionality
   - Forgot password link
   - Password visibility toggle
   - Secure login form

10. **Register** (`register.html`)
    - User registration form
    - Password strength indicator
    - Password confirmation
    - Terms & conditions acceptance
    - Newsletter subscription option
    - Social registration options
    - Real-time form validation

### Extra Modules
11. **Live Market** (`market.html`)
   - Real-time crypto prices
   - Market statistics
   - Price charts (placeholder for Chart.js/TradingView)
   - Market cap & volume
   - Top gainers/losers
   - Searchable market table

12. **Token Page** (`token.html`)
    - Token name & symbol
    - Tokenomics with distribution chart
    - Token utility
    - Roadmap timeline
    - Token metrics
    - Document downloads (Whitepaper, Pitch Deck)

13. **Wallet Dashboard** (`wallet.html`)
    - Portfolio overview
    - Total portfolio value
    - Available balance
    - Quick actions (Buy, Sell, Swap, Send)
    - Portfolio assets table
    - Recent transactions history

## 📁 Project Structure

```
Cryptocurrency web/
├── index.html              # Home Page 1
├── index2.html             # Home Page 2
├── about.html              # About Us Page
├── services.html           # Services Listing
├── service-details.html    # Service Details Page
├── blog.html               # Blog Listing
├── blog-details.html       # Blog Details Page
├── contact.html            # Contact Us Page
├── login.html              # Login Page
├── register.html           # Register/Sign Up Page
├── market.html             # Live Market Page
├── token.html              # Token Page
├── wallet.html             # Wallet Dashboard
├── assets/
│   ├── css/
│   │   └── style.css      # Main stylesheet
│   └── js/
│       └── script.js      # JavaScript functionality
└── README.md              # Project documentation
```

## 🎨 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with animations
- **JavaScript** - Interactive functionality
- **Bootstrap 5.3.0** - Responsive framework
- **Bootstrap Icons** - Icon library

## 🚀 Getting Started

1. **Clone or download** the project files
2. **Open** any HTML file in a web browser
3. **No build process required** - works directly in the browser

## 📝 Customization

### Colors
Edit the CSS variables in `assets/css/style.css`:
```css
:root {
    --primary-color: #0d6efd;
    --secondary-color: #6c757d;
    --success-color: #198754;
    --warning-color: #ffc107;
    --danger-color: #dc3545;
    --dark-color: #1a1a2e;
}
```

### Content
- Update text content directly in HTML files
- Replace placeholder images with your own
- Modify crypto prices data in `assets/js/script.js`

### API Integration
For live crypto prices, integrate with:
- CoinGecko API
- CoinMarketCap API
- Binance API

Example in `assets/js/script.js`:
```javascript
// Replace mock data with real API calls
fetch('https://api.coingecko.com/api/v3/simple/price?ids=bitcoin,ethereum&vs_currencies=usd')
```

## 🔧 Features to Enhance

1. **Charts Integration**
   - Add Chart.js or TradingView widgets to `market.html`
   - Implement candlestick charts

2. **Real-time Data**
   - Connect to cryptocurrency APIs
   - WebSocket integration for live updates

3. **Backend Integration**
   - Connect contact forms to backend
   - User authentication for wallet dashboard
   - Transaction history from database

4. **Additional Features**
   - Dark mode toggle
   - Multi-language support
   - Advanced search functionality
   - User dashboard with authentication

## 📱 Responsive Design

All pages are fully responsive and work on:
- Desktop (1920px+)
- Laptop (1024px - 1919px)
- Tablet (768px - 1023px)
- Mobile (320px - 767px)

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is ready for client use. Customize as needed for your specific requirements.

## 📞 Support

For questions or customization help, refer to the code comments or contact the development team.

---

**Built with ❤️ using HTML, CSS, JavaScript, and Bootstrap 5**

