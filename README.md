workshop
# e-commers.html
This HTML, CSS, and JavaScript project creates a responsive product card layout using the Fake Store API. JavaScript fetches product data asynchronously and dynamically displays each product’s image, price, description, and an “ADD TO CART” button. CSS styles the cards using Flexbox for a clean and responsive design.
# 🛍️ Fake Store Product Cards

A simple web project that fetches product information from the **Fake Store API** and displays it as attractive product cards using HTML, CSS, and JavaScript.

## 🚀 Features

* Fetches product data from an external API
* Displays product images
* Shows product prices
* Displays product descriptions
* Includes an **ADD TO CART** button
* Responsive card layout using CSS Flexbox
* Uses JavaScript `async/await` for API handling

## 🛠️ Technologies Used

* **HTML5** – Creates the webpage structure
* **CSS3** – Styles the product cards and layout
* **JavaScript** – Fetches and displays API data
* **Fake Store API** – Provides the product information

## 📂 Project Structure

```text
project/
│
└── index.html
```

## ⚙️ How It Works

1. The webpage loads the HTML structure.
2. JavaScript calls the Fake Store API using `fetch()`.
3. The API response is converted into JSON.
4. A loop goes through each product.
5. Product information is dynamically inserted into the `container` div.
6. CSS styles each product as a card.

## ▶️ How to Run

1. Save the code as `index.html`.
2. Open the file in a web browser.
3. Make sure you have an active internet connection because the project uses an external API.
4. The products will automatically appear on the page.

## 🔗 API Used

Fake Store API:

https://fakestoreapi.com/products

## 📸 Output

The webpage displays multiple product cards containing:

* Product image
* Product price
* Product description
* ADD TO CART button

## 🔮 Future Improvements

* Implement actual cart functionality
* Add product titles and categories
* Add quantity controls
* Add search and filter options
* Add a shopping cart page
* Improve mobile responsiveness
* Add loading and error messages

workshop2
  # 👟 Shoe Brand Product Showcase

A simple frontend web project that displays multiple shoe-brand products in attractive product cards. The project uses **HTML, CSS, and JavaScript** to dynamically generate the product cards from arrays containing brand names and image URLs.

## 🚀 Features

* Displays 20 shoe brands
* Dynamically creates product cards using JavaScript
* Displays product images from external URLs
* Shows brand name, price, description, and rating
* Includes a **BUY NOW** button
* Responsive card layout using CSS Flexbox
* Hover effects and box shadows for better UI
* Clean and simple product showcase design

## 🛠️ Technologies Used

* **HTML5** – Webpage structure
* **CSS3** – Styling and responsive layout
* **JavaScript** – Dynamic content generation
* **Flexbox** – Product card arrangement

## 📂 Project Structure

```text
shoe-product-showcase/
│
└── index.html
```

## ⚙️ How the Project Works

### 1. Brand Names Array

The JavaScript code stores multiple shoe brands in an array:

```javascript
brandNames = ["NIKE", "WOODLAND", "ADDIDAS", "PUMA", ...]
```

### 2. Images Array

An array contains image URLs corresponding to each shoe brand:

```javascript
images = ["image-url-1", "image-url-2", "image-url-3", ...]
```

### 3. Dynamic Card Generation

A `for` loop iterates through the arrays and creates a product card for every brand.

```javascript
for (i = 0; i <= 20; i++) {
    // Product card generation
}
```

### 4. DOM Manipulation

JavaScript uses `innerHTML` to dynamically insert the generated cards into the container:

```javascript
document.getElementById("box").innerHTML += `...`
```

### 5. CSS Styling

CSS is used to create:

* Card borders
* Rounded corners
* Box shadows
* Hover effects
* Responsive Flexbox layout
* Styled buttons
* Product image sizing

## 🎨 Product Card Contains

Each product card displays:

* 👟 Shoe image
* 🏷️ Brand name
* 💰 Price
* 📝 Description
* ⭐ Rating
* 🛒 BUY NOW button

## ▶️ How to Run

1. Copy the code into a file named `index.html`.
2. Save the file.
3. Open `index.html` in a web browser.
4. Make sure you have an internet connection because the shoe images are loaded from external URLs.
5. The product cards will be generated automatically.

## 🔮 Future Improvements

The project can be enhanced by adding:

* Search functionality
* Brand/category filters
* Different product prices
* Individual product descriptions
* Shopping cart functionality
* Product quantity selection
* Product detail pages
* Responsive navigation bar
* LocalStorage for cart data
* JavaScript-based rating system
* Checkout functionality

## 📚 Learning Outcomes

This project helped demonstrate practical understanding of:

* HTML structure
* CSS Flexbox
* CSS hover effects
* Arrays in JavaScript
* `for` loops
* Template literals
* DOM manipulation
* Dynamic HTML generation
* Working with external image resources

## 👩‍💻 Author

**Bhavya**

A beginner-friendly frontend project created to practice **HTML, CSS, and JavaScript** through a real-world e-commerce-style product showcase.


## 👩‍💻 Author

**Bhavya**

A beginner-friendly JavaScript project demonstrating API fetching, asynchronous programming, DOM manipulation, and responsive CSS layouts.
