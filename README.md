# React Accordion

A simple and interactive **Accordion component built using React.js**.
This project demonstrates how to manage component state using React `useState` and implement both **single selection** and **multiple selection** modes.

## Features

* Expand and collapse accordion items
* Single selection mode
* Multiple selection mode
* Dynamic accordion data
* React state management using `useState`
* Clean and responsive user interface

## Technologies Used

* React.js
* JavaScript (ES6+)
* HTML5
* CSS3

## React Concepts Used

### `useState`

The project uses React's `useState` hook to manage:

* Currently selected accordion item
* Multiple selected accordion items
* Single selection / multiple selection mode

### Single Selection

In single selection mode, only **one accordion item** can be open at a time.

When another item is selected, the previously opened item is closed.

### Multiple Selection

In multiple selection mode, **multiple accordion items** can be opened at the same time.

The selected item IDs are stored in an array and updated when the user clicks an accordion item.

## Project Structure

```text
Accordian/
│
├── public/
│
├── src/
│   ├── data.js
│   ├── Accordion.js
│   ├── styles.css
│   └── ...
│
├── package.json
├── package-lock.json
└── README.md
```

## How It Works

The accordion uses React state to keep track of the selected items.

For single selection:

```javascript
const [selected, setSelected] = useState(null);
```

For multiple selection:

```javascript
const [multiple, setMultiple] = useState([]);
```

When the user clicks an accordion item, the application checks whether **single selection** or **multiple selection** is enabled and updates the state accordingly.

## Installation

Clone the repository:

```bash
git clone https://github.com/ushaerikireddy-web/Accordian.git
```

Go to the project folder:

```bash
cd Accordian
```

Install dependencies:

```bash
npm install
```

Start the application:

```bash
npm start
```

The application will run at:

```text
http://localhost:3000
```

## Learning Outcomes

Through this project, I practiced:

* React functional components
* `useState` hook
* Event handling
* Conditional rendering
* Arrays and array methods
* Managing single and multiple selections
* Creating reusable UI components

## Project Purpose

This project was created to practice **React state management and interactive UI components**, especially the difference between handling a single selected item and multiple selected items.

## Author

**Usha Erikireddy**

GitHub:
https://github.com/ushaerikireddy-web

LinkedIn:
https://www.linkedin.com/in/usha-erikireddy/
