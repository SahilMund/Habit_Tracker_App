# Habit Tracker APP :-

Habit Tracker APP using Node.JS, Express.JS, MongoDB to keep track of user's habits.

## Features :-
1. SignUp :-

```
- User can registered themselves.
- The entered password and confirm password should match.
- Email should be unique.
```

2. LogIn :-

```
- Only the registered user can login.
- Entered email and password should be valid.
```

3. Dashboard Page :-

```
- User can add new habits to track.
- User can toggle the status, These are the 3 statuses of a habit:
    Done - Mark the habit as done for a day
    Not done - Mark the habit as not done for a day
    None - User did not take any action on a habit for a day
- User can delete an habit.
- User can add/remove the habit to/from the favorites.
- User can toggle the daily/weekly view.
```

4. Dashboard [Daily View] Page :-

```
- Showing the count of total completed, InCompleted and unMarked habits.
- Showing the count of total days the user completed the habit and the count of total days the habits is entered but either             inCompleted or unmarked.
```

5. Dashboard [Weekly View] Page :-

```
- Showing the current streak of the habits.
- A view to display 7 days of each habit, User can toggle the status of the habit.
```



</ol><h2>Tools/Technologies Used</h2>
<hr>
<ul>
<li>Node.JS</li>
<li>Express.JS</li>
<li>MongoDB</li>
</ul>


## How To Use :-
<hr>

####    Step 1 :-  Clone the repo
 
 ```
git clone https://github.com/SahilMund/Habit_Tracker_App.git
 ```
####    Step 2 :- To install the dependencies

```
npm install
```

#### Step 3 :- To run the application
```
npm start
```

#### Step - 4 :- Check the application on the PORT - 8050



## Folder Structure :-

```
.gitignore
README.md
assets
   |-- css
   |   |-- dashboard.css
   |   |-- header.css
   |   |-- user_form.css
config
   |-- flash-middleware.js
   |-- mongoose.js
controllers
   |-- habit_controller.js
   |-- user_controller.js
index.js
models
   |-- habit.js
   |-- user.js
package-lock.json
package.json
routes
   |-- index.js
   |-- users.js
views
   |-- dashboard.ejs
   |-- layout.ejs
   |-- partials
   |   |-- _daily-view.ejs
   |   |-- _habit-input.ejs
   |   |-- _navbar.ejs
   |   |-- _toggle-view.ejs
   |   |-- _weekly-view.ejs
   |-- user_sign_in.ejs
   |-- user_sign_up.ejs
```
