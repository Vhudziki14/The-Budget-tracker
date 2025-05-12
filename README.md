# The-Budget-tracker
ST10395237 PHOTO PRINCE RATLABALA
ST10376793 NDAMULELO NEGUDA
ST10165029 VHUDZIKI MATHIMANE

# The Budget Tracker App

The Budget Tracker App is a simple Android application designed to help users manage their finances effectively. It provides features to create and view categories, track entries, and set budget goals. Users can also register and log in to manage their information securely.

---

## Features

### 1. **Login and Registration**
- Users can register with their full name, email, username, and password.
- Secure login system with username and password validation.
- Mock user data for demonstration purposes.

### 2. **Dashboard**
- A central hub that provides an overview of the user's financial activities.
- Displays total balance, period expenses, and period income.
- Includes navigation buttons to access:
  - View Entries
  - Manage Categories
  - Set Goals
  - Exit App

### 3. **Manage Categories**
- Users can create categories (e.g., "Groceries," "Entertainment," etc.).
- Pre-populated with sample categories for demonstration purposes.
- Categories are displayed in a scrollable list using `RecyclerView`.

### 4. **Create and View Entries**
- Users can create financial entries with:
  - Title
  - Amount
  - Category
  - Optional photo upload
- Displays a scrollable list of entries using `RecyclerView`.
- Pre-populated with sample entries for demonstration.

### 5. **Set Budget Goals**
- Users can set minimum and maximum budget goals.
- The app validates the input to ensure the minimum goal is less than or equal to the maximum goal.
- Pre-filled with sample goals for demonstration.

---

## Screens and Layouts

### 1. **Login Screen**
Allows users to log in using their username and password. Includes a button to navigate to the registration page.

![Login Screen](screenshots/login_screen.png)

### 2. **Register Screen**
Allows users to register by entering their full name, email, username, password, and confirming the password.

![Register Screen](screenshots/register_screen.png)

### 3. **Dashboard**
Provides an overview of financial activity and navigation options.

![Dashboard](screenshots/dashboard.png)

### 4. **Manage Categories**
Enables users to create and view categories.

![Manage Categories](screenshots/manage_categories.png)

### 5. **Create and View Entries**
Allows users to add and view financial entries.

![Create and View Entries](screenshots/create_entries.png)

### 6. **Set Budget Goals**
Allows users to set and save budget goals.

![Set Budget Goals](screenshots/set_goals.png)

---

## How to Run the App

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/budget-tracker-app.git
   ```
2. Open the project in Android Studio.
3. Build and run the app on an emulator or physical device.

---

## Technologies Used

- **Kotlin**: Programming language for Android development.
- **Android SDK**: Core platform for building Android apps.
- **RecyclerView**: For displaying scrollable lists of items.
- **Room Database** (Optional): Can be integrated for data persistence.
- **Material Design**: For UI components and styling.

---

## Future Improvements

1. Add Room Database for persistent data storage.
2. Implement authentication with Firebase or another backend service.
3. Add data visualization (charts and graphs) for financial insights.
4. Add notifications for budget limits and expense tracking.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Author

**Nenguda**
- GitHub: [Nenguda](https://github.com/Nenguda)
- Email: [your-email@example.com](mailto:your-email@example.com)
