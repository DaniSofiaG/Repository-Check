# Criteria A
## Problem Definition
Based on the interview and consultation with the client, a problem has been identified. The client has made it their new year’s goal to travel more. However, it has been a lot more difficult than they ever expected. First, the client gets discouraged from traveling because  they find it tedious to make a new plan from scratch. Another issue is that the client struggles to keep their travel plans organized and so they end up having incomplete plans. For the same reason, they complete the same tasks twice, so they end up having days where they have two different things to do at the same time. They also forget to plan for certain days or areas for their travel, like booking transportation or activities. Other travel planning resources are just for viewing and there is no way to  interact and clarify questions with the author. The client has tried to use blog posts, articles and others on the internet before, but it is difficult to use them as anything else than travel ideas because contacting editors or authors of outdated blog posts is unreliable because of the lack of contact information. When searching on the internet and other platforms, the information is all over the place, so it’s difficult to filter what the client is looking for. Finally, the client is looking to travel but does not know where or what to do.

## Client Interview
https://drive.google.com/file/d/1orSLlgucg5nOzehw_2nyuLq0gyB6MzOv/view?usp=sharing

## Rationale For Proposed Solution [Should I include using Web Sockets?]
Based on the client’s needs, an adequate solution would be a web platform dedicated to facilitating the creation of travel plans and connecting travelers around the world to share ideas and information. The proposed web app will allow users to create a portfolio of their travel plans, reuse customizable plan templates, provide a direct chat to connect users, have functions for categorization and filtering, allow the users to create tasks lists and customize calendars, and help the user select random plans. Python 3.8, Flask, Jinja 2, JavaScript, CSS and SQLite will be used to develop the web app. [1]() Python is a cross-platform language, meaning that if the client wants to run the web app in a different operating system is not likely that they will run into any problems. [2]() Flask is a framework to build web applications, it is simple and flexible using modular programming to keep the program lightweight, thus it won’t use as much space when using like other alternatives such as Django. [3]() Jinja2 is a templating language that allows you to develop HTML using a similar syntax to python which makes it easier to understand since a big part of the code is going to be done using python, this also makes it easier to present and explain to the client. [4]() JavaScript is a fast and versatile programming language for web app development that will improve the functionality of the platform by allowing more features to be integrated into it which will make the client’s experience a lot better, compared to only using a single language that might limit the feature of the web app. [5]() CSS will be used to design the website because in terms of design, it has a wider range of formatting options and uses substantially less code, making the webpage less dense for browsers to support it. Using CSS will allow the web app oto be designed according to the client’s needs and desires. In order for the network to work properly, the data provided by users must be stored, for this creating a database with a series of tables is a great option. [6]() SQLite does not need to read entire files, instead it reads and stores the necessary data, making it a great option for this website. 

## Design Statement 
I will create a travel planning web app for facilitating travel planning and connecting travelers around the world to share ideas and information about travel. The proposed web app will allow users to create a portfolio of their travel plans, reuse customizable plan templates, provide a direct chat to connect users, have functions for categorization and filtering, allow the users to create tasks lists and customize calendars, and help the user select random plans. The proposed web app will be created using Python 3.8, Flask, Jinja 2, JavaScript, CSS and SQLite. It will take around 16 weeks to complete based on the success criteria.

## Success Criteria
```[issue 1: The client gets discouraged from traveling because  they find it tedious to make a new plan from scratch]``` The web app allows the client to select and custom an already existing travel plan template.

```[issue 2: The client struggles to keep their travel plans organized]``` When the user creates a new plan on the web app, it gets saved into the same folder that is inside a page of the web app with all the user’s plans. There is also a way to save others' posts into a collection to keep ideas more organized.

```[issue 3: They end up having incomplete plans. For the same reason, they complete the same tasks twice, so they end up having days where they have two different things to do at the same time]``` For each plan the user can create a task list to help them know the things they have already planned and what they are still missing.

```[issue 4: They end up having incomplete plans. For the same reason, they complete the same tasks twice, so they end up having days where they have two different things to do at the same time]``` The user can create a customizable calendar as part of their plans.

