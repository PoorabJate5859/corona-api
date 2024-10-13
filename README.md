# COVID-19 Statistics Web App

A simple, responsive web application built using **HTML**, **CSS**, and **JavaScript** that fetches and displays real-time COVID-19 statistics. The app allows users to view global COVID-19 stats or search for country-specific data using the [Disease.sh API](https://disease.sh/).

## Table of Contents
- [Features](#features)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features

- View **global COVID-19 statistics** including total cases, deaths, and recovered.
- **Search for any country** to view COVID-19 statistics specific to that country.
- Responsive design that works on both desktop and mobile devices.
- Fetches live data from the **Disease.sh API**.
- Error handling for invalid country searches.

## Screenshots

### Global Statistics View
![image](https://github.com/user-attachments/assets/5495f211-9a62-4c5c-8424-eb0425bd655e)


### Country Search View
![image](https://github.com/user-attachments/assets/5a0e61d4-c7bf-4703-8e2d-93dee0065ca9)


## Installation

To run this project locally, follow these steps:

1. **Clone this repository:**
   ```bash
   git clone https://github.com/PoorabJate5859/corona-api.git
   ```

2. **Navigate to the project folder:**
   ```bash
   cd corona-api
   ```

3. **Open the project in a browser:**
   - Open `index.html` in your preferred web browser.

   Alternatively, you can set up a simple HTTP server (optional) to run the project.

   Example using **VS Code**:
   - Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension.
   - Right-click `index.html` and select "Open with Live Server."

## Usage

1. **Global Data**: Click the "Global Data" button to display worldwide COVID-19 statistics.
2. **Country Data**: Click the "Country Data" button to search for a country, enter the country name, and click "Search" to display the stats for that country.
3. **Live Updates**: All data is fetched live from the [Disease.sh API](https://disease.sh/).

## Technologies Used

- **HTML**: For page structure.
- **CSS**: For styling the app's user interface.
- **JavaScript**: For fetching data from the API and dynamically updating the UI.
- **Disease.sh API**: For fetching real-time COVID-19 data.

## Contributing

Contributions are welcome! If you'd like to improve this project:

1. **Fork the repository**.
2. **Create a new feature branch**: 
   ```bash
   git checkout -b feature-name
   ```
3. **Commit your changes**: 
   ```bash
   git commit -m 'Add feature'
   ```
4. **Push to the branch**: 
   ```bash
   git push origin feature-name
   ```
5. **Submit a pull request** with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
```
