# Pocket Pilot (Jetpack Compose Version)

## Overview

This Android application tracks a flight journey with multiple stops, displaying stop details, visa requirements, and progress. The app includes a toggle button for unit conversion (km/miles) and updates progress dynamically as stops are reached. This version is implemented using Jetpack Compose and Kotlin.

## Features

- **Scrollable list of stops** using LazyColumn.
- **Progress bar** that updates as stops are reached.
- **Color-coded stops**: Green for reached, red for pending.
- **Distance unit toggle**: Switch between kilometers and miles.
- **Bottom section** showing total distance covered.

## Project Structure
```plaintext
PocketPilotJetpackCompose/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/pocketpilot/
│   │   │   │   ├── MainActivity.kt
│   │   │   │   ├── StopItem.kt (Composable for each stop)
│   │   │   │   ├── StopList.kt (Composable for the list of stops)
│   │   │   │   ├── ProgressBar.kt (Composable for progress bar)
│   │   │   ├── res/
│   │   │   │   ├── drawable/
│   │   │   │   │   ├── bottom_box_background.xml