```[issue 5: When searching on the internet and other platforms, the information is all over the place, so it's difficult to filter exactly what the client is looking for. ]``` The web platform has functions for categorization and filtering.

```[issue 6: the client is looking to travel but do not know where or what to do]``` The web platform has a function to select a random plan that the user can choose to use like it is, customize it, select another random plan or simply not accept it. 


## Client Consulatation
<img width="924" alt="Screen Shot 2023-06-20 at 13 33 45" src="https://github.com/DaniSofiaG/IA/assets/111941990/945d7f49-1437-46df-ade2-40713861c058">

<img width="921" alt="Screen Shot 2023-06-20 at 13 33 49" src="https://github.com/DaniSofiaG/IA/assets/111941990/5e5cbcba-0209-4e02-8348-4a6887e05f3b">

<img width="900" alt="Screen Shot 2023-06-20 at 13 33 55" src="https://github.com/DaniSofiaG/IA/assets/111941990/389a0c41-ef6c-473b-aa9a-6e25b2bfd548">

<img width="928" alt="Screen Shot 2023-06-20 at 13 40 11" src="https://github.com/DaniSofiaG/IA/assets/111941990/be729486-2116-4311-a472-39e43524588c">

<img width="905" alt="Screen Shot 2023-06-20 at 13 34 04" src="https://github.com/DaniSofiaG/IA/assets/111941990/4d974d78-4fc9-4367-b25a-35f5f977aceb">

<img width="916" alt="Screen Shot 2023-06-20 at 13 34 12" src="https://github.com/DaniSofiaG/IA/assets/111941990/45e8e70a-711a-4e9e-8a5e-2e5e2f197c50">

<img width="903" alt="Screen Shot 2023-06-20 at 13 34 19" src="https://github.com/DaniSofiaG/IA/assets/111941990/0b7a7f17-7d4f-43ae-a3d4-34ff095b26cd">

<img width="894" alt="Screen Shot 2023-06-20 at 13 34 25" src="https://github.com/DaniSofiaG/IA/assets/111941990/038ccaaa-5e97-46ed-b61a-cb4431642ee7">



<img width="283" alt="Screen Shot 2023-06-05 at 23 26 42" src="https://github.com/DaniSofiaG/AI/assets/111941990/0169a7db-cfe3-4d51-a352-b18a4d017a64">


Home page
Login / Registration
My Portfolio *** Success Criteria
Explore 
Inside Other's Pieces
My Boards *** Success criteria 
Users Directory
Different Users Gallery  *** Success Criteria
Chat 

# Criteria B
## Record of Tasks
### Planning:
| Task No |                  Planned Action                 |                                                                                        Planned Outcome                                                                                       | Time estimate |  Date  | Criterion |
|:-------:|:-----------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:-------------:|:------:|:---------:|
|    1    | Planning: Initial Client Meeting                | Meet with the client to understand the problem and needs. Record the consultation and upload it to the project repository.                                                                      |     40 min    |  Jun 5 |     A     |
|    2    | Planning: Brainstorming for Solutions           | Ideate solutions addressing client's issues based on problems identified.                                                                                                                    |     20 min    |  Jun 5 |     A     |
|    3    | Planning: Presentation of Proposed Solution     | Present the solution idea to the client, finalize the proposed solution, and explain the development approach. Record and upload the meeting summary.                                       |     40 min    |  Jun 6 |     A     |
|    4    | Planning: Define Success Criteria               | Create a set of success criteria based on the proposed solution and identified problems. Communicate with the client for questions, changes, and approval.                                   |     20 min    |  Jun 6 |     A     |
|    5    | Planning: Write Design Statement                | Write and upload the design statement for the project into GitHub.                                                                                                                             |     7 min     |  Jun 6 |     A     |
|    6    | Planning: Upload Communication with Client      | Collect all communication with the client, censor private information, and upload it to GitHub.                                                                                               |     20 min    |  Jun 8 |     A     |

