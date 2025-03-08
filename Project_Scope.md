# Android Weather App Project Scope

## Overview
This project aims to build a private Android application that summarizes data from public weather stations on the Avalanche Canada website.

## Objectives
- Fetch and parse weather data from Avalanche Canada.
- Display key weather details (temperature, snowfall, wind speed, etc.) in a user-friendly format.
- Store and update data periodically on the device.
- Keep the application simple and private for personal use.

## Features
- **Data Fetching:** Use Retrofit (or Jsoup if scraping is needed) to retrieve data.
- **Data Storage:** Utilize Room Database or SharedPreferences for local storage.
- **User Interface:** Simple design using Jetpack Compose or XML layouts.
- **Background Updates:** Implement periodic updates using WorkManager.
- **Error Handling:** Manage API failures and network errors gracefully.

## Milestones
1. **Initial Setup:** Set up GitHub repo and Android Studio project.
2. **Data Retrieval:** Implement data fetching from the Avalanche Canada website.
3. **Data Processing:** Parse and store weather data.
4. **UI Development:** Build a basic UI to display the weather summaries.
5. **Testing & Debugging:** Thoroughly test the app on a physical device.
6. **Future Enhancements:** Consider adding graphs, notifications, and offline caching.

## Resources
- [Android Studio](https://developer.android.com/studio)
- [Retrofit Documentation](https://square.github.io/retrofit/)
- [Room Database Documentation](https://developer.android.com/training/data-storage/room)
- [WorkManager Documentation](https://developer.android.com/topic/libraries/architecture/workmanager)
- Useful GitHub repositories for code snippets and examples.

