# NightlyInsight
# Computer Science: Internal Assessment

![sleep-tired-1](https://github.com/OswellSkg/comsci_IA/assets/112055140/bb927204-4363-4660-8379-31ba697933ea)

https://tenor.com/view/sleep-tired-gif-23650631

# Criteria A: Planning

## Problem definition

The client, person A is currently a high school student at an international school in Tokyo. Since a young age, she has been developing a habit of sleeping very late, such habit has not changed. However, given that high school is a crucial stage in her educational career, she is willing to correct it. She has several problems that she faces when she attempts to resolve this issue. Firstly, she has a hard time keeping track of her sleep schedule and ends up having daytime naps that only worsen her sleep schedule even more. Secondly, she is not fully convinced of her terrible sleep schedule. Thirdly and finally, the client is very forgetful of the motivation to better her sleep schedule. These problems contribute to her terrible sleep schedule and only reinforce it in such a way that worsens it. 

## Rationale for Proposed Solution

As a solution to the client's problem, I will propose a mobile application that will be able to track the client's sleep schedule and indicate the amount of sleep that the client had per week. The application will evaluate whether the client had a sufficient amount of sleep or not each day on a calendar with three colors: Green, Yellow, and Red. Furthermore, the application will have a weekly goal-setting function that will help the client stay motivated to improve their sleep schedule. The app also compares the client's daily sleep amount with the amount of sleep deemed necessary for one to stay healthy on a data plot, urging the client to improve their sleeping habit. 
## Design Statement 

The application will be a sleep schedule tracker in which the client is able to record their sleep performances every day. It will be constructed using Python, KivyMD, and SQLite on Pycharm for my client for personal use. It will take 4-5 weeks to code and will be evaluated according to the criteria A, B, C, D, and E as seen in the [link](https://docs.google.com/spreadsheets/d/1B3HfHEN7qSuDfxGyv4nNJefHmbGMWLu9FOd9l2NEqSw/edit?usp=sharing).

## Success Criteria
1. The client is able to input sleep data into the application (Input & Save)
2. The application is able to present a calendar that indicates the sleep hours of each day
3. The application can also indicate the quality of sleep per day with three colors on the calendar (Red, Yellow, and Green)
4. The client is able to set a weekly goal of the total amount of sleep they want to achieve (with the minimum being the minimum amount of sleep one needs to stay healthy)
5. The application will take a record of how many times the client failed or succeeded in achieving their weekly goal
6. The application resets the goal every week for the client to update it
7. The application graphically analyzes the sleeping trend of the client

Success criteria 1, and 2 will solve the client's first problem of having a "hard time keeping track of her sleep schedule" <br>
Success criteria 3 and 7 will solve the client's second problem of being "not fully convinced of her terrible sleep schedule" <br>
Success criteria 4, 5, and 6 will solve the client's third problem of being "very forgetful of the motivation to better her sleep schedule" <br>


# Criteria B: Design

## System Diagram

![Wireframe Diagram-Page-1 drawio](https://github.com/OswellSkg/comsci_IA/assets/112055140/f64ddc6d-5d0b-4e31-8a3d-9bda5c710160)

<i>Fig. 1</i> This is the system diagram for the application.

This system diagram visually represents the system as well as the components of the application that will be programmed. It clarifies relationships between compenents. For instance, it is clear from the diagram that the NightlyInsight.db database will bilaterally connect to app's both python and kivyMD files. These programs will be receiving input from the keyboard and outputting through the laptops screen.

## Wireframe Diagram 

<img width="542" alt="Screen Shot 2023-11-04 at 13 40 45" src="https://github.com/OswellSkg/comsci_IA/assets/112055140/bdb07a2e-3f78-4825-a6f5-f20897c635ef">

<i>Fig. 2</i> This is the wireframe for the application. 

The wireframe diagram above is a visual representation of the application GUI structure. It consists of Login, Home, Calendar, Register, and Data screen. The arrow represents which button leads to which screen. 

## ER Diagram

![Wireframe Diagram-Page-3](https://github.com/OswellSkg/comsci_IA/assets/112055140/58f7f7ef-5453-40b2-9c5f-0ac3fd5946d9)


<i>Fig. 3</i> This is the ER Diagram showing the two tables: users, and sleep_data.

The user's table of the NightlyInsight will store the user's username as a string, password as a string, as well as their weekly goal of sleep as an integer, and finally id them. The password will be hashed for security reasons. The sleep_data will gather data of the user_id to distinguish which user's sleep the data belongs to as an integer, the amount of sleep as an integer, as well as the date of the sleep as a string. 

## Record of Tasks
https://docs.google.com/document/d/1xnl3_qt5ToP3yCtgorY-RFfB_ZXItlj07jwOs4aSo-8/edit?usp=sharing
