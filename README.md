# Introduction
The city of Mumbai, India is relatively Big and it is packed with restaurants, night life and amazing people. For people that are new to Mumbai, despite its small geographic size, it can be daunting to figure out what restaurants are worth going to and where they are. For people that used to live in Mumbai or are visiting Mumbai, how do you know what the best places are to get something to eat?

# Best_Restro
I have created a simple guide on where to eat based on Foursquare likes, restaurant category and geographic location data for restaurants 
in Mumbai. I will then cluster these restaurants based on their similarities so that a user can easily determine what type of restaurants 
are best to eat at based on Foursquare user feedback.

# Data Requirements
For this project, I will be utilizing the Foursquare API to pull the following location data on restaurants in Mumbai, India:
• Venue Name
• Venue ID 
• Venue Location 
• Venue Category 
• Count of Likes

# Data Acquisition Approach
To acquire the data mentioned above, I will need to do the following: 
• Get geolocator lat and long coordinates for Mumbai, India
• Use Foursquare API to get a list of all venues in Mumbai 
• Get venue name, venue ID, location, category, and likes
