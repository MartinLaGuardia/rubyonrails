# README

Making my first Ruby on rails app has been more fun than I expected: 
As I had no knowledge about the language, nor about the framework, I had to read some articles and watch tutorials on Youtube, but what helped me the most was to follow the official documentation, especially rubygems.org that guided me through this new way of installing dependencies. 
Thanks to the automated generators of the platform I created the "/welcome" with the Hello world and then I went on to create some "articles/new" that I learned to save in sqlite3, and then display them in "articles/3" and "articles/4". 
Today I installed Bootstrap to style the web and I couldn't get it to work, I guess that some point of the configuration is not right. 
At times I felt like I was working with Express and its views rendered with HBS. 
Thanks to Ryan Dahl for Node.Js, to David Heinemeier for rails and to you for be there.
Regards. 


These are the steps I followed:

* Documentation

* Preparation of the working environment: installations and configurations.

* Creation of model, controllers, routes and views.

* Testing on localhost :3000


## Paths:

| get | bienvenida | home#index |
| get| articles/new | articles#new| 
| post| articles | articles#create| 
| get| articles/:id | articles#show| 

## Data base:
sqlite3
