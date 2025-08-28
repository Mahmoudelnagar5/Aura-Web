# 🌟 Aura - AI Study Companion

<p align="center">
  <img src="assets/images/logo.png" alt="Aura Logo" width="120" height="120">
</p>

<p align="center">
  <strong>Your intelligent study companion, powered by advanced AI to help you absorb, retain, and master any subject</strong>
</p>

<p align="center">
  <a href="#-download">📱 Download</a> •
  <a href="#-features">✨ Features</a> •
  <a href="#-technology-stack">🛠️ Tech Stack</a> •
  <a href="#-getting-started">🚀 Getting Started</a> •
  <a href="#-contributing">🤝 Contributing</a>
</p>

---

## 📋 Table of Contents

- [🌟 Overview](#-overview)
- [📱 Download](#-download)
- [✨ Features](#-features)
- [🛠️ Technology Stack](#-technology-stack)
- [📁 Project Structure](#-project-structure)
- [🚀 Getting Started](#-getting-started)
- [🏗️ Installation](#-installation)
- [👥 Meet Our Team](#-meet-our-team)
- [🤝 Contributing](#-contributing)
- [📄 Development Guidelines](#-development-guidelines)
- [📝 License](#-license)
- [📞 Contact](#-contact)

---

## 🌟 Overview

**Aura** is an intelligent study companion that revolutionizes the way you learn and retain information. Built with cutting-edge AI technology, Aura analyzes your study materials, creates personalized summaries, and helps you master any subject through interactive learning features.

Transform your learning experience with:
- **AI-Powered Analysis**: Advanced document processing using Gemini AI
- **Smart Summarization**: Automatic content summarization and key point extraction
- **Multilingual Support**: Seamless English ↔ Arabic language switching
- **Interactive Learning**: Progress tracking, vocabulary building, and smart quizzes
- **Modern Design**: Clean, responsive UI with dark/light theme support

---

## 📱 Download

### Android APK
[![Download APK](https://img.shields.io/badge/Download-APK-green?style=for-the-badge&logo=android)](https://drive.google.com/uc?export=download&id=1MC-40oo6i0xJbhOoxywIm_A89vSTpPLU)

**App Size**: 35 MB  
**Requirements**: Android 6.0 or higher

### iOS App Store
🚧 **iOS version coming soon!** Stay tuned for updates.

---

## ✨ Features

### 🤖 AI-Driven Intelligence
- Advanced document analysis powered by Gemini AI
- Intelligent content understanding and important information extraction
- Automatic summarization and key points extraction
- Chart and table recognition from documents

### 📄 Smart Document Analysis
- Reading and analyzing PDF documents
- Converting complex texts into easy-to-understand summaries
- Recognizing charts and tables and converting them to text
- Fast and efficient processing with offline functionality

### 🎓 Advanced Learning Features
- Intelligent study assistant that helps you understand materials better
- Personal vocabulary library for important terms and concepts
- Interactive questions to test knowledge and enhance understanding
- Progress tracking and improvement analytics
- Multilingual support with instant English ↔ Arabic translation

### 🎨 Modern User Experience
- Clean, intuitive interface with Material Design 3
- Dark/Light mode support for comfortable studying
- Responsive design optimized for all screen sizes
- Smooth animations and micro-interactions

### 🔒 Privacy & Security
- Secure authentication with Firebase integration
- Local data storage for offline functionality
- No data collection without explicit user consent
- End-to-end encryption for user-generated content

---

## 🛠️ Technology Stack

### Core Framework
- **Flutter**: Cross-platform mobile application framework
- **Dart**: Programming language optimized for mobile development
- **SDK Version**: ^3.9.0

### Key Dependencies
```yaml
dependencies:
  carousel_slider: ^5.1.1      # Image carousel functionality
  cupertino_icons: ^1.0.8       # iOS-style icons
  flutter: sdk: flutter
  font_awesome_flutter: ^10.10.0 # Font Awesome icons
  google_fonts: ^6.3.1          # Google Fonts integration
  url_launcher: ^6.3.2          # URL launching capabilities
```

### Development Tools
```yaml
dev_dependencies:
  flutter_lints: ^5.0.0          # Code linting and analysis
  flutter_test: sdk: flutter     # Unit testing framework
```

### Platform Support
- 📱 **Android**: Native Android app (.apk)
- 🍎 **iOS**: Native iOS app (.ipa) - Coming Soon
- 🌐 **Web**: Progressive Web App (PWA) support
- 🖥️ **Desktop**: Windows, macOS, and Linux support

### AI Integration
- **Gemini AI**: Google's advanced AI for document analysis and processing
- **Translation API**: Real-time language translation services
- **OCR Engine**: Optical character recognition for document scanning

---

## 📁 Project Structure

```
aura_web/
├── lib/                          # Main application source code
│   ├── main.dart                # Application entry point
│   ├── global/                  # Global constants and utilities
│   │   └── page_one_info.dart   # App configuration and constants
│   └── screens/                 # UI screens and pages
│       └── page_one.dart        # Main promotional/marketing page
│
├── web/                          # Web-specific files
│   ├── index.html              # Web application entry point
│   ├── manifest.json           # PWA manifest
│   └── icons/                  # App icons for web
│
├── android/                     # Android-specific configurations
├── ios/                         # iOS-specific configurations
├── windows/                     # Windows-specific configurations
├── macos/                       # macOS-specific configurations
├── linux/                       # Linux-specific configurations
│
├── assets/                      # Static assets
│   └── images/                 # Image assets for app screenshots
│
├── pubspec.yaml                # Flutter project configuration
├── pubspec.lock               # Dependency lock file
└── README.md                  # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Flutter SDK**: ^3.9.0 or higher
  ```bash
  flutter --version
  ```

- **Dart SDK**: Included with Flutter installation

- **Development Environment**:
  - Android Studio / VS Code with Flutter extensions
  - Xcode (for iOS development)
  - Chrome (for web development)

### Environment Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/username/aura-web.git
   cd aura-web
   ```

2. **Install dependencies**:
   ```bash
   flutter pub get
   ```

3. **Verify installation**:
   ```bash
   flutter doctor
   ```

### Running the Application

#### For Web (Development)
```bash
flutter run -d chrome
```

#### For Android
```bash
flutter run -d android
# or run through Android Studio
```

#### For iOS (when available)
```bash
flutter run -d ios
# Requires Xcode and iOS Simulator
```

---

## 🏗️ Installation

### Building for Release

#### Android APK Build
```bash
# Build APK for release
flutter build apk --release

# Build app bundle (recommended for Play Store)
flutter build appbundle --release
```

#### Web Build
```bash
# Build web application
flutter build web --release
```

### Firebase Integration (Optional)

If you plan to add Firebase features:

1. Install Firebase CLI
2. Configure Firebase project
3. Add `firebase_core` dependency
4. Initialize Firebase in `main.dart`

---

## 👥 Meet Our Team

### Mahmoud Elnagar
**Flutter Developer**  
[![GitHub](https://img.shields.io/badge/GitHub-333333?style=flat&logo=github)](https://github.com/Mahmoudelnagar5)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/mahmoud-elnagar-11040a259/)

*Expert in Flutter development with a passion for creating beautiful, performant mobile applications. Specializes in cross-platform development and UI/UX implementation.*

### Omar Ayman
**Backend Developer**  
[![GitHub](https://img.shields.io/badge/GitHub-333333?style=flat&logo=github)](https://github.com/Ammoor)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/omar-ayman-gaber)

*Backend development specialist focusing on scalable APIs and cloud infrastructure. Expertise in AI integration and data processing systems.*

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help make Aura even better:

### Ways to Contribute

- 🐛 **Bug Reports**: Found a bug? [Create an issue](https://github.com/username/aura-web/issues)
- 💡 **Feature Requests**: Have an idea? [Share your suggestions](https://github.com/username/aura-web/issues)
- 🔧 **Code Contributions**: Ready to code? See our contribution guidelines below

### Development Workflow

1. **Fork** the project
2. **Create** your feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Contribution Guidelines

- Follow the existing code style and conventions
- Add tests for new features
- Update documentation as needed
- Ensure all tests pass before submitting PR
- Squash commits for cleaner pull request

---

## 📄 Development Guidelines

### Code Style
```bash
# Run Flutter analyzer
flutter analyze

# Format code
flutter format lib/

# Run tests
flutter test
```

### Git Commit Conventions
We follow conventional commits:
```bash
feat: add new feature
fix: bug fix
docs: documentation update
style: code formatting
refactor: code restructure
test: add tests
chore: maintenance tasks
```

### Branching Strategy
- `main`: Production-ready code
- `develop`: Active development branch
- `feature/*`: New features
- `fix/*`: Bug fixes
- `hotfix/*`: Critical fixes

### Testing
- Write unit tests for business logic
- Add widget tests for UI components
- Integration tests for key user flows
- Manual testing for UI/UX changes

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction...**

---

## 📞 Contact

### Project Links
- **GitHub Repository**: [Aura-Web](https://github.com/username/aura-web)
- **Issues**: [Report Bugs & Request Features](https://github.com/username/aura-web/issues)
- **Discussions**: [Community Forum](https://github.com/username/aura-web/discussions)

### Support
- 📧 **Email**: [support@aura-app.com](mailto:support@aura-app.com)
- 🐛 **Bug Reports**: [GitHub Issues](https://github.com/username/aura-web/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/username/aura-web/discussions)

### Social Media
- 📘 **Facebook**: [@AuraStudyApp]()
- 🐦 **Twitter**: [@AuraStudyApp]()
- 📷 **Instagram**: [@AuraStudyApp]()

---

<p align="center">
  Made with ❤️ by the Aura Development Team
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart"/>
  <img src="https://img.shields.io/badge/Google%20AI-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google AI"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white" alt="Firebase"/>
</p>

---

<div align="center">

**📚 Transform your learning experience with Aura - Your AI Study Companion 📚**

</div>
