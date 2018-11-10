# InternKit
The application designed and built by members in Codepath's Android development course, group 47
## 1. User Stories

**Required Must-Have Stories**
* A 'registration or login page' that appears the first time a user enters the app or if they want to log in to a different profile. User can register a new account in the app on this page.
* A 'main screen' that displays available homes/ apts/ rentals to stay at. Can filter by many categories such as location, price, length of stay, etc.
* A 'user page' that displays all the information associated with a user's account such as their username, email, and settings among other things.
* A 'reservations page' that shows all current and past places that the user has stayed at. This will let them keep track of where they have been as well as see upcoming trips and places they will be staying at. This will also include functionality for people to postlistings as a host.

**Optional Nice to Have Stories**
* An 'explore page' that shows a feed of posts from either people you follow or people who have similar upcoming trips or search filter preferences. This will allow students to connect and possibly find others to split the cost of living for the stay. 
* A 'sponsorship page' that will allow people to sponsor students or offer accomodations to students with particular needs. Could be similar to gofundme but for students who have received internship opportunities. This pages reflects the overall idea of the app to help reward and create opportunities for students who have worked hard to attain an internship.

## 2. Screen Archetypes
* Login
  * This is the "registration or login page". 
* Stream
  * "Main page", displays all listings and allows filtered searches
  * "Explore page", allows for social networking and resources to make using the app easier and more enjoyable.
  * "Sponsorship page", allows for sponsorship and financial assistance for students.
* Detail
  * When a listing is clicked, the details, inclduing location, price, availability, and host among other things, will be a detail screen that can be found through clicking on listings
  * When a user views the profile of another user, this is also a detail page
* Creation
  * When a user creates a profile
  * When a user creates new listing 
  * When a user creates a post for the explore page
* Profile
  * Profile pages
* Settings
  * Settiings will be accessible from the profile page
  
## 3. Navigation

**Tab Navigation**
* First tab will lead to the main screen that dispalys listings
* Second tab will lead to the explore page
* Third tab will lead to the sponsorship page
* Fourth tab will lead to user profile page

**Flow Navigation**
* Main Screen 
  * Click listing -> detail page of that listing
  * Click profile -> detail page of that user's profile
  * Click 'post' on profile or listing -> creation page for user to write comment, post, or review about a host or listing
* Explore Page
  * Contains same as Main Screen essentially, able to go to listings, profiles, or create post
* Sponsorship Page
  * Click student profile -> allow user to donate or offer housing or financial aid
  * Same three navigation flows as Main Screen
* Profile Page
  * Click 'edit' -> creation page to create information about user
  * Click 'settings -> settings page
   
