# Comprehensive MERN E-commerce React Website 👜
<div align="center"><img height="350px" src="https://github.com/shanibider/ANASTACIA-MERN-ECOMMERCE-WEBSITE/assets/72359805/9717a097-24f9-4175-af71-1b3ebac20dc3"></div>


#### **Live Demo:** [Explore the live website.🖥](https://anastacia-mern-ecommerce-website.onrender.com/)

A comprehensive feature-rich e-commerce website developed as a server-client React application, powered by the: 
<h2 align="center"> MERN (MongoDB, Express.js, React.js, Node.js) <img height=30px src="https://skillicons.dev/icons?i=mongodb"> <img height=30px src="https://skillicons.dev/icons?i=express"> <img height=30px src="https://skillicons.dev/icons?i=react">
<img height=30px src="https://skillicons.dev/icons?i=nodejs"> stack 💼 </h2>
🛒 Key features include a dynamic shopping cart, an interactive review system🖊, and organized product listings📋, enhancing user engagement. Administrators benefit from comprehensive control over user interactions, and streamlining platform management.

<br> 

# Integration between Frontend and Backend 🏆
This project demonstrates proficiency in full-stack development, including frontend UI/UX design, backend API development, database management, and integration with external services. It showcases the ability to work with a diverse set of technologies and libraries to build a scalable and robust web application.
My server-client React application leverages a comprehensive stack of **JavaScript, HTML, and CSS technologies** <img height=20px src="https://skillicons.dev/icons?i=js">  <img height=20px src="https://skillicons.dev/icons?i=html">  <img height=20px src="https://skillicons.dev/icons?i=css"> 
<br> to deliver a seamless user experience. Following established React application structures, including **routing, state management, and component-based architecture**, ensures scalability and maintainability. Emphasizing **responsive design**,
the application guarantees optimal display across diverse devices.

With **Firebase** <img height=20px src="https://skillicons.dev/icons?i=firebase"> powering our **secure user authentication** mechanism, data confidentiality is maintained through **HTTP/S protocols**.
Moreover, our robust backend comprises a blend of **Firebase database🔐 and MongoDB <img height=20px src="https://skillicons.dev/icons?i=mongodb">**, ensuring efficient data storage and management. Integration with the **<img height="30px" align="center" src="https://github.com/shanibider/ANASTACIA-MERN-ECOMMERCE-WEBSITE/assets/72359805/49484e34-14f1-46b9-9153-a25754eb797c"> API** facilitates secure transactions, providing users with a seamless shopping experience.

<br>

