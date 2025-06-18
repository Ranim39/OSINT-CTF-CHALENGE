# Simple Web Steganography CTF Project

This project is a small demonstration combining steganography and a simple web challenge.

## Description

- A main web page with an image `secret.jpg` containing a hidden message (steganography).  
- A hidden folder `/hidden_folder` accessible via a link on the main page.  
- Inside this folder, a fake flag in a README file and the real flag hidden inside the `secret.jpg` image.  
- A `flag.html` file allows you to enter a flag to check if it is correct and display a success or failure message.

## Objective

Find the real flag hidden inside the image using steganography and validate it through the `flag.html` page.

## How to run

1. Clone the repository  
2. Open `index.html` in a browser  
3. Explore the page and the hidden folder  
4. Extract the hidden message from `secret.jpg` using `steghide` (password: `ccc`)  
5. Enter the flag in `flag.html` to verify it  

## Technologies used

- HTML/CSS/JAVASCRIPT
- Steganography with `steghide` (external tool)  

---

*This project is for learning and demonstration purposes only.*
