# Generate Dynamic PDFs Using React and NodeJS

## Currency Converter Tutorial

This is a code repository for the corresponding [article](https://medium.freecodecamp.org/how-to-generate-dynamic-pdfs-using-react-and-nodejs-eac9e9cb4dde) on Medium.

In this tutorial, you will learn how to generate dynamic PDFs using HTML code as a template.

## Project Setup

1. Create a new directory
```mkdir pdfGenerator && cd pdfGenerator```
2. Create a new React App with ```create-react-app client``` and then move into newly created directory and install dependencies ```cd client && npm i -S axios file-saver```
3. Create an Express server with ```mkdir server && cd server && touch index.js && npm init``` press enter a couple of times to initialize package.json and then run ```npm i -S express body-parser cors html-pdf ``` to save all the necessary dependencies.
4. Add proxy inside of client/package.json, above the dependencies, simply add ```“proxy”: “http://localhost:5000/"```, so you can call the localhost from the client.
5. Open two different terminals:
First one: go into the client directory and ```run npm start```
Second one: go into the server directory and ```run nodemon index.js```
