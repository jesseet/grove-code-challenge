# grove-code-challenge
NetSuite Developer Code Challenge

# Directions:
1. Open the HTML page on browser
2. Select store-locations.csv file
3. Enter Location in Address or Zipcode and hit "Submit"
4. The page will display the nearest store from the location, and its distance to that store.

# Assumptions/Caveats:
1. Approached the challenge with HTML, Google Geocoding API, and JavaScript for simpler user experience.
2. Used Google Geocoding API to get the lat long, since it is the most reliable and scalable. There are other free services that could be used for this challenge.
3. Potential limitation would be csv file volume testing with special characters or missing data, since string methods were used. There could be many better tools to be explored.
4. The script requires better error handling, cleanup, parameter handling, etc.
