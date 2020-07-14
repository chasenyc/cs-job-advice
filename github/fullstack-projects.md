# Portfolio Projects
[Back to main guide](../README.md)

## Table of Contents
- [Portfolio Projects](#portfolio-projects)
  - [Table of Contents](#table-of-contents)
  - [Full Stack Projects](#full-stack-projects)
    - [Criteria for a good project](#criteria-for-a-good-project)
    - [Project Ideas](#project-ideas)
      - [A URL Shortener](#a-url-shortener)
      - [Instagram Clone](#instagram-clone)
      - [Other Clones](#other-clones)
  - [Smaller Projects](#smaller-projects)
    - [A simple testing framework](#a-simple-testing-framework)
    - [Other Ideas](#other-ideas)
  - [Resources](#resources)

## Full Stack Projects

Full stack projects are a great way to show you know your stuff. But its important to define what makes a good full stack project. The most basic definition would be that there is both a backend and a front end to your web application. A few things worth making sure are a part of your project are the following:

### Criteria for a good project
The following is a general framework to help evaluate what might make a good project to invest your time in. That being said, this criteria is in no way required and there are many impressive projects that do not hit half of these bullet points:

* **Front-end user facing portion of the site**
  
  The site should be styled with css, copy another sites design if you need to. It is important not to spend too much time trying to figure out how to make your site looks nice. You are not a designer and this should not be your main concen. If you are interested in front-end work spend the time making the user experience great but you can still copy a design to keep you focused on what will really stand out to potential employers
* **Backend serving responses to the front end**
  
  Depending on what kind of front-end you are using (such an an SPA) this quite possibly will be an API returning JSON. You should explore creating a RESTful API as a good standard for a small project's backend. Using a RESTful API will demonstrate your understanding of best-practices.
* **Data store**
  
  Use some sort of data store, ideally one of the more well known database choices such as MySQL or MongoDB. It’s definitely better to pick something that both reads and writes to the data store. For example having a text file filled with chess moves may not be quite as impressive as a MySQL database that user submitted input will be stored and read from. 
* **Authentication**
  
  Some sort of implementation of basic authentication implemented, this is an easy win in many cases as modern web frameworks will provide this right out of the box without too much heavy lifting.
* **Use of 3rd Party API**
  
  Some sort of interaction with a third party API such as google maps or even better if you can find a completely free one that will integrate nicely with your chosen project. You can find some listings of available APIs here:
    * [Programmable Web](https://www.programmableweb.com/apis/directory)
    * [Github -- public-apis/public-apis](https://github.com/public-apis/public-apis)
    * [USA.gov -- APIs and Datafeeds](https://www.usa.gov/developer)
* **Live site**
  
  Having this site live on the internet is a huge positive. As an employer being able to go to a website and see the results of your work help. Even if the code is what really matters, having something people can see has a real intangible benefit. A service like [Heroku](htps://heroku.com) is great as they provide a free tier where you can deploy a live application without paying a penny.

* **Public Repository**
  
  More important than a live site is a place where a potential employer can review your code. Seeing the final product is important but seeing the work you did to acheive the final product is a must. Make sure you have an [excellent readme](readme-guide.md) for the repository.

### Project Ideas
It s a good idea to try and find a project that hits most of the bullet points above. In most cases if there is something you are passionate about and can figure out a way to tie it into a full stack project that’s always best as it shows some of you personality and it will be something you are passionate about. If for example you are an avid chess player, building a site that analyzes opening moves and allows users to store their games would be a great idea. More often then not if you do not have some sort of original idea cloning some site's basic functionality is a great option. The following are a few ideas for those who are a little less inspired or need some guidance.

#### A URL Shortener
This project has an incredibly simple MVP state. A one table database that stores two values, the full url and a second column of the shortened url to lookup when redirecting. You need one route where a user can submit a URL and be returned a shortened url (either custom or auto-generated) and then the redirecting of any shortened routes found in your database table.

The great thing about this project are there are plenty of additional features that give room to show off your understanding of more complex topics. You can easily add authenticated users who are able to edit their saved shortened links and see a list of all of them in one place. Another feature to add is some basic analytics, you can start with just incrementing a count every time you redirect a request and start displaying that when an authenticated user views the links they have created.

You can build on tracking of locations by IP addresses. This would help integrate a third party API to get locations from IP addresses and demonstrate your ability to communicate with other services and handle errors safely so redirects still occur even if you are unable to get a location for a given IP Address.

#### Instagram Clone
An instagram clone is a great small project, the most basic iteration knocks off most of the core criteria for a good project. Building simple authentication for users, with a database to store their profile and posts. It will utilize a third party api like Amazon S3 for storing photos uploaded. And will continue to allow you to iterate with adding things like following other users, likes, comments. A good additional challenge would be to incorporate the concept of nested comments.

#### Other Clones
There are a lot of great sites out there that have potential for a clone. The benefit of building some sort of clone of a popular site, similar to what is mentioned above regarding copying UI design is that you do not have to be overwhelmed with figuring out a "new" idea along with all the design decisions. Take a look at some of the following sites and think critically about how you could implement some of the features without having to implement everything they have. For example with AirBnB, your first iteration might not include reviews, or really even the ability to book. Your first iteration can just be a website that lets users list homes for rent. Keeping the development of the site as an iterative process will allow you to reach tangible goals and not get overwhelmed by the process.

* [AirBnb](https://airbnb.com)
* [Facebook](https://facebook.com)
* [NYTimes - Cooking](https://cooking.nytimes.com)
* [Spotify](https://spotify.com)
* [Stack Overflow](https://stackoverflow.com)
* [Medium](https://medium.com)
* [Slack](https://slack.com)
* [Eventbrite](https://eventbrite.com)
* [Meetup](https://meetup.com)
* [Trello](https://trello.com)

The possibilities are endless but these are some places to look for potential ideas or just to get you brainstorming. 

## Smaller Projects

If a full-stack project is daunting for you right now, that is also okay. This can be daunting for a variety of reasons, from not having enough time to not feeling that you know enough to create a full stack website, or even that you have already built one. Regardless, there are still great additions to a GitHub portfolio that you can do, some of which are on the much simpler side, these will not only round out what potential employers see of you but hopefully also be an opportunity for learning more. The options here are really endless but Below is a few potential options to get your mind going as to what is possible.

### A simple testing framework
This is a great project I found used in a book called [Secrets of a JavaScript Ninja](https://www.manning.com/books/secrets-of-the-javascript-ninja). The basic concept is extremely simple in that you are creating a small package that tests assertions, in the first and most basic step you are just checking equality and outputting success or failures. The benefit of very iterative projects is that you are able to put something up on GitHub that works quickly. You can continue to iterate on it but it is an easy talking point and easy to have something to show almost immediately.

### Other Ideas

This section will continue to be filled in with more detail but for the time being some of these are great opportunities
- Simple game clone (i.e. Asteroids, Flappy Bird, CLI Chess)
- Lightweight ORM
- A web scrapper
- Front end only website hitting APIs

## Resources
* [donnemartin / system-design-primer](https://github.com/donnemartin/system-design-primer) 
* [checkcheckzz / system-design-interview](https://github.com/checkcheckzz/system-design-interview)

---
[Back to main guide](../README.md)