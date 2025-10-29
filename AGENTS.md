# Getting Started with open_family_tree

This document provides instructions for setting up your development environment to contribute to the `open_family_tree` project.

## Prerequisites

Before you begin, ensure you have the following installed on your system:

*   **Flutter:** This project is built with Flutter. You will need to have the Flutter SDK installed. You can find installation instructions on the [official Flutter website](https://flutter.dev/docs/get-started/install).

## Setting up your machine

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/lohnn/open_family_tree.git
    cd open_family_tree
    ```

2.  **Check your Flutter environment:**
    Run the `flutter doctor` command to ensure your environment is set up correctly. This command checks your local machine and displays a report of the status of your Flutter installation.

    ```bash
    flutter doctor
    ```
    Address any issues reported by `flutter doctor`.

3.  **Get dependencies:**
    Fetch the project dependencies by running the following command in the project's root directory:
    ```bash
    flutter pub get
    ```

## Running the application

Once you have completed the setup, you can run the application on your desired device or emulator.

```bash
flutter run
```

This will launch the `open_family_tree` application.
