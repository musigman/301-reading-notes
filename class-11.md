# Reading Day: 09.19.20
## EJS
EJS stands for Embedded JavaScript Templating. EJS is a simple templating language that lets you generate HTML markup with plain JavaScript. These are opening and closing EJS tags: <% %>
These tags are a way of injecting JavaScript in a an EJS file. 

## Value Points
- You can use plain JavaScript
- Fast Development time
- Simple, write the JS you want
- Speedy execution
- Easy to Debug
- Active development

To install EJS, you use the following NPM command: *npm install ejs*
Then pass DJS a template string and some data, then you have some HTML.

While watching the youtube videos and reading the documentation, I'm intriqued and curious about the uses. As far as I can tell, EJS helps create a backend window to the server engine. This looks like it could be fun! I'm sure that I'll get hands on with it soon.

## Books API - Working with Volumes
I'm not clear how this reading connects with EJS.
What I got out of this is that You can perform a volumes search by sending an HTTP GET request to the following URI:
**https://www.googleapis.com/books/v1/volumes?q=search+terms**

This request has a single required parameter:
**q -** Search for volumes that contain this text string. There are special keywords you can specify in the search terms to search in particular fields, such as:

- Intitle: return results of keyword in title
- Inauthor: return results of keyword in author
- Inpublisher: return results of keyword in publisher
- Subject: return results of keyword in subject
- Isbn: return results of keyword in isbn
- Lccn: return results of keyword in lccn
- Oclc: return results of keyword in oclc

[<== Back to Table of Contents](index.md)