# TextUtils - React Text Manipulation Tool

A modern, responsive React application for text manipulation and analysis with dark/light mode support. Built with React 18, Bootstrap 5, and React Router.

## 🚀 Features

- **Text Transformations**
  - Convert text to uppercase
  - Convert text to lowercase
  - Clear all text
  - Copy text to clipboard
  - Remove extra spaces

- **Text Analysis**
  - Word count
  - Character count
  - Reading time estimation
  - Live text preview

- **User Experience**
  - Dark/Light mode toggle
  - Responsive design with Bootstrap 5
  - Alert notifications for user actions
  - Modern, clean interface

- **Navigation**
  - Home page with text utilities
  - About page with information
  - Smooth routing with React Router

## 🛠️ Technologies Used

- **Frontend Framework**: React 18.2.0
- **Routing**: React Router DOM 6.22.3
- **Styling**: Bootstrap 5.3.3
- **Build Tool**: Create React App
- **Deployment**: GitHub Pages

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/pulkirjaincs/TextUtils-React.git
   cd TextUtils-React
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to view the application.

## 🚀 Deployment

The application is configured for deployment to GitHub Pages:

```bash
npm run build
npm run deploy
```

Live demo: [https://pulkirjaincs.github.io/TextUtils-React](https://pulkirjaincs.github.io/TextUtils-React)

## 📁 Project Structure

```
src/
├── components/
│   ├── About.js          # About page component
│   ├── Alert.js          # Alert notification component
│   ├── Navbar.js         # Navigation bar component
│   └── TextForm.js       # Main text manipulation component
├── App.js               # Main application component
├── App.css              # Application styles
├── index.js             # Application entry point
└── index.css            # Global styles
```

## 🎯 Available Scripts

- `npm start` - Runs the app in development mode
- `npm run build` - Builds the app for production
- `npm test` - Launches the test runner
- `npm run eject` - Ejects from Create React App (irreversible)
- `npm run deploy` - Deploys to GitHub Pages

## 🔧 Component Details

### TextForm Component
The main component handling text manipulation:
- State management for text input
- Text transformation functions
- Text analysis and statistics
- Responsive design with mode support

### Navbar Component
Navigation component with:
- Brand logo/title
- Navigation links (Home, About)
- Dark/Light mode toggle switch
- Responsive mobile menu

### About Component
Information page featuring:
- Accordion-style information sections
- Dark/Light mode styling
- Navigation back to home

### Alert Component
Notification system with:
- Success/error message display
- Auto-dismiss functionality
- Capitalized alert types

## 🌙 Dark/Light Mode

The application features a comprehensive dark/light mode implementation:
- Toggle switch in the navigation bar
- Dynamic background color changes
- Text color adjustments
- Alert notifications for mode changes
- Persistent mode state during session

## 📱 Responsive Design

Built with Bootstrap 5 for optimal responsiveness:
- Mobile-first approach
- Responsive navigation
- Adaptive layouts
- Touch-friendly interface

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Pulkit Jain**
- GitHub: [@pulkirjaincs](https://github.com/pulkirjaincs)
- Live Demo: [TextUtils-React](https://pulkirjaincs.github.io/TextUtils-React)

## 🙏 Acknowledgments

- React team for the amazing framework
- Bootstrap team for the responsive components
- Create React App for the development setup
- GitHub Pages for free hosting

---

⭐ Star this repository if you found it helpful!
