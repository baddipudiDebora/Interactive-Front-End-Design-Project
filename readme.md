# Enjour Your Holiday
Enjoy Your Holiday - Is is One Stop solution for your memoriable Vacation. Right from Weather Guide / List of Accomodation / Attractions / Resturaents / Forex Converstions / Holiday planner with your country holiday list, we take care of all of it.


## UX - Requirements
## 1. Strategy Plane
  	* Get potential travellers and tourism industry on a single potal to facilitate efficient and effective Travel Planning and Smooth Execution.

  	* Boost the tourism/hospitality industry with travellers from around the world by showcasing the potential places within budget of everyone to spend ones holiday.
	

#### User Needs Objectives :-
 	* Providing a browser-based front end application where potential travelers can get info on  Weather, search for list of Accomodation / Attractions / Resturaents / Forex Converstions /  holiday list of local country and some potential destinations withinthe budget reach of many.
	
#### Business Objectives :-
	1. Automating a currently manual process of visitng a travel agent office, and allowing travel inquiries and applications from the Internet.
	2. Decreasing the time to process the travel enquire from approximately 30 minutes to 5 minutes. 
	 This will help TravelIndia Company to dramatically increase the volumes of travel booking processed to meet its business plan.
	3. Providing online travel status. This will allow TravelIndia customercare to rapidly and accurately respond to customer inquiries both prior to and during the travel of the customer.
	4. Need to convert most of the enquiries to a travel candidate, using a contatc us page and live  chat.
	5. Some quotes to make user select our travel packages over our competitors we need to have some  catchy and compelling headlines.  
	6. The steps between user selecting a package and making payment should be minimal. 
	7. An online survey form to collect questionnaire from users on What makes a good holiday travel   booking experience? 

## 2. Scope Plane
 	The TravelIndia application is designed to provide the following features for current production release:
	1. An administration system for the employees of TravelIndia corporation to add new locations and packages
	2. A registration system for potential travellers / Tour Guide / Travel Agent
	3. A system for Travel agents and Guides to view packages and dates allocated to them
	4. Timely and accurate weather information to travelers, guide and the TravelIndia corporation
	5. To show we are an expert in conducting tours around in and around India the website should host some Video tutorials on travel precautions, checklist, testimonials and frequently asked questions, and sending invite to signedup users on upcomming webinars.

	Features off the table for current release -
	1. Adding services / Travel Pacakages to shopping cart and Online payment
	2. Admin login features such as, to add new tour Packages and applying sesonal discounts on particular packages
	3. Approve / Reject  / Block paticular guide based on cutomer complaints
	4. Sign-In / Sign-Up
	5. Tour Guide / Travel Agent Login to view their allocated tours 
	
	The current release would be in 3 months duration , consisting of 3 sprints.
	
		Sprint 1 - Landing Page , Sign Up/ Sign-In page (only page design not email validation for sign -in) / Trending Tours page 
		
		Sprint 2 - Connect Google Maps / Places and weather guide API 
		
		Sprint 3 - Frequently asked questions, Contact Us page (with emailJS API), Travel Essentials page with Forex calculation API, Search dynamically for weather of a place using OpenWeather MapAPI , Search Holiday list of a particular country dynamically based on Country code and year. 
	
## 3. Structure Plane
	The website should focus on visual appeal and be intuitive to target wide group of customer base ranging from teen to seniors, newly weds to couples with families.

	User Friendly navbar and footer across all pages. Multiple windows allow different information to be displayed simultaneously on the user's screen.
	
	Typical features could include:
	1. Displaying 

### Interoperability and fully functional on Mozilla / IE and Chrome
### Compatability tested for responsive Desktop / Laptop / IPad / IPhone6

## 4. Skeleton Plane
#### Interface Design
		Home Page, Weather Update , explore by state name, FAQs , Contact Us.And Footer contains About US, 

#### Navigation Design
		User can navigate from any of these pages  Home Page, 4 pages of the Trending tours, Adventure Tours, FAQs , Contact Us, Travel Essentials SignIn-SignUp. (All pages interlinked using navbar)
		
#### Information Design
		Icons for HomePage, FAQs page.

		Why choose us also has 4 icons for 4 reasons.

		To maintian minimum content and large images, incorporate a heroimage to motivate a person to register to travel.And 4 reasons quotes in Home page to compel user to select us over our competitors
	

		“Travel isn’t always pretty. It isn’t always comfortable. Sometimes it hurts, it even breaks your heart.
		But that’s okay. We’ll take care the journey, be with your throughout and make sure it leaves good marks on your memory, on your consciousness, on your heart, and on your body. You take something with you. Hopefully, you leave something good behind.”

