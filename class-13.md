# Reading Day: 09.22.20
## Update/Delete

## Client/Server Architecture
At a basic level, the web uses a client/server architecture that can be summarized as:
a **Client** (usually a browser) sends a request to a **Server**. Examples of servers include *Apache, Nginx, IIS, and Tomcat)*. Requests are sent using the HTTP protocol.

An HTML form on a web page is a convenient way to configure an HTTP request to send data to a server. This enables the user to provide information to be delivered in the HTTP request.

## Form Element
The *form* element defines how data will be sent. All of its attributes let you configure requests to be sent when a user presses a submit button. The two most important attributes are *action* and *method*

## Action Attribute
The *action* attributed defines where the data gets sent. its value must be a valid relative or absolute URL. An example of and absolute URL is a full website url: http://www.keithmusig.com/images/some-image.jpg. Relative URLs look like this: images/some-image.jpg.

## HTTP and HTTPS
You can specify a URL that uses the HTTPS protocol. HTTPS is a secure protocol. HTTPS encrypts data along with the rest of the request. How data is sent depends on the **Method** attribute.

## The Method Attribute
The most common *Method* attributes are the **Get** and **Post** method. Get is used by browsers to ask the server to send back a given resource.

The browser uses Post to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request. 

## Retrieving Data
Whatever HTTP method is chosen, the server receives a string that will be parsed in order to get the data as a list of key/value pairs. 

**PHP** offers some global objects to access the data. There are other server-side technologies you can use for form handling including **Perl, Java, .Net and Ruby**.

## Sending Files
Sending files with HTML forms is a special case, as files are binary data. Because HTTP is a a text protocol, there are special requirements.

The **enctype** attribute lets you specify the value of the content-type HTTP header included in the request generated when the form is submitted. It means: 'This is form data that has been encoded into URL Parameters.

## Security
Each time you send data to a server, you need to consider security. HTML forms are the most commonly attacked. 
To improve security it is recommended:
- Limit the incoming amount of data to allow only what is neccessary.
- Store uploaded files on a different server and allow access to the file only through a different subdomain.


[<== Back to Table of Contents](index.md)