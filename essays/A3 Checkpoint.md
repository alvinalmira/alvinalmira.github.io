---
layout: essay
type: essay
title: Assignment 3 Checkpoint
date: 2020-12-03
labels:
  - Assignment 3
  - Checkpoint
---

Checkpoint A: 
Describe your design for your site's shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.<br>
 
  - I’m planning on making my shopping cart a separate page that users can view and edit. I’ll try using sessions to store product quantities and then get the quantities from where the product quantities are stored and write it on the invoice. I’m thinking about adding a function that enables users to delete products that they decide they don’t want anymore. To add to that, I’m thinking about adding an input field for the quantities on the shopping cart so customers can change the quantity they want from the shopping cart.<br><br>
 
 
 
Checkpoint B:
Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their keys) you will use to manage the shopping cart data and how they will be used in $_SESSION.<br>
 
  - Sessions will hold product quantities in it whenever the user clicks add to cart. I’m going to run a for loop so that it will loop through the product index. I will be using JSON as the data format. For example I will create an array like:<br><br>
Session[‘cart’][‘tools’] = array();
 
 
 
Checkpoint C:
How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?<br>

  - The way I will prevent users from accessing the shopping cart page will be to set up a conditional statement that checks if there is a user cookie that exists. If a user cookie does not exist, my site will redirect the user back to the products page; even if the user manually types in the invoice page string, my function will redirect the user to the products page.<br><br>
 
 
 
Checkpoint D:
Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary):<br>

  - The way I will provide personalization in the UI is by getting the user’s cookie—which contains their name— and document.write() the user’s name onto the top of the invoice. I’m going to change the Login button to “Hello user” when a user is logged in.<br><br>
 
 
 
Checkpoint E:
If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?<br>

- I will not be working with a partner for this Assignment.<br><br>
 
Checkpoint F:
How are you approaching Assignment 3 differently than Assignment 2?<br>

  - For Assignment 2, I didn’t do nearly as much research into the code that I was using and ended up getting shortcomings for validation, personalization, and sticky date. I’m going to do more research by referring to sources and reading into what functions I would need, how to use the function, and how other users have used this function and made it work for them. I’m going to dedicate more time to practicing and testing code bit by bit instead of testing chunks of code at a time. So far, I’m testing cookies and will start testing sessions for my products and invoice page; I’m still planning how I will fix the design of my site to accommodate multiple pages and a main products page. I will focus more on the functionality rather than making the site look really nice.
<br><br>
