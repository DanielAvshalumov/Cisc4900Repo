# Virtual Muse Demo 

## Repository Purpose

This is the pre-version 1.0 of our product we would like to display to 
possible investors. The purpose this will serve is to showcase the 
capabilities of current open source technology, our fine tuning abilities,
and the results it can produce. This will also be a new challenge for me
as I will be using Typescript, which I haven't utilized in a project so 
far. 

## Contents

This will contain a front-end client written in React, and a backend server
leveraging the NodeJs Framework. As well as any external code such as a
Dockerfile or code that we are using from AWS Lambda.

## Architecture

The server will be extending the MVC architecture style to represent the
business logic in an easier to read, loosely coupled, and entensible way.
The client side will be separated by two folders, the components needed
to construct the User Interface, and services that will be used to call
endpoints created on the server. Additionally, we have AWS services set up
that will respond to certain triggers, such as file uploads to S3.
