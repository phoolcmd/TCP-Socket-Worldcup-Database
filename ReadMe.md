# WorldCup Database
**Project Creators:** Bailey Seyller & Noah Wood

This project is a multithreaded TCP socket database written in Java and JavaFX. It allows users to create, read, update, and delete player and team data for the FIFA World Cup.

# How to Use
1. Compile and run the ServerApplication located in "src/main/java/edu/ucdenver/app".
2. Run the ClientApplication located in "src/main/java/edu/ucdenver/app".
3. Run the AdminApplication located in "src/main/java/edu/ucdenver/app".
4. Use the AdminApplication to edit the countries, teams, players, and matches.
5. Use the ClientApplication to view matches based on team and date.

The "t.txt" file can be used in the load file tab in the ServerApplication to load up some basic player information for testing if the file name is typed in full.

Note: Currently the UI is not very pretty and there are some exception handling issues and bugs if things aren't added properly.

![1](https://user-images.githubusercontent.com/121768237/227258739-cf6cecdb-8483-4cf3-89e2-88267f328000.PNG)
![2](https://user-images.githubusercontent.com/121768237/227258769-89e9f8e3-725c-4b53-b3ae-2ea1e4c95c3d.PNG)


# Programming Concepts Used
- **Multithreading:** This project uses multithreading to allow for multiple clients to connect to the server at the same time. This improves the responsiveness and overall performance of the database.

- **TCP Sockets:** The database uses TCP sockets to establish connections between the server and clients. This ensures reliable and ordered data transmission.

- **Object-Oriented Programming:** The project follows object-oriented design principles by breaking down the functionality of the database into separate classes and methods. This allows for easier maintenance, modification, and expansion of the codebase.

- **JavaFX GUI:** The user interface of the database is built using JavaFX. This allows for a modern and customizable GUI with support for styling and theming.

- **Exception Handling:** The project includes exception handling to catch and handle errors that may occur during runtime ensuring that the database operates reliably and prevents crashes or data corruption.
