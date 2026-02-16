# Nubank Home Design Flutter (Solo Mode)

This project is a Flutter implementation of the Nubank app's home screen. It replicates the UI and interactions of the popular Brazilian fintech app.

**Note:** This version has been modified to be a "Solo Mode" experience. Social features involving other participants ("Refer friends", "Charge", "Transfer") have been removed from the interface.

## 📱 Features

*   **Splash Screen:** Animated Nubank logo on startup.
*   **Home Screen:**
    *   **Draggable Cards:** A PageView with custom physics and animations for swiping between cards (Credit Card, Account Balance, Rewards).
    *   **Animated Menus:**
        *   **Top Menu:** Access to profile and app settings by pulling down the card view or tapping the top bar.
        *   **Bottom Menu:** Horizontal scrollable list of actions (Mobile Recharge, Loans, Deposit, Limit Adjustment, Pay, Block Card).
    *   **Interactive Elements:** Eye icon to toggle balance visibility, animated transitions.

## 🛠 Tech Stack

*   [Flutter](https://flutter.dev/) - UI Toolkit for building native apps.
*   Dart - The programming language used.

## 🚀 How to Run

1.  Clone this repository.
2.  Navigate to the project directory.
3.  Install dependencies:
    ```bash
    flutter pub get
    ```
4.  Run the app:
    ```bash
    flutter run
    ```

## 📝 Recent Changes (Solo Mode)

The following features were removed from the bottom menu to focus on a solo user experience:
*   Indicar amigos (Refer friends)
*   Cobrar (Charge)
*   Transferir (Transfer)

## 🤝 Original Project Credits

This project is based on a tutorial. Check out the original author:
*   [Github](https://github.com/RenatoLucasMota)
*   [Youtube Channel](https://www.youtube.com/channel/UCd-vLa_qcKve3CsDFlYiygA)

## 🐞 Bugs/Requests

If you encounter any problems, feel free to open an issue.
