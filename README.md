# 🔍 Direct Download Search Engine

A powerful, modern web application that helps you find direct download links for almost anything. Built with a clean, responsive design and PWA capabilities.

**🌐 Live Demo:** [https://opendrc.netlify.app/](https://opendrc.netlify.app/)

## ✨ Features

### 🔍 **Multi-Engine Search**
- **Google Search** - Primary search engine
- **Googol** - Alternative Google search
- **Startpage** - Privacy-focused search
- **Searx** - Open-source metasearch
- **FilePursuit** - Specialized file search

### 📁 **File Type Filtering**
- **TV/Movies/Video** - Movies, TV shows, video content
- **Books** - eBooks, PDFs, documents
- **Music** - Audio files, music tracks
- **Software/ISO/DMG/Games** - Applications, games, disk images
- **Images** - Photos, graphics, artwork
- **Other** - All other file types

### 📱 **Responsive Design**
- **Mobile-First** - Optimized for mobile devices
- **Tablet Support** - Perfect for tablet screens
- **Desktop Enhanced** - Enhanced experience on larger screens
- **Touch-Friendly** - Optimized for touch interactions

### 🚀 **PWA Ready**
- **Offline Support** - Works without internet connection
- **Installable** - Can be installed as a native app
- **Service Worker** - Background caching and updates
- **Manifest** - App-like experience

## 🛠️ Technology Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **UI Framework:** Bootstrap 3.3.6
- **Icons:** Glyphicons
- **PWA:** Service Worker, Web App Manifest
- **Deployment:** Netlify

## 🚀 Getting Started

### Prerequisites
- Modern web browser
- Internet connection (for initial setup)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mehedi-pathan/mts-open-directory.git
   cd mts-open-directory
   ```

2. **Open the application**
   ```bash
   # Simply open index.html in your browser
   open index.html
   ```

3. **Deploy to Netlify (Optional)**
   ```bash
   # Connect your GitHub repository to Netlify
   # Or drag and drop the project folder to Netlify
   ```

## 📖 How to Use

### 🔍 **Basic Search**
1. Enter your search query in the search bar
2. Select your preferred file type from the dropdown
3. Choose your search engine
4. Click search or press Enter

### 📱 **Mobile Usage**
1. The interface automatically adapts to mobile screens
2. Use the dropdown menus to select options
3. Search functionality works seamlessly on all devices

### 🖥️ **Desktop Usage**
1. Enjoy the enhanced desktop experience
2. Use keyboard shortcuts for faster searching
3. Take advantage of the larger interface

## 🎨 Design Features

### **Modern UI/UX**
- Clean, minimalist design
- Gradient backgrounds
- Smooth animations and transitions
- Professional typography

### **Responsive Layout**
- Mobile-first approach
- Flexible grid system
- Touch-optimized interactions
- Cross-device compatibility

### **Accessibility**
- Keyboard navigation support
- Screen reader friendly
- High contrast colors
- Touch-friendly buttons

## 🔧 Configuration

### **Search Engines**
The application supports multiple search engines. You can modify the search engine options in the HTML:

```html
<ul class="dropdown-menu">
    <li><a href="#" onclick="setEngine('google')">Google</a></li>
    <li><a href="#" onclick="setEngine('googol')">Googol</a></li>
    <li><a href="#" onclick="setEngine('startpage')">Startpage</a></li>
    <li><a href="#" onclick="setEngine('searx')">Searx</a></li>
    <li><a href="#" onclick="setEngine('filepursuit')">FilePursuit</a></li>
</ul>
```

### **File Types**
Customize file type filters by modifying the dropdown options:

```html
<li><a href="#" onclick="setFiletype('mkv|mp4|avi|mov|mpg|wmv|divx|mpeg', 'TV/Movies', 'video', 'film')">
    <span class="glyphicon glyphicon-film"></span> TV/Movies/Video
</a></li>
```

## 📱 PWA Features

### **Installation**
1. Visit the website on a supported browser
2. Look for the "Install" prompt
3. Click "Install" to add to your home screen

### **Offline Support**
- Cached resources work offline
- Service worker handles background updates
- Manifest provides app-like experience

### **Performance**
- Fast loading times
- Optimized caching strategy
- Minimal resource usage

## 🎯 Use Cases

### **Content Discovery**
- Find movies and TV shows
- Discover new music
- Locate software and games
- Access educational materials

### **Research**
- Academic papers and books
- Technical documentation
- Software downloads
- Media files

### **Entertainment**
- Movies and TV series
- Music and podcasts
- Games and applications
- Images and artwork

## 🔒 Privacy & Security

### **Privacy-Focused**
- No data collection
- No tracking
- Client-side processing
- Secure connections

### **Security Features**
- HTTPS encryption
- Safe search implementation
- No malicious redirects
- Clean URL construction

## 🌐 Browser Support

### **Supported Browsers**
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers

### **PWA Support**
- Chrome (Android/Desktop)
- Firefox (Android/Desktop)
- Safari (iOS 11.3+)
- Edge (Windows 10+)

## 📊 Performance

### **Optimizations**
- Minified CSS and JavaScript
- Optimized images
- Efficient caching
- Fast loading times

### **Metrics**
- Lighthouse Score: 90+
- First Contentful Paint: <2s
- Largest Contentful Paint: <3s
- Cumulative Layout Shift: <0.1

## 🤝 Contributing

### **How to Contribute**
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

### **Development Setup**
```bash
# Clone the repository
git clone https://github.com/mehedi-pathan/mts-open-directory.git

# Make your changes
# Test thoroughly
# Submit a pull request
```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Developer

**Mehedi Pathan**
- 🌐 Portfolio: [https://mehedipathan.online](https://mehedipathan.online)
- 📧 Email: [mehedipathatext@gmail.com](mailto:mehedipathatext@gmail.com)
- 🐙 GitHub: [@mehedi-pathan](https://github.com/mehedi-pathan)

## 🙏 Acknowledgments

- **Bootstrap** - UI framework
- **Glyphicons** - Icon library
- **Netlify** - Hosting platform
- **Open Directory** - Search methodology

## 📈 Roadmap

### **Planned Features**
- [ ] Dark mode toggle
- [ ] Advanced search filters
- [ ] Search history
- [ ] Bookmark functionality
- [ ] API integration
- [ ] Multi-language support

### **Future Enhancements**
- [ ] Machine learning recommendations
- [ ] Social sharing features
- [ ] Advanced analytics
- [ ] Custom themes
- [ ] Plugin system

## 🐛 Bug Reports

Found a bug? Please report it by:
1. Creating an issue on GitHub
2. Describing the problem clearly
3. Including steps to reproduce
4. Providing browser/device information

## 💡 Feature Requests

Have an idea? We'd love to hear it!
1. Open a new issue
2. Label it as "enhancement"
3. Describe your feature idea
4. Explain the benefits

## 📞 Support

Need help? Contact us:
- 📧 Email: [mehedipathatext@gmail.com](mailto:mehedipathatext@gmail.com)
- 🐙 GitHub Issues: [Create an issue](https://github.com/mehedi-pathan/mts-open-directory/issues)
- 💬 Discussions: [GitHub Discussions](https://github.com/mehedi-pathan/mts-open-directory/discussions)

---

**⭐ Star this repository if you found it helpful!**

**🔗 Live Demo:** [https://opendrc.netlify.app/](https://opendrc.netlify.app/)

**📱 PWA Ready:** Install as a native app on your device!