### Design:
| Task No |                   Planned Action                |                                                                                             Planned Outcome                                                                                            | Time estimate |  Date  | Criterion |
|:-------:|:-----------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:-------------:|:------:|:---------:|
|    7    | Design: System Diagram                          | Create a system diagram for the travel planner web app. Write a footnote and upload it to GitHub.                                                                                              |     20 min    |  Jun 9 |     B     |
|    8    | Design: Wireframe Diagram                       | Create a wireframe diagram for the web app, visualize it, write a footnote, and upload it to GitHub.                                                                                        |      1 hr     | Jun 12 |     B     |
|    9    | Design: Research Algorithms                     | Research algorithms for implementing different features based on success criteria.                                                                                                           |      1 hr     | Jun 13 |     B     |
|    10   | Design: Select Algorithms                       | Select algorithms for developing specific features of the web app.                                                                                                                           |     15 min    | Jun 14 |     B     |
|    11   | Design: Create Flow Chart (Feature 1)           | Create the first flow chart for implementing an algorithm in one feature.                                                                                                                      |     30 min    | Jun 14 |     B     |
|    12   | Design: Create Flow Chart (Feature 2)           | Create a second flow chart for implementing an algorithm in another feature.                                                                                                                  |     30 min    | Jun 15 |     B     |

### Development:
| Task No |                   Planned Action                |                                                                                             Planned Outcome                                                                                            | Time estimate |  Date  | Criterion |
|:-------:|:-----------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:-------------:|:------:|:---------:|
|   13    | Development: Create Database Schema             | Design the database schema based on the web app's requirements and success criteria. Create tables for user accounts, travel plans, posts, and more.                                   |     1 hr     | Jun 16 |     C     |
|   14    | Development: Implement User Registration         | Develop user registration functionality including email validation and password hashing. Ensure data is stored securely in the database.                                              |     2 hrs    | Jun 17 |     C     |
|   15    | Development: User Login                         | Implement user login functionality, ensuring secure access with password hashing. Create user sessions and authentication.                                                        |     2 hrs    | Jun 18 |     C     |
|   16    | Development: Create Travel Plan Templates        | Develop a feature to create and customize travel plan templates based on client's needs. Ensure templates are saved securely.                                                        |     3 hrs    | Jun 19 |     C     |
|   17    | Development: Save User's Posts                  | Implement functionality to save user's travel plans and posts into a dedicated folder within the web app. Ensure organization and secure storage.                                    |     2 hrs    | Jun 21 |     C     |
|   18    | Development: Task List Creation                  | Create a task list feature for users to manage tasks in their travel plans, preventing duplication and ensuring completeness.                                                    |     3 hrs    | Jun 22 |     C     |
|   19    | Development: Customizable Calendars             | Implement customizable calendar functionality for users to manage schedules within their travel plans. Ensure customization and proper saving.                                   |     3 hrs    | Jun 23 |     C     |
|   20    | Development: Direct Chat Feature                 | Create a direct chat
## Design Overview
### > System Diagram
<img width="688" alt="Screen Shot 2023-08-02 at 10 26 08" src="https://github.com/DaniSofiaG/IA/assets/111941990/ec3af0d1-374d-40cb-bb3e-f4a9b5ada023">
[Pending]

