# Shorebird Example

A Flutter application demonstrating the integration and usage of [Shorebird](https://shorebird.dev) for code push updates. This example shows how to implement over-the-air updates in your Flutter application using Shorebird.

## Features

- Integration with Shorebird Code Push

## Prerequisites

Before running this project, make sure you have the following installed:

- [Shorebird CLI](https://docs.shorebird.dev/guides/install)

## Getting Started

1. Clone this repository:
   ```bash
   git clone <your-repository-url>
   cd shorebird_example
   ```

2. Install dependencies:
   ```bash
   flutter pub get
   ```

3. Initialize Shorebird in your project:
   ```bash
   shorebird init
   ```

4. Run the app:
   ```bash
   flutter run
   ```

## Project Structure

```
lib/
  ├── main.dart          # Main application file with Shorebird integration
  └── ...
```

## How It Works

The application demonstrates basic Shorebird functionality:

- Checks if Shorebird is available on the device
- Displays the current patch version

## Additional Resources

- [Shorebird Documentation](https://docs.shorebird.dev)
- [Shorebird GitHub](https://github.com/shorebirdtech/shorebird)
