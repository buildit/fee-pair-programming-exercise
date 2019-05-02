This overview explains BuildIt's front-end on-site coding challenge. If you have any questions while reading please email your point of contact for clarification.

# Quick Overview

If you don't want to read the text below in detail (which we recommend) here is everything you need to know in bullet point form.

* You *must* come to the interview with the following 
  * Bring a scaffold (Create React App, Angular CLI) checked into public version control (Github, BitBucket)
  * Bring an API key generated from [OMDb API](http://www.omdbapi.com/apikey.aspx)
  * Bring your laptop with the scaffold ready for coding
* Interview is a 2 hour test writing a simple single page app
* You are required to write some tests

# Interview Prep

Before arriving, we ask that you bootstrap an application using your favorite framework (React, Angular, Vue, etc) and configure testing (Jest, Jasmine, Mocha, etc). Please push this setup to public version control (Github, Bitbucket, ect) and email your contact a link to the repo.

1. Setup a front-end coding environment capable of handling tests and API calls (Create React App, Angular CLI, ect)
    1. Place your coding environment in version control
    1. Email your BuildIt contact with a link to your public repo
1. Get an API key from the [OMDb API](http://www.omdbapi.com/apikey.aspx)
    1. Bring this to your interview for API calls

# The Interview

You'll be coding with BuildIt's front-end developers to complete the following criteria.

1. Print an OMDb search query as a list of movies on a single page (example https://www.omdbapi.com/?s=star_wars&apikey=YOUR_KEY)
1. Make 3 different movie search query buttons
1. Clicking a button replaces printed movies with the query's results

*Note: Please don’t do any application coding yet. We want to see how you setup a project, coding will be done during the interview.

The coding test is up to 2 hours and you might not finish. If you don't that's okay, you will be evaluated based upon the grading criteria instead of project completion.

**DISCLAIMER**: If you take longer than 40 minutes on a single task, we may end the test early. As you may not have enough time to finish.

## Test Criteria

Please write the following tests to demonstrate code integrity with the least amount of code. Mocks, substitution, and other techniques are completely valid.

* Certify an HTTP call is made
* Clicking a button triggers intended functionality
* Verify that movie data is printed in the DOM from a returned call

## What resources are okay?

You're allowed to use search engines and tools such as Stackoverflow during the coding exercise. The goal here is to demonstrate how you work on a project.

## What criteria will I be evaluated on?

Candidates will be evaluated on the following criteria and how they approach it. While you're coding we encourage you to walk us through your thought process as it will play a large part in your scoring.

- Initial project setup
- Usage of JavaScript in relation to a production environment
- API Consumption
- Finalized code architecture
- Ability to work with your selected framework and tools
- Communication with code pair members
- Quality of written tests

## What to bring?

For the interview we ask that you please bring your laptop with the version controlled coding environment you've prepared. Candidates will be asked to complete the coding test with the setup they've brought.

# Take-Home Version

If you're planning to complete this test at your own pace please do the following. Submissions will be graded on and expected to have this additional criteria.

* Clicking a movie routes to a single page about that movie
* Style the application visually
* Test coverage across the app

## Submitting Your Take-Home

When submitting your takehome please ensure the following is complete.

* Provide a README.md file that documents:
  * How to run / build / test your creation
  * Your thought process when creating the solution
  * Any tradeoffs you made
  * anything you might implement with more time (features, fixes, technical debt corrections etc)
* If your solution uses a package manager, please ensure that there are no globally installed dependencies required to build / run your app. This avoids environment issues when trying to build your solution
  * If you have to have global packages please explain why
* Host your code on a public web server of your choice
* Submit your code into a public git repository of your choice (github / bitbucket etc)
