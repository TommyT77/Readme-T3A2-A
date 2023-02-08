Trending food on social media app 

R1 Website 
	purpose (problem statement)[David] 2/02/2022
functionality/features,
Target audience
tech stack
Problem Identified
Finding food trends and associated restaurants are quite hard to find on social media. Finding the restaurant name, location, what time they are open, do they take bookings, how much does the food cost and what others have said about the restaurant require more research on the User’s part. Furthermore, if for some reason, you can’t get to the restaurant from the post, then how about another restaurant that serves the same food. 

It’s often a multi-step process from finding a food trend to booking the restaurant, and that’s what our app aims to address. 

Purpose 

RoondayView is a Web application that aims to make trending dishes more visible to users’ specific food interests. Users are able to see trending (ranked) dishes as well as the restaurants that serve the specific dish. This saves time for users, as the restaurant profile is readily available. It removes the extra steps and time that users would normally invest to find a specific dish and restaurant.




Functionality & Features (fix)

1. Blog’s of a food dish that is ranked by the number of likes given by users  

2. Booking

Reviews: User’s are able to  leave reviews [non-mvp] once they have visited the restaurant and log their time and date of visit of the restaurant (likes are not constrained).

3. User booking request button

4. Restaurant Profile page: restaurant staff are able to create and edit their profile page. They are also able to respond to reviews.

5. Restaurant booking accept button

Admin 
Target Audience
Local and international food community?
Restaurant Owners and Staff

Tech Stack 
Mern 
MongoDB: a document oriented  NoSQL database that stores data used in websites.
ExpressJS: a node.js framework that defines routes and handle HTTP requests and responses
React.JS: a Javascript library that is used to build reusable front-end components 
Nodejs: a Javascript runtime environment, used in conjunction with Express to build server side 
HTML5: markup language that documents the structure of the elements in a website. 
CSS: a style sheet that customises the elements in  HTML documents.
Netlify: allows for deployment of front end website on to the internet
Railway: allows for deployment of the server side on to a cloud server 
CloudAtlas: allows for deployment of the database on to the cloud
Git: a source control system allowing for management of repositories 
Backend Dependencies
	Node.js
	NPM
	Express
	Config
Jest
Jsonwebtoken
bycrypt(nonMVP)
mongoose(nonMVP)
Nodemon?
Dotenv

Fronted Dependencies
	ReactJS




R4 User stories 

As a user, I want to be able to view a list of trending food dishes, so that I can find a restaurant that serves them
As a user, I want to see the booking availability of the restaurant, so that I can book the restaurant  I like
As a user, I want to see the restaurant opening times, so that I know when to visit
As a user, I want to able to filter cuisines to find a food dish, so that I can  find a restaurant
As user, I want to be able to post reviews to help other users make a decision about a restaurant
As a user, I want to see my reservation, so that I can modify or cancel a booking
As a Reviewer, I want to be able see the reviews, so that I can delete or modify my review
As a user, I want to see the restaurant menu, so that I can see if the meal’s are in my budget
As a user, I want to see the restaurant location/address, so I know where it is located
As a user, I want to see ranking of restaurants in an suburb, so that I can see a if there is an interesting restaurant near me

NON-MVP User Stories
As a Reviewer, I want to see my reviews, so that I can see if other reviewers or users have interacted with my reviews






Admin

As an Admin, I want to see all reviews, so that I can flag or remove reviews and conversations that are not constructive
As an Admin, I want to see Users, Reviewers and Staff, so that I can remove them if they are being offensive
As an Admin, I want to be able to remove restaurants if they are no longer in business 


Staff 

As a staff, I want to see the restaurant opening times, so that I can update opening times 
As a staff, I want to see the restaurant menu so that I can make changes to the menu 
As a staff, I want to see the restaurant menu so that I can update the prices of the menu items
As a staff, I want to see the restaurant reviews so that I can respond reviews
As a staff, I want to see restaurant page, so that I can leave ad-hoc messages, ie. “due to the ongoing drought and flood, menu items that have tomatoes will not be served”.
As a staff, I want to be able see incoming bookings, so that I can accept or decline bookings
