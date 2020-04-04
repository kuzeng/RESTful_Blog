# 7 RESTful ROUTES

name    url         http verb      desc.
==============================================================
INDEX   /dogs          GET      Display a list of all dog
NEW     /dogs/new      GET      Displays form to make a new dog
CREATE  /dogs          POST     Add new dog to DB
SHOW    /dogs/:id      GET      Shows info about one dog
EDIT    /dogs/:id/edit GET      Show edit form for one dog
UPDATE  /dogs/:id      PUT      Update a particular dog
DESTROY /dogs/:id      DELETE   Delete a particular dog

# Introduction
* Define REST and explain WHY it matters
* List all 7 RESTful routes
* show example of RESTful routing in practice

REST - a mapping between HTTP routes and CRUD


BLOG
CREATE
READ    /allBlogs
UPDATE  /updateBlog/:id
DESTROY /destroyBlog/:id

# Blog Index
* Setup the Blog App
* Create the Blog model
* Add INDEX route and template

# Basic Layout
* Add Header and Footer Partials
* Include Semantic UI
* Add Simple Nav

# Putting the C in CRUD
* Add NEW route
* Add NEW template
* Add CREATE route
* Add CREATE template

# SHOWtime
* Add Show route
* Add Show template
* Add links to show page
* Style show template

# Edit/Update
* Add Edit Route
* Add Edit Form
* Add Update Route
* Add Update Form
* Add Method-Override

# DESTROYYYYY
* Add DESTORY Route
* Add Edit and Destroy Links

# Final Updates
* Sanitize blog body
* Style Index
* Update REST Table