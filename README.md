# Demo-Transaction-API-JMETER

## About this Project
This is a API testing demo project where I try to test an API(dmoney) which is an Mobile Financial Services (MFS) like Bkash/Nagad.In this project I have done all tests manually and I have done all the assertion points to do the API Automation and then genrate the HTML Report.

## Tools & Technology Used
- JMETER

## Prerequisites
- jdk

## Request I have Covered
- Login to the User
- Create an Agent account
- Create a Customer account
- Deposit 2000 tk to agent from system account
- Deposit 1000 tk to customer from agent account
- Check balance from customer account
- Withdraw 500 tk from customer account
- Payment 200 tk from customer account
- Delete Agent account
- Delete Customer account

## How to run this project
- Clone This project
- Then run the follwing command
- ``` $ jmeter -n -t Jmeter Performance test using API Chaining.jmx -l Dmoney-Load-Test.csv -e -o Reports ```
