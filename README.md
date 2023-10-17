# back4app-custom-library
Library for making HTTP requests to back4app. *With authentication*
* Author - Iliyan Nikolaev M. 
* Release date - Q4'23

*Inspired by the JS-Applications course at the Software Academy - [SoftUni](https://softuni.bg/).*

## Benefits of the library:
* An easy way to send requests to Back4App.
* An abstract function that automatically sends authorized requests if a user is logged into your application.
* The library's functions can be used in both vanilla JavaScript applications and with other libraries or frameworks (such as React, Angular, etc.).

## Technologies
* Javascript
* [Back4App](https://www.back4app.com/)


## Implementation Plan
### Part 1
Creating and setting up an application in Back4app

### Part 2
Create a file named constants.js or .env and place the variables inside:
* APPID="..."
* JSKEY="..."
* B4AHOST="https://parseapi.back4app.com"

IMPORTANT: If you are using an .env file, you will need to make minimal changes in the "b4aRequest.js" module to import the above-mentioned variables from the .env file.

### Part 3
* Copy the code from the "b4aRequest.js" and "b4aAuth.js" modules and place them in the "src" directory of your project. Then, import the functions you need wherever you need them.

### Postscript 
The code also contains helpful explanations in the form of comments. If you don't understand bulgarian, you can use OpenAI to translate them 😁
