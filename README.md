# 09 Node.js Homework: Professional README Generator

## Task

To create a command-line application that dynamically generates a professional README.md file from a user's input using the [Inquirer package](https://www.npmjs.com/package/inquirer). The [Professional README Guide](https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide) was used as a template to create a high-quality, professional README. 

The application is invoked by using the following command:

```bash
node index.js
```

## User Story

```md
AS A developer
I WANT a README generator
SO THAT I can quickly create a professional README for a new project
```

## Acceptance Criteria

```md
GIVEN a command-line application that accepts user input
WHEN I am prompted for information about my application repository
THEN a high-quality, professional README.md is generated with the title of my project and sections entitled Description, Table of Contents, Installation, Usage, License, Contributing, Tests, and Questions
WHEN I enter my project title
THEN this is displayed as the title of the README
WHEN I enter a description, installation instructions, usage information, contribution guidelines, and test instructions
THEN this information is added to the sections of the README entitled Description, Installation, Usage, Contributing, and Tests
WHEN I choose a license for my application from a list of options
THEN a badge for that license is added near the top of the README and a notice is added to the section of the README entitled License that explains which license the application is covered under
WHEN I enter my GitHub username
THEN this is added to the section of the README entitled Questions, with a link to my GitHub profile
WHEN I enter my email address
THEN this is added to the section of the README entitled Questions, with instructions on how to reach me with additional questions
WHEN I click on the links in the Table of Contents
THEN I am taken to the corresponding section of the README
```

## Submission

The following steps showcase how to use the app. A video is availbe as well here: https://drive.google.com/file/d/1Jp_SKQXlK0p8aOSD03_nVbvEepKPjmzR/view

```md

1. Open terminal in the location of "index.js"

2. Enter "node index.js"

3. Answer all the questions

4. Once all the questions have been answered, the README will be created in same folder as "index.js"

```

A GIF going through a sample example is shown below:


![Sample Example](./Assets/Professional%20README%20Generator.gif)
    

