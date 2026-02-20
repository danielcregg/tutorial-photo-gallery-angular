# Tutorial Photo Gallery - Ionic Angular

![Ionic](https://img.shields.io/badge/Ionic-3880FF?style=flat-square&logo=ionic&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

A cross-platform photo gallery application built with Ionic, Angular, and Capacitor that runs on iOS, Android, and the web from a single codebase.

> **Note:** This repository is a fork of [ionic-team/tutorial-photo-gallery-angular](https://github.com/ionic-team/tutorial-photo-gallery-angular).

## Overview

This project is the companion application for the official Ionic Framework ["Your First App: Angular"](https://ionicframework.com/docs/angular/your-first-app) tutorial. It demonstrates a complete CRUD workflow where users can capture photos using the device camera, persist them to the filesystem, display them in a gallery grid, and delete individual photos. The app leverages Capacitor's native APIs to provide a consistent experience across web browsers and mobile platforms.

## Features

- **Camera Integration** -- Capture photos directly from the device camera using the Capacitor Camera API
- **Persistent Storage** -- Save photos to the device filesystem with automatic reload on app restart
- **Photo Gallery Grid** -- Display captured images in a responsive grid layout
- **Delete Photos** -- Remove photos via an action sheet dialog with filesystem cleanup
- **Cross-Platform** -- Single codebase that runs on iOS, Android, and the web
- **Tab-Based Navigation** -- Clean tab interface built with Ionic UI components

## Prerequisites

- **Node.js** 14 or higher
- **npm** 6 or higher
- **Ionic CLI** (`npm install -g @ionic/cli`)
- **Xcode** (for iOS development)
- **Android Studio** (for Android development)

## Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/danielcregg/tutorial-photo-gallery-angular.git
   cd tutorial-photo-gallery-angular
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Usage

Run the app in a web browser:
```bash
ionic serve
```

Run on iOS:
```bash
ionic cap run ios
```

Run on Android:
```bash
ionic cap run android
```

For a more detailed walkthrough, refer to the official [Ionic tutorial guide](https://ionicframework.com/docs/angular/your-first-app).

## Tech Stack

| Technology | Purpose |
|---|---|
| Angular 12 | Application framework |
| Ionic Framework 5 | UI component library |
| Capacitor 4 | Native runtime for cross-platform deployment |
| TypeScript | Type-safe application logic |
| SCSS | Component styling |

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
