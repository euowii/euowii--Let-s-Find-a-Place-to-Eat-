# Inspiration
After playing hours of basketball with friends, we were all left starving. The problem? After spending 30 minutes trying to figure out where to eat, it was impossible to come up with a decision that everyone agreed upon. Why not create a web app that would solve this issue? After all, I'm sure there are other friend groups out there that may have similar situations occur regularly. 
# What the web app does and how it helps.
The web app will utilize Geolocation API to gather information that will be used by the Places API in order to generate a place for you and your friends to eat. It takes away the human decision making process. With no single individual suggesting a place to eat and leaving the decision making in the hands of a web app, everyone in the group is more likely to be content with the final decision. 

<img width="1415" alt="Screen Shot 2022-04-28 at 3 25 16 PM" src="https://user-images.githubusercontent.com/92958732/165857965-b4770318-a1ea-43d4-9f06-ceb83211acd8.png">

<img width="1410" alt="Screen Shot 2022-04-28 at 3 25 43 PM" src="https://user-images.githubusercontent.com/92958732/165857979-0ac88108-479b-43b2-8be9-df324b84f18a.png">

# How I built it?
Geolocation API, Places API, HTML, CSS, Bootstrap, JavaScript, Node.js, EJS, and Express
# Challenges I ran into 
One of the parameters required by Places API was the longitude and latitude of a location. One of the issues that this API gave me was that not all of the restaurants given to me using this API displayed whether or not the store was currently open. Because of this, I had to completely filter out these locations. The second issue the Places API gave was that it required a latitude and longitude paramater. Typically, people don't usually enter their latitude and longitude for their current location, but will instead enter their address. In order to solve this issue, I needed the use of another API. I decided to utilize the Geolocation API to turn the location entered by the user into a longitutde and latitude, which could then be used by the Places API to search for nearby places to eat. 
# Accomplishment I'm proud of
First off, I'm really proud of this project because it was the first time I built something using technology that's typically not taught in the classroom. I had to do a lot of self learning to create what I had created. Secondly, I'm proud that this web app has 100% coverage for edge cases. In other words, if you enter an invalid rating, adress, or if you enter a radius that yeilds no available places to eat in the areae, the user will receive a message depending on what caused the error
# What I learned
I learned how to search for answers online when I needed help or was not able to get answers that I was looking for. Creating something using technologies I had not learned in the classroom for the first time was daunting, and I learned how to effectively search for problems related to errors I was receiving which I will carry with me on futuree projects. 
# Features I plan on adding
One of the features I plan on adding in the future is the ability to "re-roll". In other words, once you've received a place to eat, the option to tap a button and be able to generate a new place to eat without having to input your information all over again. The other feature I hope to implement in the future is having the web app display the directions to the restaurant from the users inputted location
# How you can access the web app?
Here's a link to the web app. I hosted it on Heroku. Feel free to give it a spin!
https://glacial-fortress-04947.herokuapp.com/

