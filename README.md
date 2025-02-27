<p align="center">
  <img src="https://github.com/crescent-igor/Chelf-PayPal-VAP-FinalAssignment/blob/master/chelf-logo.png">
</p>
This repository contains the schema for the proposed API called "Chelf" as part of the value added program conducted at VIT. It is a play on words with Chef and self, as it defines the motive behind the application, anyone can be a chef.
 
"There is no sincere love than the love of food"
 
This saying by playwright George Bernard Shaw can be considered the inspiration behind this application. Everyone likes having their favourite food from their favourite chefs, many people also don't mind experimenting with new dishes while some people want to try all there is to offer the world. Often, exotic and foreign dishes are sold at higher prices. The other choice would be to find the best restaurant in your city for a particular dish and travelling there everyday. Otherwise you order food which again is not fresh and may not taste exactly the best. Using chelf you can choose a dish from around the world by any chef and get it delivered to you. Now here's what is new, the package delivered to you will be a bunch of ingredients curated for easy usage, dish secrecy and contain the exact quantity required to cook the food. The customers then can prepare the dish using the ingredients by following a simple guide. This will enable the food cooked to be fresh and authentic. The pricing of food also is something which sets chelf apart as local  ingredients cost less and foreign ingredients cost slightly higher.
#### ChelfDaily
Another feature of chelf is ChelfDaily. It is a food subscription program where curated dishes are served as collections. The food is delivered according to a time table which is revised regularly. The users can subscribe to the service by adding it to the cart. The collections have their own categories and ratings, they have been integrated into the cart order functionalities. Chelf daily can also be subscribed in a weekly, monthly and annual basis.  
### Novelty
 The novelty of "Chelf" is that:
 1.  The dish prices vary across cities based on market prices of ingredients
 2.  The prices of exotic ingredients are provided at much lesser prices
 3.  Chefs from across the world and across various levels from celebrity to upcoming can showcase their dishes
 4.  The food is fresh and hygienic as it is prepared right out of your own kitchen
![alt text][diag]
 
[diag]: https://github.com/crescent-igor/Chelf-PayPal-VAP-FinalAssignment/blob/master/Chelf.png
 
API documentation available at:
 
https://app.swaggerhub.com/apis-docs/panther_meh/Chelf/1.0.0
 
API YAML schema at:
 
https://app.swaggerhub.com/apis/panther_meh/Chelf/1.0.0
 
## Routes
### Admin
The system administrator has the authority to add and delete chefs after due check. Also adds and deletes system support employees. Can also delete users if need be. Manages the ingredients data and the prices.
- Log In
- Log Out
- Add/Delete Chefs
- Add/Delete Support Staff
- Delete User
- Add/Update/Delete ingredients to system
- Add/Update/Delete ChelfDaily Collections
### Support
Attend to register ticket complaints by users. Act on the complaint directly or redirect to concerned employees. Update complaint status accordingly.
- Log In
- Log Out
- View Complaints
- Update Complaint status
### Chef
Can browse through the site as a user as a chef is also a user with advanced functionalities. Additionally the chef can build his profile and add/modify/delete dishes. The chef can also browse ingredients to find exact IDs of particular ingredients.
- Log In
- Log Out
- Browse ingredients
- Browse Chefs
- Add Dishes
- Update/Delete dishes he has added
- All other User functions
### User
Customers signed up and logged in to the site can browse through the chefs and dishes. Required filters can be utilised to get desired results for dishes and chefs such as cuisine, rating, name and the chef class.The customer can then add the dishes to the cart and specify the quantity. He can also view the price of the dishes in the cart which is calculated in realtime in the back end. He can then process the order for the cart and specify the delivery address, payment method etc. The user can track the order till it gets delivered. The user can also register complaints against orders if facing any issues.
- Log In
- Log Out
- Browse Dishes by Id or name
- Browse Dishes using filters
 - Rating
 - Cuisine
- Browse Chef profiles by Id or name
- Browse Chef using filters
 - Class
 - Rating
 - Cuisine
- View/Update/Delete Self profile
- Add/View/Update/Delete Rating for a Chef
- Add/View/Update/Delete Rating for a Dish
- Get cart items
- Add/Edit/Delete Dish to cart
- Add/Edit/Delete ChelfDailySubscription to the cart
- Place an Order
- View/Update/Delete an Order
- Check order status
- Post a complaint regarding an order
- View/Update the complaint
### Guest
Guest users are allowed to browse through the Chefs and Dishes. He can also add, update and delete dishes to the cart. The guest however cannot place orders,give ratings or perform any other functions.
- Sign Up and become a User
- View Chefs by Id or name or filters
- View Dishes by Id or name or filters
- Add/update/delete items from cart
 
To make the application practical given below are a few scenarios:
### Scenario 1
You want to have pasta by a particular chef from Rome. Yes, you can follow one of his food shows but you need to go out and find all the ingredients required. Since you are in India, all the local spices and ingredients mentioned may not be available, even if they are, they might not be the exact quality also foreign spices usually are more expensive. Let's assume you got your ingredients now cooking with the exact quantity and mix is difficult and as the spices may not be the same, you might end up with something else.
####
If you order the same dish through chelf, your dish will cost you based on your location and ingredients hence it will cost you higher than it costs in Rome but it would be much cheaper than going around and looking for these spices as Chelf would have these spices in bulk all around the world. The cooking itself would be simple as you will find many ingredients already mixed in proportions to make your task easier and preserve secrecy of some dishes. You can cook and enjoy your meal which would be as close to the authentic pasta as it can get.
### Scenario 2
You are an Indian in Japan and crave your favourite Indian curry. You, in this case aren't the greatest of cooks and have no one who can cook for you. You can visit an Indian restaurant    but it is pretty far from your place and you can't afford going there everyday.
####
In this case you can order the curry from chelf. Now to save money you can choose a basic chef and proceed ordering your ingredients. The ingredients would be priced based on your location, which is Japan hence cost slightly higher than local. Your food will be delivered and you can cook it as it is just following instructions and adding ingredients. You can practice this regularly as it would provide you with authentic Indian curry at the cheapest price abroad. An extension to this would be using ChelfDaily subscription to an Indian collection where the food would be delivered to you everyday.
 
 
## How to use Chelf?
###  Customer
Sign up to chelf using your email, set up your username at chelf and you are ready to go. Browse the application for your favourite dishes by your favourite chefs from around the world. You can filter out the results based on cuisine, chef status and ratings. Add your choice to the cart along with the number of people to be served and place your order. The bill will be generated based on your meal and your delivery destination and the package will be at your doorstep soon. The package will contain clear instructions on how to prepare the dish from the ingredients which are labelled and easily identifiable. The package is curated to serve the number of people mentioned. Follow the steps and enjoy your meal. For any queries or complaints you can post a ticket on our application for a particular order.
 
### Chef
An account is created once you contact the admin to be a part of chelf. You can easily post dishes from your application thereafter and start building your profile on chelf. The ingredients of the dishes need to be specified exactly as to cater the customers with the best and authentic quality. Showcase the masterchef in you and let people around the world enjoy a taste of your talents. You can easily track your account on the profile.
 

