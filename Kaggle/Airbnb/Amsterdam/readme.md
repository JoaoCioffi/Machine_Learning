
COLAB DIRECT LINK: 
<https://colab.research.google.com/drive/1pA_M6eoU2Xuot8QKNqTl920jNlU7Lc-W#scrollTo=tiNzPoBwbD9C>


# Problem Statement:

> Source: <https://medium.com/@uzairaslam.vf/predicting-the-price-of-airbnb-accommodations-in-amsterdam-using-machine-learning-3e695a949091>

> Official Database: <http://insideairbnb.com/get-the-data.html>

# Metadata: 
> Source: 
<https://docs.google.com/spreadsheets/d/1iWCNJcSutYqpULSQHlNyGInUvHg2BoUGoNRIGa6Szc4/edit#gid=982310896>
- id: Airbnb's unique identifier for the listing;
- name: Name of the listing;
- host_id: Airbnb's unique identifier for the host/user
- host_name: Name of the host. Usually just the first name;
- neighborhood_group: The neighbourhood group as geocoded using the latitude and longitude against neighborhoods as defined by open or public digital shapefiles;
- neighborhood: No metadata available
- latitude: Uses the World Geodetic System (WGS84) projection for latitude and longitude;
- longitude: Uses the World Geodetic System (WGS84) projection for latitude and longitude;
- room_type: All homes are grouped into the following three room types: (1) Entire place, (2) Private room and (3) Shared room. ***Entire places*** are best if you're seeking a home away from home. With an entire place, you'll have the whole space to yourself. This usually includes a bedroom, a bathroom, a kitchen, and a separate, dedicated entrance. Hosts should note in the description if they'll be on the property or not (ex: "Host occupies first floor of the home"), and provide further details on the listing. ***Private rooms*** are great for when you prefer a little privacy, and still value a local connection. When you book a private room, you'll have your own private room for sleeping and may share some spaces with others. You might need to walk through indoor spaces that another host or guest may occupy to get to your room. ***Shared rooms*** are for when you don't mind sharing a space with others. When you book a shared room, you'll be sleeping in a space that is shared with others and share the entire space with other people. Shared rooms are popular among flexible travelers looking for new friends and budget-friendly stays.
- price: daily price in local currency
- minimum_nights: minimum number of night stay for the listing (calendar rules may be different)
- number_of_reviews: The number of reviews the listing has
- last_review: The date of the last/newest review
- reviews_per_month: The number of reviews the listing has over the lifetime of the listing
- calculated_host_listings_count: The number of listings the host has in the current scrape, in the city/region geography.
- availability_365: avaliability_x. The availability of the listing x days in the future as determined by the calendar. Note a listing may not be available because it has been booked by a guest or blocked

As the Summers roll over in full swing and in case you’re still struggling to decide upon your most desirable destination of the year — then without further ado, know that Amsterdam awaits you for your most exquisite escapade!

Planning to travel to Amsterdam either for a luxury vacation or on a budget getaway could change into an ambiguous situation when finding the right place to stay. However, on the brighter side, it is never too difficult to stroll around the streets of Amsterdam — owing to the perfect embodiment of it’s European architecture. Delightedly and much to our relief, the Airbnbs all around the city can help you find your desirable accommodation in good value for money and that too in a sound neighbourhood.

As Airbnb is one of the most popular choices for accommodation amongst tourists from all over the world, in this study we'll be unveiling the best Airbnb accommodations in Amsterdam. While exploring the real data set for Amsterdam provided by Airbnb by answering the following questions, out task is to make it easy to select the next travel accommodation on Airbnb in Amsterdam.

1. What is the most popular neighborhood to stay in Amsterdam?

2. What is the average price/night for Airbnb in Amsterdam?

3. What factors influence the price of Airbnb accommodation in Amsterdam?

---
# Main Libraries
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

<div style="display: inline_block"><br> 
    
</div>

---
