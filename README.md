**Project Description: Online Banking Management System**

The "Online Banking Management System" is designed to offer a comprehensive and user-friendly platform for a seamless banking experience. The main goal is to develop a secure and efficient online system enabling customers to perform various banking transactions easily. This project includes features like account management, user login systems, administrative access control, and multi-threaded concurrent access.

**Key Features:**
1. **Account and Customer Information Management:** All customer information and account transactional details are securely stored in files, ensuring data integrity and confidentiality.

2. **Login System:** Users must log in with their credentials to access their accounts, providing an added layer of security.

3. **Administrative Access Control:** The system includes password-protected administrative access to safeguard the entire management system from unauthorized access.

4. **Multiple Types of Logins:** The system supports three types of logins - normal user, joint account user, and administrator, offering specific privileges based on user roles.

5. **Administrator Functions:** Upon logging in as an administrator, authorized personnel can perform account-related operations, such as adding, deleting, modifying, and searching for specific account details.

6. **Interactive User Menu:** Users are presented with an interactive menu upon connecting to the server, allowing them to choose from various banking functionalities like deposit, withdraw, balance inquiry, password change, view details, and exit.

7. **File Locking Mechanism:** The system employs proper file locking techniques, specifically read and write locks, to ensure data consistency and protect critical data sections for joint account holders during simultaneous operations.

8. **Socket Programming:** Proper file locking techniques, specifically read and write locks, are used to ensure data consistency and protect critical data sections for joint account holders during simultaneous operations.

9. **System Calls:** Throughout the project, system calls are utilized instead of library functions where possible, to enhance efficiency and optimize process management, file handling, file locking, multi-threading, and inter-process communication mechanisms.

# Instructions to use

Step 1: Begin by executing the dataop.c program and provide the required registration information.

`$ gcc dataop.c -o data`

`$ ./data`

Step 2: Start the Server

`$ gcc -pthread server.c -o server`

`$ ./server`

Step 3: Launch the Client

`$ gcc client.c -o client`

`$ ./client`
