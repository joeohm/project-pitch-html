 # Final Project Pitch

## **Overall idea **

We want to make a birthday reminder app where you can add a person’s date of birth and get a reminder by e-mail in advance of the birthday.
The registered birthday should include information about the person, and settings for when the reminder should be sent, along with any other information the user wants to see in the reminder such as birthday present info.


## **Technological stack **

### Frontend

- React
- Redux
- React Router
- Styled components
- Material UI

### Backend

- Node
- Express
- MongoDB
- Nodemailer
- CRON scheduler

### Other

- Gmail SMTP server
- GitHub - repository
- Figma/Trello - for task management
- JamBoard


## Pages *- example*

- Sign in/sign up
- Registered birthdays
- Add new birthday
- Detail view for single birthday - (show/edit/delete)
- (optional) Settings page
- (optional) Landing page with “coming-up birthdays”


## Roadmap

### Stage 1

At the end of stage 1 we want to have:

- A complete design sketch in Figma
- This should show what the page looks like in different devices (phone, tablet, desktop, big screen) and all different pages
- Integrate with SMTP server, and set up CRON job

### Stage 2

At the end of stage 2 we want to have:

- Backend with functionality for adding birthdays
- Frontend set up with Redux, routing and basic components
- Basic styling and layout
- Implement Material UI listview for registered birthdays


### Stage 3

At the end of stage 3 we want to have:

- A working authentication
- Backend with functionality to edit and delete a birthday
- Hook up CRON job with data from backend, check if there is a birthday reminder for that day and send it out to the user
- A working form in frontend for adding a new birthday
- Single birthday page


### Stage 4

In stage 4 we want to tie the knots and:

- Polish the styling and get UX feedback from the community.
- Analyse and implement feedback


### Stage 5

- Stretch goals

## MVP and Stretch goals

### MVP

- Login
- Lists all registered birthdays
- Add new birthday
- Send e-mail with birthday reminder through SMTP server (Gmail)


### Stretch goals

- Different views for registered birthdays, for example list/cards/calendar
- Landing page with info about “birthdays coming up” (within 30 days) 
- Settings page for default birthday reminders, with possibility to override in each specific birthday
- Advanced settings like ”I don’t know the exact date of birth” which option to specify a range


## **Team members**

*Joel Öhman, Nina Berggren, Viktor Svensson*

## Designs

https://jamboard.google.com/d/13BqfrsojkzIkIAyj-z56PwOwxkOAvQLu_TrhRl_Aceo/viewer?f=0