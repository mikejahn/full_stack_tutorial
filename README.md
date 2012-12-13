full_stack_tutorial
===================

this tutorial will show you how to get raw JSON data into a database and then use this data to  create:
* API
* Web Interface
* Mobile Web Interface
* iPhone App


1.  Head on over to https://data.cityofchicago.org/
 *  https://data.cityofchicago.org/ is a nifty website that lists all the open data the city of Chicago provides for any developer to use to build applications.
 *  Head on over to https://data.cityofchicago.org/api/views/28km-gtjn/rows.json (This is a list of all the fire stations in chicago in JSON format.)

* save this file as fire_stations.json


2.  Now we are going to write a ruby script to parse this data and import it into a mySQL database
 * create a new ruby file
 * <code>
   require 'rubygems'
   require 'json'
   </code>

