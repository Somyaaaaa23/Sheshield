# SheShield App Setup Guide

## Environment Variables Setup

Create a `.env` file in the root directory with the following variables:

```env
# Firebase Configuration
FIREBASE_API_KEY=your_firebase_api_key_here
FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
FIREBASE_PROJECT_ID=your_project_id
FIREBASE_STORAGE_BUCKET=your_project.appspot.com
FIREBASE_MESSAGING_SENDER_ID=your_sender_id
FIREBASE_APP_ID=your_app_id

# Twilio Configuration (for SMS features)
TWILIO_ACCOUNT_SID=your_twilio_account_sid
TWILIO_AUTH_TOKEN=your_twilio_auth_token
TWILIO_PHONE_NUMBER=your_twilio_phone_number

# Google Gemini AI (for chat features)
GEMINI_API_KEY=your_gemini_api_key

# Supabase Configuration
SUPABASE_URL=https://your_project.supabase.co
SUPABASE_ANON_KEY=your_supabase_anon_key
```

## New Features Implemented

### 1. Profile Picture Upload
- ✅ Firebase Storage integration
- ✅ Image compression and optimization
- ✅ Real-time upload progress
- ✅ Error handling and user feedback
- ✅ Automatic profile picture updates

### 2. Contact Support
- ✅ Phone support: +918005626743
- ✅ Email support: support@sheshield.com
- ✅ Website support: https://sheshield.com
- ✅ Multiple contact options
- ✅ Support hours information
- ✅ Emergency guidance

### 3. FAQ System
- ✅ 15 comprehensive questions and answers
- ✅ Expandable FAQ items
- ✅ Categorized information
- ✅ User-friendly interface
- ✅ App-specific guidance

## Setup Instructions

1. **Install Dependencies:**
   ```bash
   flutter pub get
   ```

2. **Configure Firebase:**
   - Set up Firebase project
   - Enable Authentication, Firestore, Storage, and Messaging
   - Add your Firebase configuration to `.env`

3. **Configure Twilio (Optional):**
   - Set up Twilio account for SMS features
   - Add Twilio credentials to `.env`

4. **Configure Google Gemini (Optional):**
   - Get API key from Google AI Studio
   - Add to `.env` for chat features

5. **Run the App:**
   ```bash
   flutter run
   ```

## Features Overview

### Profile Management
- Upload and update profile pictures
- Edit personal information
- Change password functionality
- Real-time profile updates

### Support System
- 24/7 phone support
- Email support with auto-subject
- Website knowledge base
- Emergency guidance integration

### FAQ System
- Comprehensive app guidance
- Expandable question format
- User-friendly navigation
- Emergency procedure information

## Troubleshooting

### Common Issues:
1. **Firebase Storage not working:** Ensure Firebase Storage is enabled in your project
2. **Image upload fails:** Check internet connection and Firebase Storage rules
3. **Contact support not working:** Verify phone permissions and URL launcher setup
4. **FAQ not loading:** Check if the FAQ screen is properly imported

### Error Handling:
- All features include comprehensive error handling
- User-friendly error messages
- Graceful fallbacks for failed operations
- Network connectivity checks

## Security Notes

- Profile images are stored securely in Firebase Storage
- User data is encrypted and protected
- Support communications are secure
- Emergency contacts are verified before use

## Support

For technical support, contact:
- Phone: +918005626743
- Email: support@sheshield.com
- Website: https://sheshield.com 