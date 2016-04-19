# Rails as an API Study

Use your favorite search engine and the provided readings to research and answer
the following questions (no prior knowledge is expected).

In your answers, be sure to cite any relevant sources you consulted in your
search. We ask you to write answers in your own words in order to see how you
process what you've read. Please do not answer with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

Please note:

-   Many of the readings will mention the "view" layer. We won't be covering the
    view layer in this program.
-   We'll use our [rails-api-template](/ga-wdi-boston/rails-api-template)
    repository as the basis for our rails applications.
    This template excludes the "view" layer.

## Required Readings

-   [Starting Ruby on Rails: What I Wish I Knew | BetterExplained](http://betterexplained.com/articles/starting-ruby-on-rails-what-i-wish-i-knew/)
-   [Intermediate Rails: Understanding Models, Views and Controllers | BetterExplained](http://betterexplained.com/articles/intermediate-rails-understanding-models-views-and-controllers/)
-   [Getting Started with Rails — Ruby on Rails Guides](http://guides.rubyonrails.org/getting_started.html)
-   [The Rails Command Line — Ruby on Rails Guides](http://guides.rubyonrails.org/command_line.html)
-   [Rails Routing from the Outside In — Ruby on Rails Guides](http://guides.rubyonrails.org/routing.html)
-   [Action Controller Overview — Ruby on Rails Guides](http://guides.rubyonrails.org/action_controller_overview.html)

## Define Model Responsiblities

In your own words, define what the responsibilities of the model layer are in
Rails.

```md
The Model layer does all the heavy lifting and communicates with the database.
```

## Define Controller Responsiblities

In your own words, define what the responsibilities of the controller layer are
in Rails.

```md
The controller layer dictates what the Model layer should do.
```

## Define Router Responsiblities

In your own words, define what the router does in Rails.

```md
The router determines how the Model will communicate with the web server
```

## The Request-Response Cycle in Rails

Starting with a client making a GET request to a particular URL, describe how
the parts of Rails interact to produce and send a response.

```md
Web browser makes a request to the Web Server which then identifies routes and
sends them to a dispatcher. This dispatcher interacts with the controller which
tells the model(s) how to interact with the database (i.e. GET data). This data
returned to the Controller, passed through the web server, and received by the
browser.
```
