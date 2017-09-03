# Angular Todo App

## Overview

### What is this app for?

This is a Todo app. It helps users to keep track of any things that they have todo.


### What does it do?

This app will allow users to register and login. Once the users have done that, they'll be able to create items to add to their todo list. Once they've created their todo list, they'll be able to update the status of each item and even delete items!

### How does it work?

This app uses JSON Web Tokens to authenticate users and keep them logged in. All the data is consumed from an API hosted on Heroku using AngularJS. The site is styled with Bootstrap.

## Features

### Existing feautures
-None yet!

### Features Left to Implement
-User Based Features
	-Registration
	-Login
	-Logout
-Todo Based Features
	-Creating Todo Items
	-Retrieving Todo Items
	-Update Todo Items
	-Deleting Todo Items

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


## Contributing

### Getting the code up and running
1. Firstly you will need to clone this repository by running the ```git clone <project's Github URL>``` command
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
OK, so now we have our seven steps that a developer will need to follow in order to contribute to the repo! Anything contained within the opening and closing ``` shows up as code. This is like using HTML’s <code> element.

At the moment, we only use this to inform others of the commands they need to run – however, Markdown does also allow for you to specify a language so it can highlight the syntax accordingly. For example:


```javascript 
function greet(target) {
    console.log("Hello, " + target + "!");
}
 
greet("World");
```
This will give us the following:

markdown


We don’t need this kind of fanciness at the moment, but it’s a really useful way of highlighting certain areas of your code, or giving examples of how to use some of the code that you’ve built!

Notice that we’re using a numbered list! Once again, this is similar to HTML’s <ol> and once we tab in and start number items inside an existing numbered list, it will automatically create a list ordered by roman numerals.

The last new thing that we have in there is the single asterisks (*). These simply denote that the text inside should be italicized.


Screenshot from 2016-10-26 07-32-10.png

 
Now that we have our README.md file done, we can go ahead and push it up to Github. In order to do that, we just use our usual Git commands:

1
2
3
git add README.md
git commit -m “Add README”
git push
And there we have it!


Screenshot from 2016-10-26 11-07-53.png

 
As a bit of practice, try to keep your README file up-to-date as you make your way through this module!


SUMMARY

So in this lesson we’ve managed to create ourselves a nice README.md file that will give other developers (or anyone that visits this repository) an overview of what purpose this project solves, what it does (or will eventually do!), the tech involved in making it work, and how other developers can get access to the code and how they can make modifications and even contribute to the existing project.

We managed to achieve this by creating a simple Markdown file and using some basic formatting syntax! This tiny amount of syntax allowed us to create headers of different sizes, bold and italic text, create lists (both ordered and unordered) with sublists, create links, and stylized code areas.

 COMPLETED CODE
The code for this lesson can be found at https://github.com/Code-Institute-Org/full_stack_solutions/tree/master/Stream-1/angular-todo/markdown


 ADDITIONAL PERSPECTIVES FROM PEOPLE WE LIKE

Markdown Cheatsheet
PREVIOUS UNIT
MARK THIS UNIT COMPLETE