### > Flow Charts (For the flowcharts do I have to mention that I connect to the database to get the array?)
#### Search bar method / Binary Search Algorithm
![Search Bar Algorithmv_ Binary Search- Flow Diagram](https://github.com/DaniSofiaG/IA/assets/111941990/83fb70f6-23f0-42bf-b296-6641728592a8)
Foot note: The Binary Search algorithm is used to create more effective search methods within the web app. The algorithm takes a set of data that it first cuts in half and searches one half, if the element that we’re searching for is in that half then it cuts it to half again and repeats the same process until only the desired element is left.

#### User Dashboard Organization / Quick Sort Algorithm
![User Dashboard Organization _ Quick Sort Algorithm Flow Diagram](https://github.com/DaniSofiaG/IA/assets/111941990/3db72bbf-31d4-42fc-b907-9d73f1516f12)
Foot note: The Quick Sort algorithm is used to effectiveley organize arrays. In the case of this Travel planning web app it is used to orgnnaize the the users dashboard based on the elements unique key assign to then when first stored and saved into the database.

### > Wireframe Diagram
![Wireframe Diagram (3)](https://github.com/DaniSofiaG/IA/assets/111941990/a36437a5-c389-4c68-a960-54d380ad6622)
Foot note: Wireframe diagram of the design and connectivity of the travel planner web app.
## Test Plan

| Test # | Description                                      | Type          | Planned Output                                                                                                      | Test Steps                                                                                                      |
|-------|--------------------------------------------------|---------------|--------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| 1     | Register an account                              | Unit Testing  | User's account information is recorded in the database.                                                         | 1. Click on "Register" on the homepage. 2. Fill out the registration form with email: "user.testing@gmail.com" and password "aX3483L9". 3. Click "Register". |
| 2     | Login to the application                         | Unit Testing  | User can log in using the registered account information.                                                       | 1. Click on "Login" on the homepage. 2. Enter email (user.testing@gmail.com) and password used during registration. 3. Click "Login." |
| 3     | Select and customize a travel plan template      | Unit Testing  | User can select and customize an existing travel plan template.                                                  | 1. Log in as "user.testing@gmail.com". 2. Click "Browse Templates." 3. Select a template. 4. Customize it. 5. Save the customized plan. |
| 4     | Saving plans and posts                           | Unit Testing  | User's new plans and saved posts are organized in a dedicated folder in the web app.                            | 1. Create a new plan. 2. Save other user's posts to a collection. 3. Verify the plans and saved posts are in the dedicated folder. |
| 5     | Create and manage a task list                    | Unit Testing  | User can create, manage, and track tasks in their plans.                                                        | 1. Open a plan. 2. Create tasks. 3. Mark completed tasks. 4. Verify the tasks are tracked. |
| 6     | Customizable calendar in plans                   | Unit Testing  | User can create and customize a calendar for each plan.                                                        | 1. Open a plan. 2. Create a customizable calendar. 3. Customize the calendar. 4. Verify the customized calendar is saved. |
| 7     | Direct chat with users                           | Unit Testing  | Users can directly chat with each other within the app.                                                         | 1. Find another user. 2. Initiate a chat. 3. Send and receive messages. 4. Verify direct chat functionality. |
| 8     | Categorization and filtering functions            | Unit Testing  | Users can effectively categorize and filter travel plans.                                                       | 1. Browse plans. 2. Use filter and categorization functions. 3. Verify filtered results. |
| 9     | Select a random travel plan                      | Unit Testing  | Users can select a random travel plan for inspiration.                                                            | 1. Click "Get Random Plan." 2. Choose to use, customize, select another, or reject the plan. |



<img width="283" alt="Screen Shot 2023-06-05 at 23 26 21" src="https://github.com/DaniSofiaG/AI/assets/111941990/c049c80a-ca38-470e-96d9-353cd87c5bec">

# Criteria C
### List of techniques
- If statements
- Forloops
- Variables
- CSS Styling
- Functions
- Connecting to a database
- Arrays
- OOP

## Explanation of Techniques and Evidence 
<img width="283" alt="Screen Shot 2023-06-05 at 23 26 52" src="https://github.com/DaniSofiaG/AI/assets/111941990/a46aeb3f-01e0-4974-9d55-87c9e98d182e">

### Success criteria 1
#### Issue: The client gets discouraged from traveling because  they find it tedious to make a new plan from scratch
Solution: The web app allows the client to select and custom an already existing travel plan template

#### APP ROUTE
```.py
# Plan creation and list
@app.route('/plans/<user_id>', methods=["GET", "POST"])
def plans(user_id):
   # Check if user is authenticated
   user_cookie = request.cookies.get('user_id')

   if not user_cookie or int(user_cookie) != int(user_id):
       return render_template("plans.html", message="Unauthorized access", user_id=user_id)

   if request.method == 'POST':
       # Get form data
       plan_title = request.form['plan_name']
       plan_dates = request.form['plan_dates']

       # Store the plan in the database
       with database_travel1("travel_project.db") as db:
           try:
               query = "INSERT INTO user_plans(user_id, plan_title, plan_dates) VALUES (?, ?, ?)"
               values = (user_id, plan_title, plan_dates)
               db.run_save(query, values)
               db.commit()
               msg = "Plan created successfully."

               # Redirect to prevent form resubmission
               return redirect(url_for('plans', user_id=user_id))
           except Exception as e:
               print(f"Error creating plan: {e}")
               msg = "Error creating plan. See terminal for details."

   # Retrieve user's plans
   with database_travel1("travel_project.db") as db:
       user_plans = db.search("SELECT * FROM user_plans WHERE user_id = ?", (user_id,))

   return render_template("plans.html", user_plans=user_plans, user_id=user_id)

# Copy existing plan
@app.route('/copy_plan/<user_id>', methods=["POST"])
def copy_plan(user_id):
   if request.method == 'POST':
       selected_plan_id = request.form['plan_id']

       # Retrieve the selected plan details
       with database_travel1("travel_project.db") as db:
           selected_plan = db.search
```






### Success criteria 2
#### Issue: The client struggles to keep their travel plans organized
Solution: When the user creates a new plan on the web app, it gets saved into the same folder that is inside a page of the web app with all the user’s plans. There is also a way to save others' posts into a collection to keep ideas more organized.


```.py

```





### Success criteria 3
#### Issue: They end up having incomplete plans. For the same reason, they complete the same tasks twice, so they end up having days where they have two different things to do at the same time
Solution: For each plan the user can create a task list to help them know the things they have already planned and what they are still missing.

#### HTML
```.py
</head>

<body>

   <h1>My Travel Plans</h1>

   <div class="container">
       <div id="newtask">
           <input type="text" id="taskInput" placeholder="Add Tasks">
           <button id="push" onclick="addTask()">Add</button>
       </div>
       <div id="tasks"></div>
   </div>
```




### Success criteria 4
#### Issue: They end up having incomplete plans. For the same reason, they complete the same tasks twice, so they end up having days where they have two different things to do at the same time
Solution: The user can create a customizable calendar as part of their plans.

#### HTML
```.py
<!DOCTYPE html>
<html lang="en">

<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>My Travel Plans</title>

   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/fullcalendar/3.10.2/fullcalendar.min.css" />
   <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>
   <script src="https://cdnjs.cloudflare.com/ajax/libs/moment.js/2.29.1/moment.min.js"></script>
   <script src="https://cdnjs.cloudflare.com/ajax/libs/fullcalendar/3.10.2/fullcalendar.min.js"></script>

</head>

<body>

```
```.py

   <select id="month" onchange="renderCalendar()">


   <script>
       document.querySelector('#push').onclick = function(){
           if(document.querySelector('#newtask input').value.length == 0){
               alert("Kindly Enter Task Name!!!!")
           }

           else{
               document.querySelector('#tasks').innerHTML += `
                   <div class="task">
                       <span id="taskname">
                           ${document.querySelector('#newtask input').value}
                       </span>
                       <button class="delete">
                           <i class="far fa-trash-alt"></i>
                       </button>
                   </div>
               `;

               var current_tasks = document.querySelectorAll(".delete");
               for(var i=0; i<current_tasks.length; i++){
                   current_tasks[i].onclick = function(){
                       this.parentNode.remove();
                   }
               }
           }
       }

   </script>

   <input type="number" id="year" min="1900" max="2100" value="2023" onchange="renderCalendar()">

   <div id="calendar"></div>

   <div id="eventPopover" style="display:none;">
       <h3 id="eventPopoverTitle"></h3>
       <p id="eventPopoverDescription"></p>
   </div>

   <h2>Schedule</h2>
   <form id="eventForm">
       <label for="destination">Event:</label>
       <input type="text" id="Event" name="event" required>

       <label for="date">Date:</label>
       <input type="datetime-local" id="date" name="date" required>

       <label for="description">Description:</label>
       <input type="text" id="description" name="description" required>

       <button type="button" onclick="addEvent()">Add Event</button>
   </form>

   <script>
       document.addEventListener('DOMContentLoaded', function () {
           renderCalendar();
       });

       function addTask() {
       }

       function renderCalendar() {
           const calendarContainer = document.getElementById('calendar');
           const monthSelect = document.getElementById('month');
           const yearInput = document.getElementById('year');
           const selectedMonth = parseInt(monthSelect.value);
           const selectedYear = parseInt(yearInput.value);

           calendarContainer.innerHTML = '';

           const calendar = $(calendarContainer).fullCalendar({
               header: {
                   left: 'prev,next today',
                   center: 'title',
                   right: 'month,basicWeek,basicDay'
               },
               editable: true,
               events: [],
               eventClick: function (calEvent, jsEvent) {
                   showEventPopover(calEvent, jsEvent);
               }
           });


           const events = [
               {
                   title: 'Meeting',
                   start: '2023-12-07T10:00:00',
                   end: '2023-12-07T12:00:00',
                   description: 'Discuss project plans'
               },
           ];

           calendar.fullCalendar('renderEvents', events, true);
       }

       function showEventPopover(calEvent, jsEvent) {
           const eventPopover = document.getElementById('eventPopover');
           const eventPopoverTitle = document.getElementById('eventPopoverTitle');
           const eventPopoverDescription = document.getElementById('eventPopoverDescription');

           eventPopoverTitle.textContent = calEvent.title;
           eventPopoverDescription.textContent = calEvent.description;

           eventPopover.style.display = 'block';
           eventPopover.style.left = `${jsEvent.pageX}px`;
           eventPopover.style.top = `${jsEvent.pageY}px`;

           document.addEventListener('click', function closePopover(event) {
               if (!event.target.closest('#eventPopover')) {
                   eventPopover.style.display = 'none';
                   document.removeEventListener('click', closePopover);
               }
           });
       }

       function addEvent() {
           const eventForm = document.getElementById('eventForm');
           const eventData = {
               title: eventForm.elements.event.value,
               start: eventForm.elements.date.value,
               description: eventForm.elements.description.value,
           };

           $('#calendar').fullCalendar('renderEvent', eventData, true);
           eventForm.reset();
       }
   </script>
</body>

</html>

```


The interactive calendar and the to-do list functions of the webpage are made with Java script inside the html of the inside_my_plans page of the code and they are meant to help the user organize and give more detail into every individual plan. In the case of the to-do list the java script handles the onclick function of the button add tasks and the functions to save and delete them. The list is directly connected to the div in the html. In the case of the calendar, I decided to use the full calendar library to help me make it interactive, thus the calendar can have different events that can be moved around and modified and added as pop-ups as visual representations inside the calendar of each individual plan. 




Success criteria 5
Issue: When searching on the internet and other platforms, the information is all over the place, so it's difficult to filter exactly what the client is looking for
Solution: The web platform has functions for categorization and filtering.

```.py

```





### Success criteria 6
#### Issue: The client is looking to travel but do not know where or what to do
Solution: The web platform has a function to select a random plan that the user can choose to use like it is, customize it, select another random plan or simply not accept it. 

#### APP ROUTE
```.py

@app.route('/generate_random_plan/<user_id>', methods=['GET'])
def generate_random_plan_route(user_id):
   # Choose random plan
   if existing_plans:
       random_plan = random.choice(existing_plans)

       plan_details = {
           "plan_id": random_plan["plan_id"],
           "title": random_plan["title"],
           "destination": random_plan["destination"],
           # Add more details as needed
       }

       json_response = f'{{"plan_id": {plan_details["plan_id"]}, "title": "{plan_details["title"]}", "destination": "{plan_details["destination"]}"}}'

       return json_response
   else:
       return '{"message": "No existing plans."}'

```


The Random Plan generator allows the user to click a button and be given any random plan template that is saved into the database of the webpage. In the future I would like to allow users to make their plans public or private so that they can choose if their plans are shown both in the explore page and in the random plan generator.





















### Profile + Outsider Profile View: Direct connection with other users to get information
#### Success Criteria: ```[issue 5: lack of contact information on travel posts]```







# Criteria D
## Complete Project Code 
<img width="283" alt="Screen Shot 2023-06-05 at 23 27 02" src="https://github.com/DaniSofiaG/AI/assets/111941990/ccb44162-bcd8-4acb-86a9-9348a241a910">

# Criteria E
## Evaluation
## Recommendations
<img width="287" alt="Screen Shot 2023-06-05 at 23 34 06" src="https://github.com/DaniSofiaG/AI/assets/111941990/235d8d3c-adaf-4964-b5b6-e2e369aafb18">

# Bibliography 
