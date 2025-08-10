# Booking API Performance Testing With JMeter
In this project, I have used JMeter to find the actual throughput(TPS), expected TPS and Bottleneck TPS for a site with a given number of users and time. Load test and Stress test(s) were carried out to find TPS values.
## Site Tested
https://restful-booker.herokuapp.com/
### Paths:
- /booking
- /booking/<booking_id>
### Scenario:
120,000 users over a 12-hour period log in, create a booking, and search for the booking.

### Parameters
- Users: 120000
- Time: 12 Hours
- Error Threshold: 0.5%
- Timer: Gaussian Random Timer (Deviation 2000ms, Constant delay 500ms)
## Tools Used
- Apache JMeter
## How to run this project
- Clone this project
- Open the .jmx file using JMeter
## Load Test & Stress Test 
https://docs.google.com/spreadsheets/d/16C54xq4QQ9s7wdNTGePQAyzbppqsY4XcKxBGxeycftU/edit?gid=0#gid=0
## Expected Throughput
<img width="226" height="173" alt="Screenshot_2" src="https://github.com/user-attachments/assets/c04b91b8-6bc8-46b1-bcbd-a21e1f5cce72" />

## Load Test Results
<img width="613" height="270" alt="Screenshot_3" src="https://github.com/user-attachments/assets/a2cc5ab1-e14b-4632-8ef8-b86b627f1b32" />

## Reports of Load Test

<img width="1673" height="816" alt="Screenshot_1" src="https://github.com/user-attachments/assets/bd2b47aa-2448-4824-ac21-9aa9d1255e71" />

## Stress Test Results

<img width="713" height="308" alt="Screenshot_6" src="https://github.com/user-attachments/assets/3286eeb6-d2ab-41cc-bd7e-526db3b3e302" />

## Bottleneck Throughput
<img width="310" height="125" alt="Screenshot_5" src="https://github.com/user-attachments/assets/37e254c4-9b93-41a9-8efa-81aa31b1342a" />

## Reports of Stress Test

<img width="1716" height="714" alt="Screenshot_4" src="https://github.com/user-attachments/assets/83d4f0dd-68b7-4cdf-8081-48c2e072ab50" />
