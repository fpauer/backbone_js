# Simple TO-DO Page using Backbone 1.3.3

This a simple example of the main features of Backbone.js and how you can create a basic to-do list.

## Some concepts about MVC (or derivatives, MVP / MVVM).

* A way of cleanly separating data, presenting data, and business logic (e.g. “To get the total exports of a country, you must sum its exports with every individual country”). Following definitions differ slightly depending on which interpretation you’re using, but the gist is similar.

	+ Model: Provider of data - could be an API. Could be a javascript object. Could be anything. It’s the “state” of the application, anything from the data in your viz to which buttons are current clicked and whether we’re showing exports or imports.
	+ Controller: Sits between everything and decides how to process the user input, where to gather data from, what to do with it, etc.
	+ View: e.g. templating - how the application actually looks to the user and where the user interacts with the application.

###Brief Background

A common problem with large JS web application developed is that they can become pretty messy really quickly. The lack of structure makes the code hard to maintain. This is where Backbone comes into play. It provides structure to organize the code and increase maintainability. Backbone is not the only framework like this; in fact, there are many JS frameworks that attempt to offer similar benefits, like Ember.js, Angular.js and so on. However, I choose Backbone because it’s one of the most widely used frameworks in its category. It has a vibrant community and it’s also being fully used in production for a considerable number of big companies like: Wal-Mart mobile, Groupon, Khan Academy, Pandora, Wordpress, Foursquare, and so on.

## Pre-requisities - http://backbonejs.org

Backbone has a hard dependency on [Underscore.js](http://underscorejs.org/) (>=1.8.3). 
For RESTful persistence and DOM manipulation with Backbone.View, include [jQuery](https://jquery.com/) ( >= 1.11.0), and json2.js for older Internet Explorer support. 


Backbone.js has hard dependency on underscore.js and a soft dependency on jQuery. It’s made up of the following modules:

- Views
- Events
- Models
- Collections
- Routers
