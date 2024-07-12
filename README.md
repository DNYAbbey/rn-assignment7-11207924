# rn-assignment7-11207924
# Shopping App

This is a simple Shopping App built with React Native and Expo. The app allows users to add, view, and remove items from a shopping list. The data is stored locally on the device using AsyncStorage.

## Functionality
- Add items to the cart
- View all items in the cart
- Remove items from the cart

## Design Choices
 - The user interface is designed to be simple and intuitive, with a focus on usability. 
 - The main screen displays the list of available items icluding images, a descrription and price of the item with an option to add items to cart. From this screen the user can navigate to the checkout page using the shopping bag icon.
 - The checkout page displays the items added to the cart with an option to remove the item from the cart. It also shows the estimated cost of all items in cart.
 - API Calls: Utilized Axios for fetching product data from an external API due to its ease of use and built-in request/response interceptors.
 - Navigation: The primary navigation structure made use of Drawer Navigator from React Navigation, which made HomeScreen, CartScreen, and other possible screens easily accessible.


 ## Data Storage
 - To store the shopping list data locally on the device, the app makes use of AsyncStorage.
 - AsyncStorage is a simple, unencrypted, asynchronous, persistent, key-value storage system that is global to the app.
 - Three functions were used to implement the functionalities regarding the storage; addToCart, fetchCart and removeFromCart, which do as their names suggest.


 ## Screenshots of Application
 ![Home screen](Shopping/images/rn-7%20shot%201.jpg)
 ![Home screen](Shopping/images/rn-7%20shot%203.jpg)
 ![Home screen](Shopping/images/rn-7%20shot%205.jpg)
 ![Product detail screen](Shopping/images/rn-7%20shot%202.jpg)
 ![Cart screen](Shopping/images/rn-7%20shot%204.jpg)