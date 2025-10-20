# Advancing Information and Telecommunication Workshop

[![Workshop](https://img.shields.io/badge/Event-August%201--3%2C%202026-purple)](https://github.com/yourusername/ieice-workshop)
[![Location](https://img.shields.io/badge/Location-Yogyakarta%2C%20Indonesia-green)](https://maps.app.goo.gl/GVXrM2F3PyvBDhFQ6)
[![Format](https://img.shields.io/badge/Format-Hybrid-blue)](https://github.com/yourusername/ieice-workshop)

A collaborative workshop website between **IEICE (Japan)** and **IES–PENS (Indonesia)** focused on bridging theoretical research and practical applications in information and telecommunication systems.

## 🌐 Live Website

Visit the workshop website: [https://yourusername.github.io/ieice-workshop](https://yourusername.github.io/ieice-workshop)

*(Replace with your actual GitHub Pages URL)*

## 📅 Event Information

- **Date:** August 1–3, 2026
- **Location:** Yogyakarta Marriott Hotel, Yogyakarta, Indonesia
- **Format:** Hybrid (Onsite + Virtual)
- **Organizers:** 
  - IEICE (Institute of Electronics, Information and Communication Engineers) - Japan
  - IES (International Electronics Symposium) - PENS, Indonesia

## 🎯 Workshop Focus

The workshop highlights cross-disciplinary topics including:
- Signal processing and networking architectures
- IoT and AI-driven systems
- 5G/6G communication technologies
- Resilient digital infrastructures
- Software/hardware co-design for scalable services

## 🤝 Supported By

- **IEICE** - Institute of Electronics, Information and Communication Engineers
- **PENS** - Politeknik Elektronika Negeri Surabaya
- **PLN** - Indonesia State Electricity Company
- **Shell** - Energy and Petrochemical Company

## 🏗️ Project Structure

```
ieice-workshop/
├── index.html              # Main workshop website
├── assets/                 # Images and logos
│   ├── ies-2026-logo.png
│   ├── ieice.png
│   ├── Logo_PENS.png
│   ├── Logo_PLN.png
│   ├── Shell_logo.svg
│   ├── Google_Scholar_logo.svg
│   └── headshot/           # Speaker photos
│       ├── ieice.png
│       ├── pens1.png
│       ├── pens2.png
│       └── brin.png
├── README.md               # This file
└── .gitignore             # Git ignore rules
```

## 🚀 Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select branch `main` and root folder `/`
4. Save and wait for deployment
5. Your site will be live at `https://yourusername.github.io/ieice-workshop`

### Local Development

Simply open `index.html` in your web browser. No build process or server required!

```bash
# Clone the repository
git clone https://github.com/yourusername/ieice-workshop.git

# Navigate to the directory
cd ieice-workshop

# Open in browser (or double-click index.html)
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **Tailwind CSS** (CDN) - Utility-first CSS framework
- **Vanilla JavaScript** - Interactive features (countdown timer, smooth scrolling, animations)
- **Google Maps Embed API** - Venue location display

## ✨ Features

- ✅ **Responsive Design** - Mobile, tablet, and desktop optimized
- ✅ **Countdown Timer** - Live countdown to workshop opening
- ✅ **Smooth Animations** - Scroll-reveal and parallax effects
- ✅ **Interactive Navigation** - Smooth scrolling to sections
- ✅ **Google Maps Integration** - Venue location with marker
- ✅ **Two Submission Paths** - Separate guidelines for IES and IEICE participants
- ✅ **Speaker Profiles** - Google Scholar integration
- ✅ **Hybrid Event Info** - Clear online/onsite participation details

## 📝 Customization Guide

### Update Event Dates
Edit the JavaScript countdown timer in `index.html`:
```javascript
const workshopDate = new Date('August 1, 2026 09:00:00').getTime();
```

### Add Speaker Information
Replace placeholder text in the speaker cards:
```html
<h3>[Professor Name]</h3>
<a href="#" target="_blank"><!-- Add Google Scholar URL --></a>
```

### Update Submission Links
Replace `#` with actual submission portal URLs:
```html
<a href="#" class="...">Submit via EDAS</a>
<a href="#" class="...">Submit via IEICE</a>
```

### Change Venue
Update the Google Maps iframe location:
```html
<iframe src="https://www.google.com/maps?q=YourVenue&output=embed"></iframe>
```

## 📧 Contact & Support

For workshop inquiries:
- **IES:** [https://ies.pens.ac.id](https://ies.pens.ac.id)
- **IEICE:** [https://www.ieice.org/eng](https://www.ieice.org/eng)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Workshop organizers: IEICE and IES–PENS
- Supporting organizations: PLN, Shell
- All contributing speakers and participants

---

**© 2025 Advancing Information and Telecommunication Workshop**  
*Organized by IES (Indonesia) and IEICE (Japan)*
