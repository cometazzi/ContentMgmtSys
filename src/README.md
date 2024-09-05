## Jared Doderer Individual Project
 =-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

### Problem Statement

In my day job we have an old document system named Alfresco, packaged as a ready-to-deply EC2 instance by Bitnami.  Our
installation is getting very long in the tooth, but Bitnami no longer offers pre-configured images.  At the time that we
implemented our Alfresco system it was the best Document Management System available at a reasonable cost.  We have been
looking around to see what else is available, but as a small business we fall through the cracks of allt he enterprise
use cases.  Most available Document Management Systems are part of a whole suite of Content Management Software that 
contains a large plethora of additional software we do not want, need, nor wish to play a license for.  Smaller Document
Management Systems are klunky and inadequate for our needs.  We appear to be in a niche size and market.

I intend to construct a simple, light and fast document management system that will allow authenticated users to upload 
documents, update documents, and find and retrieve documents easily and efficiently.  There will be two different levels
of access- Regular users who can search and retrieve company documents, and Adminstrators who can upload, update, delete
and/or otherwise manage the documents available.

### Project Technologies and Techniques:

* Security/Authentication
    * AWS Cognito
* Database
    * MySQL 8.x
* ORM Framework
    * Hibernate Version TBD
* Dependency Management
    * Maven
* Web Services consumed using Java
    * TBD
* CSS
    * Bootstrap or Materialize
* Data Validation
    * Bootstrap Validator for front end
    * Explore Hibernate Validator?
* Logging
    * Log4J2
* Hosting
    * AWS
* Tech I'd like to explore as part of this work
    * CI tools in AWS
    * Materialize
    * Google Maps API
    * Hibernate Validator
    * Hibernate Search
* Project Lombok
* Unit Testing
    * JUnit tests to cover all testable logic
* IDE: IntelliJ IDEA

### Design (coming soon)

* [User Stories](DesignDocuments/userStories.md)
* [Screen Design](DesignDocuments/Screens.md)


### [Project Plan](ProjectPlan.md) (coming soon)

### Examples of documentation of progress, reflections, and time spent on this class
Choose a format that works for you, or create your own.

#### [Weekly Refelection](WeeklyReflection.md)
#### [Journal](Journal.md)
#### [TimeLog](TimeLog.md)