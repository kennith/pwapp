# Comments

I just completed the progressive web app Code Lab. 

One of the ideas of progressive web app is to make the web application more like a native application. 

The hardest part of progressive web app is probably the service worker. It requires some planning on what needs to be cached, what needs to update, and how to handle the updated service worker. The good part is there is sw-toolbox and sw-precache to help handling these situation.

Anyway, the last step of the code lab introduces Firebase. I tried it and it's amazingly fast and easy. If you need to deploy static web pages, Firebase will definitely make your deployment A LOT easier. 

---

# Your first Progressive Web App Code Lab

These are the resource files needed for the [Your first Progressive Web App](https://codelabs.developers.google.com/codelabs/your-first-pwapp/#0)
code lab from Google.

This is a work in progress, if you find a mistake, please [file an issue](https://github.com/googlecodelabs/your-first-pwapp/issues). Thanks!

## What you’ll learn
* How to design and construct an app using the “app shell” method
* How to make your app work offline
* How to store data for use offline later

## What you’ll need
* Chrome 47 or above, though any browser that supports service workers and `cache.addAll()` will work
* [Web Server for Chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb), or use your own web server of choice.
* The [sample code](https://github.com/googlecodelabs/your-first-pwapp/archive/master.zip)
* A text editor
* Basic knowledge of HTML, CSS and JavaScript
* (Optional) Node is required in the last step to deploy to Firebase
