# QR_GENERATOR_NODE.JS
A simple QR Code Generator CLI tool built using Node.js. This tool allows users to generate QR codes from URLs and save them as images, along with storing the URL in a text file for reference. The generated QR code can be easily scanned to quickly access the provided URL.

# Features
- Generates QR codes from user-provided URLs.
  <img width="300" height="100" alt="image" src="https://github.com/Purnima3/QR_GENERATOR_NODE.JS/assets/96184253/56e968a3-5757-4d4e-8eb2-9eb22bccb295">

- Saves generated QR codes as PNG images.
  <img width="300" height="100" alt="image" src="https://github.com/Purnima3/QR_GENERATOR_NODE.JS/assets/96184253/e017ab5c-30ab-4638-a395-154b31c689f3">

- Stores the provided URL in a text file for future reference.
  <img width="300" height="100" alt="image" src="https://github.com/Purnima3/QR_GENERATOR_NODE.JS/assets/96184253/2a5ab643-a7b9-4b89-8123-ecc0f94a82c6">

- Uses an interactive prompt for user input.

# Technologies Used
- Node.js for building the command-line interface and handling file operations.
- inquirer for interactive command-line prompts.
- qr-image for generating QR codes.
- fs module for reading/writing files.

# How to Use
- Clone this repository.
- Navigate to the project directory.
- Install dependencies using npm install.
- Run the QR Code Generator using node index.js.
- Follow the prompts to enter a URL and generate a QR code.
- The generated QR code will be saved as qr_img.png, and the URL will be saved in URL.txt.

# Why This Project?
This project demonstrates the practical use of QR code generation in a command-line environment. It's a great way to learn about Node.js, handling user input, working with external modules, and basic file operations.
