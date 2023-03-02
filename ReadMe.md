# WorldCup Database
**Project Creators:** Bailey Seyller & Noah Wood

This project is a multithreaded TCP socket database written in Java and JavaFX. It allows users to create, read, update, and delete player and team data for the FIFA World Cup.

# How to Use
Compile and run the ServerApplication located in "src/main/java/edu/ucdenver/app".
Run the ClientApplication located in "src/main/java/edu/ucdenver/app".
Use the GUI to interact with the database.
The "t.txt" file can be used in the load file tab in the ServerApplication to load up some basic player information for testing if the file name is typed in full.
Note: Currently the UI is not very pretty and there are some exception handling issues and bugs if things aren't added properly.

# Programming Concepts Used
- **Multithreading:** This project uses multithreading to allow for multiple clients to connect to the server at the same time. This improves the responsiveness and overall performance of the database.

- **TCP Sockets:** The database uses TCP sockets to establish connections between the server and clients. This ensures reliable and ordered data transmission.

- **Object-Oriented Programming:** The project follows object-oriented design principles by breaking down the functionality of the database into separate classes and methods. This allows for easier maintenance, modification, and expansion of the codebase.

- **JavaFX GUI:** The user interface of the database is built using JavaFX. This allows for a modern and customizable GUI with support for styling and theming.

- **Exception Handling:** The project includes proper exception handling to catch and handle errors that may occur during runtime. This ensures that the database operates reliably and prevents crashes or data corruption.
