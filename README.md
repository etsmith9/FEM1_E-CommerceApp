Module Project: Advanced React E-Commerce Web App

Advanced React E-Commerce Web App

To successfully build our advanced e-commerce application and achieve the learning objectives, we need to establish clear project requirements. These requirements outline the key features and functionalities that our application must encompass. Below, you'll find a comprehensive list of project requirements based on our learning objectives:
💡 Note:
Our project leverages the FakeStoreAPI to simulate asynchronous data fetching. This API, available at https://fakestoreapi.com/, provides a simulated environment for fetching product/category data. By utilizing this mock API, we can demonstrate the capabilities of the advanced topics reviewed within our Module’s Lessons.
While both Context API and Redux Toolkit are valuable tools for state management, we'll focus on Redux for this project to deepen understanding and practice with Redux concepts.
Additionally, we'll encourage the use of React Query for data fetching due to its simplicity and efficiency, while still allowing flexibility for the use of Redux Toolkit for state management.
Click Here To View On Google Classroom
Project Requirements
Product Catalog:
Product Listing and Display:
Use React Query to retrieve all of the products in the store and display them on the Home component. 
Show the title, price, category, description, rate, and image.
Each product should have a button that will allow the user to add it to the shopping cart
Category Navigation:
Provide a select drop down that allows users to select a product category
NOTE: FakeStoreAPI has an endpoint that will give you an array of all the product categories
Use React Query to request that endpoint to populate your select dropdown.  
The dropdown should not be hard coded, it should dynamically pull the values from the API
When the user selects a different category from the dropdown, only display the products from that category.
NOTE: The FakeStoreAPI has an endpoint that allows you to get products of a specific category.  Make sure to use React Query to make the request to this endpoint.  
Shopping Cart:
State Management with Redux Toolkit:
Utilize Redux Toolkit for managing the shopping cart state, including adding, updating, and removing products from the cart.
Define reducers and actions to handle cart-related state changes and interactions with the FakeStoreAPI.
Shopping Cart Component:
Create a Shopping Cart component where users can view and manage the products within their cart.
Display a list of products currently added to the cart including the title, image, count, and price of each product.
Each product should have a button that removes the it from the cart
REMEMBER: Users should be able to add products to the shopping cart directly from the home product listing page.
Session Storage for Shopping Cart:
Store, retrieve, and update the shopping cart data in sessionStorage to ensure persistence across different components and browser sessions.
Store the shopping cart as an array of product objects
Total Amount and Price Calculation:
In the shopping cart component, display the total number of products in the cart
Display the total price of all the products in the cart.
Update these values dynamically as users modify the contents of their cart, ensuring accuracy and real-time feedback.
Checkout Functionality:
Implement a checkout feature allowing users to complete their purchases.
FakeStoreAPI does not have a way to process orders so this feature should simulate a checkout by clearing the Redux state and sessionStorage
Provide visual feedback to users upon successful checkout, indicating that their cart has been cleared.
GitHub Repository:
Create a GitHub repository for the project and commit code regularly.
Maintain a clean and interactive README.md file in the GitHub repository, providing clear instructions on how to run the application and explanations of its features.
Submission
Upon completing the project, submit your code, including all source code files, and the README.md file in your GitHub repository to Google Classroom.

