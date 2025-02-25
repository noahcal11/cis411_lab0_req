# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Noah Calisti  
**GitHub Handle:** noahcal11  
**Repository:** [My Forked Repository](https://github.com/noahcal11/cis411_lab0_req)  
___

## 1. Overview
The user places their order on the app, chooses delivery time and location, and pays. Once payment is received, the chefs begin making the food and a delivery person selects the job. When the food is ready, the delivery person takes the food to the classroom/dorm and, upon user retrieval, confirms delivery.
![Order Food Diagram](/assets/FoodDiagram.png) 

## 2. Requirements
- **Business**: The business objective that the system needs to satisfy.
  - B.1 The system must limit orders based on staff capacity, so that the delivery Service Level Agreement of within 10 minutes of promised delivery is not placed in jeopardy. (Boss)
  - B.2 The Union and Falcon must have enough staff to devote several members to delivery needs (Falcon student worker)
  - B.3 The system must keep track of revenue generated from delivery orders to ensure profitability (Finance major)
- **User**: The actions that a user takes within the system
  - U.1 The user must associate their account with payment method (e.g., Falcon Dollars or Credit Card) (Student 1).
  - U.2 The user must select a specific classroom location for delivery (Brett Graff)
  - U.3 The user must provide detail deliveries, such as delivery in the room or leaving food at the door (Brett Graff)
  - U.4 The user must have a phone number associated with their account (Connor Daudt)
- **Functional**: The functions should the system perform
  - F.1 The system must present a ten-minute-wide anticipated delivery window prior to allowing the user to confirm the order (Student 2).
  - F.2 The system must also provide dorm delivery to the lobby of a student's residence (Teddi Powell)
  - F.3 Professors must have the option to opt in or out of delivery to their classroom to prevent disrupting class (Teddi Powell)
  - F.4 With the user's consent, the system must send a text alert upon food delivery (Connor Daudt)
- **Non-Functional**: The characteristics that the system should have.
  - N.1 The system must render pages in less than 1 second after any user action or application event. (UX Expert)
  - N.2 The system must display clear warnings when there is high ordering traffic that might cause delays (Falcon worker)
  - N.3 The system must handle 1000 users without performance loss (Marcus Glueck)
- **System**: Specifications about how the system should be built.
  - S.1 The system must use Messiah University Single Sign On (SSO) solution for any accounts with a messiah.edu domain. (Policy IT01.02)
  - S.2 The system must load functionally on all common displays (browsers, tablets, mobile, web, etc.) (Marcus Glueck)
  - S.3 The system must only be accessible to users connected to a Messiah trusted network (Falcon/Union policy)

## 3. Assumptions
 - A.1 This system assumes that the university will allow food delivery into classrooms
 - A.2 This system assumes that many professors will allow food delivery into their class
 - A.3 This system assumes that students will be willing to pay an extra fee for delivery

## Appendix: GitHub Notes

### A.1 Forked Repository
![Forked Repo Diagram](/assets/ForkedRepo.png)  

### A.2 Git Logs
In this section, provide the logs from *Step 2.7* and *Step 6.4*.  
2.7 Logs:
```
137441b (HEAD -> labreport, origin/labreport) everything done except for logs
4ca940e initial commit hello @trevordbunch
50d40f8 (origin/main, origin/HEAD, main, labreq) Update references to main branch
ef962b1 Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License
```
6.4 Logs:
```
caeaf42 (HEAD -> main, labreport) diagrams updated, 2.7 log included
137441b (origin/labreport) everything done except for logs
4ca940e initial commit hello @trevordbunch
50d40f8 (origin/main, origin/HEAD, labreq) Update references to main branch
ef962b1 Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License
```
### A.3 Branch Repository
![Branch Diagram](/assets/Branches.png)

### A.4 Extra Credit
![Full Journey Diagram](/assets/FullJourney.png)