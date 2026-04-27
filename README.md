# Livana-connect

A Flutter-based family media streaming and subscription management app with Stripe integration, Firebase backend, and real-time notifications.

## Features ✨

- **User Authentication**: Firebase Auth (anonymous & email/password)
- **Family Groups**: Create and join families via hardware codes
- **Stripe Integration**: Subscription management with 30-day free trial
- **Cloud Firestore**: Real-time database for families, users, and subscriptions
- **Firebase Cloud Functions**: Callable functions for Stripe operations (Node.js v2)
- **App Check**: Security enforcement with debug tokens (dev) and Play Integrity (production)
- **Push Notifications**: Firebase Messaging for real-time updates and alerts
- **Responsive UI**: Built with Flutter ScreenUtil for multi-device support

## Tech Stack 🛠️

### Frontend (Flutter)
- **Framework**: Flutter 3.x
- **State Management**: Provider
- **UI**: Flutter ScreenUtil, Custom Widgets
- **Payments**: Flutter Stripe
- **Firebase**: 
  - Cloud Firestore
  - Firebase Auth
  - Cloud Functions
  - Firebase Messaging
  - App Check

### Backend (Node.js Cloud Functions)
- **Runtime**: Node.js 20 (GCP Cloud Functions v2)
- **Payments**: Stripe API
- **Authentication**: Firebase Admin SDK
- **App Check**: Enforcement on callables

### Infrastructure
- **Hosting**: Google Cloud (Cloud Run, Cloud Functions)
- **Database**: Firestore (NoSQL)
- **Auth**: Firebase Authentication
- **Messaging**: Firebase Cloud Messaging (FCM)

## Prerequisites 📋

- Flutter 3.x SDK
- Node.js 18+ (for local functions development)
- Firebase CLI (`npm install -g firebase-tools`)
- Google Cloud SDK (`gcloud`)
- Stripe account (API keys)

