🍖 Bustin' Chops - Food Delivery App

A comprehensive React Native mobile application built for a family's biltong business in Somerset West, Cape Town, South Africa.

## 📱 About The Project

Bustin' Chops is a full-stack delivery management system designed to handle the unique challenges of a small food business, including cash payment tracking, driver accountability, and admin oversight.

### Key Features

- **Customer Portal**: Browse products, add to cart, place orders via WhatsApp
- **Driver Dashboard**: Accept deliveries, track orders, confirm cash payments
- **Admin Panel**: Verify payments, prevent fraud, monitor operations
- **Payment Tracking**: Dual payment system (cash & card) with verification workflow
- **Anti-Fraud System**: Driver accountability and payment verification to prevent dishonesty

## 🛠️ Built With

- **React Native** - Cross-platform mobile framework
- **Expo** - Development and build tooling
- **TypeScript** - Type-safe JavaScript
- **React Navigation** - Navigation and routing
- **Firebase** - Backend and authentication (planned)
- **React Context API** - State management

## 🏗️ Project Structure

```
BustinChopsApp/
├── screens/           # All app screens
│   ├── customer/      # Home, Menu, Cart, Orders, Account
│   ├── driver/        # Driver dashboard and order management
│   └── admin/         # Admin panel for payment verification
├── context/           # State management (Cart, Auth)
├── services/          # API calls and Firebase integration
├── config/            # App configuration
└── App.js            # Main entry point
```

## 💡 Problem Solved

### The Cash Payment Challenge

In South Africa, many customers prefer cash on delivery. However, this creates accountability issues:

- How do you verify drivers actually collected payment?
- How do you prevent dishonest reporting?

### Our Solution

1. **Driver Confirmation**: Driver must confirm cash receipt before marking delivery complete
2. **Admin Verification**: All cash payments require manual admin approval
3. **Audit Trail**: Every transaction is logged with timestamps
4. **Dispute System**: Admins can flag suspicious payments

## 🚀 Getting Started

### Prerequisites

- Node.js (v18+)
- npm or yarn
- Expo CLI

### Installation

```bash
# Clone the repo
git clone https://github.com/YOUR-USERNAME/bustin-chops-app.git

# Navigate to project
cd bustin-chops-app

# Install dependencies
npm install --legacy-peer-deps

# Start the app
npm start
```

## 📲 Testing

- **Web**: Press `w` after starting
- **iOS**: Use Expo Go app and scan QR code
- **Android**: Use Expo Go app and scan QR code

## 🎯 Roadmap

- [ ] Complete Firebase integration
- [ ] Implement PayFast payment gateway
- [ ] Add real-time order tracking
- [ ] GPS location tracking for drivers
- [ ] Push notifications
- [ ] Customer ratings and reviews
- [ ] Build standalone APK for production

## 🌍 Local Context

Built specifically for the South African market:

- PayFast integration for local payments
- WhatsApp ordering (widely used in SA)
- Cash payment tracking (common in local businesses)
- Rand (R) currency

## 📚 What I Learned

- React Native mobile development
- State management with Context API
- TypeScript for type safety
- Firebase backend architecture
- Payment system design
- Anti-fraud mechanisms
- Cross-platform considerations

## 🤝 Development Process

This project was developed with assistance from AI tools and various online resources, implementing industry best practices for React Native development. The business logic and requirements are based on real-world needs from operating a small food business.

## 📧 Contact

Michelle - michelle4.dup@gmail.com

Project Link: [https://github.com/Michellex255/bustin-chops-app](https://github.com/Michellex255/bustin-chops-app)

## 🙏 Acknowledgments

- Expo Documentation
- React Navigation Docs
- Firebase Guides
- Stack Overflow Community
- AI Development Tools

---

**Note**: This is a working prototype. Firebase and payment integrations are in development.
