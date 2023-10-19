# Demo Transaction API Testing With JMeter

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
- Then run the follwing command:
- ``` $ jmeter -n -t d_money_API_testing_JMETER.jmx -l d_money_API_testing_JMETER.csv -e -o Reports ```

## JMETER ScreenShot:
![interface](https://github.com/rabbypathan/Demo-Transaction-API-JMETER/assets/70917088/dfdf5ba5-77b4-44fb-90b6-8c53603a65b3)

## HTML Report ScreenShot:
![reports1](https://github.com/rabbypathan/Demo-Transaction-API-JMETER/assets/70917088/d9dd7a2b-bd9d-41f2-8926-7e94b8949ecb)
![reports](https://github.com/rabbypathan/Demo-Transaction-API-JMETER/assets/70917088/a8777608-b696-4fd5-84fc-6b9a02f3e04e)





