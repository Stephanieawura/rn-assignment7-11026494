# RN-ASSIGNMENT7-11026494

## Description
This project is a mobile application for displaying products, viewing product details, and managing a shopping cart. The app fetches product data from an external API and allows users to add and remove items from their cart, with cart data stored locally on the device.

## Design Choices
- **Navigation:** Used React Navigation's Drawer Navigator for easy access to different screens.
- **Data Fetching:** Used Axios for fetching data from an external API.
- **Local Storage:** Used AsyncStorage for persisting cart data locally.

## Data Storage Implementation
The cart items are stored locally using AsyncStorage. The `addToCart` and `removeFromCart` functions manage the cart data by updating the AsyncStorage.

## Screenshots
![alt text](Cartscreen1.jpg)
![alt text](Cartscreen2.jpg)

![alt text](homescreen1.jpg)
![alt text](homescreen2.jpg)




## Installation
1. Clone the repository.
2. Install dependencies: `npm install`
3. Run the app: `npx react-native run-android` or `npx react-native run-ios`

## License
This project is licensed under the MIT License.
