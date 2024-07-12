# rn-assignment7-11116940

# Kwesi Ahenkorah Gyamenah

# Assignment 7

## Overview

This project is a React Native shopping application built using Expo. The app features a HomeScreen displaying a list of products, a CartScreen for viewing and managing items in the cart, and a ProductDetailScreen for detailed information about each product. 

## Design Choices

### UI Design
- **HomeScreen**: Displays a list of products fetched from an external API. Each product card includes an image, name, price, and an "Add to Cart" button. Product names are displayed in uppercase for a consistent and bold look.
- **CartScreen**: Lists all items added to the cart with their details and a "Remove" button to delete items from the cart. The total price is displayed at the bottom.
- **ProductDetailScreen**: Shows detailed information about a selected product, including the image, title, description, price, and options to add the product to the cart.
- **Drawer Navigator**: Provides easy navigation between different sections of the app like Store, Jewelry, and Electronics. Currently, only the Store section is functional.

### Navigation
- **React Navigation**: Used for managing navigation between screens. A Drawer Navigator is implemented for primary navigation, and Stack Navigation is used within the Store section.

### Styling
- **Tenor Sans Font**: Used for text elements to match the provided UI design.
- **Custom Icons and Images**: Utilized to enhance the visual appeal and match the design specifications.

## Data Storage

### AsyncStorage
- **Cart Data**: Items added to the cart are stored using AsyncStorage, ensuring data persistence across app sessions. This allows users to exit the app and return later without losing their cart contents.
- **Implementation**: When a product is added to or removed from the cart, the state is updated and the data is saved to AsyncStorage.

### API
- **FakeStoreAPI**: Product data is fetched from `https://fakestoreapi.com/products`. This API provides a variety of products with details needed for the HomeScreen and ProductDetailScreen.

## Screenshots

### HomeScreen
![photo_4_2024-07-12_08-36-00](https://github.com/user-attachments/assets/7569d6d3-d0c6-40d7-8a9d-47b24b6fca98)
![photo_2_2024-07-12_08-36-00](https://github.com/user-attachments/assets/01ad8153-3f88-465b-9f35-d0ab1584ed0a)

### ProductDetailScreen
![photo_1_2024-07-12_08-36-00](https://github.com/user-attachments/assets/426a7717-aab9-42d1-a6ce-66f979c70fd7)

### CartScreen
![photo_3_2024-07-12_08-36-00](https://github.com/user-attachments/assets/533f39ea-4e04-4c78-bb92-d5f7ae92a503)


## How to Run the Project

1. **Clone the Repository**
   ```sh
   git clone https://github.com/kwesiahenkorahg/rn-assignment7-11116940.git
   cd assignment7
   ```

2. **Install Dependencies**
   ```sh
   npm install
   ```

3. **Start the App**
   ```sh
   expo start
   ```

## Conclusion

This app demonstrates a basic implementation of a shopping cart with persistent storage, leveraging the power of React Native and Expo for mobile app development. The focus on design consistency and usability ensures a smooth and visually appealing user experience.

