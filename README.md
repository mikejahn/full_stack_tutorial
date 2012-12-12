full_stack_tutorial
===================

this tutorial will show you how to get raw JSON data into a database and then use this data to  create:
* API
* Web Interface
* Mobile Web Interface
* iPhone App


1.  Head on over to https://data.cityofchicago.org/
 *  https://data.cityofchicago.org/ is a nifty website that lists all the open data the city of Chicago provides for any developer to use to build applications.
 *  Head on over to https://data.cityofchicago.org/api/views/cbyb-69xx/rows.json?accessType=DOWNLOAD (This is a list of all the bike racks in chicago in JSON format.)


2.  Now we are going to write a ruby script to parse this data and import it into a mySQL database
