---
layout: essay
type: essay
title: Checkpoint Assignment 3 Essay
date: 2020-05-09
labels:
  - Assignment 3
  - Progress
  - Checkpoint Essay
---
Checkpoint A:

Describe your design for your site's shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.

The design for my site’s shopping cart will be implemented on a separate cart.html page that the user will be able to interact with. There will be a “Cart” button on the navigation bar that the user can press once they’re ready to check out. When they click the button it will take them to the separate cart page that will list the items that they’ve selected along with other information such as quantity, prices, and total price. In this page, they will also be able to add or take off items in their cart. When they press the "Purchase" button on this page, it will lead them to the login/registration page (if they are not signed in yet), then to the invoice page. I haven’t completely figured out the technical parts of my website yet but I hope to use sessions to carry the product quantity from/to my shopping cart instead of constantly using query strings.



Checkpoint B:

Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their keys) you will use to manage the shopping cart data and how they will be used in $_SESSION.

Because I need to store multiple products into a data structure somehow, I will store the product quantity in an array $_SESSION[‘cart’] = array(); I will probably include a table format for the shopping cart page.



Checkpoint C:

How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?

I will use sessions or cookies to prevent the customer from checking out without being logged in. A particular security concern that this tackles is hackers trying to get into the system.



Checkpoint D:

Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary):

I will personalize the pages. I will utilize cookies and/or sessions so that the browser will show messages that are personalized for the user, including any relevant personal information about the user. 



Checkpoint E:

If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?

I will not be working with a partner.



Checkpoint F:

How are you approching Assigment 3 differently than Aassignment 2?

There are a lot of changes that I need to make in this assignment compared to assignment 2. I need to first figure out how to use cookies and sessions and then work through everything else, as I feel like I have to utilize it a lot in this assignment. 
