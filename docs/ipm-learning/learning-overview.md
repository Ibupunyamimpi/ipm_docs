# IPM Learning Platform Staff Guide

Welcome to the user guide! This document can be used to get up and running as a Staff member of the new IPM Learning Platform.

The application is separated into 2 sections, Content and Orders. Content deals with the creation of Course, Bootcamps, Videos, Quizzes, and Events, while Orders deals with user orders and payments.

Links:
- Home Page https://ipm-learning-ivcyg.ondigitalocean.app/

---

## Content

1) Create a Category. (Examples: Marketing, Accounting, Personal Growth, etc)


2) Create a Course (choose a type: Course, Bootcamp, Event)
  A) Course: this is the default type, designed to have several content modules (Video, Text, Quiz)
  B) Bootcamp: similar to a Course but with the addition of Event content modules
  C) Event: a single Event content module

4) Create Content Modules (Videos, Events, Text, Quizzes) and assign the Content Modules to a Course

![](https://ipm-media.sgp1.digitaloceanspaces.com/staff-guide/overview.png)

### A) Video: 
    - Click "+ Add" next to video from the menu
    - Choose an exisiting course from the drop down menu, add a title and description (the URL slug is created automatically)
    - Select an order for the content in the course. For example, the first content module should have a value of 1, the second a value of 2, and so on. This can be re-arranged later.
    - Add the time required to complete the module under Duration (free form text)
    - Add a forum link to Rumii (optional)
    - Add the Youtube video ID: find the Youtube video link and grab the ID at the end
      - Example: full link https://www.youtube.com/watch?v=_NeJ3Kg6OUo
      - ID: _NeJ3Kg6OUo (keep this part only)
 
 ![](https://ipm-media.sgp1.digitaloceanspaces.com/staff-guide/create_video.png)
 
 ### B) Text
    - Same process as the Video content
    - Text Content section accepts Markdown text for formatting, it is recommended to create the draft content in a Markdown editor (https://stackedit.io/app) and then copy/paste the code into Text Content box
   
  ![](https://ipm-media.sgp1.digitaloceanspaces.com/staff-guide/create_text.png)
  
 ### C) Quiz
      1) Create a quiz and assign it to a course, select order
      2) Create quiz questions (1 to 100)
        - Type the question, the options, and the answer
        - The answer text must be the EXACT same as the correct option!
 
 ![](https://ipm-media.sgp1.digitaloceanspaces.com/staff-guide/create_quiz.png)
  ![](https://ipm-media.sgp1.digitaloceanspaces.com/staff-guide/add_quiz_question.png)
    
Tips:
- Don't mark a Course as 'active' until all Content Modules have been added and it is ready for purchase
- Click the content module category (example: 'Videos') to see all Video content modules


## Orders

COMING SOON


## For Admins
- To create a new staff user, scroll to the bottom of the menu panel and select 'Users'
- Add a username and password, then make sure both 'Active' and 'Staff' check boxes are selected
- Next select 'content_staff' and click the '->' button to add the new user to the Content Staff group
