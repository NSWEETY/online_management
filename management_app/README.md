# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions


* It is a DBMS project which tells that the students enroll online courses
* Rails 5.1.7
* Ruby 2.6.3
* sublime txt
* courses  will have short name ,name, description
* the index page will have a listing of courses that are available

*
    


* commands used

* cd Desktop
* cd online_management
* cd management_app
* Rails -v
* Ruby -v
* bundle install
* Rails s
* rails generate migration create_courses
* rails db:migrate
* rails console
* Course.all ->display table
* Course ->description of table
* it101 = Course.create(short_name: "it101", name: "Database management", description: "An in-depth  look at database management as they related to computer scienceA subject database is a collection of specialized information with a narrow focus. The best part of a subject database is that it can help refine your search results, saving you lots of time. In the corporate world, subject databases, such as Dun & Bradstreet, are used daily by millions of business professionals. ")
*  Course.find(1) -> to select particular record
* working_c = Course.find(4) -> for particular value
* working_c 
* working_c.description 
* working_c.short_name = "IT-104" ->updation
* working_c.save 
* Course.destroy(5) ->delete
* student =  Student.create(name: "sweety", email: "sweety234@gmail.com")
* 








* pages
* /courses/new
* /about
* /students
* /students/new

* DBMS part
* courses table  - id (primary key)  ,short_name ,  name , description
* student table - id (primary key) ,name ,email

* ...
