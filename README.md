## View Online
https://bdaisey.github.io/addyvalidate/


## Overview
This tool uses the ‘Address Standardization Web Tool’ from the API of the United States Postal Service to search for an address provided by the user. The user enters a Street Address and Zip Code into the HTML form. If found in the USPS database, the Street Address will be corrected to the exact string USPS uses and the fields for City, State, and Zip Code Extension will be populated in the HTML form, letting the user know their search was successful.

## How it Works
1. Captures Street Address and Zip Code into HTML form (user prompted to input).
2. Builds url using the XML Request format required by USPS.
3. Uses XMLHttpRequest (XHR) object to send request to USPS servers.
4. Receives USPS response using the responseXML property of XHR objects.
5. Parses XML response and places values for City, State, Zip Code Extension into HTML form.

