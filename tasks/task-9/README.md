# Task 9 - Testing Dashboard.

## Objectives

- Learn to test Frontend React and Redux applications. 
- Learn to use StorybookJS and Jest

## Learning Resources

Here are the list of learning resources for this task. 

Topic | Resource
------------ | -------------
Getting Started with React Storybook | [Link to this resource](https://www.youtube.com/watch?v=E2c183LS4lA)
React Storybook: Design, Dev, Doc, Debug Components | [Link to this resource](https://www.youtube.com/watch?v=PF0Vi-iIyoo)
Create Powerful Interactive Style Guides with Storybook | [Link to this resource](https://www.youtube.com/watch?v=cOI_k_5iOos)
Jest Course | [Link to this resource](https://www.youtube.com/watch?v=4kNfeI37xu4&list=PLLnpHn493BHEB-YOl0APuQsrzlb3zbq3y)
Jest Crash Course | [Link to this resource](https://www.youtube.com/watch?v=7r4xVDI2vho)


## Tasks

#### Step 1: Tests for Add Website form. 

- When you write test for add website form, make sure: 
    - You show loaders properly, when the form is being submitted. 
    - Check URL validation.  
    - Test the form by keeping fields blank. 
    - Fill the form properly and test if the new website is added to the list. 
 
#### Step 2: Test website list

- When you write test for list website component, make sure: 
    - You show loaders properly, when the list is being loaded.  
    - When there are no websites in the list. You show the info message. 
    - You list all the websites properly. 
    - When there is error in loading, an error message is shown on the page. You can mock that error in Storybook + Jest. 

#### Step 3: Test log out

- Make sure when you click on log out, you're redirected to sign in page and you have cleared all local storage and sessions. Try navigating back to dashboard (without logging in( and make sure you're automatically navigated back to sign in.  

## Deliverable

- Push changes to your frontend Git Repo with tests. 
- Make sure the build passes on Travis. 


