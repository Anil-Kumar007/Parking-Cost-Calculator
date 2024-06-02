# Parking-Cost-Calculator
A demo website PARKING COST CALCULATOR where tester can test the application for parking their vehicle under different circumstances.
![image](https://github.com/Anil-Kumar007/Parking-Cost-Calculator/assets/156831352/39941c5e-c21b-47ea-adf4-7a873cd61eb2)


Web app link:  **https://www.shino.de/parkcalc/**

Parking Rates:
Parking rate refers to the cost incurred for using a parking space for a certain period of time. Parking rates are typically charged on an hourly basis and can vary depending on the location, time of day, and type of parking facility. Understanding the parking rate is essential for individuals who need to budget for parking expenses or for businesses that manage parking facilities.


Understanding of application:
A parking user has basically 5 options to park their vehicle in parking lot and every options has different fare for parking.
- Valet Parking
- Short-Term (hourly) Parking
- Long-Term Garage Parking
- Long-Term Surface Parking (North Lot)
- Economy Lot Parking

![image](https://github.com/Anil-Kumar007/Parking-Cost-Calculator/assets/156831352/98a6d4c8-1517-4459-9fbd-8645c2fc761d)



- Valet Parking
$18 per day
$12 for five hours or less
(When user is using valet Parking option 
      1. For Five hours or less the valet cost will be $12.
      2. for whole 24 hours He/She can park their vehicle for $18
      3. If exceeded then charges will apply for whole day )


- Short-Term (hourly) Parking
$2.00 first hour; $1.00 each additional 1/2 hour
$24.00 daily maximum
(When user is using short term Parking option 
      1. For first hours or less the charges will be $2. If timing exceeds more than 1 hour then 1/2(half hour) for each half hour additional $1 will be charged.
      2. Keep in mind the toll collector will not charge more than $24 dollar as its a maximum.
      3. If car owner comes after 24 hours then additional 1/2(half hour) for each half hour additional $1 will be charged.

- Long-Term Garage Parking
$2.00 per hour
$12.00 daily maximum
$72.00 per week (7th day free)
(When user is using Long-Term Garage Parking option 
      1. For each hours $2 will be charged. 
      2. Keep in mind the toll collector will not charge more than $14 dollar as its a maximum for the day.
      3. $72.00 per week will be charged and  (7th day free).


- Long-Term Surface Parking (North Lot)
$2.00 per hour
$10.00 daily maximum
$60.00 per week (7th day free)
(When user is using Long-Term Surface Parking option 
      1. For each hours $2 will be charged. 
      2. Keep in mind the toll collector will not charge more than $10 dollar as its a maximum for the day.
      3. $60.00 per week will be charged and  (7th day free).

- Economy Lot Parking
$2.00 per hour
$9.00 daily maximum
$54.00 per week (7th day free)
(When user is using Economy Lot Parking option 
      1. For each hours $2 will be charged. 
      2. Keep in mind the toll collector will not charge more than $9 dollar as its a maximum for the day.
      3. $54.00 per week will be charged and  (7th day free).

Notes 1: A Lost Ticket Fee of $10.00 will be assessed when the original parking stub cannot be produced when exiting the parking facilities (does not apply to Valet Parking)

Notes 2: Once a user has choose a Parking Lot 
                     then input entry date and time and,
                     input leaving date and time

Note 3: ESTIMATED PARKING COSTS
                    1. must show the total cost of parking in that specific parking lot that a user has used.
                    2. total time calculation of parking must be visible for avoiding conflictions in receipt.

Note 4: Check the button (Calculate).

Tester Roles and Responsibilities:
1. Prepare RTM 
2. Develop the different types of test cases
- UI Test cases
- Functional Test Cases
- Positive and Negative Test cases
- System Testing Test Cases
3. Prepare Defect log

=========================================================================================================================================================================================

Hypotetically assuming some Requirements:
1. UI Requirements:
   Requirement 1
   a. The name of the Website will be "Parking-Cost-Calculator" the name should reflect on upper mid side.
   b. The color will be used as purple color.

   Requirement 2
   a. A table will be form which includes
      1. two coloumns and
      2. four rows

         #In first coloumn all four rows:
         - Choose a Parking Lot
         - Please input entry date and time
         - Please input leaving date and time
         - ESTIMATED PARKING COSTS

         #In second coloumn first row
         - There is a requirement of drop down which includes above mentioned parking lots
         - By default name will show as "Vallet Parking" in drop down menu
           
         #In Second coloumn Second row
         - There is requirement of two edit box and two radio button
           1. Date field format (MM/DD/YY) and
           2. timmings
           3. AM / PM radio buttons
          
         #In second coloumn third row
         - There is requirement of two edit box and two radio button
           1. Date field  (MM/DD/YY) and
           2. timmings
           3. AM / PM radio buttons
              
         #In second column Fourth row
         - Total Balance should reflect once vehicle is about to left the parking lot
         - By default it should reflect $ 0.

   Requirement 3
   a. requirement of Calculate button
   b. name of button will be calculate

   Requirement 4
   a. requirement of Reset button
   b. name of button will be Reset
   c. It will reset all fields to default fields in table.

