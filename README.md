<img src="./readme/title1.svg"/>

<br><br>

<!-- project philosophy -->
<img src="./readme/title2.svg"/>

> ExchangeXpert is a cutting-edge website platform designed to empower investors with AI-driven insights and tools. By analyzing stock news and using advanced machine learning algorithms.
>
> ExchangeXpert provides personalized stock recommendations, helping users make informed investment decisions.
> 
> The aim of the ExchangeXpert project is to provide investors with a powerful, AI-driven platform that simplifies the process of stock trading and investment. By leveraging cutting-edge artificial intelligence and machine learning technologies.

### User Roles
#### Admin
- As an admin, I want to view a list of all user accounts, so I can monitor user activity and manage the platform effectively.
- As an admin, I want to monitor all automated trading strategies set up by users, so I can ensure compliance with platform policies.
- As an admin, I want to send notifications to users about significant market events, so they are informed and can make timely decisions.

#### Normal User
- As a user, I want to view recommended stocks, so I can easily find investment opportunities.
- As a user, I want to set up automated trading strategies, so I can take advantage of market opportunities without constant monitoring.
- As a user, I want to receive notifications for significant market events and updates on my investments, so I can stay informed and take timely actions.

<br><br>
<!-- Tech stack -->
<img src="./readme/title3.svg"/>

###  ExchangeXpert is built using the following technologies:

- This project uses the [React library](https://reactjs.org/) for building user interfaces. React allows us to develop efficient and scalable front-end applications with its component-based architecture, making it ideal for real-time data updates and complex UI designs.
- [Laravel](https://laravel.com/) serves as the backend framework, handling API requests, authentication, and server-side logic. It ensures the application is secure, scalable, and maintainable.
- [MySQL](https://dev.mysql.com/doc/) A reliable, high-performance relational database used for storing user information, trading data, and historical stock data. It ensures data consistency and supports complex querying.
- [Prophet](https://facebook.github.io/prophet/) Prophet, initially developed by Facebook, is used for stock price forecasting. It provides a robust statistical model that supports both daily and long-term stock predictions.
- [Python](https://www.python.org/) Powers the backend trading bots, integrating with APIs like Alpaca to automate stock trading operations. Python's rich ecosystem for financial analysis and automation makes it ideal for building complex trading algorithms.
- [Alpaca](https://alpaca.markets/) Integrated as the broker for real-time stock data and executing buy/sell orders. Alpaca offers commission-free trading and a robust API that facilitates both paper trading and live trading. ExchangeXpert leverages Alpaca to fetch stock market data, manage portfolios, and automate trades through its trading bots.

<br><br>
<!-- UI UX -->
<img src="./readme/title4.svg"/>


> We designed Coffee Express using wireframes and mockups, iterating on the design until we reached the ideal layout for easy navigation and a seamless user experience.

- Project Figma design [figma](https://www.figma.com/file/LsuOx5Wnh5YTGSEtrgvz4l/Purrfect-Pals?type=design&node-id=257%3A79&mode=design&t=adzbABt5hbb91ucZ-1)


### Mockups
| Markets screen  | Stock Screen | Login Screen |
| ---| ---| ---|
| ![Markets](./assets/Merkets%20page.png) | ![Stock](./assets/Merkets%20page%20of%20one%20stock.png) | ![Login](./assets/login.png) |

<br><br>

<!-- Database Design -->
<img src="./readme/title5.svg"/>

###  Architecting Data Excellence: Innovative Database Design Strategies:

- Insert ER Diagram here
![Markets](./assets/database.png)

<br><br>


<!-- Implementation -->
<img src="./readme/title6.svg"/>

<br><br>


<!-- Prompt Engineering -->
<img src="./readme/title7.svg"/>

###  Mastering AI Interaction: Unveiling the Power of Prompt Engineering:

- This project uses advanced prompt engineering techniques to optimize the interaction with natural language processing models. By skillfully crafting input instructions, we tailor the behavior of the models to achieve precise and efficient language understanding and generation for various tasks and preferences.

<br><br>

<!-- AWS Deployment -->
<img src="./readme/title8.svg"/>

###  Efficient AI Deployment: Unleashing the Potential with AWS Integration:

- This project leverages AWS deployment strategies to seamlessly integrate and deploy natural language processing models. With a focus on scalability, reliability, and performance, we ensure that AI applications powered by these models deliver robust and responsive solutions for diverse use cases.

<br><br>

<!-- Unit Testing -->
<img src="./readme/title9.svg"/>

###  Precision in Development: Harnessing the Power of Unit Testing:

- This project employs rigorous unit testing methodologies to ensure the reliability and accuracy of code components. By systematically evaluating individual units of the software, we guarantee a robust foundation, identifying and addressing potential issues early in the development process.
<br><br>
<img src="./assets/test1.png"/>
<img src="./assets/test2.png"/>
<img src="./assets/test3.png"/>


<!-- How to run -->
<img src="./readme/title10.svg"/>

> To set up Coffee Express locally, follow these steps:

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [example](https://example.com)
2. Clone the repo
   git clone [github](https://github.com/your_username_/Project-Name.git)
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

Now, you should be able to run Coffee Express locally and explore its features.