Abstract

The Event Planner application was created to provide a lightweight, user-friendly method of tracking personal events. The application emphasizes simplicity, security, and offline functionality, with the optional addition of SMS alerts where device permissions allow. This report summarizes the design, development, and testing of the app while reflecting on the knowledge and skills demonstrated throughout the process.

Purpose and Goals

The primary purpose of the Event Planner app is to address the user need for a fast and intuitive way to manage events without requiring an online account or complex configurations. Users can create, update, and delete events within seconds, with data stored securely in a local SQLite database. The application also supports optional SMS reminders for events, ensuring that important dates are not overlooked. By focusing on privacy and accessibility, the design goals emphasized reliability, minimal permissions, and a clear user experience.

User-Centered Design

The design of the Event Planner interface was guided by principles of usability and minimalism. The grid-based layout supports quick scanning of events, while the bold iconography and clean forms make navigation accessible to a broad range of users. User needs were kept at the center of each design decision by minimizing unnecessary complexity and ensuring that all features remained functional offline. These choices created a user experience that balances simplicity with functionality.

Development Process

The app development followed an incremental and modular approach. Core features—such as database persistence, event management, and UI interaction—were developed and tested separately before integration. Strategies such as modular coding practices, Android lifecycle management, and iterative testing were employed to ensure that each component performed reliably. These strategies can be applied to future development projects to reduce debugging time and support clearer organization of code.

Testing and Evaluation

Testing was performed both on an Android emulator and on devices with SMS capability enabled. The process emphasized validation of database persistence, add/edit/delete functionality, and runtime permission handling. Testing confirmed that events remained saved across sessions and that the app remained fully usable even when SMS permissions were denied. This process was essential in identifying and resolving edge cases, thereby ensuring a stable user experience.

Challenges and Innovation

A significant challenge in development was balancing the inclusion of SMS alerts with Android’s strict runtime permission requirements. The solution involved implementing fallback functionality and clear user messaging, ensuring that the application retained its core usefulness even when permissions were denied. This innovative solution allowed the app to demonstrate role-appropriate SMS features while maintaining compliance with platform guidelines.

Key Success

The most successful technical component of the project was the persistent SQLite database integration. Ensuring that user data remained secure and accessible across sessions highlighted strong knowledge of Android’s data management practices. This achievement demonstrated effective skills in handling persistence, lifecycle management, and secure local storage.

Conclusion

The Event Planner project demonstrates the integration of user-centered design, modular coding practices, and rigorous testing to produce a reliable and accessible application. Challenges such as permissions and offline functionality were addressed with innovative solutions, while key successes included the seamless integration of SQLite persistence. Overall, the project reflects the developer’s ability to combine technical knowledge with user experience design to create a functional, secure, and adaptable mobile application.
