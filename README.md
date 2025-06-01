
# 🛒 E-commerce App

A responsive e-commerce application built using **React** and **Redux**, featuring product browsing, user authentication, cart management, and filtering by category.

## 🚀 Features

- User Registration and Login
- Product Listing
- Shopping Cart Functionality
- Filtering Products by Category
- Redux for State Management
- Responsive UI Design

## 🛠️ Technologies Used

- React
- Redux
- JavaScript (JSX)
- HTML5 & CSS3

## 📦 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/karthikkharv/E-commerce.git
   cd E-commerce
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Start the development server:**

   ```bash
   npm start
   ```

   Visit `http://localhost:3000` in your browser.

## 🧭 Features in Detail

### 🧾 Authentication

- ![Screenshot (61)](https://github.com/user-attachments/assets/d67805e9-5dec-4f5e-a3ae-31467f4c075f)
- Users can **register** a new account.

- ![Screenshot (60)](https://github.com/user-attachments/assets/33b6c12b-c73f-477e-950a-9a7d8c1f3dda)
- Secure **login** with stored credentials.
- User session persists across the app.

### 🛍️ Product Listing
 ![Screenshot (63)](https://github.com/user-attachments/assets/dce6b224-b723-455e-a2f1-4998bd09a79e)

- Products displayed in a grid layout.
- Each product shows an image, name, price, and "Add to Cart" button.
### 🛒 Cart Functionality
![Screenshot (62)](https://github.com/user-attachments/assets/0c633fef-e566-4a3b-8a7c-fa1834d9a393)

- Items can be added or removed from the cart.
- Cart persists with Redux state.
- Total price calculated dynamically.


### 🧮 Category Filtering
![Screenshot (66)](https://github.com/user-attachments/assets/9604b386-e5c9-4866-8015-7d0fbd353dd4)

- Filter products by **category name** using dropdown or sidebar buttons.
- Dynamic updates to the product grid.

- Uses Redux to manage filtered product state.

Example:

```jsx
const filteredProducts = allProducts.filter(
  (product) => product.category === selectedCategory
);

```

### 🧠 Redux State Management

- Global state includes:
  - `auth` (user login status)
  - `cart` (items, quantity, total)
  - `products` (all and filtered products)

## 📂 Folder Structure

```bash
E-commerce/
├── public/
├── src/
│   ├── components/        # Reusable UI components
│   ├── pages/             # Page components (Home, Login, Register)
│   ├── redux/             # Redux actions, reducers, store
│   ├── App.js             # Main app component
│   └── index.js           # Entry point
├── package.json
└── README.md
```

## 🤝 Contributing

Contributions are welcome! Please fork the repo and open a pull request.

## 📄 License

This project is open-source and available under the MIT License.
