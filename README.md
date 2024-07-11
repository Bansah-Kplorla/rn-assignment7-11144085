# rn-assignment7-11144085
Shopping Cart Application
This React Native application is a shopping cart system that allows users to view a list of products fetched from an external API, preview detailed information about each product, add products to their cart, and remove products from their cart. The selected items are stored locally on the device using AsyncStorage. The app includes a drawer navigation for easy access to different screens.

Features
HomeScreen: Displays a list of available products fetched from an external API.
ProductDetailScreen: Shows detailed information about a selected product.
CartScreen: Displays selected items in the cart.
Drawer Navigation: Provides easy access to different screens through a swipe gesture or button.
Add to Cart Button: Allows users to add products to their cart.
Remove from Cart Button: Enables users to remove items from their cart.
Data Storage: Uses AsyncStorage to store selected items locally on the device.
Design Choices
Component Structure:
HomeScreen: Renders a list of products.
ProductDetailScreen: Renders detailed information about a product when a product is selected from the HomeScreen.
CartScreen: Displays items added to the cart.
Drawer Navigation: Provides a navigation menu accessible through a swipe gesture or button.
Data Fetching: Used fetch to retrieve product data from an external API. Managed asynchronous operations with async/await to ensure smooth data fetching and rendering.

State Management: Utilized React's useState, useEffect, and useContext hooks for managing state across components. Created a CartContext to handle cart state and actions like adding and removing items from the cart.

Local Storage: Implemented AsyncStorage for persistent storage of cart items on the user's device. Ensured that cart items are loaded from AsyncStorage when the app starts and saved whenever the cart is updated.

UI Design: Designed a clean and user-friendly UI using React Native's StyleSheet. Incorporated responsive design principles to ensure a consistent experience across different devices and screen sizes.

Implementation Details
Fetching Data from API: Used the useEffect hook to fetch data from an external API when the HomeScreen component mounts. Stored the fetched data in a local state variable and rendered it using a FlatList.

Product Details: Implemented navigation from HomeScreen to ProductDetailScreen when a product is selected. Passed the selected product's data through React Navigation's route params to display detailed information.

Cart Functionality: Created addToCart and removeFromCart functions within the CartContext. Managed cart state using the useContext hook in the CartScreen component to display selected items. Stored cart items in AsyncStorage and retrieved them on app startup to persist cart state.

SCREENSHOTS
![MyScreenshot-III](https://github.com/Bansah-Kplorla/rn-assignment7-11144085/assets/170067731/b41f2705-33fd-4192-a76b-1434c5879581)


![MyScreenshot-II](https://github.com/Bansah-Kplorla/rn-assignment7-11144085/assets/170067731/2a48ca4e-f966-4c8b-9beb-17bca0a66fb8)


![MyScreenshot-I](https://github.com/Bansah-Kplorla/rn-assignment7-11144085/assets/170067731/3797525e-ee56-4d35-95ae-9255f152ee2c)

![IMG-20240710-WA0014](https://github.com/Bansah-Kplorla/rn-assignment7-11144085/assets/170067731/99020aa6-2fa9-4ecb-bcb9-dc9037f86616)

![IMG-20240710-WA0016](https://github.com/Bansah-Kplorla/rn-assignment7-11144085/assets/170067731/48896e89-6712-4562-aac3-6bdce573096f)

![IMG-20240710-WA0021](https://github.com/Bansah-Kplorla/rn-assignment7-11144085/assets/170067731/afe3fbf4-b545-4dea-8863-10d895c1aa7f)

![IMG-20240710-WA0028](https://github.com/Bansah-Kplorla/rn-assignment7-11144085/assets/170067731/a5a55a10-e56a-43a7-970f-1fd190945661)

![IMG-20240710-WA0036](https://github.com/Bansah-Kplorla/rn-assignment7-11144085/assets/170067731/05654e0e-51dc-4c0f-ad0c-212f513d2ea0)

![IMG-20240710-WA0020](https://github.com/Bansah-Kplorla/rn-assignment7-11144085/assets/170067731/9b0dbe8c-cd61-4d5b-93cd-2a2960aa9ec2)

![IMG-20240710-WA0018](https://github.com/Bansah-Kplorla/rn-assignment7-11144085/assets/170067731/75844261-a9ed-4bec-8416-3a744fcba7f2)

![IMG-20240710-WA0026](https://github.com/Bansah-Kplorla/rn-assignment7-11144085/assets/170067731/74bf6d49-1978-46bb-bc79-bb52f279103e)

![IMG-20240710-WA0031](https://github.com/Bansah-Kplorla/rn-assignment7-11144085/assets/170067731/adc6fdc4-2bd3-445b-9307-09e2a2192f7c)

![IMG-20240710-WA0032](https://github.com/Bansah-Kplorla/rn-assignment7-11144085/assets/170067731/eb7c4900-6d39-4f5c-af71-c20753d80a4a)

![IMG-20240710-WA0035](https://github.com/Bansah-Kplorla/rn-assignment7-11144085/assets/170067731/3ce0c9e5-863d-4a1c-9263-713c3a4d7ef0)

![IMG-20240710-WA0024](https://github.com/Bansah-Kplorla/rn-assignment7-11144085/assets/170067731/996313ec-5712-4103-8a65-7b1c1cbf809f)














