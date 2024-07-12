# rn-assignment7-11144085

Shopping Cart Application
This React Native application is a shopping cart system enabling users to browse a list of products fetched from an external API, view detailed information about each product, add items to their cart, and remove items from their cart. The selected items are stored locally on the device using AsyncStorage. The app features a drawer navigation for seamless access to different screens.

Features
HomeScreen: Displays a list of products fetched from an external API.
ProductDetailScreen: Shows detailed information about a selected product.
CartScreen: Displays items that have been added to the cart.
Drawer Navigation: Provides easy access to different screens via a swipe gesture or button.
Add to Cart Button: Allows users to add products to their cart.
Remove from Cart Button: Enables users to remove items from their cart.
Data Storage: Uses AsyncStorage to store selected items locally on the device.
Design Choices
Component Structure:

HomeScreen: Renders a list of products.
ProductDetailScreen: Displays detailed information about a selected product from the HomeScreen.
CartScreen: Shows items that have been added to the cart.
Drawer Navigation: Provides a navigation menu accessible through a swipe gesture or button.
Data Fetching: Utilized the fetch function to retrieve product data from an external API. Managed asynchronous operations with async/await to ensure smooth data fetching and rendering.

State Management: Utilized React's useState, useEffect, and useContext hooks for managing state across components. Created a CartContext to handle cart state and actions, such as adding and removing items from the cart.

Local Storage: Implemented AsyncStorage for persistent storage of cart items on the user's device. Ensured that cart items are loaded from AsyncStorage when the app starts and saved whenever the cart is updated.

UI Design: Designed a clean and user-friendly UI using React Native's StyleSheet. Incorporated responsive design principles to ensure a consistent experience across different devices and screen sizes.

Implementation Details
Fetching Data from API: Used the useEffect hook to fetch data from an external API when the HomeScreen component mounts. Stored the fetched data in a local state variable and rendered it using a FlatList.

Product Details: Implemented navigation from HomeScreen to ProductDetailScreen when a product is selected. Passed the selected product's data through React Navigation's route params to display detailed information.

Cart Functionality: Created addToCart and removeFromCart functions within the CartContext. Managed cart state using the useContext hook in the CartScreen component to display selected items. Stored cart items in AsyncStorage and retrieved them on app startup to persist cart state

SCREENSHOTS
![MyScreenshot-III](https://github.com/Bansah-Kplorla/rn-assignment7-11144085/assets/170067731/b41f2705-33fd-4192-a76b-1434c5879581)


![MyScreenshot-II](https://github.com/Bansah-Kplorla/rn-assignment7-11144085/assets/170067731/2a48ca4e-f966-4c8b-9beb-17bca0a66fb8)


![MyScreenshot-I](https://github.com/Bansah-Kplorla/rn-assignment7-11144085/assets/170067731/3797525e-ee56-4d35-95ae-9255f152ee2c)

![Screenshot-VI](https://github.com/user-attachments/assets/92dad6ab-930c-49d8-9e2c-6527cd1729fb)

![Screenshot-V](https://github.com/user-attachments/assets/a46007a7-a09e-4b7b-a484-366a8d57bb1a)

![Screenshot-IV](https://github.com/user-attachments/assets/c0feff61-6cbd-4010-8cb9-a4ffa8213058)

![Screenshot-VIII](https://github.com/user-attachments/assets/bccc991d-44ab-4d1e-8c8b-11173e3d2ac7)

![Screenshot- IX](https://github.com/user-attachments/assets/63c002d8-dd01-48f1-a34a-4426c42ba2b8)

![Screenshot-X](https://github.com/user-attachments/assets/c4bb7751-1943-44a4-b7e5-9288f32ba23d)

![Screenshot-XI](https://github.com/user-attachments/assets/83dcd6a2-dcec-4642-90b9-857af6c090d8)

























