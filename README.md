# Ethiopian Airlines Interface Design - Book a Flight UX

A modern, clean, and authentic Native Android application interface design replicating the **Ethiopian Airlines** mobile app "Book a Flight" home screen. Built using modular Android XML layouts, custom vector drawables, Material Components, and official brand colors.

---

## 📱 Interface Overview & Features

### 1. Brand Header (`layout_header.xml`)
* **Color Palette**: Ethiopian Airlines signature dark green (`#136B38`) with edge-to-edge status bar integration.
* **Logos & Branding**:
  * Main Ethiopian Airlines text logo with Amharic subtext (*የኢትዮጵያ*).
  * Sleek 3D white wing emblem positioned on the top right.
  * Star Alliance partnership emblem.
  * Globe language selector, notification bell, and main menu drawer.
* **Titles**: Main header title *"Book a Flight"* and tagline *"Make your flight unforgettable!"*.

### 2. Search Flights Card (`layout_search_card.xml`)
* White rounded card (`16dp` corner radius, `6dp` elevation) overlapping the dark green header.
* **Departure Input**: *"From: Addis Ababa (ADD) Ethiopia Africa"* with takeoff airplane icon (`ic_flight_takeoff`).
* **Arrival Input**: *"To"* hint with landing airplane icon (`ic_flight_landing`).
* **Swap Direction Button**: Circular badge centered between From and To boxes.
* **Action Button**: Full-width golden button *"Search Flights"* (`#EAA000`).

### 3. Join ShebaMiles Loyalty Program (`layout_shebamiles_card.xml`)
* Section header title *"Join ShebaMiles"*.
* Cream/beige background card (`#F4F0EA`).
* Integrated banner featuring membership cards, ShebaMiles ribbon logo, benefit description text (*"Join Ethiopian Airlines loyalty program"*, *"Enjoy exclusive member benefit!"*), and green action arrow (`➔`).

### 4. Top Destinations (`layout_top_destinations.xml`)
* Section header title *"Top destinations from Addis Ababa"*.
* High-resolution destination card featuring Wat Arun Bangkok temple image at sunset.
* Text overlay *"Bangkok Suvarnabhumi"* with drop shadow and yellow circular arrow button.

### 5. Quick Services (`layout_quick_services.xml`)
* 3 circular action badges:
  * **Bid to upgrade** (Tricolor Ethiopian leaf logo)
  * **Preferred seat** (Outline seat icon)
  * **On Board Wi-Fi** (Tricolor Ethiopian leaf logo)

### 6. Bottom Navigation (`layout_bottom_nav.xml`)
* Fixed bottom navigation bar (`60dp` height, white background).
* 4 main navigation items: **Home** (active green), **Book**, **My Trips**, and **Check-in**.

---

## 🛠️ Project Structure & Architecture

```
app/src/main/res/
├── drawable/
│   ├── bangkok.png                      <-- Destination background image
│   ├── bg_card_white.xml                <-- White card background shape
│   ├── bg_circle_icon.xml               <-- Circular icon badge background
│   ├── bg_gold_button.xml               <-- Golden button background shape
│   ├── bg_input_box.xml                 <-- Input field background shape
│   ├── ic_ethiopian_wing.xml            <-- White wing vector asset
│   ├── ic_star_alliance.xml             <-- Star Alliance vector asset
│   ├── shebamiles_image.png             <-- Loyalty program banner image
│   └── ... (Vector icons for flight, menu, bottom nav)
├── layout/
│   ├── activity_main.xml                <-- Main layout incorporating modular inclusions
│   ├── layout_header.xml                 <-- Top dark green brand header
│   ├── layout_search_card.xml            <-- Flight search card view
│   ├── layout_shebamiles_card.xml        <-- ShebaMiles section card
│   ├── layout_top_destinations.xml       <-- Destination card view
│   ├── layout_quick_services.xml         <-- Circular quick service buttons
│   └── layout_bottom_nav.xml             <-- Fixed bottom navigation bar
└── values/
    ├── colors.xml                        <-- Ethiopian Airlines brand palette
    ├── strings.xml                       <-- String resources
    └── themes.xml                        <-- Theme & status bar setup
```

---

## 💻 Technical Setup & Requirements

* **Language**: Kotlin & Android XML Layouts
* **Min SDK**: 24 (Android 7.0)
* **Target SDK**: 37 (Android 15+)
* **Dependencies**: Material Components (`com.google.android.material:material`), AndroidX AppCompat & ConstraintLayout.

---

## 🚀 How to Run the App

1. Clone the repository:
   ```bash
   git clone https://github.com/Leta-Kasahun/lab-1-ux-design-13eyob.git
   ```
2. Open the project in **Android Studio**.
3. Sync Gradle and run on an Android Emulator or connected device.
