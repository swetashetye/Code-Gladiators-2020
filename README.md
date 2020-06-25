# Code-Gladiators-2020
Code Gladiators is an annual coding competition by TechGig, that draws the best and the brightest coding talent from all over the world. With multiple contests in emerging technologies and the coveted title of Code Gladiators up for grabs, the competition sees enthusiastic participation and has grown from strength to strength with each passing year.

The first round is an Open Coding Round, where we had to solved two problems which we can solve with whatever langauage of choice.
1.	Powerpuff Girls 
2.	BeyBlade Tournaments 


The code is written in Python language.

# Problem 1: The Powerpuff Girls (100 Marks)

Professor Utonium is restless because of the increasing crime in the world. The number of villains and their activities has increased to a great extent. The current trio of Powerpuff Girls is not well to fight the evils of the whole world. Professor has decided to create the maximum number of Powerpuff Girls with the ingredients he has.

There are N ingredients required in a certain quantity to create a Powerpuff Girl. Professor has all the N ingredients in his laboratory and knows the quantity of each available ingredient. He also knows the quantity of a particular ingredient required to create a Powerpuff Girl. Professor is busy with the preparations and wants to start asap.

The villains, on the other hand, want to destroy the laboratory and stop Professor Utonium from creating more Powerpuff girls. Mojo Jojo is coming prepared with ammunition and Him is leading other villains like Princess, Amoeba Boys, Sedusa, Gangreen Gang etc.

Professor does not have much time as villains will reach the laboratory soon. He is starting the process but does not know the number of Powerpuff Girls which will be created. He needs your help in determining the maximum number of Powerpuff Girls which will be created with the current quantity of ingredients. 

Example:
Professor Utonium requires 3 ingredients to make Powerpuff Girls. The 3 ingredients are present in the laboratory in the given quantity:

 
To make a Powerpuff Girl, Professor Utonium requires:
1.	3 units of Ingredient A
2.	6 units of Ingredient B
3.	10 units of Ingredient C

The maximum number of Powerpuff Girls which can be created are 3 as after 3, Professor will run out of Ingredient C.

Can you determine the maximum number?

Input Format
The first line of input consists of the number of ingredients, N
The second line of input consists of the N space-separated integers representing the quantity of each ingredient required to create a Powerpuff Girl.
The third line of input consists of the N space-separated integers representing the quantity of each ingredient present in the laboratory.


Constraints
1<= N <=10000000 (1e7)
0<= Quantity_of_ingredient <= LLONG_MAX 

Output Format
Print the required output in a separate line.

# Problem 2: Beyblade World Championship (100 Marks)

Tyson is all prepared for the Beyblade World Championship. The tournament is team-based and each team can have N members. A player can fight against a single player only. Team G-Revolution is all excited and pumped up as they have practised a lot. Kenny, the mind of team G-Revolution, has created a database where he has the data about the power of other teams’ members and his own team members. The tournament is going to start in some time and Kenny moves to the cafeteria to have a snack before the competition.

The team G-Revolution is to fight in some time and they are tensed up as someone has kidnapped Kenny from the cafeteria. They have made a police complaint and the police are searching for Kenny. Luckily, they have found his device with all the data. The problem is, the data is present randomly and not in the order they have to fight the opponent. Team G-Revolution wants to win at any cost and for that, they need the order in which they have to fight optimally to win the maximum number of battles.

A player can win only when his/her beyblade power is strictly greater than the opponents beyblade power.

Example: 

Consider the team size is 3, N = 3


The 3 players of both the teams are shown with their beyblade powers.

Team G-Revolution is presented in the order: Tyson, Max, Ray

Team All Starz is presented in the order: Michael, Eddy, Steve

With the given arrangement, Team G-Revolution would be able to win only 1 fight. Team G-Revolution should be shuffled in an optimal manner as below:

The maximum number of fights Team G-Revolution can win is 2 when they are arranged optimally or fight in an optimal order.

Team G-Revolution needs help with the device. Tyson has heard about your skills and called you up to help them shuffle their positions in an order such that they would be able to win the maximum number of fights. Can you help Tyson and Team G-Revolution?

Input Format 

The first line of input consists of the number of test cases, T

The first line of each test case consists of the number of members each team can have, N.

The second line of each test case consists of N space-separated integers representing the power of beyblades of Team G-Revolution members.

The third line of each test case consists of N space-separated integers representing the power of beyblades of opponent team members.

Constraints 

1<= T <=100000

1<= N <=100000 

0<= Power of Beyblade <= LLONG_MAX 

Output Format
For each test case, print the maximum number of fights Team G-Revolution can win if they go to fight in an optimal manner.

