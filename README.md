# CS465-Fullstack

#Architecture 

-Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA). 

 

Express is used to set up the web server that will listen to incoming requests and return output from the Node.js platform. It is used with the templating language handlebars to generate and render HTML formats and pages. Angular is the front-end framework used to develop the interface for the website. Angular is ideal for its use of single-page application (SPA) functionality. This crowdsources computational power allowing for a faster response from the site and reducing potential latency. 

 

-Why did the backend use a NoSQL MongoDB database? 

 

MongoDB is used for its NoSQL databases to store information from both the client and administrative side. What makes MongoDB ideal for this application is its speed and flexibility. 

 

#Functionality 

-How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces? 

 

JSON is a format derived from the JavaScript language but is independent of any programming language. JSON is also presented in a string and can only be presented in text. The front end sends JSON formatted data to the backend where JSON stores and receives data to be sent back to the front end. 

 

-Provide instances in the full stack process when you refactored code to improve functionality and efficiencies and name the benefits that come from reusable user interface (UI) components. 

 

In the app.component.html I refactored hard code that displayed the initial application view of the trip listing page, to now support routing. With this being, the router is now in control of all the page transitions, including the initial page displayed. Another instance where I refactored code to improve functionality is by creating a partial folder to store the header and footer, so it did not have to be coded in every page. Reusable UI decreases the overall size of the application, minimizes errors and vulnerabilities, and also makes for a quicker development process. 

 

#Testing 

-Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application. 

 

API methods determine what a user needs to submit in order to access data on the backend of the application. I used the GET method to read from the trips list and each individual trip. The key security feature in this application was injecting authentication middleware into the API routes. This required any updates to the database, PUT and POST methods, to require authentication which protects the API routes from unauthenticated users. 

 

#Reflection 

-How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field? 

 

Before starting this course, I had worked on both front-end and back-end development of applications but had not worked on the combination of these two on a single project. 

This course not only provided me with that opportunity, but also piqued my interest in front end development, steering me more towards frontend engineering jobs. During the development of this application, I have learned how to use Angular to create a scalable web application and handlebars to minimize the overall size of my application. This course has strengthened my knowledge of MEAN and increased my comfortability in developing all parts of a website. 
