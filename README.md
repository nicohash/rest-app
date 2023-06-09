# Weather Rest App

A simple rest app build with React and Flask

React was used to build a beautiful and functional weather web-app.
Flask handles the API operations for us.



Our project is designed to run locally. However we have created a live server implementation for the React frontend without the API from Flask.
It can be accessed at https://weathersunrise.de.cool/.

We could not include the API at server level because we would have needed a paid subscription from our provider for this.

The React frontend can also be used without the API. More info on this [here] (frontend/README.md)

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Installation

```zsh
git clone https://github.com/nicohash/weather-rest-app.git ~/weather-rest-app
cd ~/weather-rest-app
```

## Usage

```zsh
python -m flask run
```

### Hint

U may need to use the python3 command instead depending on your configuration

## APIs used in this project

- [Open Weather Map](https://openweathermap.org/current)
- [Sunset and Sunrise](https://sunrise-sunset.org/api)

## 
