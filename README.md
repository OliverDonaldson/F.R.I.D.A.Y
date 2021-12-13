# F.R.I.D.A.Y
#### Video Demo:  <https://www.youtube.com/watch?v=sDPMtDm68uI>
#### Description: 
Friday is a web application made using HTML, Python, CSS, and Java. Bootstrap was also implemented into the site. Friday is a web application created to help users with savings advice and provide them with the info they need to achieve their goals. F.R.I.D.A.Y is also created in a way to be as user-friendly as possible with easy to access pages and an included voice assistant to help them navigate around the site and provide better user experience. The Acronym F.R.I.D.A.Y stands for Finance, Resources, Information, Data, Assistance and Yield. The website was also designed so that it can be used on any device such as a phone and computer, this is done with a collapsible navbar and page sizing.

The code contains 9 HTML templates, 4 Python code, and 1 JavaScript. I implemented my CSS into the HTML templates for easier access. All my HTML templates were extended off my Base.html which contained majority of the layout, the navbar and alerts settings and the bootstrap code for the design. The alerts were activated whenever a user signed or logged in and for general success or error alerts which where coded in the base.html template. The most important codes where the Python codes. First was the main.py which was where the web application was created and could only be activated from the main.py terminal. __init__.py contained the code for the login management and registered the database using the db. functions. One of the most important codes was the auth.py. Here was where I used the POST and GET functions and render_template. This was created using inspiration from the week 9 finance website, auth.py was where I rendered all the websites HTML templates and flashed all alerts and errors. Views.py was where I mainly focused implementing the JavaScript from index.js, views.py was where the main functions for the savings page were done for example removing the user input from the database when the X button was clicked and flashing the user whether the note was too short. Views.py was also they place where the home symbol was defined (‘/’). Models.py was where the IDs of all the input fields such as the user_id, email, name, etc was defined in the database for example ( id = db.Column(db.Integer, primary_key=True) ).  

From the 9 HTML files there was, about.html, advice.html, assistant.html, base.html, home.html, login.html, savings.html, sign_up.html and welcome.html. About.html was the about page which explains basic information on the website such as explaining what F.R.I.D.A.Y means and what it does. The advice page was where I have put a collection of saving advice ideas from different popular banking and saving websites such as ASB a New Zealand bank. The advice page went with a separate page design that looked more like a social media page which is scrollable and separated the different ideas into coloured boxes. The assistant.html page was a tricky but also fun page to create this was created with inspiration from the week 6 python computer generated voice. For the assistant I had to convert some of the python to HTML and add many commands such as the use of the ‘href’ and ‘response’ functions. The voice of the assistant is the 28th voice in the google voices selection. The speechRec is compatible with many different windows webkits. The assistant is very user friendly and has a built-in profanity filter to block any unwanted user voice input. The assistant also types out the users input and shows the conversation history. The assistant page also has a different design compared to all the other pages, it has a colourful webpage and is confined to a conversation box cantered in the middle. This page was made colourful to put the user at ease and make it more approachable, the colour scheme was also like the home and welcome pages which were designed to attract attention. The homepage (home.html) was where all (‘/’) links went to and was the page which explained how to navigate around the website, the homepage also contained links to the savings, assistant, and advice page.  

The login and signup pages had the most unique design, a more simplistic design. These two pages contained the most amount of CSS code compared to the other HTML pages. The total CSS code in the login page added up to roughly 105 lines of code. Majority of the CSS code was the login/signup box design and the light animation rotating around the user box. The login and signup page were done using <form method=”POST”> which added all the users input to the database. I had to make sure I had defined all the IDs of all the <input> types or else it would not have been added to the database and none of the authentication would have worked. Each ID had to be different and defined in models.py and auth.py for example in the sign-up page which required a password and a confirmed password, the IDs of both passwords had to be different such as Password1 and Password2.  

I had a variety of design ideas for this website. Most of the design was divided into 3 different design styles. Colourful and attractive, simple and classy, plain and dark. The colourful and attractive pages where the welcome, home, about, and assistant pages. The idea for this design was to attract attention and give a more approachable feel to it, with the use of warm colours this helped with this specific design. The login and signup pages have a simple and classy look, this was to signify a more important and serious feel to the pages. The advice and savings page were created with plain and cooler colours. Cool colours are thought to be calming, relaxing, and reserved. Cool colours are harmonious and trustworthy and can even be used at neutrals against sharper colour choices such as the welcome and home pages. Blue is the inly primary colour on the cool side of the colour wheel, meaning every cool hue indicates some variant of blue. The website has a trend of the use of blue colour and some inspiration was taken from a New Zealand stocks website which also has a cool colour trend to it. 

Overall the website was designed to be welcoming and easy to use with a safe enviroment for all users.

Created by: Oliver Donaldson 
  2021
