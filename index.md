## Table of Contents

* [Overview](#overview)
* [Useful Links](#useful-links)
* [User Guide](#user-guide)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)

## Overview

![Landing Page Image](assets/images/prototypes/landing-mockup0.png "Landing Page")

[Books for Bows](https://github.com/books-for-bows) is a marketplace for University of Hawai’i students to buy textbooks from and sell textbooks directly to fellow students. 

We decided to create this project because shopping for textbooks can be confusing, difficult, and frustrating:
* The campus bookstore is expensive and wasteful; you don't NEED a brand new book if you are going to use it for one semester. 
* It's hard to filter for UH textbooks on Craigslist, and you have to sort through all the textbooks listed.
* Sometimes it can be hard to tell if you have the right book and you may accidentally buy the international version. 
* Even if you find a cheaper book online, shipping is a real hassle. The cost to ship can bring the overall price of the textbook to the original price anyway, not to mention that it could take a month of the book to actually arrive on island. 

Components of the web application:

* There are four primary collections (Users, Books, Classes, Listings)
* Three main pages (Marketplace, Profile, Search) that uses the prior data collections and allows users to manipulate and filter through those collections.
* Code that fills the database with default data for Users, Books, and Classes. To demonstrate usage of the marketplace.
* A page to filter through different Classes and Books to query the collections to obtain a specific book.

## Useful Links

* [Books For Bows GitHub Organization](https://github.com/books-for-bows)
* [Books For Bows Deployed on Galaxy](http://books-for-bows.meteorapp.com/#/)
* [Milestone 1](https://github.com/books-for-bows/books-for-bows/projects/2)
* [Milestone 2](https://github.com/books-for-bows/books-for-bows/projects/3)
* [Milestone 3](https://github.com/books-for-bows/books-for-bows/projects/4)

## User Guide

### Landing page

Welcome to the Books for Bows website! This landing page will greet you upon arrival to our site. 
![Landing Page Image](assets/images/prototypes/landing-mockup0.png "Landing Page")

### Login

If you have already made an account you can log in.
![Login Page](assets/images/prototypes/login-mockup.png "Login Page")

### Register

You can make an account here. Accounts will provide you with access to additional pages and features. 
![Register Page](assets/images/prototypes/register-mockup.png "Register Page")

### Marketplace

Anyone can come to the marketplace to see all the textbooks available for purchase. Each book card acts like a folder which contains the listings for the textbook it represents. As long as there is at least one listing for a textbook, a book card will appear in the marketplace. 

The card displays:
* Image of cover
* Title
* Author
* Price (or price range if there are multiple sellers)
* Course alphas that use the book

![Marketplace Page](assets/images/prototypes/marketplace-mockup.png "Marketplace Page")

### Shelf

When you click on a card from the marketplace, you will be taken to a new page. Here, you are able to view all the available listings of the associated textbook, as well as additional information supplied by the seller such as condition or any pictures.

![Shelf Page](assets/images/prototypes/shelf-mockup.png "Shelf Page")

### Create Listing

Logged in users can create listings that will be displayed on the marketplace.

![Create Listing Page](assets/images/prototypes/createlisting-mockup.png "Create Listing Page")

## Community Feedback 
We appreciate the feedback and will take it into consideration for future Books for Bows updates. 

## Developer Guide 

It is built with the technology stack that consists of:

* [Meteor](https://www.meteor.com/) for Javascript-based implementation of client and server code.
* [React](https://reactjs.org/) for component-based UI implementation and routing.
* [Semantic UI React](https://react.semantic-ui.com/) CSS Framework for UI design.
* [Uniforms](https://uniforms.tools/) for React and Semantic UI-based form design and display.


## Development History 
### Milestone 1 - Prototypes and Mockups 
(Nov 9 2019 – Nov 21 2019) 
* [Milestone 1](https://github.com/books-for-bows/books-for-bows/projects/2)
![Bookstore Page](assets/images/prototypes/Bookstore.png "Bookstore Page"){:height="25%" width="25%"}


### Milestone 2
(Nov 22 2019 – Dec 4 2019) 
* [Milestone 2](https://github.com/books-for-bows/books-for-bows/projects/3)
![Marketplace Page](assets/images/mockups/marketplace-mockup.png "Marketplace Page"){:height="25%" width="25%"}

### Milestone 3 
(Dec 5 2019 – Dec 17 2019) 
* [Milestone 3](https://github.com/books-for-bows/books-for-bows/projects/4)
![Current Marketplace Page](assets/images/prototypes/Bookstore.png "Current Page"){:height="25%" width="25%"}

### Milestone 4 – Moving Forward 
In the future we hope to implement improved functionality and features, based on the feedback we received in Milestone 3. 

