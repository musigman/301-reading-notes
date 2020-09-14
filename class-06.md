## Reading Day: 09.13.20
# An Introduction to Node.js

Stack Overflow defines Node.js as an event-based, non-blocking, asynchronous I/O runtime that uses Google's V8 JavaScript engine and libuv library. The V8 engine is the open-source JavaScript engine that runs in Google Chrome and other browsers. It was designed for performance and is responsible for compiling JavaScript directly to native machine code that your computer can execute. What this means is Node.js is a program we can use to execute JavaScript on computers.

Installing Node.js from a version manager allows you to install multiple versions of Node and switch between them at will. As far as I can tell this allows you to work with and test older browsers.

## NPM
Node comes with a package manager called npm, which is also the world's largest software registry. There are over 1 million packages of JavaScript code available to download. Billions are downloaded each week.

## What Is it Used For?
Node.js and npm are designed to automate the process of developing a modern JavaScript application. These tools can be used for bundling JavaScript file and dependencies into static assets to running tests or automatic code linting and style checking.

Both Node and npm create development environments for other modern JavaScript framework like *React, Angular, and Yarn* technologies.

## Running JavaScript on a Server
One of the biggest cases for Node.js allows JavaScript to run on the server. 
Node is event-driven meaning everything that happens in Node is a reaction to an event. It uses the libuv library to implement asynchronous, non-blocking behavior.

Node.js execution model causes little overhead and is capable of handling a large number of simultaneous connections. It has a built-in module to implement cloning on a single server. The traditional approach to scaling a Node app is to clone it and have cloned instances share the workload.

## Apps
Node is particularly suited to building applications that require some form of real-time interaction or collaboration. Examples would be *Chat sites or apps involving data streaming.

## Advantages
Node.js is fast, makes it easy to use JavaScript on a web server and a browser and lets you easily share code between *server and client.*

Another advantage is the ability to speak with the *JSON* data exchange format.
JSON is the most important data exchange format on the web right now. When you're working with Node, data can flow neatly between layers between JSON without having to be reformatted. You can have one syntax from browser to server to database. 

Node can also be used as a scripting language, can be used to write a command line tool and build cross-platform desktop apps.

After completing my first 'Server Related' (Portfolio) project this past weekend, I feel I have a greater understanding of what goes into publishing a website or online app. Node.js is part of the framework that makes it possible.

[<== Back to Table of Contents](index.md)