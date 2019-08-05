# Steps to Create Meow App! - Intro to Creating a Rails app
**A super simple app to view all the cats!**

Intended for developers brand new to Rails.

## Objectives
1. Explain what Rails is.
1. Illustrate MVC architecture.
1. Identify the steps to starting a new Rails project.
1. Summarize steps to build cats index page. Follow MVC pattern.

    - Dream drive, what's the ultimate goal? (Vertical slice)
    - Start server, go to localhost:3000/cats (Follow the errors.)
    - Open/Draw route
    - Create controller to route request
    - Create model & migration
    - Create view

## Deliverables
1. Slack to me: In your own words, describe the flow a network request takes through Rails MVC. 


## Creating a new Rails Project

### Step One: Create your Rails app
* In your terminal, type `rails new meow-app -T -d=postgresql --skip-turbolinks --skip-spring`
* Setup the database `rails db:create`
* Add any desired gems (PRY!!!), then run `bundle`


### Step Two: Follow the Errors
* We're "dream-driving" the development of this app so we'll start with what we want the users to see. When a user visits `localhost:3000/cats` they should see a list of all the cats, the cat's name, and the cat's breed.
* Currently when we visit `localhost:3000/cats`, we get errors. Follow these errors to build your feature.
