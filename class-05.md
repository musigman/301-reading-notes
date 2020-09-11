## Reading Day: 09.10.20
# Getting Started with Heroku

The most helpful thing I've read about Heroku today is this: *Heroku is the quickest way for a company to become an apps company. Heroku is a service that enables companies to spend their time developing and deploying apps that immediately start producing value.*

The following is abstract terminology that I will eventually understand.

# Procfile
A Procfile is a text file in the root directory of an application. An example would be: *web: node index.js* This declares a single process type 'web' and the command needed to run it. It declared that this process type will be attached to the HTTP routing stack of Heroku, and receive web traffic when deployed. Procfiles can contain additional process types.

# Dyno
A dyno is like a lightweight container that runs the command specified in the Procfile. You can check how many dynos are running using the ps command: **$ heroku ps**

By default, your app (running on Heroku) is deployed on a free dyno. Free dynos will sleep after a half hour of inactivity if they don't receive any traffic.

# App Dependencies
Heroku recognizes an app as Node.js by the existence of a package.json file in the root directory. For your own apps, you can create one by running *npm init --yes* from the command terminal. The *package.json file determines both the version of Node.js and dependencies that should be installed with your application.

# Add Ons
Heroku stores 1500 lines of logs from your application.

# Error message
My Heroku tutorial experience was cut short when it stopped responding in my terminal and I wasn't able to run the app. I reported the problem. 


[<== Back to Table of Contents](index.md)