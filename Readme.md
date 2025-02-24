# StoreHub

This project is a powerful backend application designed for seamless file storage and management, much like Google Drive. Built with MongoDB, Express, and Node.js, it offers a robust set of features including secure user authentication, smooth file uploads, intuitive folder management, and efficient media streaming—creating a reliable, scalable solution for all your file handling needs.

![image](https://github.com/Pranay36/Store-Hub/blob/main/assets/storehub%201.png)

![image](https://github.com/Pranay36/Store-Hub/blob/main/assets/storehub%202.png)
![image](https://github.com/Pranay36/Store-Hub/blob/main/assets/storehub%203.png)
![image](https://github.com/Pranay36/Store-Hub/blob/main/assets/store%20hub%204.png)


## Tech Stack

- **Backend**: Node.js, Express
- **Database**: MongoDB, Mongoose
- **Authentication**: JWT, bcrypt
- **File Handling**: Multer, Cloudinary
- **Middleware**: Cookie-parser

## Features

  **User Authentication and Authorization**: Secure account creation and login using JWT and bcrypt.
- **File Uploads**: Store files in Cloudinary with support for multiple file types.
- **Folder Management**: Create, delete, and manage folders to keep your files organized.
- **File Management**: Search, download, delete files, and view media directly in the browser.
- **Media Streaming**: Stream video files using efficient networking techniques like data chunking for smooth playback.

## Important Concepts

 **Mongoose Transactions**: Ensure consistent, reliable database operations, preserving the integrity of your data even in the event of failures.
- **Retry Mechanisms**: Minimize data loss with intelligent retry strategies that handle operation failures and improve system reliability.
- **Efficient Data Handling**: Optimized schema design ensures faster queries, minimizing delays and enhancing performance for high-volume data operations.
- **Production-Level Code Quality**: Written with robust error handling, clean coding practices, and careful attention to scalability and maintainability.

## Usage

- **Create an Account**: Sign up using the provided endpoint.
- **Upload Files**: Upload files to Cloudinary via the upload endpoint.
- **Manage Files and Folders**: Use the respective endpoints to create/delete folders, search, download, and delete files.
- **Stream Media**: View images and videos directly in the browser.



## Acknowledgements

- Inspiration from Google Drive for the application's core concept.
- Libraries and frameworks used: Express, MongoDB, Mongoose, JWT, bcrypt, Multer, Cloudinary, and Cookie-parser.
