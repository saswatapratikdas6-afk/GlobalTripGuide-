# GlobalTripGuide 🌍

A comprehensive travel platform for exploring India's diverse regions, connecting tourists with local guides and showcasing the incredible destinations across the country.

## 🌟 Live Demo

**[View Live Demo](https://saswatapratikdas6-afk.github.io/GlobalTripGuide-/)**

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Multilingual Support](#multilingual-support)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

GlobalTripGuide is a user-friendly web platform designed to help travelers discover and explore India's rich cultural heritage, diverse landscapes, and tourist destinations. The platform serves as a bridge between tourists and certified local guides, offering personalized travel experiences across six major zones of India.

## ✨ Features

### For Tourists
- **Zone-based Exploration**: Browse destinations by geographical regions (North, South, East, West, Central, Northeast)
- **Detailed Destination Information**: View tourist places with descriptions, images, and pricing
- **Easy Booking System**: Simple registration and booking process for tours
- **Multilingual Support**: Available in 15 languages including Hindi, English, Spanish, French, German, Japanese, Chinese, Russian, Arabic, Portuguese, Italian, Korean, Dutch, Swedish, and Turkish

### For Guides
- **Guide Registration Portal**: Comprehensive registration system for local guides
- **Document Verification**: Secure upload system for ID verification and certifications
- **Professional Profile Creation**: Detailed profiles showcasing expertise and specializations
- **Service Area Management**: Define coverage areas and availability

### Technical Features
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, intuitive interface with smooth animations
- **Real-time Language Switching**: Instant translation without page reload
- **Form Validation**: Client-side validation for all user inputs
- **Image Optimization**: Optimized images with fallback options

## 🛠 Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS
- **Icons**: Unicode Emojis
- **Fonts**: Google Fonts (Pinyon Script)
- **Images**: Unsplash API integration
- **Deployment**: GitHub Pages

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/saswatapratikdas6-afk/GlobalTripGuide-.git
   cd GlobalTripGuide-
   ```

2. **Open the project**
   - Simply open `index.html` in your preferred web browser
   - Or use a local server for development:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

3. **Access the application**
   - Open your browser and navigate to `http://localhost:8000` (if using local server)
   - Or directly open the `index.html` file

## 📖 Usage

### For Visitors

1. **Browse Destinations**
   - Click "Start Your Journey" on the homepage
   - Select a geographical zone (North, South, East, West, Central, Northeast)
   - Choose a state to explore
   - View detailed information about tourist places

2. **Book a Tour**
   - Click "Book Tour" on any destination
   - Fill in the customer registration form
   - Provide travel details and preferences
   - Submit the booking request

3. **Language Selection**
   - Use the language dropdown in the navigation bar
   - All content will instantly translate to your selected language

### For Guides

1. **Register as a Guide**
   - Click "Guide Portal" in the navigation
   - Select "Register as New Guide"
   - Complete the comprehensive registration form
   - Upload required documents (ID, certifications, profile photo)
   - Submit for verification

2. **Login**
   - Use the Guide Portal login after approval
   - Access guide dashboard and manage bookings

## 📁 Project Structure

```
GlobalTripGuide/
│
├── index.html              # Main HTML file
├── README.md               # Project documentation
└── assets/
    ├── css/
    │   └── styles.css      # Custom styles (embedded in HTML)
    ├── js/
    │   └── script.js       # JavaScript functionality (embedded in HTML)
    └── images/             # Project images and assets
```

## 🌐 Multilingual Support

The platform supports 15 languages with complete translations:

- **English** (en) - Default
- **Hindi** (hi) - हिन्दी
- **Spanish** (es) - Español
- **French** (fr) - Français
- **German** (de) - Deutsch
- **Japanese** (ja) - 日本語
- **Chinese** (zh) - 中文
- **Russian** (ru) - Русский
- **Arabic** (ar) - العربية
- **Portuguese** (pt) - Português
- **Italian** (it) - Italiano
- **Korean** (ko) - 한국어
- **Dutch** (nl) - Nederlands
- **Swedish** (sv) - Svenska
- **Turkish** (tr) - Türkçe

### Adding New Languages

To add a new language:

1. Add the language option to the select dropdown in HTML
2. Create a new language object in the `translations` object in JavaScript
3. Translate all keys following the existing pattern
4. Test the language switching functionality

## 🌈 Zones and Coverage

### Northern Zone
- Delhi, Punjab, Haryana, Himachal Pradesh, Uttarakhand, Jammu & Kashmir

### Eastern Zone
- West Bengal, Odisha, Jharkhand, Bihar

### Western Zone
- Rajasthan, Gujarat, Maharashtra, Goa

### Southern Zone
- Tamil Nadu, Kerala, Karnataka, Andhra Pradesh, Telangana

### Central Zone
- Madhya Pradesh, Chhattisgarh, Uttar Pradesh

### Northeastern Zone
- Assam, Meghalaya, Manipur, Tripura, Nagaland, Mizoram, Arunachal Pradesh, Sikkim

## 🎨 Customization

### Changing Colors
- Update Tailwind CSS classes in the HTML
- Modify the CSS custom properties for consistent theming
- Update gradient backgrounds by changing the gradient classes

### Adding New Destinations
- Update the `statesData` object for new states
- Add entries to the `placesData` object for new tourist places
- Include high-quality images from Unsplash or other sources

### Modifying Forms
- Update form fields in the HTML modals
- Add corresponding translation keys for new fields
- Update form validation logic in JavaScript

## 🤝 Contributing

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/new-feature
   ```
3. **Make your changes**
   - Follow existing code style and structure
   - Add appropriate comments
   - Test thoroughly across different devices and browsers
4. **Commit your changes**
   ```bash
   git commit -m "Add new feature: description"
   ```
5. **Push to your branch**
   ```bash
   git push origin feature/new-feature
   ```
6. **Create a Pull Request**

### Guidelines for Contributors
- Maintain responsive design principles
- Ensure all new text is translatable (add to translations object)
- Test functionality across different browsers
- Follow accessibility best practices
- Keep the code clean and well-documented

## 🙏 Acknowledgments

- **Unsplash** for providing high-quality destination images
- **Tailwind CSS** for the utility-first CSS framework
- **Google Fonts** for the beautiful typography
- **India Tourism** for inspiration and destination information

## 📞 Contact

For questions, suggestions, or support, please reach out through:
- GitHub Issues: [Create an issue](https://github.com/saswatapratikdas6-afk/GlobalTripGuide-/issues)
- Live Demo: [GlobalTripGuide](https://saswatapratikdas6-afk.github.io/GlobalTripGuide-/)

---

**Discover Incredible India with GlobalTripGuide** 🇮🇳
