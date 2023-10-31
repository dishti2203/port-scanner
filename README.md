

1. Developed a **Port Scanner** using Python's **socket** and **termcolor** libraries.
2. The scanner takes a **target IP address** and a **range of ports** as input.
3. Implemented a function `scan(target, ports)` that initiates the scanning process for the given target and range of ports.
4. Within this function, a loop iterates over the range of ports and calls the `scan_port(ipaddress, port)` function for each port.
5. The `scan_port(ipaddress, port)` function attempts to establish a socket connection to the given IP address and port.
6. If the connection is successful, it means the port is open, and this information is printed to the console.
7. If the connection fails (which raises an exception), it means the port is closed, and the exception is silently passed.
8. The scanner supports scanning multiple targets simultaneously. If multiple targets are provided (separated by commas), the scanner will iterate over each target and scan all specified ports.
9. Used the termcolor library to provide colored terminal output for better readability.

This project demonstrates your skills in network programming with Python, understanding of TCP/IP and socket programming, ability to handle exceptions, and create user-friendly console output. It shows that you can build a robust and efficient network security tool that can scan multiple targets and a range of ports simultaneously.
