# The Munich Flat Finder
 
## Overview

See the Project Pitch [on this presentation](https://github.com/mathilde206/MunichFlatFinder/blob/master/Project_%20The%20Munich%20Flat%20Finder.pdf) 

### What is this app for?
 
This is an app to help newcomers in Munich find a flat. 
 
### What does it do?
 
This app will allow users to search for appartment listings for various areas in Munich. They will also see information about each area. In the FAQ section, they will be able to see tips to find a flat and what to do next.
 
### How does it work
 
This app uses a 'fake' API from ImmobilienScout24 and Google Maps to show listings in Munich. The site is styled with Bootstrap, the pictures come from Pixabay, with a creative common 0 license.  
 
## Features

### Existing Features

-General Features
  - A responsive website for mobile, tablet and desktop.

- Flat Search
    - Show a list of search results for flats Note
    - Show results according to each area
    - Show other relevant data for each area. 

- FAQ
    - A bootstrap accordeon to present Q&A

- Contact Form
    - Validate the form  

### Features to Implement

- Flat Search: 
  - Use the real API from Immoscout     
 
## Tech Used
### Some the tech used includes:
- [AngularJS](https://angularjs.org/)
    - We use **AngularJS** to handle page routing, we also use it to make calls to the REST API and build custom directives
- [Bootstrap](http://getbootstrap.com/)
    - We use **Bootstrap** to give our project a simple, responsive layout
- [npm](https://www.npmjs.com/)
    - We use **npm** to help manage some of the dependencies in our application
- [bower](https://bower.io/)
    - **Bower** is used to manage the installation of our libraries and frameworks
 

## Testing
All the tests can be found on this [document](https://github.com/mathilde206/MunichFlatFinder/blob/master/MunichFlatFinder%20-%20Tests.pdf).

## Contributing
### Getting the code up and running
1. Firstly you will need to clone this repository by running the ```git clone https://github.com/mathilde206/MunichFlatFinder.git``` command
2. After you've that you'll need to make sure that you have **npm** and **bower** installed
  1. You can get **npm** by installing Node from [here](https://nodejs.org/en/)
  2. Once you've done this you'll need to run the following command:
     `npm install -g bower # this may require sudo on Mac/Linux`
3. Once **npm** and **bower** are installed, you'll need to install all of the dependencies in *package.json* and *bower.json*
  ```
  npm install
 
  bower install
  ```
4. After those dependencies have been installed you'll need to make sure that you have **http-server** installed. You can install this by running the following: ```npm install -g http-server # this also may require sudo on Mac/Linux```
5. Once **http-server** is installed run ```http-server -c-1```
6. The project will now run on [localhost](http://127.0.0.1:8080)
7. Make changes to the code and if you think it belongs in here then just submit a pull request

### Contribute ideas
If you would like to contribute to the content (extra tips about Munich, correct a wront information), feel free to get in touch with me. 

