# Wallpaper App

This is a modern Flutter-based mobile application that allows users to browse, search, and download high-quality wallpapers. It integrates with the Pexels API to fetch a vast collection of images based on search queries and categories. The app provides a clean and responsive UI experience on both Android and iOS platforms.

## Features

- View trending wallpapers
- Search wallpapers by keywords
- Browse wallpapers by predefined categories like Nature, Animals, Technology, and more
- Download and save wallpapers directly to the device
- Mark wallpapers as favorites for later access
- Smooth UI transitions and minimal design
- Responsive layout for various screen sizes

## Tech Stack

- Flutter – UI Framework
- Dart – Programming Language
- Pexels API – Image Source
- Provider – State Management
- SharedPreferences – For saving user preferences and favorites
- CachedNetworkImage – Efficient image caching
- URL Launcher – For opening external URLs
- Firebase Analytics – (Optional) Analytics integration

## Getting Started

### Clone the repository

```bash
git clone https://github.com/mrkankilic27/wallpaper-app.git
cd wallpaper-app
```

### Install dependencies

```bash
flutter pub get
```

### API Key Setup

This application uses the Pexels API to fetch wallpapers. Follow the steps below to set it up:

1. Visit [Pexels API](https://www.pexels.com/api/) and create an account to get your API key.
2. Create a `.env` or configuration file and store your API key securely.
3. Replace the placeholder `YOUR_API_KEY` in the source code with your actual key.

Example:

```dart
const String apiKey = 'YOUR_PEXELS_API_KEY';
```

**Important:** Never commit your API key to version control. Use environment variables or secret management practices in production.

### Run the App

```bash
flutter run
```

## Folder Structure

```bash
/lib
  /models           # Data models
  /screens          # All screen widgets
  /widgets          # Reusable components
  /services         # API and data services
  /utils            # Constants and utilities
  main.dart         # App entry point
```

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Author

**Mertcan Kankılıç**  
GitHub: [@mrkankilic27](https://github.com/mrkankilic27)  
Email: mertcankankilic27@gmail.com

---

Feel free to contribute, fork the repo, or open issues!