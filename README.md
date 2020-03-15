# Table of Contents

- **[Getting Started](https://github.com/iamsainikhil/weather-react#-getting-started)**
- **[Motivation](https://github.com/iamsainikhil/weather-react#-motivation)**
- **[Technologies](https://github.com/iamsainikhil/weather-react#-technologies)**
- **[Challenges](https://github.com/iamsainikhil/weather-react#-challenges)**
- **[Architecture](https://github.com/iamsainikhil/weather-react#-architecture)**
- **[Roadmap](https://github.com/iamsainikhil/weather-react#-roadmap)**
- **[Contribution](https://github.com/iamsainikhil/weather-react#-contribution)**
- **[License](https://github.com/iamsainikhil/weather-react#-license)**
- **[Contact](https://github.com/iamsainikhil/weather-react#-contact)**
- **[Acknowledgements](https://github.com/iamsainikhil/weather-react#-acknowledgements)**
  - **[API](https://github.com/iamsainikhil/weather-react#api)**
  - **[3rd-party Libraries](https://github.com/iamsainikhil/weather-react#3rd-party-libraries)**
  - **[Icons](https://github.com/iamsainikhil/weather-react#icons)**
  - **[Styling](https://github.com/iamsainikhil/weather-react#styling)**
- **[Featured On](https://github.com/iamsainikhil/weather-react#-featured-on)**

# 🚀 Getting Started

**\*Follow the instructions describe in-detail **[here](https://www.notion.so/reactweather/Weather-React-Repo-Setup-Instructions-1a789c2e47f545ceb87062d171a66b6b)** to set up the project locally on your machine.\***

> _These instructions are very important to avoid the **Blank Page** issue when running the application on `http://localhost:3000`._

## 💡 Motivation

I started learning React in February 2020 and thought of putting knowledge into reality by developing an application. I am interested in building an application that API resource-intensive to challenge writing efficient code keeping performance, UX, maintainability, scalability, and optimization.

There are so many weather-related applications out in the wild. So, the goal is to create a UI that is beautiful yet simple and effective for any user to use.

## 💻 Technologies

- This application is created with **[Create React App](https://create-react-app.dev/)**
- **[React](https://reactjs.org/)** _(v16.12)_
- Styling syntax was written in SCSS and using **[TailwindCSS](https://tailwindcss.com/)**
- There are bunch of scripts that run when you start application to compile `scss` to `css`

## 😢 Challenges

- First, I used the OpenWeatherMap API to fetch the weather forecast data. However, 5-day forecast data was not reliable i.e. _when a user on 14th March 2020 at 7:00 PM EST tries to fetch 5-day forecast data will get day forecast data starting 15th March 2020 at 12:00 AM UTC._ This posed a big problem of categorizing 5-day data into individual days since the data is not always consistent and is based on UTC and not the user timezone. Finally, I switched to Dark Sky API which is more reliable and provides a robust data model. However, there is a limit of `1000` calls/day.
- Dark Sky API needs a proxy server to send and receive a response which was easy in the development stage using a browser extension like **[this](https://chrome.google.com/webstore/detail/moesif-orign-cors-changer/digfbfaphojjndkpccljibejjbppifbc)** to enable CORS in the browser. However, I can't every user to install this extension in their browser to check the weather forecast. So, I overcome this issue temporarily for now using the `cors-anywhere` library which you can get more info by checking **[here](https://github.com/Rob--W/cors-anywhere)**.

## 📖 Architecture

### ❕ **Application Architecture Documentation will be added soon...**

## 🏎 Roadmap

- [ ] Build a proxy server using Express for Dark Sky API requests
- [ ] Unit Testing
- [ ] Refactoring Code
- [ ] Update Favorites UI
- [ ] Add documentation for components using **Storybook**
- [ ] Develop desktop application using **Electron**
- [ ] Develop Android and iOS app using **React Native**

## 🙌 Contribution

- Open pull request with improvements.
- If you have any new idea, check the **[feature request](https://github.com/iamsainikhil/weather-react/blob/master/.github/ISSUE_TEMPLATE/feature_request.md)** template to create a request.
- If you found any issue or a bug, check the **[bug report](https://github.com/iamsainikhil/weather-react/blob/master/.github/ISSUE_TEMPLATE/bug_report.md)** template to create a report.

## 📃 License

Have a look at the **[license file](https://github.com/iamsainikhil/weather-react/blob/master/LICENSE)** for details

## 📧 Contact

Whether you’d like to discuss a project, ask me about my website or simply say “hello”, I’d love to hear from you.

Email: **[contact@iamsainikhil.com](mailto:contact@iamsainikhil.com)**

## 😍 Featured On

- **[React.js Examples](https://reactjsexample.com/a-nice-weather-app-built-using-react/)**
- **[Morioh](https://morioh.com/p/fc5f51d76847)**

## 🙏 Acknowledgements

See the **[Acknowledgements](https://github.com/iamsainikhil/weather-react/wiki/Acknowledgements)** page on the wiki for a list of Acknowledgements for Weather React codebase.
