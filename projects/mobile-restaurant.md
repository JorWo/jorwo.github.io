---
layout: project
type: project
image: img/mobileRestaurant/logo.jpg
title: "Mobile Restaurant"
date: 2021
published: true
labels:
  - Javascript
  - EJS
  - Node.js
  - Express
  - MongoDB
summary: "A web app designed to replace waiters at a restaurant."
---
<div class="d-flex w-25 my-4">
  <img class="img-fluid shadow rounded" src="../img/mobileRestaurant/view1.png">
  <img class="img-fluid shadow rounded" src="../img/mobileRestaurant/view2.png">
  <img class="img-fluid shadow rounded" src="../img/mobileRestaurant/view3.png">
  <img class="img-fluid shadow rounded" src="../img/mobileRestaurant/view4.png">
</div>

This is a web app designed for mobile devices to completely replace waiters or be a useful tool for waiters to assist them when taking orders.

Imagine walking into a waiter-less restaurant completely operated by robots. You take seat and scan the QR code at the table to immediately being ordering. Food arrives at your table by robot or a conveyer belt. You can continue ordering more food at the palm of your hands with the app. Once you are finished eating, you pay for the food through the app and you leave the restaurant. This is the vision I have in mind with this app.

This app is a personal project I completely built. It is designed on the front-end with HTMLS, CSS, pure Javascript, and EJS, which is a simple templating framework. On the backend, it uses Node.js, Express, and MongoDB to store all the customer's orders into a database. The orders stored on the database is then displayed in a kitchen view showing the order at which table, the time elapsed since order, and the ability to close the ticket.

In the future, I plan to upgrade this project on the front-end using React.js and Boostrap. I also plan to use the data stored in the database to run a recommendation algorithm to suggest other foods they may enjoy for returning customers.

<hr>

Source: <a href="https://github.com/JorWo/mobileRestaurant"><i class="large github icon"></i>jorwo/mobileRestaurant</a><br>
Webpage: <a href="https://jorwo.github.io/mobileRestaurant/website/">jorwo.github.io/mobileRestaurant</a>
