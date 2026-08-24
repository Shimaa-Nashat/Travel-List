# ✈️ Travel List

A simple and interactive **Travel List** web application built with **React.js**.
It helps you organize the items you need to pack before traveling and keeps track of what has already been packed.

[🌐 Live Demo](https://travel-list-five-amber.vercel.app/)
## 🚀 Features

* ➕ Add items to your travel packing list
* 🗑️ Delete items from the list
* ✅ Mark items as packed
* 🔄 Unpack items when needed
* 📊 Track the number of items packed
* 📈 Display the packing progress
* 📱 Responsive and user-friendly interface

## 🛠️ Technologies

* **React.js**
* **JavaScript (ES6+)**
* **HTML5**
* **CSS3**
* **Create React App**
* **React Hooks**

## 📂 Project Structure

```text
Travel-List/
│
├── public/
│   ├── index.html
│   └── ...
│
├── src/
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── ...
│
├── package.json
├── package-lock.json
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Travel-List.git
```

### 2. Navigate to the project folder

```bash
cd Travel-List
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm start
```

## 📖 How to Use

1. Enter the item you want to take with you.
2. Select the quantity.
3. Click **Add** to add the item to your list.
4. Check the checkbox when you pack an item.
5. Use the delete button to remove an item.
6. Use the sorting options to organize your list.
7. Check the statistics at the bottom to see your packing progress.

## 📊 Packing Statistics

The application displays useful statistics such as:

* Total number of items
* Number of packed items
* Percentage of items already packed

Example:

```text
💼 You have 10 items on your list, and you already packed 6 (60%).
```

## 🎯 Project Purpose

This project was created as a practical React.js project to practice:

* Components
* Props
* State management
* Event handling
* Rendering lists
* Conditional rendering
* Array methods such as `map()` and `filter()`
* Passing data between components

## 🧠 React Concepts Used

### Components

The application is divided into reusable React components.

### Props

Data is passed from parent components to child components using props.

### State

React state is used to manage the packing list and user interactions.

### Array Methods

The project uses JavaScript array methods such as:

```javascript
map()
filter()
```

For example, packed items can be calculated with:

```javascript
const packedItems = items.filter((item) => item.packed === true);
```

## 👩‍💻 Author

**Shimaa Nashat**

⭐ If you like this project, consider giving it a star!
