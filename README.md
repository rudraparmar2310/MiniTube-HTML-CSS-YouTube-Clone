# MiniTube - HTML & CSS YouTube Clone

A static YouTube-style front-end built with only HTML and CSS. Recreates the look-and-feel of a video platform — responsive video cards, channel sidebar, top navigation, search bar, and video detail layout — without JavaScript or backend. Great as a portfolio piece to demonstrate layout, responsive design, CSS grid/flex mastery, and pixel-perfect styling.

## 🎯 Features

### Homepage (index.html)
- **Top Navigation Bar** - Fixed header with logo, search bar, voice search, and action buttons
- **Collapsible Sidebar** - Navigation menu with Home, Trending, Subscriptions, Library, History, and more
- **Category Chips** - Horizontal scrollable filters for content categories
- **Responsive Video Grid** - Auto-adjusting grid layout (1-4 columns based on screen size)
- **Video Cards** - Thumbnail, duration badge, channel avatar, title, views, and upload time

### Video Page (video.html)
- **Video Player Area** - 16:9 aspect ratio video display
- **Video Information** - Title, stats, action buttons (like, share, download, save)
- **Channel Section** - Avatar, name, subscriber count, and subscribe button
- **Video Description** - Formatted text with lists, links, and hashtags
- **Comments Section** - Add comment input and sample comments with interactions
- **Suggested Videos** - Sidebar with related video recommendations

## 🎨 Design Features

- **Dark Theme** - YouTube-style dark color scheme
- **CSS Variables** - Easy theme customization
- **Flexbox & Grid** - Modern responsive layout techniques
- **Smooth Transitions** - Hover effects and animations
- **Font Awesome Icons** - Scalable vector icons
- **Semantic HTML** - Proper accessibility and SEO structure

## 📱 Responsive Breakpoints

- **Desktop (1920px+)** - 4-column video grid, full sidebar
- **Large (1328px)** - 3-column grid
- **Medium (992px)** - Icon-only sidebar, 2-column layout
- **Tablet (768px)** - Hidden sidebar, single column video page
- **Mobile (480px)** - Optimized mobile experience, single column grid

## 🚀 Getting Started

### View the Website

1. Clone the repository:
```bash
git clone https://github.com/rudraparmar2310/MiniTube-HTML-CSS-YouTube-Clone.git
```

2. Open `index.html` in your browser or use a local server:
```bash
cd MiniTube-HTML-CSS-YouTube-Clone
python3 -m http.server 8080
# Then navigate to http://localhost:8080
```

### File Structure

```
MiniTube-HTML-CSS-YouTube-Clone/
├── index.html          # Homepage with video grid
├── video.html          # Video player page
├── styles.css          # All styling and responsive design
└── README.md           # Project documentation
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Styling, animations, and responsive design
- **Font Awesome 6.4.0** - Icon library (via CDN)
- **Google Fonts** - Roboto font family

## 🎓 Learning Outcomes

This project demonstrates mastery of:
- CSS Grid and Flexbox layouts
- Responsive web design principles
- CSS custom properties (variables)
- Semantic HTML structure
- Accessibility best practices
- Cross-browser compatibility
- Pixel-perfect UI replication

## 📸 Screenshots

### Desktop View
![Desktop Homepage](docs/desktop-home.png)
![Desktop Video Page](docs/desktop-video.png)

### Mobile View
![Mobile Homepage](docs/mobile-home.png)
![Mobile Video Page](docs/mobile-video.png)

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements!

## 📄 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

Created by [rudraparmar2310](https://github.com/rudraparmar2310)

---

**Note:** This is a static front-end clone for educational purposes. No actual video functionality or backend is included.
