# RFP - Featured Location
## Statement Of Purpose
We would  like to build an app wherein we'll develop a city guide for Maryville. A city guide is a must-have for us whenever we visit to a new location. It not only offers us with essential city information, but it also saves us time. This will undoubtedly assist users in saving critical time that cannot be replaced, as well as being economically viable.
## Objective
The primary goal of the city guide app designed for Maryville is to provide users with accurate, up-to-date, and relevant information about everything they need to know when visiting Maryville. It is a web-based platform that stores information about Maryville City and assists all users who have just visited our website and registered. They may search for prominent places in the city and also users can add locations and do updates without the assistance of a human guide. The website provides comprehensive information about hotels, hospitals, schools, and gas stations in Maryville. Any anybody with a basic understanding of the internet can utilize this website.
## Client
- Dr. Denise Case
- Assistant Professor,Northwest Missouri State University
- 44691-02 Graduate Directed Project
- Fall 2021
## Team Members and their roles
- Shiva Ram Kothapally - QA Analyst
- Keerthi Muli - Backend Developer
- Jaya kumar Saga - Team Lead
- Rasagna Reddy Banda - UI Developer
## Functional Requirements
### Authentication page:
1.	Provide Username, password
2.	Provide ***"Forgot Password"*** hyperlink
3.	Give a ***“Submit”*** button which gives access to the user to enter the next page if only the given credentials are valid
4.	Throw an error when provided credentials are not valid
5.	Provide a ***“Signup”*** button if it is a new user, this helps a new user to enter his information in a signup form

### Featured spot of the day:
1.	User enters to this page after successful login
2.	Give a title named ***“Maryville City”***
3.	Provide a heading with featured spot of the day ex: “Colden pond”
4.	Provide image of the shown spot
5.	Provide a brief information of the spot
6.	Give a hyperlink named ***“City Guide”***
7.	When clicked on the hyperlink redirect to the next page

### More locations:
1.	Provide a list of locations of the city like 
    -   Hospitals
    -	Restaurants
    -	Gas stations
    -	Hotels
2.	Provide a ***"Button"*** where user can add a location if they wants to, this functionality is done by using CRUD operations in the backend

## Entities 
Below are the expected entites
- Users
    - Username
    - Password
    - CreatedOn
    - isDeleted
 - Locations
    - LocationId
    - Name
    - OpenHours
    - Address
    - City
    - State
    - Zip
    - CreatedBy
    - CreatedOn
    - LastShowed
 - LocationPhone
    - LocationId
    - Phone

## ER Diagram
 ![ER](https://github.com/KeerthiMuli/featured-locations/blob/main/images/LocationsER.png)

## Bidder Qualifications
## Performance Metrics
## Schedule Duration
Module 1: Acting as clients and building an architecture of the App<br>
Module 2: Talk through the initial planning and design<br>
## Development Details
