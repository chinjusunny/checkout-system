# Checkout System

Website using Codeigniter 3.1.11 and Bootstrap 3.3.7

**Step 1: Shopping cart**

You are building a checkout system for a shop which only sells apples and oranges.  
Apples cost 70cents and oranges cost 35cents.  
Build a checkout system which takes a list of items scanned at the till and outputs the total cost  
For example: [ Apple, Apple, Orange, Apple ] => $2.45  
Make reasonable assumptions about the inputs to your solution; for example, many candidates take a list of strings as input  
  
**Step 2: Simple offers**

  The shop decides to introduce two new offers:  
- Buy one, get one free on Apples  
- 3 for the price of 2 on Oranges  
Update your checkout functions accordingly

## Built With

- Bootstrap
- PHP
- Codeigniter
- jQuery

## Installation

Project runs from index.php page : http://localhost:8888/checkout/
## Screenshots



## Testing

Execute the following commands from the project directory:

    1. $ vendor/bin/phpunit -c application/tests/ application/tests/WelcomeTest.php
    2. $ vendor/bin/phpunit -c application/tests/ application/tests/FunctionTest.php

Codeigniter controller to test the basic functions:

    http://localhost:8888/checkout/TestingController 
