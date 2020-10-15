## Python-10 Assignment

***

### Warm-up Exercise

#### **Part 0** 

Write a program that does the following in order:
1. Asks the user to enter a number “x” 
2. Asks the user to enter a number “y”
3. Prints out “x” raised to the power “y” 
4. Prints out the `log (base 2)` of “x”


***

### Dream Home Savings Calculator

- Consider the situation where you have graduated from Tech I.S. and have an IT job

- You have to build a program that helps you calculate how many months it takes to save up for the **down-payment**

- The program will take in inputs as specified below and output the number of months it takes to save up for the **down-payment**

- Assume the following:
    - portion of down-payment (of total cost of home): `25%`
    - interest rate for saving money in bank: `4%`
        - so additional funds earned due to interest:
            - `(current savings)*(interest rate)/12`
    - monthly salary: `(annual salary)/12`


- *Part 1* below considers a job that gives no raise, but *Part 2* considers a job where there is a semi-annual raise


#### **Part 1**

Write a program that does the following:

- takes following inputs:
    - takes user input of annual salary
    - takes in percentage of monthly salary savings 
    - takes in input of cost of dream home

- outputs:
    - number of months it takes to save up for _down-payment_


_Test Case 1:_

```python
Enter your annual salary:​ 120000
Enter the percent of your salary to save:​ 10 
Enter the cost of your dream home:​ 1000000
Number of months:​ 183
```

_Test Case 2:_

```python
Enter your annual salary:​ 80000
Enter the percent of your salary to save:​ 15 
Enter the cost of your dream home:​ 500000
Number of months:​ 105
```

#### **Part 2**

Write a program that does the following:

- takes following inputs:
    - takes user input of annual salary
    - takes in percentage of monthly salary savings 
    - takes in input of cost of dream home
    - takes in semi-annual raise as percent of annual raise

- outputs:
    - number of months it takes to save up for _down-payment_

_Test Case 1:_

```python
'Enter your starting annual salary:'​ 120000
'Enter the percent of your salary to save:'​ 5 
'Enter the cost of your dream home:'​ 500000
'Enter the semi­annual raise:'​ 3
'Number of months:​' 142
```

_Test Case 2:_

```python
'Enter your starting annual salary:'​ 80000
'Enter the percent of your salary to save:'​ 1
'Enter the cost of your dream home:'​ 800000
'Enter the semi­annual raise:'​ 3
'Number of months:​' 159
```

_Test Case 3:_

```python
'Enter your starting annual salary:'​ 75000
'Enter the percent of your salary to save:'​ 5 
'Enter the cost of your dream home:'​ 1500000
'Enter the semi­annual raise:'​ 5
'Number of months:​' 261
```