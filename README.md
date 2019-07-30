# Greetings, UXDI!

### Overview

In this lesson, we will cover the basics of HTML, CSS, and JavaScript so that you have a better understanding of the elements that make up a webpage. 

## The basics

First of all, let's talk about this seemingly simple question... *What is the internet?*

Well, let's start with what we already know. We know that we can type a URL into the nav bar of a browser and access the associated website. 

But what actually *happens* when we do this?

Let's say we were to go to https://www.google.com. That address is really an alias, or a domain name, for the specific IP address where the google server lives. The DNS (Domain Name System) is a phonebook-like system that looks up the IP address.

Here's the basic process:

- You type www.google.com into your browser's address bar
- The browser sends an HTTP request to a DNS server
- The DNS server looks for a server that has a big list of all .com websites and sends us the IP address of that server. An IP address is a series of digits that act just like a physical street address.
- Now that we're in the .com server, they send us to yet another server that will send us to a more specific DNS server that, for example, maybe contains only websites that start with the letters E through K.
- We have finally been taken to the DNS server that knows where Google.com is! The final DNS server gives us the specific IP address of Google.com (139.130.4.5).
- Our browser finally goes to the address given by the last DNS Server and we see the beautiful Google landing page of the day!

## What is this client/server magic?

The internet comes down to requests and responses - you send information out to the web, and based on the info you send, you get information back. When two computers connect over the Internet, they establish a server-client relationship.

A **server** is a computer that is set up to accept requests and respond to them. We often say these systems host or serve webpages. They share their resources with clients.

A **client** is a computer that initiates a request from a server. When you open a webpage, your computer is the client, initiating the request on your behalf. We can also call your web browser (Chrome, Edge, Firefox, etc) the client, since it is the program on your computer that handles making the request and displays the response.
  > Ex: web browsers, terminals, SQL clients
  
The key here is that two computers get connected in a server-client relationship. The client initiates a request and the server responds. The client handles the response in some way that is useful for the user, like displaying the webpage on screen.

Note that it is possible for the same computer to play the role of server and client. It is common for a developer to set up their own computer to play the role of server while they're building a webpage. Then they can preview the site they're building while they're building it.

## A Website is Like a House

I like the metaphor used in [this article](https://generalassemb.ly/blog/website-is-like-a-house/).



### HTML

HTML stands for Hyper Text Markup Language. It's not technically a coding 'language', but it makes up ...


### CSS

<img src="https://media.giphy.com/media/yYSSBtDgbbRzq/giphy.gif" alt="css" width="400"/>


CSS stands for Cascading Style Sheets. While also not technically a coding language, it is something that developers must become comfortable with 

[Here's](http://www.brokenlandbar.com/) an example of a website with hardly any CSS.


Box Model:

![](https://www.topalovich.com/wp-content/uploads/2017/09/Box_Model.png)



[Fonts](https://fonts.google.com/)

[Colors](https://htmlcolorcodes.com/color-picker/)

[Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)




(thank you to [Britney Jo Ludkowski](https://git.generalassemb.ly/britneyjolud) for some parts of this repo)

