# Full Stack Projects
Full stack projects are a great way to show you know your stuff. But its important to define what makes a good full stack project. The most basic definition would be that there is both a backend and a front end to your web application. A few things worth making sure are a part of your project are the following:

## Criteria for a good project
- **Front-end user facing portion of the site**
  
  This should be styled with css, copy another sites design if you need to. It is important not to spend too much time trying to figure out how to make your site looks nice. You are not a designer and this should not be your main concen
- **Backend serving responses to the front end**
  
  Depending on what kind of front-end you are using this quite possibly will be an API returning JSON. You should explore creating a RESTful API as a good standard for a small project's backend. Using a RESTful API will demonstrate your understanding of best-practices.
- **Data store**
  
  Some sort of database being used, while any data store is a plus. It’s definitely better to pick something that both reads and writes to the data store. For example having a text file filled with chess moves may not be quite as impressive as a MySQL database that user submitted input will be stored and read from. 
- **Authentication**
  
  Some sort of implementation of basic authentication implemented, this is an easy win in many cases as modern web frameworks will provide this right out of the box
- **Use of 3rd Party API**
  
  Some sort of interaction with a third party API such as google maps or even better if you can find a completely free one that will integrate nicely with your chosen project
- **Live site**
  
  Having this site live on the internet is a huge positive. As an employer being able to go to a website and see the results of your work help. Even if the code is what really matters, having something people can see has a real intangible benefit. A service like [Heroku](htps://heroku.com) is great as they provide a free tier where you can deploy a live application without paying a penny.

### Project Ideas
It s a good idea to try and find a project that hits most of the bullet points above. In most cases if there is something you are passionate about and can figure out a way to tie it into a full stack project that’s always best as it shows some of you personality and it will be something you are passionate about. If for example you are an avid chess player, building a site that analyzes opening moves and allows users to store their games would be a great idea. More often then not if you do not have some sort of original idea cloning some site's basic functionality is a great option. The following are a few ideas for those who are a little less inspired or need some guidance.

#### A URL Shortener
This project has an incredibly simple MVP state. A one table database that stores two values, the full url and a second column of the shortened url to lookup when redirecting. You need one route where a user can submit a URL and be returned a shortened url (either custom or auto-generated) and then the redirecting of any shortened routes found in your database table.

The great thing about this project are there are plenty of additional features that give room to show off your understanding of more complex topics. You can easily add authenticated users who are able to edit their saved shortened links and see a list of all of them in one place. Another feature to add is some basic analytics, you can start with just incrementing a count every time you redirect a request and start displaying that when an authenticated user views the links they have created.

You can build on tracking of locations by IP addresses. This would help integrate a third party API to get locations from IP addresses and demonstrate your ability to communicate with other services and handle errors safely so redirects still occur even if you are unable to get a location for a given IP Address.

#### Instagram Clone
An instagram clone is a great small project, the most basic iteration knocks off most of the core criteria for a good project. Building simple authentication for users, with a database to store their profile and posts. It will utilize a third party api like Amazon S3 for storing photos uploaded. And will continue to allow you to iterate with adding things like following other users, likes, comments. A good additional challenge would be to incorporate the concept of nested comments.