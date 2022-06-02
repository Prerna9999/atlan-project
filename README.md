# ATLAN PROJECT



## 👨‍🔧 Tech Stack

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

## OVERVIEW
It is basically an SQL editor web application where any user can run any SQL queries. There are some predefined table stored which user can use for running any SQL queries.

Users can see query runtime in milliseconds(ms).


## SOME Predefined SQL Queries

- `select * from customers`
- `select * from categories`
- `select * from employee_territories`
- `select * from order_details`
- `select * from orders`
- `select * from products`
- `select * from regions`
- `select * from shippers`
- `select * from suppliers`
- `select * from territories`

## ⏱ Page Load Time

Page Load time of this website in desktop is of approx 1.6s.

I calculated the performance and load time of this website using the BrowserStack SpeedLab tool.


### [BrowserStack Report](https://www.browserstack.com/speedlab)

<img width="689" alt="image" src="https://user-images.githubusercontent.com/85393240/171674771-d35c9f53-1591-4971-b340-8f8e7736485b.png">

## Steps I took to optimize the page load time

Used code-splitting with React.Lazy() and Suspense to lazy load the components and split javaScript into multiple chunks using Dynamic runtime Imports for faster page load.

Used React.Memo() to optimize the render performance of functional components.

Used PurgeCSS to tree-shake unused styles and optimize my final build size.

Used Lighthouse DevTools Extension to find the performance issues and fix them using their actionable suggestion.

Used vercel to deploy this website to leverage its Vercel Edge Network compression that results in the better performance.

## Available Scripts

In the project directory, you can run:

### `npm start`
 For starting a web app
### `npm build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

## Dependencies
@testing-library/jest-dom: "^5.11.4",
@testing-library/react: "^11.1.0",
@testing-library/user-event: "^12.1.10",
alasql: "^1.7.3",
react: "^17.0.2",
react-ace: "^9.5.0",
react-dom: "^17.0.2",
react-helmet: "^6.1.0",
react-hot-toast: "^2.1.1",
react-json-to-csv: "^1.0.4",
react-scripts: "4.0.3",
react-table: "^7.7.0",
web-vitals: "^1.0.1"
