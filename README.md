# QR Scanner

This project is a simple command-line tool that allows users to generate QR codes from URLs and save the URL to a text file.

## Dependencies

1. inquirer: Used for getting user input in the command line.
1. qr-image: Used for generating QR code images.
3. fs: Node.js native module used for file system operations.
   
## Prerequisites

Before running this project, make sure you have Node.js and npm installed on your system.

## Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Run `npm install` to install the required dependencies.

## Usage

To run the QR scanner, use the following command:

```bash
node index.js
```

The program will prompt you to enter a URL. Once you enter the URL, it will generate a QR code image named qr_img.png and save the URL to a text file named URL.txt

