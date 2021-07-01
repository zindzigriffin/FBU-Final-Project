App Design Project (Zindzi Griffin) - README Template
===

# Restuarant Finder

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Restuarant Finder simplifies the task of finding eateries so that you can spend more time dining and less time deciding. 

Finding a place to eat can be overwhelming and we want to simplify that process by providing you with restuarants near your location, filtering options, and reduce the clutter on the screen by showing you only a few options at a time.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Food & Drink
- **Mobile:** Mobile App
- **Story:** Allows users to choose their favorite types of food/cuisines and use that information to display restuarants that fall into the type of food and cuisine, and select a restuarant of their choice and display the location the user selected using Google Maps API. 
- **Market:** Anyone that struggles with finding places to eat can use this app. Ability to save restuarants that they went to using this app. 
- **Habit:** People will naturally come back whenever they want to find a restuarant to eat at.
- **Scope:** This app can maybe expand to where people can leave reviews for the restuarant they visited and maybe third party app integration such as uber eats integration where people can order food.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can create an account.
* User can login.
* App has landscape and portrait view capibilities.
* User can save restuarants they visted by clicking the save button.
* App uses google maps API to find the location of the restuarant selected and provide directions to the restuarant.
* User can pull to refresh the page with new restuarants 
* User can pick their favorite types of food/cuisine and the app can use that information to display restuarants based on their choice.
* User can save their preferences (restuarants they visted and restuarants they want to try) in a separate tab within the app.
* User can write reviews on the restuarants they visited and user can see how many characters they have typed when they write their review
* User can see if the restuarant has outdoor dining and/or if they deliver

**Optional Nice-to-have Stories**

* User can see deals & offers a restuarant of their choice is having.
* User can see what restuarants are POC owned
* User can view the restuarants health inspection report
* User can see the most popular restuarants
* User can view the menu for that restuarant

### 2. Screen Archetypes

* Login Screen
   * Create an account 
   * Login in with their username and password
* Saved Prefences Tab
   * Contains a list of the restuarants the user has saved upon clicking the save button
   * Contains a list of restuarants the user wants to try
* Home Screen/ Stream Screen
    * Displays a scrollable list of restuarants and their locations based on the type of food the user is interested in.
    * User can click on a restuarant they are interested in and view details about the restuarant such as whether they have indoor/outdoor dining,their menu, a section to write reviews, view other people's reviews, restuarant hours, phone number etc
* Search Screen
    * User can search for restuarants based on the provided location 
* Price Range Tab
    * Shows the restuarants from lowest to highest price

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Home Feed
* Saved Prefrences Tab
* Search Tab 
* Price Range Tab

*Bottom Navigation

**Flow Navigation** (Screen to Screen)

* Login Screen
   * Home Screen
* Search Screen
   * Saved Preferences
   * Prince Range 
   * Home Screen
* Home Screen/ Stream Screen
    * None 
* Prince Range 
    * Home Screen
    * Saved Preferences 
* Saved Preferences
    * Home Screen
    * Price Range
    * Search Screen

## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
