# Flutter Template with Clean Architecture

## Description

This repository contains a Flutter project template with Clean Architecture, which separates concerns into well-defined layers for better organization, maintenance, and scalability of the code. The project structure follows the principles of Clean Architecture and provides a solid foundation for developing Flutter applications in a structured and modular way.

## Usage Instructions

1. **Clone the Repository**
```bash
git clone https://github.com/darioortelus/flutter-template.git
```  
3. **Install Dependencies**
Navigate to the project directory and run the following command to install dependencies:
cd flutter-template-clean-architecture
```bash
flutter pub get
```

5. **Configure Credentials**
If the project requires credentials, such as API keys, make sure to configure them correctly in the code or in secure configuration files that are not included in the public repository.

6. **Run the Application**
To run the application on an emulator or connected device, use the following command:
```bash
flutter run
```
8. **Run Tests**
Use the following command to run unit and integration tests:
```bash
flutter test
```
9. **Customize the Project**
Customize the project according to your application's needs, including modifying screens, widgets, business logic, and services.

10. **Contribution**
If you wish to contribute to the project, follow best collaboration practices and create pull requests with your improvements or fixes.

11. **Additional Documentation**
Add additional documentation, such as code style guides, contribution rules, and more, to facilitate collaboration and project maintenance.

## Project Structure

The project follows a file structure organized according to Clean Architecture principles. Make sure to review the project structure and understand the responsibility of each directory and file before making modifications.

flutter-template/
|-- android/
|-- ios/
|-- lib/
| |-- data/
| | |-- repositories/
| | | |-- user_repository.dart
| | | |-- product_repository.dart
| | |-- datasources/
| | |-- remote/
| | | |-- user_remote_datasource.dart
| | | |-- product_remote_datasource.dart
| | |-- local/
| | |-- user_local_datasource.dart
| | |-- product_local_datasource.dart
| |-- domain/
| | |-- entities/
| | | |-- user.dart
| | | |-- product.dart
| | |-- repositories/
| | |-- user_repository.dart
| | |-- product_repository.dart
| |-- presentation/
| |-- screens/
| | |-- home_screen.dart
| | |-- profile_screen.dart
| |-- widgets/
| |-- custom_button.dart
| |-- drawer_menu.dart
|-- test/
|-- pubspec.yaml
|-- README.md


## Contributions

Contributions are welcome to improve this project and make it more useful for the Flutter community. Feel free to open issues to report problems or suggest improvements, and send pull requests with your contributions.

We hope this project is helpful and helps you get started with Flutter and Clean Architecture effectively!
