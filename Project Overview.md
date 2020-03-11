# Project Overview

## Project Schedule

This schedule will be used to keep track of your progress throughout the week and align with our expectations.  

You are **responsible** for scheduling time with your squad to seek approval for each deliverable by the end of the corresponding day, excluding `Saturday` and `Sunday`.

|  Day | Deliverable | Status
|---|---| ---|
|Day 1| Gallery In Jquery| Completed
|Day 1| Wireframes / Priority Matrix / Timeline | Incomplete
|Day 3| Core Application Structure (HTML, CSS, etc.) | Incomplete
|Day 4| MVP & Bug Fixes | Incomplete
|Day 5| Final Touches | Incomplete
|Day 6| Present | Incomplete


## Project Description

Use this section to describe your final project and perhaps any links to relevant sites that help convey the concept and\or functionality.
 
 A portfolio website showcasing all the projects done in class

## Google Sheet

Include link to your google sheet here.  Here is the sample [Juan Guzman](https://docs.google.com/spreadsheets/d/1avtWUBuFSA1Irkpus9lx_NYoQkLzzQKcjvZNbn35-bA/edit#gid=0) 

## Wireframes

Upload images of wireframe to cloudinary and add the link here with a description of the specific wireframe. Do not include the actual image and have it render on the page.  

[https://www.figma.com/](https://www.figma.com/)
[https://mockflow.com/app/#Wireframe](https://mockflow.com/app/#Wireframe)

[My Wireframe1](https://res.cloudinary.com/dbrdhogvw/image/upload/v1583780565/IMG_7780_rgnvpr.jpg)

[My Wireframe2](https://res.cloudinary.com/dbrdhogvw/image/upload/v1583780566/IMG_7566_wt7cuq.jpg)

[My Wireframe3](https://res.cloudinary.com/dbrdhogvw/image/upload/v1583780563/IMG_7521_ikff1i.jpg)

## Time/Priority Matrix 

Include a full list of features that have been prioritized based on the `Time and Priority` Matix.  This involves drawing a a square.  In the middle of the square, on the x axis draw a line.  The most left part of the line should start with 0hrs and the end of the line should include 2hrs.  This line will be used to estimate how much time any one feature will take to complete. 

Now draw a vertical line on the y axis.  The top of this line should have `High` and the bottom `Low`.  This line will be used to assign a priority to to each feature you wish to include in the project.  

Now create a separate list starting with A and assign it one of the features.  Continue to assign each feature a letter.  Once complete add each letter to the matrix assigning based on what your feel it's prioirty is an how long it will take to implement. If any one feature takes longer than 2hrs to complete than break it down into smaller tasks and reassign them a new letter. 

Once complete tally up the time and determine how long the project will take to complete. Now break those features into MVP and PostMVP so you can guarantee you will have a fully functioning project to demo. 

[Time-Priority Matrix](https://res.cloudinary.com/dbrdhogvw/image/upload/v1583850477/IMG_3911_qbouyv.jpg)

### MVP/PostMVP - 5min

The functionality will then be divided into two separate lists: MPV and PostMVP.  Carefully decided what is placed into your MVP as the client will expect this functionality to be implemented upon project completion.  

#### MVP (examples)

- Gallery
- About
- Contact
- Hamburger Menu
- Responsiveness

#### PostMVP 

- Animation the First Div
- Animate gallery showing up
- Animate heading
- Animate Contact form

## Functional Components

Based on the initial logic defined in the previous sections try and breakdown the logic further into functional components, and by that we mean functions.  Try and capture what logic would need to be defined if the game was broken down into the following categories.

Time frames are also key in the development cycle.  You have limited time to code all phases of the game.  Your estimates can then be used to evalute game possibilities based on time needed and the actual time you have before game must be submitted. It's always best to pad the time by a few hours so that you account for the unknown so add and additional hour or two to each component to play it safe.

| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| About me | H | 3hrs| 4hrs| 3hrs|
| Finishing Responsiveness | H | 3hrs|  |  |
| Contact | H | 5hrs| 3 | 3 |

## Additional Libraries
 Use this section to list all supporting libraries and thier role in the project. 

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description  

I took me a while but i finally used Jquery to create the board on my website

function createMyProjects(){
    for(let i =0; i < projects.length; i++){
        let $article = $(`
        <article id="3685" class="location-listing">
           <a class="project-titles" href="#">${projects[i].title}</a>
        <div class="project-image">
        <a href=${projects[i].url}>
             <img width="300" height="169" src=${projects[i].image} alt="startup matchmaker"></a>
        </div>
        </article>`)

        $('.grid-container').append($article)
    }
  }
  createMyProjects()
```
function reverse(string) {
	// here is the code to reverse a string of text
}
```

## Issues and Resolutions
 Use this section to list of all major issues encountered and their resolution.

 - Error : Couldnt get the Jquery code to pull the keys from the object. 
 - Resolution : didnt reference the object correctly "${projects[i].image}".


#### SAMPLE.....
**ERROR**: app.js:34 Uncaught SyntaxError: Unexpected identifier                                
**RESOLUTION**: Missing comma after first object in sources {} object
