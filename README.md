# Ethiopian Airlines Interface Design

Native Android application interface replicating the Ethiopian Airlines mobile app "Book a Flight" home screen.

## App Interface Preview

<p align="center">
  <img src="screenshots/app_preview1.png" width="340" alt="Ethiopian Airlines UI Top Screen" />
  <img src="screenshots/app_preview2.png" width="340" alt="Ethiopian Airlines UI Bottom Screen" />
</p>

## Overview

This project implements the home screen user interface of the Ethiopian Airlines mobile application. The design follows modern Android UX principles using modular XML layouts and Material Components.

### Main Components:

- **Header Section**: Brand branding, Amharic typography, Star Alliance logo, menu, and quick controls.
- **Flight Search Card**: Overlapping search card for origin/destination selection and flight search button.
- **ShebaMiles Loyalty Banner**: Loyalty program promotion card with member benefits.
- **Top Destinations**: Featured destination showcase cards with visual previews.
- **Quick Services**: Action shortcuts for upgrade bidding, seat selection, and on-board Wi-Fi.
- **Bottom Navigation**: Fixed navigation bar for main app sections (Home, Book, My Trips, Check-in).

## Project Structure

- `activity_main.xml` - Root view combining modular layout components.
- `layout_header.xml` - Brand header layout.
- `layout_search_card.xml` - Flight search card layout.
- `layout_shebamiles_card.xml` - ShebaMiles banner layout.
- `layout_top_destinations.xml` - Destination card layout.
- `layout_quick_services.xml` - Quick service buttons layout.
- `layout_bottom_nav.xml` - Bottom navigation layout.

## How to Build & Run

1. Open the project in **Android Studio**.
2. Sync Gradle dependencies.
3. Run on an Android emulator or physical device running Android 7.0 (API 24) or higher.
