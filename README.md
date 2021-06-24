# Capacitated Vehicle Routing Problem (VRP)  
## (Genetic Algorithm, Python, Google Colab)  
  
Consider the following problem:  
![image](https://user-images.githubusercontent.com/42261330/123304956-84fedc00-d55a-11eb-80d2-0ca94aade700.png)  
A trucking company needs to deliver goods to all customers.  
Demands of all customers must be satisfied by multiple trips of a single truck (or simultaneous movements of multiple trucks).  
Each truck's trip is limited to its capacity (total number of carried goods must be less than the truck's capacity).  
The objective is to minimize the total travel times of the trucks.  
  
A solution example is shown below:  
![image](https://user-images.githubusercontent.com/42261330/123306141-deb3d600-d55b-11eb-88d0-ecad43e36a65.png)  
  
The VRP is solved using a genetic algorithm with the following framework:  
![image](https://user-images.githubusercontent.com/42261330/123306378-2fc3ca00-d55c-11eb-8f03-39043cf5b468.png)  
  
The crossover and mutation operators are presented as follows:  
![image](https://user-images.githubusercontent.com/42261330/123306462-48cc7b00-d55c-11eb-80fa-f2cad15290a8.png)
