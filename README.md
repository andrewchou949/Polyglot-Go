# Polyglot-Go

Polyglot-Go is a comprehensive project aimed at showcasing the integration of various technologies to build a multi-functional application. The project demonstrates the use of custom widgets, integration with Firestore, and implementation of various components.

![Project Poster](CSS%20497%20Capstone%20Poster.png)

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)

## Features
- Custom Widgets
- Firestore Integration
- Modular Components

## Installation

### Prerequisites
- Flutter SDK
- Dart
- Firestore account setup

### Steps
1. Clone the repository:
    ```bash
    git clone https://github.com/andrewchou949/Polyglot-Go.git
    cd Polyglot-Go
    ```
2. Install the dependencies:
    ```bash
    flutter pub get
    ```
3. Configure Firestore:
   - Ensure you have the necessary Firestore configurations in `firestore.rules` and `firestore.indexes.json`.

## Usage
1. Run the application:
    ```bash
    flutter run
    ```

## Project Structure
```plaintext
Polyglot-Go
├── CSS 497 Capstone Poster.png    # Project poster
├── README.md                      # Project readme
├── components                     # Directory for various components
│   └── ...                        # Component files
├── customWidgets                  # Directory for custom widgets
│   └── ...                        # Custom widget files
├── firestore.indexes.json         # Firestore index configurations
├── firestore.rules                # Firestore security rules
├── pages                          # Directory for application pages
│   └── ...                        # Page files
├── pubspec.yaml                   # Dart package configuration
