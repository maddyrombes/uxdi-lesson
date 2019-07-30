# Greetings, UXDI!

### Overview

In this lesson, we will cover the basics of HTML, CSS, and JavaScript so that you have a better understanding of the elements that make up a webpage. 

## The basics

What happens when we browse the web?

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

## Clients and Servers

So... *What is the internet?*

The internet comes down to requests and responses - you send information out to the web, and based on the info you send, you get information back. When two computers connect over the Internet, they establish a server-client relationship.

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/Client-server-model.svg/250px-Client-server-model.svg.png" width=400/>

A **server** is a computer that is set up to accept requests and respond to them. We often say these systems host or serve webpages. They share their resources with clients.

A **client** is a computer that initiates a request from a server. When you open a webpage, your computer is the client, initiating the request on your behalf. We can also call your web browser (Chrome, Edge, Firefox, etc) the client, since it is the program on your computer that handles making the request and displays the response.
  
The key here is that two computers get connected in a server-client relationship. The client initiates a request and the server responds. The client handles the response in some way that is useful for the user, like displaying the webpage on screen.

Note that it is possible for the same computer to play the role of server and client. It is common for a developer to set up their own computer to play the role of server while they're building a webpage. Then they can preview the site they're building while they're building it.

## A Website is Like a House

I like the metaphor used in [this article](https://generalassemb.ly/blog/website-is-like-a-house/).

Here are the elements that make up a website:

- HTML: The backbone of the site. This includes text, images, videos, and the basic structure.
- CSS: The way the site looks: color; font family and size; margins and spacing; etc.
- JavaScript: Determines how a user can interact with a site, including click events, form handling, popups, and really anything that moves.
- The back end: databases & handling data


### HTML

HTML stands for Hyper Text Markup Language. It's not technically a coding 'language', but all programmers must know how to write it, as it holds the text and structure of a site. 

Most HTML elements have an opening tag and a closing tag. For instance:

- paragraph: `<p>Hello!</p>
- headers (h1 through h6): `<h1>This is a top-level header.</h1>`
- navigation bars: `<nav>I would put some nav elements here.</nav>`
- divs, or block dividers: `<div>I can put a whole lot of other elements in here!</div>`
- links, or a tags: `<a href="link_url">The text I want to show for my link goes here</a>`

Some HTML elements don't technically *contain* anything, so they are self-closing. For example:

- images: `<img src="image_source_here"/>`
- line breaks: `<br/>`
- input fields for forms:

```
<form>
  <input type="text"/>
</form>
```

Formatting HTML correctly is essential to making it readable. Basically, each nested element should be indented three spaces or one tab from the previous one.

See how the input tag above has an attribute of `type="text"`? We can add other attributes to these tags as well.

Importantly, we can add `class` and `id` to HTML tags so that we can interact with them using CSS. For instance:

```
<div class="container">
  <p id="amazing-paragraph">My amazing paragraph</p>
  <p id="fantastic-paragraph">My fantastic paragraph</p>
</div>
```

Classes can be assigned to *multiple* elements, so they would be used when you want multiple things to have the same style. Ids can only be applied to one element.

I'll dive into how to interact with these elements using CSS below.


### CSS

<img src="https://media.giphy.com/media/yYSSBtDgbbRzq/giphy.gif" alt="css" width="400"/>

CSS stands for Cascading Style Sheets. While also not technically a coding language, developers rely on CSS to make their sites pretty and engaging. 

If we didn't use CSS, all websites would look something like [this](http://www.brokenlandbar.com/)...

Writing CSS is pretty simple. There are three main ways to use CSS to interact with our HTML elements:

- by tag type:
```
p {
  font-size: 14px;
}
```
- by class name, using a dot:
```
.container {
  border: 10px solid black;
}
```
- by id name, using an octothorp:
```
#amazing-paragraph {
  color: blue;
}
```

There are built-in fonts that you can use in CSS, but I like to use [Google Fonts](https://fonts.google.com/).

There are also built-in colors, but you can use any hex number or RGB(A) color, too. I like to use a [color picker](https://htmlcolorcodes.com/color-picker/).


### Javascript

Now we're getting into real programming!

While HTML and CSS are standard for all websites (there are no alternatives), Javascript is one of many coding languages that developers use. However, it is arguably the most popular language for developing front-end sites.

Coding in 'vanilla' Javascript, i.e. using pure HTML, CSS, and Javascript, can be a really nice way to build sites. However, frameworks like React and Angular are also gaining popularity.

In our codealong, I will show you some basic implementation of Javascript on a webpage. 


## THANK YOU and please reach out to me if you have any questions!


(thank you to [Britney Jo Ludkowski](https://git.generalassemb.ly/britneyjolud) for some parts of this repo)

