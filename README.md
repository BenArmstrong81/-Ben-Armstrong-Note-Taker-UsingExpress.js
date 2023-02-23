# Ben-Armstrong-Note-Taker-UsingExpress.js

## Your Task
Your assignment is to modify starter code to create an application called Note Taker that can be used to write and save notes. This application will use an Express.js back end and will save and retrieve note data from a JSON file.
The application’s front end has already been created. It's your job to build the back end, connect the two, and then deploy the entire application to Heroku.
## User Story
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
## Acceptance Criteria
```
GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page
WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
WHEN I enter a new note title and the note’s text
THEN a Save icon appears in the navigation at the top of the page
WHEN I click on the Save icon
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes
WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column
WHEN I click on the Write icon in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column
```
## Mock-Up
The following images show the web application's appearance and functionality:
![Existing notes are listed in the left-hand column with empty fields on the right-hand side for the new note’s title and text.](./Assets/11-express-homework-demo-01.png)
![Note titled “Balance accounts” reads, “Balance account books by end of day Monday,” with other notes listed on the left.](./Assets/11-express-homework-demo-02.png)

## Getting Started
On the back end, the application should include a `db.json` file that will be used to store and retrieve notes using the `fs` module.
The following HTML routes should be created:
* `GET /notes` should return the `notes.html` file.
* `GET *` should return the `index.html` file.
The following API routes should be created:
* `GET /api/notes` should read the `db.json` file and return all saved notes as JSON.
* `POST /api/notes` should receive a new note to save on the request body, add it to the `db.json` file, and then return the new note to the client. You'll need to find a way to give each note a unique id when it's saved (look into npm packages that could do this for you).

## Bonus
You haven’t learned how to handle DELETE requests, but this application offers that functionality on the front end. As a bonus, try to add the DELETE route to the application using the following guideline:
* `DELETE /api/notes/:id` should receive a query parameter that contains the id of a note to delete. To delete a note, you'll need to read all notes from the `db.json` file, remove the note with the given `id` property, and then rewrite the notes to the `db.json` file.

## Grading Requirements
* Application front end must connect to an Express.js back end.
* Application back end must store notes that have a unique id in a JSON file.
* Application must be deployed to Heroku.
* Application deployed at live URL.
* Application loads with no errors.
* Application GitHub URL submitted.
* GitHub repository contains application code.
* Application console is free of errors.
* Repository has a unique name.
* Repository follows best practices for file structure and naming conventions.
* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.
* Repository contains multiple descriptive commit messages.
* Repository contains quality README file with description, screenshot, and link to deployed application.
### Bonus: +10 Points
* Application allows users to delete notes.
## Review
You are required to submit BOTH of the following for review:
* The URL of the functional, deployed application.
* The URL of the GitHub repository, with a unique name and a README describing the project.

## What I Learned
We had a great introduction to Insomnia and Heroku this week which we build upon previous weeks Node.js classes. We touched upon Routes, Get/Fetch/Push, data persistence, modula routing, middelware just to name a few subjects. 

## What Problems Did we Solve?
We started with a front end file and needed to build out the back end. This I found a challenge as my skills naturally gravitate to front end development. 

# Installation
N/A - Depolyed onto live Website using Heroku.

# Usage
To use and view this challenge you can view the deployed application via the following ***link*** BEN TO AMEND ONCE LIVE

The following image's shows the web application's A) Working Console which includes User Input and all Tests passing, B) Deployed HTML file within the Browser:

![My Web Development Portfolio webpage includes a navigation bar, a professional head shot image, multiple links (placeholders at this stage) to projects completed within the UniSA Full Stack Web Development course, and working links to contact me - even download an updated resume.](./images/Ben_Armstrong_OOP_TeamProfileGenerator_ScreenShot_WorkingConsole.PNG)
![My Web Development Portfolio webpage includes a navigation bar, a professional head shot image, multiple links (placeholders at this stage) to projects completed within the UniSA Full Stack Web Development course, and working links to contact me - even download an updated resume.](./images/Ben_Armstrong_OOP_TeamProfileGenerator_ScreenShot_DeployedHTML.PNG)

# Credits
With special thanks to the UniSA Full Stack Web Development Class.

# License

Please refer to the LICENSE in the repo.
