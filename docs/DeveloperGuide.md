# Developer Guide

## Design & implementation

{Describe the design and implementation of the product. Use UML diagrams and short code snippets where applicable.}

### Sequence Diagrams
1. Database Sequence Diagram
   ![Database](Database.png) 
 
2. Login Sequence Diagram
   
   ![Login](Login.png)
 
3. Admin Main Menu Sequence Diagram
   ![Admin Main Menu](AdminMainMenu.png)

4. Customer Main Menu Sequence Diagram
   ![Customer Main Menu](CustomerMainMenu.png)


## Product scope
### Target user profile

This app is for movie lovers who want to know movie details, make online booking, and are in need of a user-friendly interface.

### Value proposition

The app is a single-user application that can computerize the processes of making online booking and purchase of movie tickets, and listing of movie details and reviews.
The app will help customers to make a movie schedule ahead of time, and enable a fast and intuitive ticket purchasing procedure.
The app will help cinema administrators to update the movie information regularly through an intuitive interface.

## User Stories

|Version| As a ... | I want to ... | So that I can ...|
|--------|----------|---------------|------------------|
|v1.0|new user|follow through with the steps provided|make a booking.|
|v1.0|indecisive user|display summaries of several movies|decide which I want to book for.|
|v1.0|user|I can have a “quit” command|close the application easily.|
|v1.0|user|load the application without any errors|use the other functions.|
|v1.0|user|see the location of the cinemas of the particular movie|go to the nearest cinema.|
|v1.0|user|see the list of the movie and timing|make plans ahead.|
|v1.0|user|book as many seats as it can hold|help my friends book too.|
|v1.0|user|book as many movies available|make plans ahead without being restricted.|
|v2.0|user|cancel any of my bookings|don't waste my money for being unable to attend.|
|v2.0|admin|add new movies|make the application is continuously updated.|
|v2.0|admin|edit new movies|make the application is continuously updated.|
|v2.0|admin|delete new movies|make the application is continuously updated.|
|v2.0|user|filter movies by their rating.|make my decision to either watch them or not.|
|v2.0|user|add a few reviews of the movies|convey my opinions about the movie to other watchers.|
|v2.0|user|view the reviews of the movies|make my decision to either watch them or not.|
|v2.0|user|filter the movies by type, director, actors...|quickly find the movie I like.|

## Non-Functional Requirements

1. Usability Requirements
    1. All text in the system must be consistently written in English.
    2. The layout of the application must be consistent throughout all the pages.
2. Performance Requirements
    1. Database must be regularly updated according to user inputs.
    2. Exceptions must be performed in cases of undesirable incidents.
3. Security Requirements
    1. All passwords must be hashed before it is stored.


## Glossary

| Word | Definition |
|------|------------|
|Admin|Authorized users of the movie application that have the ability to modify the movie details|
|User|Regular users of the movie application that have the ability to view, review, and buy tickets to available movies|
|Movie|Details on a movie, including name, dates, casts, etc.|
|Cineplex|Movie theatre where users may create bookings|
|Cinema|Individual room of the cineplex where users sit and watch the movies at|
|Seat|Individual space inside the cinema where each user sits at|
|Review|Comments and ratings of each movie|
|Showtimes|Individual entity of a particular movie, showing at a particular time|
|Booking|Individual appointment where one seat of one showtime is assigned to one user|
|Database|Offline text files that store information on cineplex, movie, showtime, and user entities|

## Instructions for manual testing

{Give instructions on how to do a manual product testing e.g., how to load sample data to be used for testing}

