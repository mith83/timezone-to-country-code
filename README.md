# timezone-to-country-code
JS Library for obtaining the country code from the timezone.
Easily convert timezone to country code or place using the timezone-to-country-code JS Library 

# Usage Example 
Here is timezone to country code js library example on using its functions.<br/> 
const t = new tz(); // Initialize the JS Class<br/> 
let userTimezone = t.getUserTimeZone(); // Gets user's timezone<br/> 
let userCountry = t.getCountryCode(userTimezone); // Gets user's country code<br/> 
let place = t.getPlace(userTimezone); // Gets user's place<br/> 
let tz_array = t.timeZoneArrayWithCountryCodes(); // Gets all timezone list as an array<br/> 

# Dependency 
Moment's Luxon 3.5.0 JS Library 
CDN: https://cdn.jsdelivr.net/npm/luxon@3.5.0/build/global/luxon.min.js

# timezone to country code CDN
https://cdn.jsdelivr.net/gh/mith83/timezone-to-country-code@latest/tz2cc.min.js


