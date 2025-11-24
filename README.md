# Al-Muslim - Islamic Mobile Application

A beautiful, feature-rich Islamic mobile application built with React Native and Expo. Get accurate prayer times, access the Quran, and practice daily Islamic remembrances (Adhkar).

## 🌟 Features

### Prayer Times 🕌
- **Real-time Countdown**: Live HH:MM:SS countdown to the next prayer
- **Location-Based**: Automatic GPS-based prayer time calculations
- **Daily Schedule**: Complete prayer timetable (Fajr, Dhuhr, Asr, Maghrib, Isha)
- **Multiple Methods**: Support for different Islamic calculation schools
- **Push Notifications**: Automatic reminders for prayer times

### Quranic Content 📖
- **Full Quran**: All 114 Surahs with complete verses
- **Search**: Advanced search by Surah name or verse content
- **Bookmarks**: Save favorite verses for quick access
- **Beautiful Layout**: Optimized text display with proper Arabic formatting
- **Bilingual**: Arabic text with English translations

### Islamic Remembrances 🤲
- **Categorized Adhkar**: Morning, Evening, After Prayer, Before Sleep, Miscellaneous
- **Counter System**: Track your progress with built-in counters
- **Beautiful UI**: Easy-to-read Arabic and English text
- **Copy & Share**: Quick access to copy adhkar text

### Customization ⚙️
- **Dark/Light Mode**: Theme support for comfortable usage
- **Multiple Languages**: English, Arabic, Urdu, Indonesian support
- **Location Settings**: Auto-detect or manually set location
- **Notification Control**: Enable/disable prayer reminders

## 🛠 Technology Stack

- **React Native** - Cross-platform mobile development
- **Expo** - Simplified development and deployment
- **TypeScript** - Type-safe JavaScript
- **React Native Paper** - Material Design UI components
- **Adhan.js** - Islamic prayer time calculations
- **Expo Location** - GPS-based location services
- **Expo Notifications** - Push notification handling
- **AsyncStorage** - Local data persistence
- **date-fns** - Date manipulation and formatting

## 📁 Project Structure

```
al-muslim-app/
├── app/                           # Expo Router pages
│   ├── _layout.tsx               # Root layout with theme setup
│   └── (tabs)/                   # Tab-based navigation
│       ├── _layout.tsx           # Tabs configuration
│       ├── index.tsx             # Home screen (Prayer times)
│       ├── prayer.tsx            # Full prayer schedule
│       ├── quran.tsx             # Quranic content
│       ├── adhkar.tsx            # Islamic remembrances
│       └── settings.tsx          # User preferences
├── src/
│   ├── components/               # Reusable UI components
│   │   ├── CountdownTimer.tsx
│   │   ├── PrayerCard.tsx
│   │   ├── QuranicText.tsx
│   │   ├── AdhkarCard.tsx
│   │   └── SurahListItem.tsx
│   ├── services/                 # Business logic services
│   │   ├── prayerTimesService.ts
│   │   ├── locationService.ts
│   │   ├── notificationService.ts
│   │   ├── quranService.ts
│   │   └── adhkarService.ts
│   ├── hooks/                    # Custom React hooks
│   │   ├── useNextPrayer.ts
│   │   └── useLocation.ts
│   ├── data/                     # JSON data files
│   │   ├── quran_full.json
│   │   └── adhkar.json
│   └── core/                     # Core utilities
│       └── storage.ts            # AsyncStorage wrapper
└── assets/                       # Images and icons
```

## 🚀 Getting Started

### Prerequisites
- Node.js 16+ and npm/yarn
- Expo CLI: `npm install -g expo-cli`
- iOS Simulator (macOS) or Android Emulator

### Installation

1. **Clone and Install Dependencies**
```bash
npm install
# or
yarn install
```

2. **Start the Development Server**
```bash
expo start
```

3. **Run on Simulator/Emulator**
```bash
# iOS (macOS only)
expo start --ios

# Android
expo start --android

# Web
expo start --web
```

## 📝 Development

### Build for Production

**iOS:**
```bash
eas build --platform ios
```

**Android:**
```bash
eas build --platform android
```

### Available Scripts

- `npm start` - Start Expo development server
- `npm run android` - Run on Android emulator
- `npm run ios` - Run on iOS simulator
- `npm run web` - Run in web browser
- `npm run lint` - Run ESLint
- `npm run type-check` - Run TypeScript type checking

## 🎨 Design System

### Color Palette
- **Primary Green**: `#006a4e` - Represents Islamic tradition
- **Secondary Gold**: `#b59410` - Represents warmth and elegance
- **Background**: `#f8f9fa` - Light and clean
- **Dark Theme**: Automatic dark mode support

### Typography
- **Headlines**: 18-24px, Bold (700)
- **Body**: 14-16px, Regular (400-500)
- **Small Text**: 12-13px, Medium (500)

## 🔐 Security & Privacy

- ✅ **Local-First**: All user data stored locally, no server transmission
- ✅ **No Tracking**: Zero analytics or user tracking
- ✅ **No Ads**: Completely ad-free experience
- ✅ **Open Source**: Fully auditable code

## 🗺️ Future Enhancements

### Phase 2
- [ ] Audio Quran recitations with multiple Qaris
- [ ] Prayer direction (Qibla compass)
- [ ] Islamic calendar with important dates
- [ ] Prayer consistency statistics

### Phase 3
- [ ] Offline mode
- [ ] Multiple language UI translations
- [ ] Quranic Tafseer (explanations)
- [ ] Duas (supplications) library
- [ ] Hadith collections

## 📱 Supported Platforms

- iOS 13+
- Android 5+
- Web browsers (Chrome, Firefox, Safari)

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Contributing

Contributions are welcome! Please feel free to:
- Report bugs
- Suggest features
- Submit pull requests

## 📞 Support

For issues, questions, or suggestions, please open an issue on GitHub.

---

**Made with ❤️ for the Muslim community**

الحمد لله على كل حال
