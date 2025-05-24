🏠 ApkaThikana Nagpur
"Ghar Dhoondo, Khushi Paao"
A comprehensive real estate rental platform designed specifically for Nagpur, helping individuals and families find their perfect home with ease.

📌 Project Overview
ApkaThikana Nagpur is a cross-platform real estate rental application built with Flutter, targeting the Nagpur rental market. The application simplifies property discovery by providing an intuitive interface for tenants, landlords, and real estate agents.

🎯 Problem Statement
Finding rental properties in Nagpur can be time-consuming and frustrating. This app aims to streamline the process by providing a centralized, user-friendly platform for property listings and searches.

🌟 Vision
To become the go-to platform for rental properties in Nagpur, connecting property seekers with their ideal homes efficiently and transparently.

🛠️ Technology Stack
Component	Technology
Framework	Flutter (Cross-platform)
Language	Dart
Authentication	Firebase Authentication
Database	Firebase Firestore
Development IDE	Android Studio
Platform Support	Web, Android, Desktop (Windows)
State Management	Provider/Bloc (planned)
✨ Current Features
✅ Implemented
 Flutter Project Setup - Multi-platform configuration
 Firebase Integration - Authentication and Firestore setup
 User Authentication - Email/Password login and registration
 Authentication State Management - AuthGate implementation
 Basic UI Structure - Login and registration screens
🔄 In Progress
 Navigation Logic - Proper routing after authentication
 User Dashboard - Home screen implementation
 UI Debugging - Resolving blank screen issues
⏳ Planned Features
 Property Listings - Display available rental properties
 Search & Filters - Advanced property search functionality
 Favorites System - Save preferred properties
 Property Details - Comprehensive property information
 Contact System - Connect tenants with landlords
 Admin Dashboard - Property management for landlords
 Image Upload - Property photo management
 Map Integration - Location-based property search
🎯 Target Audience
User Type	Description	Key Needs
🏠 Tenants	Individuals/families seeking rental homes	Easy search, detailed property info, direct contact
🏘️ Landlords	Property owners listing rentals	Simple listing process, tenant management
🏢 Real Estate Agents	Professionals managing multiple properties	Bulk listings, client management tools
🚀 Getting Started
Prerequisites
Flutter SDK (latest stable version)
Android Studio or VS Code
Firebase account
Git
Installation Steps
Clone the repository
bash
git clone https://github.com/satishrasawar/apkathikana-nagpur.git
cd apkathikana-nagpur
Install dependencies
bash
flutter pub get
Firebase Configuration
bash
# Add your google-services.json (Android)
# Add your GoogleService-Info.plist (iOS)
# Configure Firebase web config
Run the application
bash
# For web
flutter run -d chrome

# For desktop
flutter run -d windows

# For Android (when available)
flutter run
📱 Platform Support
Platform	Status	Notes
🌐 Web	✅ Working	Primary development platform
🖥️ Windows Desktop	✅ Working	Initial testing complete
📱 Android	🔄 Planned	Next development phase
🍎 iOS	⏳ Future	Long-term goal
🏗️ Project Structure
apkathikana_nagpur/
├── lib/
│   ├── main.dart              # App entry point
│   ├── firebase_options.dart  # Firebase configuration
│   ├── auth/
│   │   ├── auth_gate.dart     # Authentication state management
│   │   ├── login_screen.dart  # Login UI
│   │   └── register_screen.dart # Registration UI
│   ├── screens/
│   │   ├── home/
│   │   │   └── user_home.dart # User dashboard (in progress)
│   │   └── property/
│   │       └── property_list.dart # Property listings (planned)
│   ├── models/
│   │   └── property_model.dart # Property data model (planned)
│   ├── services/
│   │   ├── auth_service.dart  # Authentication logic
│   │   └── firestore_service.dart # Database operations (planned)
│   └── widgets/
│       └── common/            # Reusable UI components
├── android/                   # Android-specific files
├── web/                      # Web-specific files
├── windows/                  # Windows desktop files
└── firebase/                 # Firebase configuration files
🔧 Current Development Status
⚠️ Known Issues
Blank Screen Issue: App builds successfully but displays blank page due to incomplete widget tree
Navigation Logic: AuthGate routing needs implementation
UI Rendering: UserHome screen requires proper widget structure
🔨 Next Development Steps
Phase 1: Core Functionality (Current)
Fix navigation and UI rendering issues
Implement UserHome dashboard
Complete authentication flow
Phase 2: Property Management
Create property data models
Implement Firestore integration
Build property listing screens
Phase 3: Advanced Features
Add search and filter functionality
Implement favorites system
Create contact mechanisms
Phase 4: Enhancement
Add map integration
Implement image upload
Create admin dashboard
🎨 Design Philosophy
User-Centric: Simple, intuitive interface prioritizing user experience
Local Focus: Tailored specifically for Nagpur's rental market
Cross-Platform: Consistent experience across web, mobile, and desktop
Scalable Architecture: Built to accommodate future feature additions
📊 Development Progress
Project Completion: ████████░░ 30%

✅ Project Setup & Configuration  (100%)
✅ Firebase Integration          (100%) 
✅ Authentication System         (80%)
🔄 UI Implementation            (40%)
⏳ Property Management          (0%)
⏳ Search & Filters            (0%)
⏳ Advanced Features           (0%)
🤝 Contributing
This project is currently in active development. Contributions, suggestions, and feedback are welcome!

Development Guidelines
Follow Flutter best practices
Maintain consistent code formatting
Write meaningful commit messages
Test on multiple platforms before submitting
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

👨‍💻 Developer
Satish Narayan Rasawar

📧 Email: satishrasawar@gmail.com
📱 Phone: +91 9271928857
🌍 Location: Chandrapur, Maharashtra
💼 GitHub: @satishrasawar
🎯 Project Goals
Short Term: Complete core functionality and launch beta version
Medium Term: Expand to Android platform and add advanced features
Long Term: Scale to other cities in Maharashtra and beyond
🙏 Acknowledgments
Flutter community for excellent documentation and support
Firebase for providing robust backend services
Nagpur real estate market insights and feedback
Built with ❤️ for the people of Nagpur

"Ghar Dhoondo, Khushi Paao" - Find a home, find happiness

- 👋 Hi, I’m @Satishrasawar
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Satishrasawar/Satishrasawar is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
