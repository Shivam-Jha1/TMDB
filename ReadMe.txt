TMDB Client Application
Purpose
This project aims to deliver an immersive client experience for The Movie Database (TMDB) by creating a feature-rich Android application. The application leverages modern architecture and technologies to provide users with seamless access to movie information.

Architecture
The project adopts the Model-View-ViewModel (MVVM) clean architecture to ensure a modular, scalable, and maintainable codebase. This architecture separates concerns, making it easier to test, debug, and extend the application.

Components:
Model: Represents the data layer, including entities and data sources.
View: Represents the UI layer, responsible for displaying information to the user.
ViewModel: Acts as a bridge between the Model and View, handling the business logic and serving data to the UI.
Technologies Used
The application utilizes a stack of cutting-edge technologies to deliver a robust and efficient user experience.

Dagger: Dependency injection framework for managing dependencies and promoting code modularity.
Retrofit: A type-safe HTTP client for making network requests, ensuring efficient communication with the TMDB API.
Room: A SQLite object mapping library, providing a local database for caching and offline access.
Coroutines: Kotlin's native asynchronous programming framework, enhancing the app's responsiveness and scalability.
Data Binding: Simplifies UI components and ensures a tight connection between the UI and underlying data sources.
Data Sources
The application seamlessly integrates multiple data sources to provide users with a consistent experience, whether online or offline.

Local Data Source: Room database is used to store and retrieve data locally, allowing for efficient caching and offline access.
Remote Data Source: Retrofit facilitates communication with the TMDB API, ensuring real-time updates and access to the latest movie information.
Cache Data Source: The application intelligently manages caching to optimize performance and reduce redundant network requests.
Getting Started
To run the application locally, follow these steps:

Clone the repository: git clone [repository_url]
Open the project in Android Studio.
Build and run the application on your preferred emulator or physical device.
Feel free to explore the codebase, contribute, and enhance the TMDB client experience!

Acknowledgments
Special thanks to Anushka Madusanka Senior Software Engineer and Instructor and TMDB API for providing a rich source of movie information and enabling the development of this feature-packed client application.