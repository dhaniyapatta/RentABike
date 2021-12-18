# RentABike

A Python Project using the concepts of OOP and using test case modules.

## Functionality

- See available bikes on the shop
- Rent bikes on hourly basis $5 per hour.
- Rent bikes on daily basis $20 per day.
- Rent bikes on weekly basis $60 per week.
- Family Rental, a promotion that can include from 3 to 5 Rentals (of any type) with a discount of 30% of the total price

- issue a bill when customer decides to return the bike.
- display available inventory
- take requests on hourly, daily and weekly basis by cross verifying stock

For simplicity we assume that
Any customer requests rentals of only one type i.e hourly, monthly or weekly
Is free to chose the number of bikes he/she wants
Requested bikes should be less than available stock.

## WHy OOP?

Since classes are used various customers and bike rental shops can be instantiated as needed.

## Unit-Testing Module

Test module is written alongside the main program to rigorously test the classes and methods for errors.
Test methods follow snake case
Test methods are descriptive and their names tell what functionality they are testing
Always test for very extreme inputs like Null values, zero arrays, non-integer inputs, invalid dates

## Running the tests

- Python 3.4+: `pytest bikeRental_test.py`

For certain `pytest` options:

- `-v` : enable verbose output
- `-x` : stop running tests on first failure
- `--ff` : run failures from previous test before running other test cases

## Executing the Code

n

```
python main.py

# or depending upon your config

python3 main.py
```
