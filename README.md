# NightlyInsight
# Computer Science: Internal Assessment

![sleep-tired-1](https://github.com/OswellSkg/comsci_IA/assets/112055140/bb927204-4363-4660-8379-31ba697933ea)

https://tenor.com/view/sleep-tired-gif-23650631

# Criteria A: Planning

## Problem definition

The client, person A currently studies at an international high school in Tokyo. Since a young age, she has been developing a habit of sleeping very late, and such a habit has not changed since then. However, given that high school is a rigorous stage in her educational career, she is willing to correct her sleep schedule for a better high school life. She faces several problems in an attempt to fix her sleep schedule. Firstly, she struggles to keep track of her sleep schedule and ends up having naps during the daytime which only worsens her sleep schedule even more. Secondly, she is not fully convinced that her sleep schedule is detrimental and needs fixing. Thirdly and finally, the client gets demotivated very easily to improve her sleep schedule. These problems contribute to her terrible sleep schedule and only reinforce it in such a way that makes it worse. In addition, the client is also highly concerned about her privacy, so she is hesitant to use commercial applications of similar purpose. Furthermore, the client is also hesitant about using paper records, as she finds it very inefficient. 

## Rationale for Proposed Solution

As a solution to the client's problem, the proposed solution is a desktop application that will be able to keep track of the client's sleep schedule and indicate the amount of sleep that the client had per week. The application will evaluate whether the client had a sufficient amount of sleep or not each day on a calendar with three colors, Green, Yellow, and Red, with Green being the best and Red being the worst. Furthermore, the application will have a weekly goal-setting function that will help the client stay motivated to improve their sleep schedule. The app will also compare the client's daily sleep amount with the amount of sleep deemed necessary to stay healthy with a linear graph, thus, urging the client to take action to improve their sleeping habit. In order to address the client's security concerns, the application will establish a secure profile page personalized to the client. 

## Success Criteria
1. The application allows the client to enter sleep data (hours of sleep) and record it(save it)
<br>`[issue tackled: "hard time keeping track of her sleep schedule"]`

3. The application is able to present a calendar that indicates the sleep hours of each day
<br>`[issue tackled: "hard time keeping track of her sleep schedule"]`

4. The application can also indicate the quality of sleep per day with three colors on the calendar (Red, Yellow, and Green)
<br>`[issue tackled: "not fully convinced that her sleep schedule is detrimental"]`

5. The application allows the client to set weekly goals and track the progress
<br>`[issue tackled: "gets demotivated very easily to improve her sleep schedule"]`

6. The application graphically analyzes the sleeping trend of the client (Compare the client's sleep with a linear model of minimum necessary sleep -> times x hours of sleep
<br>`[issue tackled: "gets demotivated very easily to improve her sleep schedule"]`

7. The application provides a secure profile page for the client
<br>`[issue tackled: "highly concerned about her privacy"]`


# Criteria B: Design

## System Diagram

![Wireframe Diagram-Page-1 drawio](https://github.com/OswellSkg/comsci_IA/assets/112055140/f64ddc6d-5d0b-4e31-8a3d-9bda5c710160)

<i>Fig. 1</i> This is the system diagram for the application.

This system diagram visually represents the system as well as the components of the application that will be programmed. It clarifies relationships between compenents. For instance, it is clear from the diagram that the NightlyInsight.db database will bilaterally connect to the app's both python and kivyMD files. These programs will be receiving input from the keyboard and outputting through the laptop's screen.

## Wireframe Diagram 

<img width="542" alt="Screen Shot 2023-11-04 at 13 40 45" src="https://github.com/OswellSkg/comsci_IA/assets/112055140/bdb07a2e-3f78-4825-a6f5-f20897c635ef">

<i>Fig. 2</i> This is the wireframe for the application. 

The wireframe diagram above is a visual representation of the application GUI structure. It consists of a Login, Home, Calendar, Register, and Data screen. The arrow represents which button leads to which screen. 

## ER Diagram

![Wireframe Diagram-Page-3](https://github.com/OswellSkg/comsci_IA/assets/112055140/58f7f7ef-5453-40b2-9c5f-0ac3fd5946d9)


<i>Fig. 3</i> This is the ER Diagram showing the two tables: users, and sleep_data.

The user's table of NightlyInsight will store the user's username as a string, password as a string, as well as their weekly goal of sleep as an integer, and finally id them. The password will be hashed for security reasons. The sleep_data will gather data of the user_id to distinguish which user's sleep the data belongs to as an integer, the amount of sleep as an integer, as well as the date of the sleep as a string. 

## Record of Tasks
https://docs.google.com/document/d/1xnl3_qt5ToP3yCtgorY-RFfB_ZXItlj07jwOs4aSo-8/edit?usp=sharing
