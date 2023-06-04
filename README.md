# demo-transaction-api-jmeter


## Project Summary:
Here in this project JMeter (Load Tester) is used to perform some basic MFS related actions and assert them. 
Also, a constant timer of 1000MS (1S) is used to ensure one request/action is performed just after 1000MS from the latest one.
At the very end some requests/actions were used first but later kept disabled. If anyone wishes to execute them just simply enable them from accessing context menu of those respective request/action.


## Technology Used:
- JMeter


## Prerequisites:
- NodeJS


## Action Scenario:
All these actions were perfromed sequentially to evaluate the basic MFS feature.

- Admin creates an agent and a customer.
- Deposit 2000 TK to agent from system account.
- Deposit 1000 TK to customer from agent account.
- Check customer account balance.
- Customer withdraw 500 TK from agent.
- Customer pays 200 TK to a merchant account (01686606905).
- Check customer's final balance.


## How To Run:
Please follow these steps gradually
- Step 1: ``` git clone url_of_repository ```
- Step 2: ``` npm i ```
- Step 3: ``` npm test ```

After these executing a command (jmeter -n -t .\[jmx_file_name].jmx -l [csv_log_file_name].csv -e -o [ReportFolderName]) from CMD from file directory will generate a HTML report.


## Testcase:



## Report
![HTMLReport_dMoneyAPIJMeterTesting](https://github.com/NzSakib017/demo-transaction-api-jmeter/assets/134344378/16cc23ed-128f-45cf-9555-8857778700d0)


