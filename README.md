# SmartCarParkingSystem
https://www.tinkercad.com/things/23hICgx6Ovq

# Problem Statement

For most of the time, small things kill our valuable time. One such thing is Parking our car. Parking a vehicle in a tourist spot is a very hectic task. I myself have faced this problem. I went to a Hill Station. There in the hill station car parking space was not well maintained. Both entry and exit ways were the same. Moreover we couldn't know whether space is available for parking in the parking space. Because when we are inside the car, we can't see how much space is available inside the parking space right? 
Then we entered the parking area and unfortunately there was no parking space left available. So we had to return back and find some other space to park on the roadside. Because of this we lost around 45 minutes roaming here and there. 45 minutes costs us a lot. Because of this, we couldn't visit one of the most famous spots in that Hill station.
I have come up with my own solution for this problem. We can implement this solution in the real world and can save our time.

# Real-time Application of The Project
This Smart Parking System can be used in places, where both entry and exit ways are the same. Example : In Hill Stations, In Malls and everywhere where there is a need for parking. If the entry and exit ways are different, it is easy for us to count the number of cars and allocate parking spaces. It's difficult when both entry and exit ways are the same. This system can also be used in places where there is a need for counting the number of cars which enters and leaves a territory if the entry and exit ways are the same.
This project can be implemented in India because, in most parking spaces the entry and exit are the same and parking spaces are not well maintained which costs our precious time. 

# Working Principle

Generally in malls or in any tourist spots, the owner of the parking space knows how many cars can be parked in the parking space. Using this information our Smart Parking System works.
Behind the scene, in the program I have initialized the variable counter to zero.
In this project I have used two PIR Sensors. Two sensors will be placed on the sides of the parking entry and the distance between the two sensors should be atleast 4.8 metres. The length of the largest Indian car INNOVA is around 4.5 metres. Let us name the first sensor which is near to the entry as sensor1 and the second sensor which is far away from the entry way as sensor2.

# My Algorithm:
If a car passes first through sensor1 and then through sensor2, then it is an entry. So the initialized counter variable increments(counter=counter+1) by one .If a car passes first through sensor2 and then through sensor1, then it is exiting. So the initialized counter variable decrements(counter=counter-1) by one.

Working of system & its components :
Let us consider that the total cars that can be parked in parking space as n. As a car enters the counter is incremented and as a car exits the counter is decremented.

# CASE 1:
If the counter becomes greater than or equal to n, then the LCD panel displays “ NO PARKING AVAILABLE”. And the Speaker turns on and it indicates that the parking is full. And the servo motor turns on and rotates such that it blocks the entry of vehicles. If a car exits the parking space, then the servo motor automatically rotates in such a way that it allows the car to exit.

# CASE 2:
If the counter variable is less than or equal to n, then the LCD panel displays “ PARKING AVAILABLE, WELCOME”. And the servo motor stands still and does not rotate such that it allows the entry of vehicles.

To know more read the pdf attached.
