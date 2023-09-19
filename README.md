# MyCommodityPriceChart

## Introduction

Welcome to MyCommodityPriceChart! This React application is designed to provide users with insightful commodity price data through an interactive and responsive AreaChart powered by Recharts. Whether you're monitoring commodity prices for investment decisions or just exploring market trends, this app has you covered. MyCommodityPriceChart offers various features to enhance your data visualization experience.

## Key Features

- **Interactive Data Visualization:** MyCommodityPriceChart employs a responsive AreaChart that allows you to explore commodity price data with ease.

- **Time Range Filtering:** Analyze data within your desired time frame by selecting from three distinct options: Last 1 Month, Last 24 Hours, or Last 7 Days.

- **Data Input and Tracking:** Users can contribute to the dataset by adding new data points through a user-friendly input form. This feature enables you to maintain an up-to-date record of commodity prices.

- **Effortless Date Selection:** Use the date picker to conveniently select dates for new data points.

- **Responsive Design:** MyCommodityPriceChart adapts to various screen sizes, ensuring a seamless experience across devices.

## Prerequisites

Before you begin, please ensure that you have the following prerequisites installed on your system:

- [Node.js](https://nodejs.org/) (version 14 or higher)
- [npm](https://www.npmjs.com/) (version 6 or higher)

## Installation

To set up MyCommodityPriceChart on your local machine, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone <repository_url>
   ```

2. Navigate to the project directory:

   ```bash
   cd <project_directory>
   ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

## Usage

To launch the application and start exploring commodity price data, perform the following steps:

1. Initiate the development server:

   ```bash
   npm start
   ```

2. Open your preferred web browser and navigate to [http://localhost:3000](http://localhost:3000) to access the MyCommodityPriceChart application.

## Adding Data

Enhance the dataset by adding new data points to the chart:

1. Click the "Add Input" button to open an intuitive popup.

2. Input the date and value for the new data point.

3. Click the "Add Data" button to seamlessly integrate the new data into the chart.

## Filtering Data

Effortlessly filter data to match your analytical needs:

1. Utilize the dropdown menu to select your preferred time range: Last 1 Month, Last 24 Hours, or Last 7 Days.

2. Observe as the chart dynamically adjusts to display data within the selected time frame.

## Data Sources

- The initial dataset for the chart features randomly generated values over the past 30 days.

- Data is stored and retrieved from a Firebase Realtime Database using Axios, ensuring reliability and real-time updates.

## Dependencies

- [Recharts](http://recharts.org/): Used for creating interactive and visually appealing charts.

- [date-fns](https://date-fns.org/): Employs date manipulation functionalities for precise data analysis.

- [Axios](https://axios-http.com/): Utilized for seamless data fetching and management.

- [Modal](https://example-modal-library.com/): Enhances the user experience by presenting the input form as a modal.

## Credits

MyCommodityPriceChart was meticulously crafted by [Your Name] as a showcase of data visualization excellence using React and Recharts.

## License

This project is licensed under the MIT License. For additional details, refer to the [LICENSE.md](LICENSE.md) file included in the project repository.

## Feedback and Support

We appreciate your interest in MyCommodityPriceChart. If you encounter any issues, have suggestions for improvements, or require assistance, please don't hesitate to reach out to me at [vidhanvyrs@gmail.com](mailto:vidhanvyrs@gmail.com).

Happy charting, and may your commodity price analysis be both informative and rewarding!
