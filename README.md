# Request Header Parser Microservice

This is a simple Node.js and Express microservice that returns the client's IP address, preferred language, and software information based on the request headers.

## Project Overview

This project is part of the FreeCodeCamp curriculum and serves as a basic introduction to API microservices. The service parses the headers of incoming HTTP requests and returns a JSON response containing:

- **IP Address**: The IP address of the client making the request.
- **Preferred Language**: The language preferences set in the client's browser.
- **Software**: Information about the client's browser and operating system.

## Example Usage

To use the microservice, make a GET request to the following endpoint:

[base_url]/api/whoami

csharp


Replace `[base_url]` with the actual URL where your application is hosted.