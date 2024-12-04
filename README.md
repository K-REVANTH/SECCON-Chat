# SECCON Chat Application

Welcome to the **SECCON Chat Application**! 🚀 This secure messaging platform is built using Python and Tkinter, featuring multifactor authentication and a robust client-server architecture. Whether you’re chatting one-on-one or with multiple users, SECCON provides an encrypted communication channel with support for various cryptographic algorithms.

## 🌟 Features

- **Multifactor Authentication**: Secure login with multifactor authentication to ensure only authorized users can access the chat.
- **Client-Server Architecture**: A powerful server backend supports multiple clients simultaneously, enabling seamless communication.
- **Algorithm Selection**: Users can select from various encryption algorithms (RSA, DES, Caesar Cipher, Reverse Cipher, Transposition Cipher) to encrypt their messages. The chosen algorithm is communicated to the receiving end automatically.
- **Client-Client Communication**: Establish connections with one or many clients at a time. Find users using their unique IDs.
- **Dedicated Server Dashboard**: The server interface features a dashboard to manage connections and monitor activity.
- **Aesthetic Frontend**: The application boasts an intuitive and modern user interface, ensuring a pleasant chat experience.
- **IP Address Tracking**: IP addresses are used for connection tracking and user identification.

## 🛠️ Technologies

- **Python**: Core programming language used for application logic.
- **Tkinter**: GUI toolkit for building the desktop application interface.
- **Socket Programming**: For client-server communication.
- **Cryptographic Algorithms**: Includes RSA, DES, Caesar Cipher, Reverse Cipher, Transposition Cipher for message encryption.
- **Multifactor Authentication**: Enhanced security during user login.

## 📥 Setup and Installation

### Prerequisites

- Python 3.x
- Tkinter (usually included with Python installation)
- Required Python libraries (can be installed via `requirements.txt`)

### Installation Steps

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/aakulz/seccon-chat-app.git
    ```

2. **Navigate to the Project Directory:**

    ```bash
    cd seccon-chat-app
    ```

3. **Install Dependencies:**

    Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

    Install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Application:**

    Start the server:

    ```bash
    python server.py
    ```

    Start the client:

    ```bash
    python client.py
    ```

## 🖥️ Usage

1. **Launch the Server**: Start the server script to initialize the server dashboard and manage client connections.

2. **Launch the Client**: Start the client script. The login interface will prompt for credentials and MFA code.

3. **Connect to Other Users**: Use the unique ID to connect with other users or create new chat sessions.

4. **Select Encryption Algorithm**: Choose your preferred encryption method from the available options.

5. **Enjoy Secure Communication**: Chat securely with selected algorithms and see real-time updates.

## 📸 Screenshots

![Login Screen](docs/screenshots/login.png)
*Login Interface with Multifactor Authentication*

![Chat Window](docs/screenshots/chat.png)
*Modern Chat Interface with Encryption Options*

![Server Dashboard](docs/screenshots/server-dashboard.png)
*Server Dashboard for Managing Connections*

## 🤝 Contributing

Contributions are welcome! If you have suggestions, improvements, or bug fixes, please open an issue or submit a pull request.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

