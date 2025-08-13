# jack-henry-weather-api
## About
Jack Henry Weather API is an application that takes in latitude (lat) and longitude (long) coordinates (in decimal form) &amp; returns a short forecast for the area and a characterization of the temperature

## Getting Started
To get a local copy instance up and running follow these steps:

### Prerequisites

* Install Golang (if using MacOS)
  ```sh
  brew install go
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/<YOUR_GITHUB_USERNAME>/repo_name.git
   ```
2. Install program dependencies
   ```sh
   go get github.com/gorilla/mux
   go get github.com/stretchr/testify
   go get github.com/jarcoal/httpmock
   ```
3. Run the program on localhost
   ```sh
   go run main.go
   ```

<!-- USAGE EXAMPLES -->
## Usage
Type in the following into your web broser:
```
http://localhost:8080/getWeather/37.7749/-122.4195
```
Response in the browser:
```
Light Rain: cold
```
