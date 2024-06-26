# Worldwise

Worldwise is a web application that allows users to track the cities and country they have visited. It provides features such as adding, reading, updating, and deleting visited locations, along with real-time geolocation tracking.

![Worldwise Logo](public/logo.png)

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Directory Structure](#directory-structure)
- [Dependencies](#dependencies)
- [License](#license)

## Demo

Check out a live demo of Worldwise: [Worldwise Demo](https://your-demo-url.com)

![Worldwise HomePage](https://raw.githubusercontent.com/bharani-developer/Worldwise/main/public/worldwise1.png)
![Worldwise Pricing](https://raw.githubusercontent.com/bharani-developer/Worldwise/main/public/worldwise2.png)
![Worldwise Product](https://raw.githubusercontent.com/bharani-developer/Worldwise/main/public/worldwise3.png)
![Worldwise Login](https://raw.githubusercontent.com/bharani-developer/Worldwise/main/public/worldwise4.png)
![Worldwise Map](https://raw.githubusercontent.com/bharani-developer/Worldwise/main/public/worldwise5.png)
## Features

- User authentication and login
- Track cities and states visited
- Real-time geolocation tracking
- Add, read, update, and delete visited locations
- Responsive design

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Worldwise.git
    cd Worldwise
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Start the development server:
    ```bash
    npm run dev
    ```

4. Open your browser and navigate to `http://localhost:8080`.

## Usage

### Homepage

The homepage provides an option to start tracking. Click on "Start Tracking Now" to navigate to the login page.

![Homepage Screenshot](public/img-2.jpg)

### Pricing

The pricing page displays the different pricing options available for using the application.

### Products

The products page lists the available products.

### Login

Users can log in to access their visited cities and states. After logging in, users can add, update, and delete their visited locations.

### Visited Locations

Once logged in, users can view a list of cities and states they have visited. Users can add new visited locations and use their current position to update their visited locations in real-time.

## Directory Structure

+--- data
    |   cities.json
+--- dist
    +--- assets
        |   AppLayout-a9e6818a.css
        |   AppLayout-d3fb1271.js
        |   Homepage-979407c7.js
        |   Homepage-b9276e6f.css
        |   index-ab0bf52d.js
        |   index-d340e693.css
        |   Login-e0d292b8.js
        |   Login-f39ef3ff.css
        |   Logo-21773e58.js
        |   Logo-515b84ce.css
        |   PageNav-54b9dcc4.js
        |   PageNav-d3c5d403.css
        |   PageNotFound-1a64b5ee.js
        |   Pricing-85905c2c.js
        |   Product.module-02d70b80.js
        |   Product-cf1be470.css
        |   Product-e67713a1.js
    |   bg.jpg
    |   bharani.jpg
    |   icon.png
    |   img-1.jpg
    |   img-2.jpg
    |   index.html
    |   logo.png
    |   vite.svg
    |   worldwise1.png
    |   worldwise2.png
    |   worldwise3.png
    |   worldwise4.png
    |   worldwise5.png
+--- public
    |   bg.jpg
    |   bharani.jpg
    |   icon.png
    |   img-1.jpg
    |   img-2.jpg
    |   logo.png
    |   vite.svg
    |   worldwise1.png
    |   worldwise2.png
    |   worldwise3.png
    |   worldwise4.png
    |   worldwise5.png
+--- src
    +--- components
        |   AppNav.jsx
        |   AppNav.module.css
        |   BackButton.jsx
        |   Button.jsx
        |   Button.module.css
        |   City.jsx
        |   City.module.css
        |   CityItem.jsx
        |   CityItem.module.css
        |   CityList.jsx
        |   CityList.module.css
        |   CountryItem.jsx
        |   CountryItem.module.css
        |   CountryList.jsx
        |   CountryList.module.css
        |   Form.jsx
        |   Form.module.css
        |   Logo.jsx
        |   Logo.module.css
        |   Map.jsx
        |   Map.module.css
        |   Message.jsx
        |   Message.module.css
        |   PageNav.jsx
        |   PageNav.module.css
        |   Sidebar.jsx
        |   Sidebar.module.css
        |   Spinner.jsx
        |   Spinner.module.css
        |   SpinnerFullPage.jsx
        |   SpinnerFullPage.module.css
        |   User.jsx
        |   User.module.css
    +--- contexts
        |   CitiesContext.jsx
        |   FakeAuthContext.jsx
    +--- hooks
        |   useGeolocation.js
        |   useUrlPosition.js
    +--- pages
        |   AppLayout.jsx
        |   AppLayout.module.css
        |   Homepage.jsx
        |   Homepage.module.css
        |   Login.jsx
        |   Login.module.css
        |   PageNotFound.jsx
        |   Pricing.jsx
        |   Product.jsx
        |   Product.module.css
        |   ProtectedRoute.jsx
    |   App.jsx
    |   index.css
    |   main.jsx
|   .eslintrc.json
|   directory_tree.txt
|   index.html
|   package.json
|   package-lock.json
|   README.md
|   vite.config.js


## Dependencies

- `json-server`: ^0.17.3
- `leaflet`: ^1.9.3
- `react`: ^18.2.0
- `react-datepicker`: ^4.11.0
- `react-dom`: ^18.2.0
- `react-leaflet`: ^4.2.1
- `react-router-dom`: ^6.9.0
