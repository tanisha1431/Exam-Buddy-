# HaXplore 2.0 - Submission Report Format

This is the official code repository for _YAT_ . This _type of application_ was developed during HaXplore 2.0, 
the online hackathon conducted by Codefest, the annual departmental fest of Computer Science department, IIT BHU Varanasi.

### YAT

* Harshul
* Tanisha
* Aanchal
* Yashasvi

## 📝 What's the problem that we're trying to solve and why?
In a time where online classes is the norm individuals feel disconnected as they don't get to do the collaborative group studies which not only had the potential of improving the efficiency of studies but also take out the stress out of the minds of the individuals.
While trying to solve this problem the intention is to create a tool which promotes collaborative studies among individuals in existing platforms familiar to them like Discord
## 📝 Who's affected by the pain or problem?
This issue is very prominent among the student population and also working professionals among whom collaborative study or work was a very key aspect of their lives
## 📝 Does this problem have a tendency to grow and why?
The problem has a tendency to grow and persist in such times where physically meeting people is not something everyone has the luxury to do.

## *SOLUTION*✔✔
   <p align="center" width="100%">
    <img width="33%" src="https://user-images.githubusercontent.com/77191424/112718555-d545ae00-8f19-11eb-9426-7cc0bff3d5d4.png"> 
</p>
  
</p>
  <p align="center" width="100%">            
  <b> EXAMBUDDY </b>   
  </p>
              
## Implementation

We will be using node.js serverside javascript framework to handle the various commands that the user will input. Every time the user gives a command to add some image to the database the discord url will be taken and added to the mongodb database along with the tags that the user enters based on which the various notes can be queried. There will also be an OCR functionality where the user can add the picture and the bot will perform OCR and return the recognised string along with the google search lin which can improve the efficiency of searching probable solutions.
The bot will be deployed to the cloud on heroku for testing purposes so that the bot doesn’t need to be running constantly on the local system. For the final stage we intend to deploy the bot to AWS because of the multitudes of features that it provides.

### For implementation of this project we will be using the following tech frameworks and technologies -: 
  
 <p align="center" width="100%">
    <img width="33%" src="https://user-images.githubusercontent.com/77191424/112720484-aaad2280-8f24-11eb-9bac-ab4eca9edb75.png")
"> 

## How to add the bot to your server 

<p align = "center"> Go to our website https://tanisha1431.github.io/ExamBuddy/main.html and click on Learn more and add it to your server. </p>
<img width="40%" src="https://cdn.discordapp.com/attachments/776153841288216607/825668215568465930/unknown.png"/>
Now choose the server you want to add the bot to and get collaborating on your studies.

## How to use the bot 
1.Use \
```$addPic <tag1> <tag2>...```\
 to add the picture to the database\ 
2. Use \
```$getPic <tag1> <tag2>...```\
 to get the matching pics from the database \
 3. Use \
```$addTags <tag1> <tag2>...```\
 as a reply to a pic shared by the bot to add tags \
 4.
```$search```\
 and upload pic to get the search link \
 5. 
```$read```\
 and upload pic to just read the text\
