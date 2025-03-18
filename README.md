# Java Emailing System

## Overview
The **Java Emailing System** is a simple email management system implemented using Java. It allows users to create accounts, log in, and manage their emails using a stack-based data structure. This system provides basic authentication and email storage functionality.

## Features
- **User Authentication**: Create new accounts and log in securely.
- **Email Management**: Each user has a stack to manage their emails.
- **Stack Operations**: Emails are stored and managed using stack operations (PUSH, POP, Display).
- **Basic Database**: Uses an in-built database (array or structure) for storing usernames and passwords.
- **Auto-login**: Automatically logs in after successful registration.
- **Session Management**: Logs out users and clears session data.

## Technologies Used
- **Java**: Core language for implementing the system.
- **Data Structures**: Stack for email storage.
- **Basic File Handling** (if applicable) for persistent storage.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/natekark/java-emailing-system.git
   ```
2. Navigate to the project folder:
   ```sh
   cd java-emailing-system
   ```
3. Compile the Java files:
   ```sh
   javac *.java
   ```
4. Run the program:
   ```sh
   java Main
   ```

## Usage
1. **Register a new account**: Enter a unique username and password.
2. **Login**: Use your credentials to access the system.
3. **Email Operations**:
   - Send (Push) an email to the stack.
   - Read (Pop) the most recent email.
   - Display all emails in your stack.
4. **Logout**: Securely exit the system.

## Future Improvements
- Implement a **queue** for sent emails.
- Add **database integration** for persistent user storage.
- Improve **UI/UX** with a graphical interface.
- Support **email attachments**.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Added new feature"`).
4. Push to your branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License.

## Contact
For any questions or suggestions, feel free to reach out!
