# Random Color Generator

This project is a simple web application that changes the background color of the webpage to a random color every second.

## Features

- Generates a random color every second.
- Applies the random color to the background of the webpage.

## Installation

1. Clone the repository to your local machine:

    ```sh
    git clone https://github.com/vijayashanmuga/random-color-generator.git
    ```

2. Navigate to the project directory:

    ```sh
    cd random-color-generator
    ```

3. Open the `index.html` file in your preferred web browser.

## Usage

Once the `index.html` file is opened in a web browser, the background color of the page will change to a random color every second.

## Code Explanation

The main functionality of the random color generator is implemented in JavaScript. Below is the key part of the code:

```javascript
function changeBackground() {
    var a = Math.floor(Math.random() * 256);
    var b = Math.floor(Math.random() * 256);
    var c = Math.floor(Math.random() * 256);
    document.body.style.backgroundColor = "rgb(" + a + "," + b + "," + c + ")";
    // console.log(a, b, c);
}

setInterval(changeBackground, 1000);



![video](https://github.com/user-attachments/assets/c4c86305-c425-43af-9def-45e7854a816c)

![image](https://github.com/user-attachments/assets/da8f71dd-4a05-48a8-b08c-9a1d27b1e891)




