# Basic Javascript Router
> Basic Javascript Router which enables the coders to define routers as well as templates outside the script file... which is insane, right? 😀😀

## Table of contents
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## Technologies
* HTML
* JS

## Setup
* Inside your head tag define all the templates.
* Create a section/div in your body and give it an ID as 'appRoot'. (Excat name is important)
* Include the router.js file in your project html file in the bottom (or where ever the fuck you want😉).
* Next include all the routes your project has in the format
Yea, thats it. Router is all setup 😎.

## Code Examples
Basic example of template:
`<script type="text/html" id="home"><!-- Here goe the basic/ advanced html tags to get rendered runtime --></script>`
Here id='home' is the same id that will be referenced while rendering the component runtime.
 
Basic example of Route defination:
`route('/', 'home', function () {});`
Here '/' is the route where the home template should get rendered, 'home' is the id of the template that will be rendered.

## Features
List of features ready and TODOs for future development
* Separate templates
* Separate routes
* Easy to maintain

To-do list:
* Decide the active and inactive routes for the main navigation
* Nested routes

## Status
Project is: finished. Modifications are welcomed.

## Inspiration
Project inspired by john resig's, based on john resig's template engine.

## Contact
Created by [@KumarShubham001](http://www.kumarshubham.in/) - feel free to contact me!
