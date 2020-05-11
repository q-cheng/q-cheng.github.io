---
layout:     post
title:      CMU-Flea-Market
subtitle:   Team project in course Web Application
date:       2020-05-08
author:     Qian Cheng
header-img: img/post-sample-image.jpg
catalog: false
tags:
    - Web Application
---
[CMU-Flea-Market](https://cmufleamarkets.com/)
===

>### This is a team project cooperate with Jiacheng Sun, Yuyang Fan and Shenglong Zhang. You could log in to the website at [https://cmufleamarkets.com/](https://cmufleamarkets.com/).<br>

## Overview
The primary goal of this project is to construct a second hand item trading web application. 
The entire application consists of several web pages which support user administration login, item posting and item displaying etc. 
Other third party APIs such as Google Cloud API and PayPal API have been added to improve user experience and simplify trading process.
The website is based on MySQL database and django framework, and it's deployed on google cloud engine.

### Log in and register page
Allow user locate their location, choose their preference category of product and other basic information.

### Main Page
Display all product. Allow user sort all product based on price or distance between their current address and the product's address.
We also implement search based on Haystack.
Moreover, allow user add product into liked list.

### Post Page
Allow user upload multiple pictures and basic information about their product.

### Product Page
Show navigation from current user position to product's address, and add button link to seller page and purchase pase.
If current user is the seller, allow user change product information.

### User Page
Allow user change their personal information including welcome word, prefer address and etc. Also show the transaction history if current user visited
his/her own user page.

### Purchase Page
Allow user purchase with sandbox PayPal account.
>Sandbox PayPal account used for purchase: <br>
>Account: sb-hwive1317508@personal.example.com <br>
>Password: odrr0#AI