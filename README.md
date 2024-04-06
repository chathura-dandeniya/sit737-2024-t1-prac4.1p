# Calculator Microservice

This project implements a basic calculator microservice using Node.js and Express. It supports basic arithmetic operations: addition, subtraction, multiplication, and division via HTTP GET requests. Logging of requests and responses, including errors, is facilitated using Winston.

## Features

- **Basic Arithmetic Operations**: Perform addition, subtraction, multiplication, and division.
- **Logging**: Request and response logging, including errors, using Winston.
- **Error Handling**: Proper error responses for invalid operations (e.g., divide by zero) or bad input.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Node.js installed on your system.
- Basic understanding of JavaScript and Node.js.

## Installation

To install the necessary dependencies, run the following command:

```bash
npm install express winston
