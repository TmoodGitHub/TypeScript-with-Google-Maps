# Simple project built with TypeScript
Utilize the benefits of TypeScript; apply best practice and best design pattern into building an app

## Description of the project
The entire project is built with TypeScript. The objective is to use Google Map API with two markers: a User marker and a Company marker. The data collected are from NPM's Faker that generate random user name, company name, company catch phrase and longitude/latitude for both marker.

## Takeway from this project
Appreciate the importance of design pattern, scalability, and loose coupling. Other practical lesson is utilizing Class, interface, and implement which is a testament to the power of TypeScript.

## Running the app locally:

1. Download the repo
2. Install Parcel Bundler to run Typescript in the browser
  * `npm install -g parcel-bundler`
  * Type `parcel index.html` to build the project
  * After the build is complete, click on the localhost to view the work, typically `http://localhost:1234`

There you go! Every refresh will display User and Company marker at different location on the map. You will also be able to click on each marker to view User or Company's information.
