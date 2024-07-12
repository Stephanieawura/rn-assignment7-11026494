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
![Cartscreen1](https://github.com/user-attachments/assets/f83b0508-c285-4c7e-a5c6-6ef0930ac882)
![Cartscreen2](https://github.com/user-attachments/assets/452e0f70-cf18-4710-a113-29061c085b11)

![homescreen1](https://github.com/user-attachments/assets/51fc4ec5-cbb6-44ff-8723-7ec6b5c99c69)
![homescreen2](https://github.com/user-attachments/assets/510a8c82-b546-4461-806e-33b1419de173)


## Installation
1. Clone the repository.
2. Install dependencies: `npm install`
3. Run the app: `npx react-native run-android` or `npx react-native run-ios`

## License
This project is licensed under the MIT License.
