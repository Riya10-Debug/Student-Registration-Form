#  Flutter Student Registration Form

A Flutter application that implements a student registration form with proper input fields and validation. This project demonstrates form handling, user input validation, and clean UI design in Flutter.

---

##  Features

*  Name input field
*  Email input field with format validation
*  Phone number input field
*  Password field with secure input
*  Form validation for all fields
*  User-friendly layout and alignment

---

##  Technologies Used

* Flutter
* Dart

---

##  Project Structure

```id="kz81ab"
lib/
 └── main.dart
```

---

##  Getting Started

Follow these steps to run the project locally:

### Prerequisites

* Install Flutter SDK
* Install Android Studio / VS Code
* Set up an emulator or connect a physical device

---

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/flutter-student-registration.git
   ```

2. Navigate to the project directory:

   ```bash
   cd flutter-student-registration
   ```

3. Get dependencies:

   ```bash
   flutter pub get
   ```

4. Run the app:

   ```bash
   flutter run
   ```

---

##  Form Validation Rules

* **Name**

  * Cannot be empty

* **Email**

  * Must follow valid email format (e.g., [example@mail.com](mailto:example@mail.com))

* **Phone Number**

  * Must be numeric
  * Typically 10 digits

* **Password**

  * Minimum length (e.g., 6 characters)
  * Should not be empty

---

##  Implementation Details

* Uses `Form` and `TextFormField` widgets
* Validation handled using `validator` functions
* `GlobalKey<FormState>` used to manage form state
* Password field uses `obscureText: true`
* `ElevatedButton` used for submission

---
##  Future Improvements

* Add confirm password field
* Add password strength indicator
* Integrate backend (Firebase / API)
* Add success/error messages with Snackbar
* Improve UI with themes and animations

---

##  Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

##  Author

Riya Patani
---
