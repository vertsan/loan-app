# Loan Amortization App

A Flutter application for calculating loan amortization schedules with support for Khmer language (ខ្មែរ) UI. The app provides detailed payment breakdowns and allows users to export schedules as PDF or Excel files.

## Features

- **Loan Amortization Calculation**: Calculate monthly payments and generate complete amortization schedules
- **Detailed Breakdown**: View payment dates, principal, interest, and remaining balance for each period
- **Export Options**: Export amortization schedules as PDF documents or Excel spreadsheets
- **Khmer Localization**: Full Khmer (ខ្មែរ) language support
- **Cross-Platform**: Runs on Android, iOS, Web, Windows, Linux, and macOS

## Requirements

- **Flutter**: SDK installed (latest stable recommended)
- **Dart**: ^3.9.2

## Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kravorkid/loan-app.git
   cd loan-app
   ```

2. Install dependencies:
   ```bash
   flutter pub get
   ```

3. Run the app:
   ```bash
   flutter run
   ```

### Testing

Run unit and widget tests:
```bash
flutter test
```

### Code Analysis

Run static analysis:
```bash
flutter analyze
```

## Project Structure

```text
lib/
├── config/          # App configuration (themes, routes, etc.)
├── core/            # Core utilities, constants, and helpers
├── data/            # Data models, repositories, and services
├── features/        # Feature-based modules
│   ├── amortization/ # Amortization calculation and display
│   ├── export/      # PDF and Excel export functionality
│   └── input/       # Loan input form
├── l10n/            # Localization files (English and Khmer)
├── shared/          # Shared widgets, utilities, and extensions
└── main.dart        # App entry point
```

## Platforms

- Android
- iOS
- Web
- Windows
- Linux
- macOS
