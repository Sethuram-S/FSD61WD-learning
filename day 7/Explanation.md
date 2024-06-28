<center>
    <h1>Array Method</h1>
</center>
<br>
<h3>Solving problems using array functions on rest countries data (https://restcountries.com/v3.1/all).</h3>

<h4>Get all the countries from Asia continent /region using Filter method</h4>

1. Fetching Data from the API:
   - The code starts by making an HTTP request to the URL “ https://restcountries.com/v3.1/all ” using the fetch function.
   - The fetch function returns a promise that resolves with the response from the server.
   - The .then() method is used to handle the response asynchronously.
2. Parsing the Response:
   - The .then((response) => response.json()) part of the code converts the response data (which is in JSON format) into a JavaScript object.
   - The resulting object contains information about all countries.
3. Filtering Asian Countries:
   - The data.filter((country) => country.region === "Asia") line filters the countries based on their region property.
   - It creates a new array called asianCountries containing only the countries from the Asian continent.
   - The condition (country) => country.region === "Asia" checks if the region property of each country object is equal to “Asia.”
4. Logging the Result:
   - Finally, the console.log(asianCountries) statement prints the filtered array of Asian countries to the console.

<h4>Get all the countries with a population of less than 200000 using Filter method.</h4>

1. Fetching Data from the API: - The code starts by making an HTTP request to the URL “ https://restcountries.com/v
   3.1/all ” using the fetch function. - The fetch function returns a promise that resolves with the response from the server. - The .then() method is used to handle the response asynchronously.
2. Parsing the Response:
   - The .then((response) => response.json()) part of the code converts the response data (
     which is in JSON format) into a JavaScript object.
   - The resulting object contains information about all countries.
3. Filtering Countries with Population Less Than 200000:
   - The data.filter((country) => country.population < 200000) line filters the countries
     based on their population property.
   - It creates a new array called smallPopCountries containing only the countries with a population less than
   200000.
   - The condition (country) => country.population < 200000 checks if the population property of
     each country object is less than 200000.
4. Logging the Result:
   - Finally, the console.log(smallPopCountries) statement prints the filtered array of countries with
     a population less than 200000 to the console.

<h4>Print the full name and capital city of all countries using forEach method</h4>

1. Fetching Data from the API:
   - The code starts by making an HTTP request to the URL “ https://restcountries.com/v
     3.1/all ” using the fetch function.
   - The fetch function returns a promise that resolves with the response from the server.
   - The .then() method is used to handle the response asynchronously.
2. Parsing the Response:
   - The .then((response) => response.json()) part of the code converts the response data
     (which is in JSON format) into a JavaScript object.
   - The resulting object contains information about all countries.
3. Iterating Over Countries:
   - The data.forEach((country) => console.log(country.name.common + " - " + country
     capital)) line iterates over each country object in the data array and prints its full name and
     capital city to the console.
   - The condition (country) => console.log(country.name.common + " - " + country.cap
     ital) checks if the country object has a name.common and capital property.
4. Logging the Result:
   - Finally, the console.log(smallPopCountries) statement prints the filtered array of countries with
     a population less than 200000 to the console.

<h4>Print the total population of countries using reduce method</h4>

1. Fetching Data from the API:
   - The code starts by making an HTTP request to the URL “https://restcountries.com/v3.1/all” using the fetch function.
   - The fetch function returns a promise that resolves with the response from the server.
   - The .then() method is used to handle the response asynchronously.
2. Parsing the Response:
   - The .then((response) => response.json()) part of the code converts the response data (which is in JSON format) into a JavaScript object.
   - The resulting object contains information about all countries.
3. Calculating Total Population using reduce:
   - The data.reduce((acc, country) => acc + country.population, 0) line uses the reduce method to calculate the total population.
   - The reduce method iterates through each country in the data array.
   - For each country, it adds the population property to the accumulator (acc).
   - The initial value of the accumulator is set to 0.
   - The final result is the total population of all countries.
4. Logging the Result:
   - Finally, the console.log(Total population: ${totalPopulation}) statement prints the total population to the console.

<h4>Print the country that uses US dollars as currency</h4>

1. Fetching Data from the API:
   - The code starts by making an HTTP request to the URL “https://restcountries.com/v
     3.1/all” using the fetch function.
   - The fetch function returns a promise that resolves with the response from the server.
   - The .then() method is used to handle the response asynchronously.
2. Parsing the Response:
   - The .then((response) => response.json()) part of the code converts the response data (
     which is in JSON format) into a JavaScript object.
   - The resulting object contains information about all countries.
3. Filtering Countries by Currency:
   - The data.filter((country) => country.currencies.USD) line filters the data array
     to only include countries that use US dollars as their currency.
   - The condition (country) => country.currencies.USD checks if the country object has a
     currencies property and if the USD currency is present in the array.
4. Logging the Result:
   - Finally, the console.log(country.name.common) statement prints the name of the country that uses
     US dollars as currency to the console.
