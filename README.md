# 📝 TextUtils

[![React](https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://reactjs.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.0-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)](https://pulkirjaincs.github.io/TextUtils-React)


> A modern, responsive text utility application built with React. Features dark/light mode toggle, text transformations, alerts, and routing for a seamless user experience.

## ✨ Key Features

- **📱 Responsive Design**: Fully responsive layout that works seamlessly across all devices
- **🌗 Dark/Light Mode**: Toggle between dark and light themes for comfortable viewing
- **🔤 Text Transformations**: Convert text to uppercase, lowercase, remove extra spaces
- **📋 Clipboard Support**: Copy text to clipboard with a single click
- **⚡ Alerts**: Real-time alert messages for user actions like mode toggling and text operations
- **🧭 Routing**: Navigate between Home and About pages using React Router
- **🎨 Modern UI**: Clean, Bootstrap-powered interface with intuitive controls

## 🎬 Demo

You can see a live demo of the TextUtils app deployed on GitHub Pages:

[https://pulkirjaincs.github.io/TextUtils-React](https://pulkirjaincs.github.io/TextUtils-React)

## 🛠️ Tech Stack

| Category           | Technology           |
|--------------------|----------------------|
| **Frontend Framework** | React 18.2.0         |
| **Routing**           | React Router DOM 6.22.3 |
| **Styling**           | Bootstrap 5.0         |
| **Deployment**        | GitHub Pages          |
| **Package Manager**   | npm                   |

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/pulkitjaincs/TextUtils-React.git
cd TextUtils-React

# Install dependencies
npm install

# Start development server
npm start
```

### Available Scripts

| Script          | Description                  |
|-----------------|------------------------------|
| `npm start`     | Runs the app in development mode |
| `npm run build` | Builds the app for production |
| `npm test`      | Launches the test runner      |
| `npm run deploy`| Deploys to GitHub Pages       |

## 📁 Project Structure

```
TextUtils-React/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── components/
│   │   ├── About.js          # About page component with accordion
│   │   ├── Alert.js          # Alert message component
│   │   ├── Navbar.js         # Navigation bar with dark mode toggle
│   │   └── TextForm.js       # Main text manipulation component
│   ├── App.css               # Application styles
│   ├── App.js                # Main app component with routing and mode toggle
│   ├── App.test.js           # Test file for App component
│   ├── index.css             # Global styles
│   ├── index.js              # Application entry point
│   ├── logo.svg              # React logo
│   ├── reportWebVitals.js    # Performance reporting
│   └── setupTests.js         # Test setup
├── package.json              # Dependencies and scripts
├── package-lock.json         # Lockfile for npm
└── README.md                 # Project documentation
```

## 🎯 Core Components

### 🧭 Navbar Component
```javascript
// Responsive navigation bar with dark mode toggle
const Navbar = (props) => {
  // Bootstrap navbar with links to Home and About
  // Dark/light mode switch toggles app theme
}
```

### 🔤 TextForm Component
```javascript
// Text manipulation form
const TextForm = (props) => {
  // Textarea for input
  // Buttons for uppercase, lowercase, clear, copy, remove spaces
  // Displays word count, character count, reading time, and preview
  // Supports dark/light mode styling
}
```

### 📄 About Component
```javascript
// About page with Bootstrap accordion
const About = (props) => {
  // Accordion with placeholder content
  // Dark/light mode styling
  // Link back to Home
}
```

### ⚡ Alert Component
```javascript
// Alert message display
const Alert = (props) => {
  // Shows Bootstrap alert with message and type
  // Capitalizes alert type
}
```

## ⚙️ Configuration

- Dark/light mode toggle managed in App.js with state and document background color changes
- Routing handled with React Router DOM for Home (TextForm) and About pages

## 🚀 Deployment

### GitHub Pages Deployment
```bash
# Build and deploy to GitHub Pages
npm run build
npm run deploy
```

### Manual Deployment
```bash
# Build for production
npm run build

# Deploy build folder to your hosting service
# Upload the contents of build/ folder to your web server
```

## 📈 Performance Notes

- Minimal re-renders with React state management
- Bootstrap for responsive and consistent UI
- Efficient text operations with simple state updates

## 🔮 Roadmap

- [ ] Add more text transformation features (e.g., sentence case, remove punctuation)
- [ ] Implement search functionality within text
- [ ] Add user preferences for default mode
- [ ] Improve accessibility features
- [ ] Add unit and integration tests

## 🤝 Contributing

Contributions are welcome! Please fork the repository and create a pull request.

### Quick Start for Contributors
```bash
# Fork and clone the repository
git clone https://github.com/pulkitjaincs/TextUtils-React.git
cd TextUtils-React

# Create a new branch
git checkout -b feature/your-feature-name

# Make your changes and commit
git commit -m "Add: your feature description"

# Push and create a Pull Request
git push origin feature/your-feature-name
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Pulkit Jain**
- 🌐 GitHub: [@pulkitjaincs](https://github.com/pulkitjaincs)
- 💼 LinkedIn: [@pulkitjaincs](https://linkedin.com/in/pulkitjaincs)
- 📧 Email: pulkitjain.cse@gmail.com

---

<div align="center">

⭐ **Star this repository if you found it helpful!**

[![GitHub stars](https://img.shields.io/github/stars/pulkitjaincs/TextUtils-React?style=social)](https://github.com/pulkitjaincs/TextUtils-React/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/pulkitjaincs/TextUtils-React?style=social)](https://github.com/pulkitjaincs/TextUtils-React/network/members)

*Built with ❤️ using React*

</div>
