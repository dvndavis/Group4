# **MIST4610 Group 4 Project**

## Team Name:
**61608 Group 4**

## Team Members:
1. Devin Davis [@dvndavis](https://github.com/dvndavis)
2. Hadden Peel [@hmpeel](https://github.com/hmpeel)
3. Kate Macken [@katemacken](https://github.com/katemacken)
4. Keira Cullinan [@keiracullinan](https://github.com/keiracullinan)
5. Lleyton Poole [@lleytonpoole10](https://github.com/lleytonpoole10)
6. Luke Burnett [@lukeburnett16](https://github.com/lukeburnett16)

## Problem Description:


## Data Model:
Data Model Explanation: 
Our model is based on the managerial structure of two soccer teams, the U.S. Women's Soccer Team and the U.S. Men’s Soccer Team. The team entity represents all 50 players on the teams, which is represented by the one-to-many relationship we placed between teams and players. 

From the Players table, there is a one-to-many relationship between Players and Training Session. One player can go to many training sessions, and each training session includes data on the session as well as the length. The Training Session connects with the Training Type which includes the location of training and training type. 

There is also a many-to-many relationship between Players and Matches, which created the table Player Stats. Player Stats includes important information such as goals or assists scored. This information helps to connect the players to the matches they have played. Matches include attributes such as the date of the match, opponent, attendance, the revenue generated from the match, and the name of the venue. Teams have a one-to-many relationship with Matches to put the team name with the match and opponent. One team can play many matches against different opponents. 

The Equipment table has a many-to-many relationship with Training Sessions to create Equipment Utilization. Equipment is included in many training sessions, and training sessions use lots of different equipment. The Equipment table includes the name of the equipment, quantity, and condition, such as Good or Used, the date of purchase, and the last maintenance date. 

There are many staff members within each team, so we added a one-to-many relationship between the Teams and Staff tables. Staff members also connect to Training Sessions, as many staff members run the training sessions. 

From the contracts table, there are three relationships stemming from the table: Staff, Sponsors, and Players. Each sponsor has a contract, so we created a one-to-one relationship between those two tables. The sponsor table includes important information such as the name of the sponsor, the amount given, and the industry that the sponsor is in. The contract table includes information such as the start and end date and the total amount of the contract. 

Lastly, there is a community engagement entity that shows the date of community engagement and the type of engagement. Players has a one-to-many relationship with community engagement. 

<img width="1062" alt="dataModel" src="https://github.com/dvndavis/Group4/assets/163315179/12d9d350-a69f-4ef5-9fc6-79ec7d3c10ba">

## Data Dictionary:

<img width="483" alt="Screenshot 2024-03-27 at 11 55 14 AM" src="https://github.com/dvndavis/Group4/assets/163012542/91f859d3-94ff-46a2-aaf3-ff0b9c4d9a8f">
<br>
<img width="483" alt="Screenshot 2024-03-27 at 11 58 07 AM" src="https://github.com/dvndavis/Group4/assets/163012542/4b67971f-c767-4c46-8ffe-e25dd5ff3618">
<br>
<img width="482" alt="Screenshot 2024-03-27 at 12 08 57 PM" src="https://github.com/dvndavis/Group4/assets/163012542/28f9a95d-a679-4162-810d-f6d3a113e267">
<br>
<img width="485" alt="Screenshot 2024-03-27 at 12 11 24 PM" src="https://github.com/dvndavis/Group4/assets/163012542/844f9f8c-f3ec-4066-a104-c13f2dd05b79">
<br>
<img width="483" alt="Screenshot 2024-03-27 at 12 13 38 PM" src="https://github.com/dvndavis/Group4/assets/163012542/10cedca0-542a-409e-9ade-5e0406fd09f1">
<br>
<img width="387" alt="Screenshot 2024-03-27 at 12 24 44 PM" src="https://github.com/dvndavis/Group4/assets/163012542/f7b4e2e1-be50-4c31-b5c8-4debd7f458e3">
<br>
<img width="396" alt="Screenshot 2024-03-27 at 12 30 08 PM" src="https://github.com/dvndavis/Group4/assets/163012542/1e0122a1-3c95-49ad-b024-51c32a38f83b">
<br>
<img width="386" alt="Screenshot 2024-03-27 at 12 38 28 PM" src="https://github.com/dvndavis/Group4/assets/163012542/e07f804c-afd3-47af-b6ad-607ed6a1da84">
<br>
<img width="386" alt="Screenshot 2024-03-27 at 12 40 21 PM" src="https://github.com/dvndavis/Group4/assets/163012542/07e92614-bbf7-4d15-a166-6f2df94bf1ef">


## Queries:

### Query 1:

### Query 2:

### Query 3:

### Query 4:

### Query 5:

### Query 6:

### Query 7:

### Query 8:

### Query 9:

### Query 10:



## Database Information









