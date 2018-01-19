# Assignment 1 - Practice Designing Models

> * Participant Name: Blake Nguyen
> * Project Title: Recyclebot

## General Introduction

A **smart city** is an urban area that uses different types of electronic data collection sensors to supply information which is used to manage assets and resources efficiently.


![smartcity.png](./smartcity.png)


**Recycling** has always been an intersting problem as it involves so many different waste materials that contibute to this problem. First, we are all consumers and unfortunately only **some** of the consumer population show an interest in recycling. One aspect of recycling that I want to address is how to make recycling more convenient for the everyday household person. If we can figure out a way to make it more convenient it may promote better recycling habits. For example: a busy household may find it inconvenient to sort recyclable materials. Therefore, they may toss together recycable materials with non-recyclable materials because of the extra effort it takes to go through and sort the differences. The problem may be due to timing and convenience. How much time does it take to sort through recyclable and non-recyclable waste? Recycling dates back to the colonial era, this is because new materials were difficult to come by so they had to repurpose used materials. There are proposed solutions for recycling. However, even with the proposed solutions, there is still a vast amount of household that do not recycle.

Citation: http://time.com/4568234/history-origins-recycling/


## Requirements (Experimental Design)


**Set of requirements:**
The autonomous robot called Recycle-bot will be instructed to detect waste materials and classify them into either recycable materials and non-recyclable waste materials. Recycle-bot will then take recycable materials and repurpose/convert them into new materials/objects. The inputs of my system is that it will take recycable materials and non-recyclable materials. The functions of my Recycle-bot is to either destory non-recyclable waste materials and to take recycable materials and repuprose them into new materials/objects. My outputs are the new materials/objects that are converting from plastic, metal and paper recyclable materials.

**Specified problem:**
We are all consumers but only a percentage of the consumer population recycles. The problem is that we may be affected by limited resources so it is important to recycle materials that can be recycled into new materials for us.

**Hypothesis:**
With the help of Recycle-bot the average!busy household will be more likely to recycle with the incentive that the autonomous robot will repurpose recyclable materials into new materials that the household can utilize. For example, if you recycle paper, Recycle-bot can repurpose the used material into new materials like paper, paper plates, paper cups, tissue, and any other paper goods.




## Smart City (My Problem) Model

* [**Object Diagram**](model/object_diagram.md)
The object diagram depicts Recyclebot, which has two classifications non-recycable waste and recycable materials. The robot classifies items such as lightbulbs, perishable items (i.e. fruits and meats), and air filters as non-recycable. The robot will then proceed to dispose of the non-recycable items. The robot will take recycable materials such as plastic, paper, and metal and cycle the materials through a repurposing process to create new materials.
![Object_Recycle-bot.png](./Object_Recycle-bot.png)

* [**Class Diagram**](model/class_diagram.md)
Recyclebot has two attributes such as plastic, paper, and metal and amount of plastic, amount of paper, and amount of metal. The functions of Recyclebot are to destroy non-recycable waste or to repurpose recyclable materials and convert them into new materials. The functions are classified into three groups plastic, paper, and metal. The first classification is plastic and it is defined as plastic type and the density of the plastic materials. The second classification is paper and it is defined as paper type and the density of the paper materials. The last classification is metal and it is defined as metal type and the density of the metal materials. 
![Class_Recycle-bot.png](./Class_Recycle-bot.png)

* [**Behavior Diagram**](model/behavior_diagram.md)
The behavioral diagram depicts the behaviors of Recyclebot. In the diagram below, you notice that the process initates with collecting waste and recycable materials. Then it proceeds to sort non-recycable waste and recycable materials. The class is associated to two classifications labeled as non-recycable, which proceeds to destroy or properly dispose of the non-recycable waste such as perishable foods such as fruits and meats. The other classification labeled recycable materials proceeds to the process of repurposing materials to ultimately compose new materials from recycled materials.

![Behavioral_Recycle-bot.png](./Behavioral_Recycle-bot.png)


* [**Agent / User case** ](model/agent_usecase_diagram.md)
The agent-based diagram shown below depicts the Recyclebot (Agent) as it moves in an environment that can be operatored manually or autonomously. The agent has specific goals and decision based on the assessment of recycable materials and non-recycable waste. Recycable materials and non-recycable waste is being percieved by the environment of a household. The goals and decisions are influenced by the assessment of the items gathered. If the items collected are classified as recycable materials, Recyclebot will proceeed to repurpose the recycable materials into new materials. If Recyclebot detects that the items are non-recycable waste, they will proceed to dispose/destory the items.

![Agent_Recycle-bot.png](./Agent_Recycle-bot.png)


## Smart City (My Problem) Simulation

The simulation that best fits my proposed problem solution for recycling is agent-based simulations. Agent-based simulations help analyze the actions and interactions of autonomous agents such as the Recycle-bot. With the capability of viewing to assess their effects on the system itself.



## Smart City (My Problem) Model
[**Code template**](code/README.md)
/Users/BlakeNguyen/Desktop/recyclebot.py
/Users/BlakeNguyen/Desktop/repurpose.py


## **P**ortable **O**rganic **T**rouble-free **S**elf-watering System (**POTS**) Model
Here [**we provide an overview**](code/POTS_system/README.md) of the **P**ortable **O**rganic **T**rouble-free **S**elf-watering System (**POTS**) Model and provide a source code template.


**Object Diagram for POTS**
Description: The object diagram for the Portable Organic Trouble-free Self-watering System (POTS) is depicted below. The object diagram shows the class vegetable (variable) and the subclassifications of vegetables eggplant, bokchoy, pepper, and stringbean are all associated to the main variable; vegetable.

![Ob.D_POTS_Final.png](/Users/BlakeNguyen/Desktop/Ob.D_POTS_Final.png)

**Class Diagram for POTS**
Description: The class diagram depicts the model of the POTS code in more detail. The model depicts based on the code provided that the vegetable is variable with it's complements pepper, bokchoy, string bean and eggplant. The vegetables' attribute is name; string and the functions for the vegetables are the weight of the vegetabels;floats. 

![Class.D_POTS_Final.png](/Users/BlakeNguyen/Desktop/Class.D_POTS_Final.png)