## 5. Surface Plane


### List of User Stories:
Ideal new user flow would be represented by the following use case (Actor represent an ideal future user)

	#### User Story 1 -  Trending Tours page
		Actor: Enters the Application url
		System: Loads the landing page with Hero Image with motivating quotue 
		Actor: Clicks on Trending tours menu in the navbar
		System: displays the page with the 4 trending tours on our website
		System: displays picture of the city, short description, video of places to visit, weather of the city on that day, top attractions / places to visit, restaurants, Accomodations (latest data from API dynamically) 

	#### User Story 2 - Contact Up Page
		Actor: click ContactUS in the nav bar
		Sytem: Directs user to ContactUS page
		Actor: Fills the ContactUs Page with his/ her detais and needed information and clicks on submit
		System: Sends the mail to the Travel Agent with details filled in the form
	
	#### User Story 3 - FAQs page
		Actor: clicks on FAQs icon in navbar
		System: System displays Frequently asked Questions of travellers
	
	#### User Story 4 - Adventure Tours page
		Actor: clicks on Adventure Tours in navbar
		System: System displays popular adventures in tabular format

	#### User Story 5 - Travel Essentials (Forex calculator)
		Actor: clikcs on Travel Essentials Page
		System: displayes three sections - Forex calculator /  Holiday list of a company / Weather details based city 
		Actor: enters a currency code and amount needed to convert 
		System: displays the total in INR after conversion for that day

	#### User Story 6 - Travel Essentials (Holiday Calender)
		Actor: clikcs on Travel Essentials Page
		System: displayes three sections - Forex calculator /  Holiday list of a company / Weather details based city 
		Actor: enters a country code and year 
		System: displays the Holidays of that year for that country

	#### User Story 7 - Travel Essentials (Weather Guide)
		Actor: clikcs on Travel Essentials Page
		System: displayes three sections - Forex calculator /  Holiday list of a company / Weather details based city 
		Actor: enters a city name 
		System: displays the weather of that city for that day


### Wire Frame and UX design

#### each of 4 holiday destination page wireframe

![location page wireframe](https://user-images.githubusercontent.com/64851336/83449083-fedc9880-a420-11ea-8842-4337efb499eb.JPG)


##### please refer link below


## Features
### Existing Features


### Features Left to Implement
1.	

##Technologies Used
* The project uses HTML to add content to the website.
* The project used CSS to style the content.
* The project used BootStrap 4  to have reusable CSS styling.
* Icons / Images were taken from Font-Awesome website
* Styling was taken from Google fonts 
* Used JQuery Accordian

Testing
XML Validator  - Verified

CSS Validator – Verified 


### Manual Testing
Testing has been performed to verify and validate the software as per the requirements.
Manual Testing performed to test the below user stories
1.	


### Automated unit testing using open source tool selenium to test the below features
1.	Testing




##### please refer Github link below.

[GitHub](https://github.com/baddipudiDebora/Mini-Project/blob/master/Automation%20-%20Educate%20All.pdf)
 
## How your project looks and works on different browsers and screen sizes
    The website is designed with bootstrap hence mobile friendly by default.
  

###    It has been tested for iphone6/7/8 , also in iPad. 
  ##### please refer Github link below.
   [GitHub](https://github.com/baddipudiDebora/Mini-Project/blob/master/Screenshots%20of%20mobile%20and%20tab%20testing.pdf)


## Any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.



## Deployment
Code was written in replit and pushed on regular basis to github account.

#### the published github page is below

[GitHub](https://baddipudidebora.github.io/Mini-Project/)



## Credits
### Content
    The text for call out section was copied from the 



###  Media
    The photos used in this site were obtained from ...
   
	 

## Acknowledgements
    I received inspiration for this project  
https://www.travelpulse.com/news/travel-agents/4-content-ideas-for-your-travel-agent-website.html

https://www.scenicsuitcase.com/types-of-vacations/

https://www.tutorialrepublic.com/snippets/gallery.php?tag=carousel

https://www.holidify.com/collections/historical-places-in-india

http://www.thrillophilia.com/blog/bucket-list-ideas-for-adventure-travellers-in-india/

https://mdbootstrap.com/
