# Webserv by RaphRsl
![image](https://github.com/user-attachments/assets/ad2fe62c-4a91-4945-8245-7a38ae35a5e6)

## Description

The **Webserv** project allowed us to write our own HTTP server, enhancing our understanding of the intricacies of the HTTP protocol. This project provided hands-on experience with client-server communication, non-blocking I/O operations, and server configuration, making it invaluable for our programming journey.

## Overview of the Project

- **What the Project Is:**
  The **Webserv** project focused on implementing a fully functional HTTP server, enabling us to handle requests and responses using the HTTP protocol.

- **Main Technical Features or Functionalities:**
  - Developed a compliant HTTP server capable of processing multiple requests simultaneously.
  - Implemented a non-blocking I/O model using `poll()` to manage client connections.
  - Handled various HTTP methods such as GET, POST, and DELETE.
  - Configured server behavior through an external configuration file.
  - Implemented error handling and default error pages for improved user experience.

- **Languages:**
  - C++

- **Tools and Technical Notions Involved:**
  - Non-blocking I/O / HTTP protocol / Socket programming / Polling mechanisms / Error handling / Makefile configuration / Multi-threading concepts / Server configuration management

## Key Features

- Efficient handling of multiple client requests using a non-blocking architecture.
- Dynamic configuration through external files for flexible server behavior.
- Robust error handling to ensure server stability and reliability.
- Ability to serve static files and handle file uploads.
- Comprehensive logging for debugging and monitoring server activity.
- Integration with testing frameworks for validating server functionality.

## Key Parts from an Academic View

#### Subject Summary

##### Requirements
- Must be implemented in C++98.
- Must follow the established coding norms; violations will lead to a grade of 0.
- Ensure all memory is properly managed and freed to prevent leaks.
- Submission of a **Makefile** to compile the project using the appropriate flags.
- The server must be run with a specified configuration file.

##### Mandatory Part
- Developed the HTTP server with the following command:
  ```bash
  ./webserv [configuration file]
  ```
- Ensured the server operated without blocking and could handle multiple I/O operations simultaneously using `poll()`.
- Implemented the required HTTP methods and ensured compliance with HTTP status codes.
- Created default error pages and provided functionality for serving static websites.

##### Bonus Part
- Implemented support for cookies and session management.
- Handled multiple CGI processes to enhance server capabilities.

<br><br>
<hr style="width: 50%; margin: auto;">
<br><br>

*Good luck!* Don’t hesitate to reach out if you have questions or suggestions for improving this README file! Feel free to star the repository if you find it useful and want to support me! ⭐ Sharing it with friends who might be struggling will also make you a hero!

## Author and Contributing

This project was created by RaphRsl as part of my curriculum at École 42 Paris (username rroussel). It was intended for academic purposes only. If you found this project useful, please consider starring the repository to show your support! ⭐

### How to Contribute

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.
