let now = new Date();
console.log(now);
console.log(now.getDay());
console.log(now.getFullYear());
console.log(now.getMonth());

function formatDate() {
  let h5 = document.querySelector("h5");

  let days = ["Sun", "Mon", "Tue", "Wed", "Thu", "Fri", "Sat"];
  let day = days[now.getDay()];

  let months = [
    "Jan",
    "Feb",
    "Mar",
    "Apr",
    "May",
    "Jun",
    "Jul",
    "Aug",
    "Sep",
    "Oct",
    "Nov",
    "Dec"
  ];

  let month = months[now.getMonth()];
  let date = now.getDate();
  let hour = now.getHours();
  let minutes = now.getMinutes();

  // let apiKey = "5ef560c2739fa62b5e22bb83083603a3";
  // let city = "sydney";
  // let units = "metric";
  // let apiUrl = `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${apiKey}&&units=${units}`;

  // axios.get(apiUrl).then(showTemperature);
  function displayWeatherConditons(response) {
    let temperature = Math.round(response.data.main.temp);
    // let city = response.data.name;
    // let message = `It is ${temperature} degrees in ${city}`;
    // let h6 = document.querySelector("h6");
    // h6.innerHTML = message;
    // console.log(h6);
    // console.log(message);
    console.log("focus", response.data.main);
    let cityElement = document.querySelector("#city");
    let temperatureElement = document.querySelector("#temperature");
    cityElement.innerHTML = response.data.name;
    temperatureElement.innerHTML = `${temperature}°C`;
  }

  function search(city) {
    let apiKey = "5ef560c2739fa62b5e22bb83083603a3";

    let units = "metric";
    let apiUrl = `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${apiKey}&&units=${units}`;
    axios.get(apiUrl).then(displayWeatherConditons);
  }

  function handleSubmit(event) {
    // good code, need api integration here
    event.preventDefault();
    // let cityElement = document.querySelector("#city");
    let cityInput = document.querySelector("#city-input");
    // cityElement.innerHTML = cityInput.value;
    // make an API call to OpenWeather API
    // Once I get the HTTP response, we display the city name and the temperature
    let city = cityInput.value;
    search(city);
  }

  let searchForm = document.querySelector("#search-form");
  searchForm.addEventListener("submit", handleSubmit);

  function convertToFahrenheit(event) {
    event.preventDefault();
    // let temperatureElement = document.querySelector("#temperature");
    // let temperature = Math.round(response.data.main.temp);
    // console.log("focus", response.data.main);
    // let cityElement = document.querySelector("#city");
    // cityElement.innerHTML = response.data.name;
    // temperatureElement.innerHTML = `${temperatureElement}°C`;
  }
  function convertToCelsius(event) {
    event.preventDefault();
    // let temperatureElement = document.querySelector("#temperature");
    // console.log("temperature element", temperatureElement);
    // let conversionToFarenheit = temperatureElement * 1.8 + 32;
    // temperatureElement.innerHTML = conversionToFarenheit;
  }

  let farenheitLink = document.querySelector("#fahrenheit-link");
  // farenheitLink.addEventListener("click", convertToFahrenheit);

  let celsiusLink = document.querySelector("#celsius-link");
  // celsiusLink.addEventListener("click", convertToCelsius);

  h5.innerHTML = `${day} ${month} ${date}, ${hour}:${minutes}`;

  search("paris");
  return h5.innerHTML;
}
console.log(formatDate());
