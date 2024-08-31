

---

# React Dashboard App

This project is a simple React.js dashboard that displays two charts: a line chart comparing "Sales vs Orders" and a pie chart showing the "Portion of Sales" for different stores. The charts are created using `react-chartjs-2` and `Chart.js`.

## Table of Contents

- [Installation](#installation)
- [Folder Structure](#folder-structure)
- [Usage](#usage)
- [Components](#components)
- [Customization](#customization)
- [License](#license)

## Installation

To set up the project locally, follow these steps:

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/react-dashboard-app.git
   cd react-dashboard-app
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

The app will be available at `http://localhost:3000`.

## Folder Structure

The project structure is as follows:

```plaintext
my-dashboard-app/
│
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   └── Dashboard.jsx
│   ├── App.jsx
│   ├── index.js
│   ├── App.css
│   └── index.css
├── package.json
└── ...
```

- public/`: Contains the HTML file and other static assets.
- `src/`: Contains all the source code.
  - `components/`: Contains React components.
  - `App.jsx`: Main application component.
  - `index.js`: Entry point for the React application.
  - `App.css`: Styles for the application.
  - `index.css`: Global styles.

## Usage

Once the development server is running, open your web browser and navigate to `http://localhost:3000`. You will see a dashboard with a line chart and a pie chart.

- The line chart shows a comparison of "Sales vs Orders" over time.
- The pie chart shows the "Portion of Sales" for two stores: WooCommerce Store and Shopify Store.

## Components

### `Dashboard.jsx`

This component renders the dashboard, including both the line chart and pie chart. It uses `react-chartjs-2` for integrating `Chart.js` into React.

- Line Chart: Displays the sales and orders over time.
- Pie Chart: Displays the distribution of sales between two stores.

### `App.jsx`

This is the main component that includes the `Dashboard` component.

### `index.js`

This file is the entry point for the React application and renders the `App` component into the root element of the HTML.

## Customization

You can customize the charts and the overall look of the dashboard:

1. Update Chart Data:

   Modify the `lineChartData` and `pieChartData` objects in `Dashboard.jsx` to change the data displayed in the charts.

2. Change Chart Colors:

   Update the `backgroundColor` and `borderColor` properties in the `datasets` to change the colors of the charts.

3. Styling:

   Modify `App.css` and `index.css` to change the appearance of the dashboard.

