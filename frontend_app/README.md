# BMI Calculator React App

## Overview
This is a simple Body Mass Index (BMI) calculator built as a React web application. Users can input their weight and height, and the app instantly calculates their BMI value. The calculated BMI is displayed along with the category it falls into (Underweight, Normal weight, Overweight, or Obesity), providing immediate and clear feedback.

The application features a clean and modern interface with a light theme, primarily using blue (`#3b82f6`) and cyan (`#06b6d4`) accents for a professional appearance.

## Features
- **BMI Calculation:** Input your weight (kg/lb) and height (cm/in), and get your BMI calculated instantly.
- **BMI Categories:** Displays which category your BMI falls into:
  - Underweight
  - Normal weight
  - Overweight
  - Obesity
- **Responsive UI:** Modern layout, centered card interface, and mobile-friendly design.
- **Clear Feedback:** Easy to read results and immediate feedback on input.

## Usage / How to Run

### Prerequisites
- Node.js (LTS version recommended)
- npm or yarn (package manager)

### Local Development
1. **Navigate to the Project:**
    ```sh
    cd bmi-calculator-8278-8287/frontend_app
    ```

2. **Install Dependencies:**
    ```sh
    npm install
    ```
    or (if using yarn):
    ```sh
    yarn
    ```

3. **Start the Development Server:**
    ```sh
    npm start
    ```
    or
    ```sh
    yarn start
    ```
    By default, this will serve the application on [http://localhost:3000](http://localhost:3000).

### Environment Variables
The following environment variables are supported (from `.env`). For this simple calculator, these are typically not required, but may be used for advanced deployments:
- `REACT_APP_API_BASE`
- `REACT_APP_BACKEND_URL`
- `REACT_APP_FRONTEND_URL`
- `REACT_APP_WS_URL`
- `REACT_APP_NODE_ENV`
- `REACT_APP_NEXT_TELEMETRY_DISABLED`
- `REACT_APP_ENABLE_SOURCE_MAPS`
- `REACT_APP_PORT`
- `REACT_APP_TRUST_PROXY`
- `REACT_APP_LOG_LEVEL`
- `REACT_APP_HEALTHCHECK_PATH`
- `REACT_APP_FEATURE_FLAGS`
- `REACT_APP_EXPERIMENTS_ENABLED`

**Note:** You can create a `.env` file in the root of the `frontend_app` directory to override or specify any of these variables.

## How to Use the App
1. Enter your height and weight into their respective fields.
2. Press the "Calculate BMI" button.
3. Your BMI and its category will be shown below the form.

The BMI calculation uses the standard formula:
- _BMI = weight (kg) / [height (m)]²_

## Style Guide
- **Theme:** Light mode by default
- **Primary color:** #3b82f6
- **Accent color:** #06b6d4
- **Typography:** Clear, modern sans-serif fonts
- **Layout:** Centered input card, responsive to both desktop and mobile devices.

## Project Structure
```
bmi-calculator-8278-8287/
  ├─ frontend_app/
  │    ├─ README.md  # (This file)
  │    ├─ ...        # App source files (components, css, etc.)
  ├─ README.md       # Top-level project intro
  ...
```

## Contributing
- Fork this repository or clone it locally.
- Create a branch for your feature or bugfix.
- Submit a pull request describing your changes.

## License
MIT License (suggested; see main project LICENSE if present).

---
This README was generated to provide an introduction and clear setup/use instructions for the BMI Calculator React app.
