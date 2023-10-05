# Horiseon Landing Page CSS and HTML Code Refactor

## Description

Project background: The HTML and CSS files for the original landing page is functional, but it’s not concise. The CSS contains multiple classes that share the same styling but are all listed separately, and the HTML uses divs for everything instead of specifying a semantic element. Images also do not continue any alt text.

Solution: Cleaning up the code made it easier to work with in the future, and using semantic elements improved SEO and accessibility for customers that use screen readers. Adding alt text also allows customers using screen readers understand the significance of the images on the page.

Learns: There were a handful of semantic elements that I wasn’t aware of before, and was able to apply them to this code. 

## Installation

N/A

## Usage

Link to the refactored home page can be found here: https://torfirst.github.io/lego-hero-factor/
Browser inspector can be used to examine the code.

## Credits

Starter code was taken from the UCI Boot Camp GitLab. Referred to this URL for a list of common semantic elements to replace all the divs with in the starter code: https://mailchimp.com/resources/html-semantic-elements-and-webflow-the-essential-guide/

## License

No license provided with starter code. 







Follow these instructions to create your project and deploy it to GitHub Pages:

1. Create a new repository on your GitHub account and clone it to your computer.

2. When you're ready to deploy, use the `git add`, `git commit`, and `git push` commands to save and push your code to your GitHub repository.

3. Navigate to your GitHub repository in the browser and then select the Settings tab on the right side of the page.

4. On the Settings page, select Pages on the left side of the page. On the GitHub Pages screen, choose `main` in the dropdown under Branch. Click the Save button.

5. Navigate to <your-github-username.github.io/your-repository-name> and you will find that your new webpage has gone live! For example, if your GitHub username is "lernantino" and the project is "css-demo-site", then your URL would be <lernantino.github.io/css-demo-site>.

> **Important**: It might take a few minutes for GitHub pages to display your site correctly. If your project does not deploy or display correctly, check that all file paths in your application are relative and use the right casing. GitHub is case-sensitive, an inccorect capital or lowercase letter could cause problems in deployment.

Be sure to add, commit, and push your work to see the most up-to-date version of your app!

## Grading Requirements

> **Note**: If a Challenge assignment submission is marked as “0”, it is considered incomplete and will not count towards your graduation requirements. Examples of incomplete submissions include the following:
>
> * A repository that has no code
>
> * A repository that includes a unique name but nothing else
>
> * A repository that includes only a README file but nothing else
>
> * A repository that only includes starter code

This Challenge is graded based on the following criteria: 

### Technical Acceptance Criteria: 40%

* Satisfies all of the preceding acceptance criteria plus the following code improvements:

  * Application's links all function correctly.

  * Application's CSS selectors and properties are consolidated and organized to follow semantic structure.

  * Application's CSS file is properly commented.

### Deployment: 32%

* Application deployed at live URL.

* Application loads with no errors.

* Application GitHub URL submitted.

* GitHub repository contains application code.

### Application Quality: 15%

* Application resembles mock-up provided in the Challenge instructions (at least 90%).

### Repository Quality: 13%

* Repository has a unique name.

* Repository follows best practices for file structure and naming conventions.

* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

* Repository contains multiple descriptive commit messages.

* Repository contains quality README file with description, screenshot, and link to deployed application.

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository, with a unique name and a README that describes the project.

---
© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