# Technologies Used 🏆
[![My Skills](https://skillicons.dev/icons?i=js,react,html,css,bootstrap,mongodb,nodejs)](https://skillicons.dev)

### **MERN Stack:**
- [x] **MongoDB:** Efficient and scalable NoSQL database, ensuring robust data storage and retrieval capabilities.
- [x] **Express.js:** Fast and minimalist web framework for Node.js, facilitating the creation of powerful APIs and web applications.
- [x] **React.js:** Dynamic and responsive JavaScript library for building modern and engaging user interfaces, utilizing:
  - [ ] **useState:** React hook for managing state in functional components, enhancing component interactivity and reactivity. ⚛️
  - [ ] **useContext:** React hook for accessing and consuming context values across components, facilitating efficient data sharing. 🔄
  - [ ] **useReducer:** React hook for managing complex state logic with reducer functions, offering a more organized approach to state management. 🔴
- [x] **Node.js:** Lightweight and efficient JavaScript runtime environment, enabling scalable and high-performance server-side execution.

### **Firebase:**
- [x] **Authentication:** Firebase authentication services for secure user authentication and authorization management.
- [x] **Real-time Database:** Firebase real-time database for seamless and synchronized data updates across clients in real-time.

### **HTTP/S Protocols:**
- [x] **Axios:** Promise-based HTTP client for making asynchronous requests to the server, enhancing data fetching and manipulation.
- [x] **AJAX:** Asynchronous JavaScript and XML for making seamless requests to the server without refreshing the entire page.
- [x] **Fetch API:** Modern browser API for fetching resources asynchronously across the network, improving data retrieval efficiency.

### **Payment Processing:**
- [x] **PayPal API:** Integration of PayPal API for secure and reliable payment processing, ensuring seamless transactions for users.

### **Frontend Development:**
- [x] **HTML, CSS, JavaScript:** Foundational technologies for building the frontend interface, providing structure, style, and interactivity to web applications.
- [x] **Bootstrap:** Frontend framework for developing responsive and mobile-first web projects, streamlining the design and layout process and ensuring compatibility across various devices. 🌐


<br>



# Key Features 🎯

- [x] 🏠 **Home Page:** 
  - Lists products to browse and explore.

- [x] 🔍 **Detailed Product View:** 
  - Provides in-depth information about a selected product.

- [x] 📂 **Product Categories:** 
  - Categorizes products for easy navigation.

- [x] 🛒 **Shopping Cart:** 
  - Allows users to add and manage items in their cart.

- [x] 💳 **Order Processing with PayPal:** 
  - Securely handles payment processing using the PayPal API for demo purposes.

- [x] 🔐 **Secure User Registration and Login:** 
  - Ensures a safe and secure user authentication system.

- [x] 👩‍💼👨‍💼 **Admin Functionalities:** 
  - Manages 'Products' and 'Orders' lists
  - Features a dashboard displaying real-time metrics: registered users, order count, and financial performance through total money orders.
  - Enables the creation, editing, and deletion of products.

- [x] 👩‍💼 **User Functionalities:** 
  - Accesses order history.
  - Edits user profile.

- [x] 👩🏻‍🤝‍🧑🏻 **About The Team Page:** 
  - Provides information about the development team.

    
<br>



# MERN Project Architecture 📁

This repository contains the main files and folder structure for the MERN (MongoDB, Express.js, React.js, Node.js) project.
The app follows a typical MERN architecture where React is used for the front-end, Node.js and Express for the back-end, MongoDB for the database, and JWT for authentication.
These components work together to provide a seamless shopping experience for users while allowing for easy management of products, orders, and user accounts.

## Folder Structure 📁

```
MERN-project/
├── frontend/
│   ├── components/
│   │   ├── AdminRoute.js
│   │   ├── CheckoutSteps.js
│   │   ├── LoadingBox.js
│   │   ├── MessageBox.js
│   │   ├── Product.js
│   │   ├── ProtectedRoute.js
│   │   ├── Rating.js
│   │   └── SearchBox.js
│   ├── screens/
│   │   ├── AboutUsScreen.js
│   │   ├── CartScreen.js
│   │   ├── DashboardScreen.js
│   │   ├── HomeScreen.js
│   │   ├── HowToScreen.js
│   │   ├── OrderHistoryScreen.js
│   │   ├── OrderListScreen.js
│   │   ├── OrderScreen.js
│   │   ├── PaymentMethodScreen.js
│   │   ├── PlaceOrderScreen.js
│   │   ├── ProductEditScreen.js
│   │   ├── ProductListScreen.js
│   │   ├── ProductScreen.js
│   │   ├── ProfileScreen.js
│   │   ├── SearchScreen.js
│   │   ├── ShippingAddressScreen.js
│   │   ├── SigninScreen.js
│   │   └── SignupScreen.js
│   ├── App.js
│   ├── Store.js
│   ├── index.js
│   └── utils.js
├── Backend/
│   ├── routes/
│   │   ├── orderRoutes.js
│   │   ├── productRoutes.js
│   │   ├── seedRoutes.js
│   │   └── userRoutes.js
│   ├── models/
│   │   ├── orderModel.js
│   │   ├── productModel.js
│   │   └── userModel.js
│   ├── server.js
│   ├── firebase.js
│   ├── utils.js
│   ├── data.js
│   └── cloths.json
└── ...
```

- [x] **backend**: Contains the backend files and resources, following a RESTful architecture.
- [x] **frontend**: Houses the frontend files and components developed with React.js.
- [x] **config**: Stores configuration files for the project, such as database configurations or environment variables.
- [x] **models**: Defines the database models and schemas used in the application.
- [x] **routes**: Contains the route definitions for the API endpoints.
- [x] **controllers**: Includes the controller functions responsible for handling requests and responses.
- [x] **middlewares**: Houses custom middleware functions used in the API.
- [x] **utils**: Stores utility functions and helper modules used throughout the project.
- [x] **public**: Stores any static assets or files served by the backend.
- [x] **views**: Contains server-side views if any, typically used in server-side rendering applications.


## Backend Structure 🧱🔨-

### Server -

- [ ] **`server.js`:** This is the main entry point for the Node.js backend. It initializes Express, connects to MongoDB using Mongoose, defines API routes, and serves the React frontend. It also includes logic for seeding initial data and serving static files.

### Routes -

- [ ] **`orderRoutes.js`,** `productRoutes.js`, `seedRoutes.js`, `userRoutes.js`: These files define the API endpoints and route handlers for managing orders, products, user authentication, and seeding initial data.

### Models -

- [ ] `Order.js`, `Product.js`, `User.js`: These files define the data models using Mongoose, which allow you to interact with MongoDB collections.

### firebase.js -

- [ ] **`firebase.js`:** This file sets up Firebase for authentication and database management in the application. It ensures that the Firebase app is properly configured and ready to use authentication and Firestore services.

### utils.js -

- [ ] **`utils.js`:** This file provides essential utility functions and middleware for user authentication and authorization in the application. It ensures that only authenticated users with the appropriate permissions can access certain routes or perform specific actions.



## Frontend Structure 🖼 -

### Components

- [ ] **`AdminRoute.js`, `CheckoutSteps.js`, `LoadingBox.js`, `MessageBox.js`, `Product.js`, `ProtectedRoute.js`, `Rating.js`, `SearchBox.js`**.

### Screens -

- [ ] **`CartScreen.js`, `DashboardScreen.js`, `HomeScreen.js`, `HowToScreen.js`, `OrderHistoryScreen.js`, `OrderListScreen.js`, `OrderScreen.js`, `PaymentMethodScreen.js`, `PlaceOrderScreen.js`, `ProductEditScreen.js`, `ProductListScreen.js`, `ProductScreen.js`, `ProfileScreen.js`, `SearchScreen.js`, `ShippingAddressScreen.js`, `SigninScreen.js`, `SignupScreen.js`, `AboutUsScreen.js`**.

### app.js -

- `App.js`: This file is the entry point for your React frontend application- controls the frontend structure and behavior. It defines routes using `react-router-dom` for different pages/screens of the application and orchestrates the structure and behavior of your frontend application.

### store.js

- [ ] **`store.js`:** This file defines and manages the application's global state management using React context and reducers. It essentially manages the global state of the application, handling user authentication, cart management, and related operations.

### index.js

- [ ] **`index.js`:** This file serves as the entry point for the React application. It wraps the `<App />` component with providers such as `StoreProvider`, `HelmetProvider`, and `PayPalScriptProvider`.

Here's an example of how HelmetProvider and react-helmet might be use in the app:
```
// Import necessary dependencies
import { Helmet, HelmetProvider } from 'react-helmet-async';

// Wrap your entire application with HelmetProvider in index.js
ReactDOM.render(
  <HelmetProvider>
    <App />
  </HelmetProvider>,
  document.getElementById('root')
);

// In any component where you want to dynamically change document head elements, use Helmet component
const MyComponent = () => {
  return (
    <div>
      {/* Use Helmet component to set document title */}
      <Helmet>
        <title>My Page Title</title>
        {/* Add other head elements like meta tags */}
        <meta name="description" content="This is my page description" />
      </Helmet>
      {/* Your component JSX */}
      <h1>Hello, World!</h1>
    </div>
  );
};
```

 
## Components vs Screens 🥇 -

### 🗂 Components -

Components are reusable building blocks that encapsulate a piece of UI functionality. They promote code reusability and maintainability by allowing you to create modular pieces of code that can be used across different parts of your application.

### 📁 Screens -

Screens are typically higher-level components that represent entire pages or views within your application. They often contain multiple components and handle more complex logic related to rendering and managing UI state.





<br>

## 💵 Paypal API <img align="center" height="60px" src="https://github.com/shanibider/ANASTACIA-MERN-ECOMMERCE-WEBSITE/assets/72359805/1cf2f26b-937f-4eff-950d-a940409e14a9"> -

### Paypal Sandbox test accounts -
![paypalapi](https://github.com/shanibider/ANASTACIA-MERN-ECOMMERCE-WEBSITE/assets/72359805/c4790512-1e54-4b9f-a240-07d336ab2d6b)


### 💲Demo Payment via <img height="50px" align="center" src="https://github.com/shanibider/ANASTACIA-MERN-ECOMMERCE-WEBSITE/assets/72359805/acfd6955-7866-467e-8e13-d168da6bfc00"> -

To experience the payment process with PayPal, you can use our demo feature. Follow these steps to make a demo payment:

1. **Visit the Demo Payment Page**: Navigate to the payment page.
2. **Login with Demo Credentials**: Use the provided demo username and password to access the demo environment.
3. **Initiate Payment**: Enter the demo payment section and select PayPal as the payment method.
4. **Complete Payment**: Follow the instructions to proceed with the demo payment through PayPal.

### **Demo Credentials <img height="50px" align="center" src="https://github.com/shanibider/ANASTACIA-MERN-ECOMMERCE-WEBSITE/assets/72359805/04120fb3-c483-41dc-8710-f4cd74f11771">:**
- [ ] Username: `sb-gt6zp25024137@personal.example.com`
- [ ] Password: `W=Flx8z1`

By following these steps, you can simulate a payment transaction using PayPal without the need to create a real order💰. This allows you to experience the payment process and familiarize yourself with its functionality.


<br>


## The application follows these key patterns 🏆 -
THe architecture focuses on structured state management, components, and effective handling of side effects and navigation in a React app.

1. 🚀**State Management:**
   - Uses `useReducer` for organized state management.

2. 🚀**Global State:**
   - Manages global state for properties like `cart`, `userInfo`, `loading`, and `error`.

3. 🚀**Side Effects:**
   - Handles side effects, such as data fetching, with `useEffect`.

4. 🚀**Component Structure:**
   - Organizes the app into modular components, promoting a component-based architecture.

5. 🚀**React Router:**
   - Implements React Router for navigation.

6. 🚀**Conditional Rendering:**
   - Conditionally displays UI elements based on the application's state.

7. 🚀**Authentication Handling:**
   - Manages user authentication through global state.

8. 🚀**Middleware (`logger`):**
   - Uses a middleware function (`logger`) for state change logging.

9. 🚀**RESTful API Calls:**
   - Utilizes Axios for making API calls to a backend server.




<br>

## Ecommerce Website Preview :
### Demo Website

👉 Demo : 

<img src="https://user-images.githubusercontent.com/72359805/230923394-09e38358-b620-4bc1-a3f0-f2620eb510c0.mp4" alt=" Click here for Demo" width="300">



###### Home Page
![home](https://user-images.githubusercontent.com/72359805/230922135-b29b6c60-afd5-48ec-9fc4-d5e2e44a085a.PNG)

###### Product out of stock alert

![out of stock alert](https://github.com/shanibider/Anastacia-Ecommerce-React-Website/assets/72359805/58f0ea96-a220-47e3-a682-9e683fd04557)

###### Detailed Product View
![product](https://user-images.githubusercontent.com/72359805/230922485-2206ef84-98bf-42fa-8365-c2e0c192ade0.PNG)

###### Shopping Cart 
![cart](https://user-images.githubusercontent.com/72359805/230922510-57753e47-0df0-4e5e-8fe4-a7bbb61e810b.PNG)

###### Preview order  
![place order](https://user-images.githubusercontent.com/72359805/230922503-9a7df6f3-7203-43ac-87a8-a6453476bcde.PNG)


<br>

### Place an order via PayPal API:  

###### Place order  
![place order paypal](https://github.com/shanibider/Anastacia-Ecommerce-React-Website/assets/72359805/37f789f4-a0e5-4870-b250-89228553b3dc)

###### Checkout steps - shipping
![shipping](https://github.com/shanibider/Anastacia-Ecommerce-React-Website/assets/72359805/7986aa25-75fd-4cfa-b234-3e7e0858f897)

###### Checkout steps - payment method
![payment method](https://github.com/shanibider/Anastacia-Ecommerce-React-Website/assets/72359805/6207865a-b308-41b7-bb26-7ca75bcbe39c)

###### Place an order with demo user via PayPal
![place order paypal  demo 2](https://github.com/shanibider/Anastacia-Ecommerce-React-Website/assets/72359805/e98e741a-9e6a-44fb-bc25-02ff4215987b)

###### Paid order
![place order paypal  demo 3](https://github.com/shanibider/Anastacia-Ecommerce-React-Website/assets/72359805/86d4ae07-2cd3-474f-a51d-7e77d8c11cff)


<br>

## User functionality:

###### User order history
![order history](https://user-images.githubusercontent.com/72359805/230922850-bf35dce7-eaea-4ff2-9d95-741a9b0edb77.PNG)

###### User edit profile
![edit profile](https://github.com/shanibider/Anastacia-Ecommerce-React-Website/assets/72359805/422c48d0-a035-4e0c-91b0-711b9918a2b0)

<br>

## Admin functionality:

###### Admin dashboard displaying real-time metrics: registered users, order count, and financial performance through total money orders
![Admin info](https://user-images.githubusercontent.com/72359805/230922856-8218eadd-3c44-4689-8710-5757060e9177.PNG)

###### Products list
![proudcts list](https://user-images.githubusercontent.com/72359805/230922896-699796f4-1268-441f-b5c1-417273d1aec9.PNG)

######  Edit product 
![edit product](https://user-images.githubusercontent.com/72359805/230922907-bb0abeb0-6cad-42d3-9629-238447091dbd.PNG)

######  All users orders list
![orders list](https://user-images.githubusercontent.com/72359805/230922948-31ea760e-cccf-4d6c-b4ce-9b9b5d964419.PNG)

<br> 

###### Search bar
![search](https://user-images.githubusercontent.com/72359805/230922982-83d66ae1-cc6d-4cca-b5be-b21c1f7c7628.PNG)


###### about us page
![about us](https://user-images.githubusercontent.com/72359805/230923017-44b75026-def1-40bf-af5f-7d8f2d76ee1b.PNG)

![about us2](https://user-images.githubusercontent.com/72359805/230923021-ee53f35c-7676-485a-93a7-5f53cb9eaec9.PNG)

###### Spinner Component showing the loading state

![loadingBox component](https://github.com/shanibider/Anastacia-Ecommerce-React-Website/assets/72359805/51546c31-6154-4802-9eed-ea4128915cd9)





<br>

## Setup Instructions
1. Clone the repository: `git clone [repository_url]`
2. Set up the MongoDB database and Firebase authentication.
3. Configure environment variables.
4. Run Backend-
```
$ cd our-website
$ cd backend
$ npm i
$ npm start
```

5. Run Frontend-
   
open new terminal
```
$ cd our-website
$ cd frontend
$ npm i
$ npm start
```

Seed Users and Products (backend)-
Run this on browser: http://localhost:5000/api/seed
(Will returns admin email, password and sample products).

Admin Login-
Run http://localhost:3000/signin

<br>

## 🔗 Connect with me 👩‍💻😊
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shani-bider/)
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://shanibider.github.io/Portfolio/)
[![gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shanibider@gmail.com)


<footer>
<p style="float:left; width: 20%;">
Copyright © Shani Bider, 2024
</p>
</footer>

## License

This project is licensed under the MIT License.
