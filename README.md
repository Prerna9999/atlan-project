# ATLAN PROJECT



## 👨‍🔧 Tech Stack

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)


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


Users can see query runtime in milliseconds(ms).

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
