# 📦 PackPals - Package Storage Management App

A modern React Native application for package storage management, connecting storage renters with storage keepers. Built with Expo and TypeScript, integrated with PackPals .NET backend API.

## ✨ Features

- 🔐 **Custom Authentication**: Secure user authentication with JWT tokens
- 🗺️ **Storage Location Maps**: Google Maps integration for storage locations
- 📦 **Storage Management**: Browse and book storage spaces
- 💳 **Payment Integration**: Secure payments with PayOS
- ⭐ **Rating System**: Rate storage providers and experiences
- 📱 **Role-based Access**: Separate flows for Renters and Keepers
- 🎨 **Modern UI**: Beautiful interface with NativeWind (Tailwind CSS)

## 🛠️ Tech Stack

- **Frontend**: React Native with Expo
- **Language**: TypeScript
- **Routing**: Expo Router
- **Authentication**: Custom JWT (integrated with PackPals .NET backend)
- **Backend**: ASP.NET Core 8.0 with Clean Architecture
- **Database**: SQL Server
- **Payment**: PayOS
- **Maps**: React Native Maps + Google Maps API
- **State Management**: Zustand
- **Styling**: NativeWind (Tailwind CSS for React Native)

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- Expo CLI
- iOS Simulator or Android Emulator
- Google Maps API key
- PackPals .NET backend running
- PayOS merchant account (for payments)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/PackPals.git
cd PackPals
```

2. Install dependencies:

```bash
npm install
```

3. Set up environment variables:
Create a `.env` file in the root directory and add your API keys:

```env
EXPO_PUBLIC_GOOGLE_API_KEY=your_google_maps_key
EXPO_PUBLIC_BACKEND_URL=https://localhost:7056/api
EXPO_PUBLIC_PayOS_MERCHANT_ID=your_payos_merchant_id
```

4. Start the development server:

```bash
npm start
```

5. Run on your preferred platform:

```bash
# iOS
npm run ios

# Android
npm run android

# Web
npm run web
```

## 🏗️ Project Structure

```
PackPals/
├── app/                    # App screens (Expo Router)
│   ├── (api)/             # API routes
│   ├── (auth)/            # Authentication screens
│   ├── (root)/            # Main app screens
│   └── (tabs)/            # Tab navigation
├── components/            # Reusable UI components
├── lib/                   # Business logic & utilities
├── types/                 # TypeScript type definitions
├── store/                 # Global state management
├── constants/             # App constants
├── hooks/                 # Custom React hooks
├── assets/                # Images, fonts, icons
└── docs/                  # Documentation
```

## 📦 Storage Management System

PackPals connects package senders (Renters) with storage providers (Keepers) through:

**For Renters:**
- Browse available storage locations
- Book storage spaces for packages
- Track package storage status
- Rate storage experiences

**For Keepers:**
- Manage storage locations
- Handle incoming orders
- Confirm package receipts
- Track earnings and ratings

## 📱 Screenshots

[Add screenshots here]

## 🔧 Configuration

### Google Maps Setup

1. Get a Google Maps API key from Google Cloud Console
2. Enable the following APIs:
   - Maps SDK for Android
   - Maps SDK for iOS
   - Places API
   - Directions API

### VNPAY Setup

1. Create a VNPAY merchant account
2. Get your merchant ID and secure keys
3. Configure payment webhooks and callbacks

### Backend Setup

1. Clone and run the PackPals .NET backend
2. Configure database connection
3. Set up authentication JWT secrets
4. Configure PayOS payment integration

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [Expo](https://expo.dev/)
- UI inspired by modern storage and logistics apps
- Payment processing powered by PayOS (Used to be VNPay in the previous design)
- Maps integration with Google Maps Platform

---

Video source: <https://www.youtube.com/watch?v=kmy_YNhl0mw&t=174s>
