# The model View Controller (MVC) Pattern

Get /about HTTP/1.1
Host: 127.0.0.1

## Routes
Matchers for teh URL that is requested

Get for "/about"

I see you requested "/about", we'll give that to the AboutController to handle

## Models
Database wrapper

User
* query for records
* wrap individual records

## Views
Your response body content
* HTML
* CSV
* PDF
* XML

This is what gets sent back to the browser and displayed

## Controllers
Decide how to process a request and defind a repsonse