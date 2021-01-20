# Final_Project
Final Coursera Capstone Project: Neighborhood Analysis by Venue Ratings

This Readme will supplement other content associated with the Neighborhood Analysis by Venue Ratings program.

Background
  Applications like Yelp and Google Maps are used to identify venues in a city and assess their suitability by ratings submitted by past customers. 
  These applications have proven themselves to be valuable. However, for application users not familiar with a city, 
  they may not obtain full context of the venues and their locations. For example, a visitor may desire to visit areas with a high concenstation of 
  nicer restaurants and decide where to dine when they get there. 
  Additionally,  there may be an interest to seek-out higher rated restaurants and their locales in order to  experience a better-part of a city city, 
  or bad parts of a city.
  
Foursquare
  Foursquare is a US business that uses detailed location data, along with business, and customer input to 
  “tap into this intelligence to create better customer experiences and smarter business outcomes.” 
  See: https://foursquare.com.
  
Venue Rating
  Foursquare provides a user-based rating system where Foursquare used feedback from customers, 
  combined with a wealth of other data and artificial intelligence techniques to calculate overall ratings for a venue. 
  Ratings are numeric from 0 to 10, 10 being the highest rating; a 0 rating generally used for venues that have not received a rating. 
  For a detailed discussion about Foursquare’s rating system, see: 
  https://medium.com/foursquare-direct/finding-the-perfect-10-how-we-developed-the-foursquare-venue-rating-system-c76b08f7b9b3
 
Dynamic Updates
  Foursquare is continually updating ratings and other analytics as user feedback is provided. Thus the results will change over time.
  
Foursquare Rate Limiting
  The Personal-Developer account, which most person possess, is very limited for allowing calls to the Foursquare API. 
  It's very common for users to max-out their available daily calls. The calls for Venue Ratings can definitely exceed daily limits.
  The Neighborhood Analysis by Venue Ratings will identify if rate limiting is in-effect and if true, apply random rating numbers to venues.
  There is a notification displayed is rate limiting has been detected.

Program Development Notes
  I built the Neighborhood Analysis by Venue Ratings primarily using the IBM Watson Studio environment. I created a Jupyter notebook to complete the coding. 
  However due to the complexitity of the code and time required, I exceeded my free quota allowed. I completed the project using Acaconda.
