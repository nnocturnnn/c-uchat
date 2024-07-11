# c-uchat

`c-uchat` is a simple chat application written in C, utilizing GTK+3 for the graphical user interface and TLS for secure connections. The application allows users to communicate in real-time over a network.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Installation

Follow these steps to install and run `c-uchat`:

1. Install GTK+3:

    ```sh
    brew install gtk+3
    ```

2. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/c-uchat.git
    ```

3. Navigate to the project directory:

    ```sh
    cd c-uchat
    ```

4. Build the project:

    ```sh
    make
    ```

5. Run the server:

    ```sh
    ./uchat_server 1337 0.0.0.0 admin
    ```

6. Run the client:

    ```sh
    ./uchat 127.0.0.1 1337
    ```

## Usage

- **Server**: To start the chat server, use the command `./uchat_server <port> <address> <admin>`, replacing `<port>`, `<address>`, and `<admin>` with the desired port number, address, and admin username respectively.

- **Client**: To start the chat client, use the command `./uchat <server_ip> <server_port>`, replacing `<server_ip>` and `<server_port>` with the IP address and port number of the server.

## Technologies Used

`c-uchat` is built using the following technologies:

1. **GTK+3**: Used for creating the graphical user interface.
2. **JSON**: Utilized for data interchange between the client and server.
3. **CSS**: Used for styling the chat interface.
4. **TLS**: Ensures secure communication between the client and server.
5. **SQLite3**: Used for storing chat history and user data.

## Contributing

Contributions are welcome! If you'd like to contribute to `c-uchat`, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Implement your changes.
4. Test your changes thoroughly.
5. Commit and push your changes to your forked repository.
6. Submit a pull request with a detailed description of your changes.

## License

`c-uchat` is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
