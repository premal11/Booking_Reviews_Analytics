# Booking_Reviews_Analytics
This repository contains a dataset of over 515,000 guest reviews and ratings for nearly 1,500 hotels across Europe, scraped from the popular hotel reservation website Booking.com. 
Key Features of the Project:
Feature Extraction:

Identify the top five hotel features mentioned most frequently in positive and negative reviews, ensuring that identified features are substantive (e.g., "location," "staff") rather than vague terms (e.g., "great" or "negative").
Preference Analysis:

Analyze customer preferences for specific features based on traveler types, such as:
Solo travelers
Groups
Business trips
Leisure trips
Couples
Families with young children
Country-Specific Insights:

Determine the top five features that customers appreciate and complain about most for hotels located in:
The United Kingdom
France
Italy
Spain
Dashboard Visualization:

Create a dynamic dashboard that includes:
"Top Five Hotels Overall" with consistently high ratings.
"Bottom Five Hotels Overall" with consistently low ratings.
"Five Most Improved Hotels" showcasing the highest improvement in average ratings from 2015 to 2017, with visualizations displaying their average ratings across these years.
Project Summary
Dataset: Guest reviews from Booking.com hotels in Europe, with cleaned text data for the reviews and metadata about hotel addresses and review dates.
Tools: Python, Pandas, Matplotlib, Seaborn, SpaCy, Scikit-learn.
Objective: Analyze and visualize customer sentiment, most mentioned features in positive and negative reviews, and highlight hotel performance over time.
Key Insights
1. Top Hotel Features in Reviews
Positive Features:

Staff
Location
Room
Breakfast
Bed
Negative Features:

Room
Service
Staff
Breakfast
Floor
2. Customer Preferences by Traveler Type
Solo Travelers:

Positive: Staff, Location, Room, Breakfast, Bed
Negative: Room, Service, Staff, Breakfast, Floor
Group Travelers:

Positive: Staff, Location, Room, Breakfast, Station
Negative: Room, Staff, Service, Breakfast, Bed
(Add other traveler categories here)

3. Country-wise Insights
United Kingdom:

Positive: Location, Breakfast, Bed, Station, Comfortable
Negative: Breakfast, Bed, Floor, Bar, Area
France:

Positive: Location, Breakfast, Bed, Tower, Station
Negative: Breakfast, Bed, Floor, Area, Water
(Add other countries here)

4. Hotel Ratings Analysis
Top 5 Hotels:

Ritz Paris
Hotel Casa Camper
41
Hotel de La Tamise Esprit de France
Le Narcisse Blanc Spa
Bottom 5 Hotels:

Hotel Liberty
Kube Hotel Ice Bar
Villa Eugenie
Savoy Hotel Amsterdam
Holiday Inn Paris Montparnasse Pasteur
5. Most Improved Hotels (2015-2017)
Le Lavoisier
Mercure Paris Bastille Saint Antoine
L Edmond Hotel
MiHotel
Villa Lutce Port Royal
Dashboard Visualizations
This project includes the following visualizations:

Top Five Hotels Overall: Bar chart showing the top 5 hotels with the highest average ratings.
Bottom Five Hotels Overall: Bar chart displaying the bottom 5 hotels with consistently low ratings.
Five Most Improved Hotels: Line plot showing the rating improvements from 2015 to 2017 for the top 5 most improved hotels.
