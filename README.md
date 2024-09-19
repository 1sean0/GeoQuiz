# GeoQuiz

GeoQuiz is an Android trivia application designed for publication on the Google Play Store. The app tests users' knowledge with true/false questions and provides instant feedback, enhancing the learning experience.

## Features

- **Trivia Quiz:** Engages users with a series of true/false questions, providing immediate feedback through custom Toast messages.
  
- **Answer Review:** The "PREVIOUS" button allows users to review or change their previous answers, utilizing the ViewModel from Android’s Lifecycle library for effective state management.

- **Responsive User Interface:** Built with ConstraintLayout and Material Design components, ensuring a visually appealing and intuitive user experience.

- **ViewBinding Integration:** Simplifies UI interactions by eliminating the need for frequent calls to `findViewById()`, resulting in cleaner and more efficient code.

- **Seamless User Interaction:** Utilizes Kotlin Coroutines and Activity KTX to handle user interactions and lifecycle events smoothly.

- **Cheat Feature:** Includes a "CHEAT" option that tracks cheat attempts using SharedPreferences, displaying results in a custom Material Design dialog for enhanced user engagement.

## Technologies Used

- **Programming Languages:** Java, Kotlin
- **Development Tools:** Android Studio
- **Frameworks:** AndroidX, Material Design Components
- **Architecture:** MVVM (Model-View-ViewModel)
