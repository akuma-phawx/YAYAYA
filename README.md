# Assessment Overview 🌍

The assessment is designed to assess your skills in building a Vue 3 application using Vite, Bootstrap, Vuelidate, TypeScript, Vue Transitions, and your ability to create an interactive 3-step wizard. We have bootstrapped a project for you which you can fork. It already includes the project structure (feel free to expand it), bootstrap, vuelidate and @vue/test-utils. Follow the below:

Mockup: https://mockittapp.wondershare.com/proto/ZbRjCnXFrpggqziKM8Vsgo/sharing?view_mode=read_only

To make the current repo work netlify for instance, fork the project in Github with the following git repo: https://gitlab.onecentral.net/assessments/frontend-assessment.git
And then you can easily deploy it in Netlify. 

## 3-Step Wizard (High Priority)

Create a 3-step wizard with the following steps:

**Step 1:**

- Contains an input field.
- After typing at least 3 characters, it should perform a search using any free API of your choice and display the results. You can use for example https://data.overheid.nl/json/api/1/action/application_search?search=kaart You can put the search string into the 'search' query parameter.
- Clicking on a result should navigate to the next step.

**Step 2:**

- Displays detailed information about the clicked result from Step 1. (e.g. https://data.overheid.nl/json/api/1/action/application_show?id=4405 but feel free to display it as you want).
- Include a "Next" button to proceed to Step 3.

**Step 3:**

- Contains three input fields (First Name, Last Name, and Email) that should be validated using Vuelidate 
- When the "Submit" button is clicked, validate the inputs (only validate for 'required' and 'email'), and display a success message.

## State Persistence (High Priority)

Ensure that the wizard retains the state when navigating back and forth between the steps.

## Styling Vue Transitions (Low Priority)

- Use Bootstrap for styling.

## Vue Transitions (Low Priority)

- Use Vue Transitions for animations where needed within the wizard.

## Unit Test (Low Priority)

Include one unit test of your choice to demonstrate your testing skills. Created 2 mock files for an idea but you are free to create any unit test of your choice.

Use comments in your code! The assessment should be completed in approximately 2 hours. Please focus on the High Priority steps first and depending on your time left if any, move on to the lower priority steps.

## Submission Guidelines

Please follow these guidelines for your assignment submission:

- Fork the gitlab repo provided to you.
- Deploy the application at any platform of your choice free of charge (e.g., [Netlify](https://www.netlify.com/)).
- Include a INSTRUCTIONS.md file with instructions on how to run your project locally and any additional notes you would like to share.

Best of luck! 🌟🌟🌟
