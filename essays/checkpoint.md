---
layout: essay
type: essay
title: Checkpoint Assignment #3
# All dates must be YYYY-MM-DD format!
date: 2022-11-18
published: true
labels:
---

<p>Show what each page will look like. The pages do not have to be “functional” but the design should clear.</p> <p><a href = "https://youtu.be/ubj1YPyGINY">Here is my screencast.</a></p>
<p><img src = "https://raw.githubusercontent.com/klai9/klai9.github.io/main/img/checkpoint.png"></p>
<p>Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.</p>
<p>The cart will be a separate page that the items get sent to. There are three “add to cart” buttons, one on each product page, so the products can be added in bulk instead of one-at-a-time. The quantities will be overwritten if more of the same items are added, they’ll be added together. There will be a separate form to adjust the quantities of the items in the cart.</p>
<p>Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.</p>
<p>The cart will be an object and all of the products will be inside that object as arrays. The object will be added to the session. </p>
How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?</p>
<p>The checkout button will send the user to the login page if there isn’t a cookie. If the user is already logged in, it’ll go to the invoice. This means a user cannot checkout unless they have logged in and have a cookie. A security concern would be anyone could hack in, I am not educated in webpage security nor have I been taught so anything is possible. 
<p>Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)</p>
<p>I’ll take the user information saved in the cookie to personalize my store, like a welcome message with their name when they log in, and messages in the invoice and email page.</p>
<p>If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?</p>
<p>I'm working alone.</p>
<p>How are you approaching Assignment 3 differently than Assignment 2?</p>
<p>I have been planning what I’m going to do before I actually try to write the code. This assignment is more about putting things together but there are still things I’m not sure on how to accomplish that I need to google. I’m taking it slower and trying to make sure I’m doing things efficiently and not freaking myself out when I think things are too complicated. </p>

