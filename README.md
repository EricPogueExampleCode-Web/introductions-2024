# Introductions (2024)
This repository was created by Eric Pogue and ChatGPT to be a template for creating an "Introductions" website.

Additional GitHub Page information can be found at [GitHub Pages](https://pages.github.com/). Also, there is a 5-minute 
[Hello World with GitHub Pages](https://www.lewis.education/?cpsc=sp24-cpsc-20000-002#/activity/hello-world-web-part-1)
video tutorial that was created for the Lewis University ”Introduction to Computer Science” class that might be helpful. 

# Activity / Assignment
Follow the instructions below to create your own personal Introductions webpage using GitHub Pages. As always, be careful 
about sharing confidential information. 

---

# Background

## The initial prompt given to ChatGPT was:
```
Create an HTML and CSS-based application that introduces yourself and includes the following items:
    Your first and last name
    The name that you would prefer to be called if that is different from your first name
    Your current or most recent job title
    A summary of your current or most recent job responsibilities
    Your hobbies or special interests
    Your reasons for pursuing this degree
    Your reasons for taking this course
    A fun fact about yourself that will help your classmates remember you
```

This is provided only as background. No action is needed on your part yet. 

## ChatGPT responded with:
As an AI, I don't have personal information such as a name, job title, or hobbies. However, I can create a template based on your 
request. You can fill in your personal details where necessary. Below is a basic HTML and CSS code to create a webpage introducing 
yourself:
```
<!DOCTYPE html>
<html>
<head>
    <title>About Me</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            line-height: 1.6;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .main-info {
            background: #333;
            color: #fff;
            padding: 20px;
        }
        .main-info h1 {
            margin: 0;
        }
        .hobbies, .career, .course {
            background: #e7e7e7;
            padding: 15px;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="main-info">
            <h1>Your Name: [Your Full Name]</h1>
            <p>Preferred Name: [Your Preferred Name]</p>
            <p>Current/Recent Job Title: [Your Job Title]</p>
        </header>

        <section class="career">
            <h2>Job Responsibilities</h2>
            <p>[Summary of your current or most recent job responsibilities]</p>
        </section>

        <section class="hobbies">
            <h2>Hobbies and Special Interests</h2>
            <p>[Your hobbies or special interests]</p>
        </section>

        <section class="career">
            <h2>Reasons for Pursuing This Degree</h2>
            <p>[Your reasons for pursuing the degree]</p>
        </section>

        <section class="course">
            <h2>Reasons for Taking This Course</h2>
            <p>[Your reasons for taking this course]</p>
        </section>

        <section class="fun-fact">
            <h2>Fun Fact</h2>
            <p>[A fun fact about yourself]</p>
        </section>
    </div>
</body>
</html>
```

You can replace the placeholders (like [Your Full Name]) with your personal information. This code provides a simple 
web page with sections for each of the items you've listed. The CSS is basic, providing a clean and readable layout. 
You can further customize the style and layout to fit your preferences.

## Eric’s Comments:
Wow. I’m impressed with ChatGPT’s response. I have taken the generated code and added it to this template GitHub 
repository along with adding this README.md file and an MIT LICENSE file. 

Note that the initial prompt was challenging to craft and required several iterations before ChatGPT responded with a
solid response. 

Did you notice that ChatGPT failed to style the “Fun Fact” section? Can you fix that?

# Second ChatGPT Prompt Requesting Instructions
The next prompt directed at ChatGPT occurred in three parts and included:
1. Describe how to use GitHub Pages to deploy an introductions website using a GitHub repository as a template.
2. Move and renumber step 3 so that it is step 2. 
3. Update the instructions so that we make the code changes within GitHub instead of cloning the repository.

Note that editing the file on GitHub (instead of cloning them and editing them locally) is “wrong” in software 
development. However, we are doing it here for simplicity. Also, note that I am a firm believer in CI/CD so it
was important to me that GitHub Pages hosting (step 3 initially) occurred before updating the code (step 2
initially).

## After all three prompts, ChatGPT responded with:
Certainly! Here's the updated guide where the code changes are made directly within GitHub, without cloning the repository:

## Deploying a Project Site on GitHub Pages Using a Template Repository

### Step 1: Find and Use a Template Repository

#### Search for a Template
- Go to GitHub and find a repository that's set up as a template for an introductions website or a similar project.
- Look for repositories with a "template" badge.

#### Create a New Repository from the Template
- Click on the "Use this template" button on the template repository's page.
- Name your repository.
- Optionally, add a description.
- Choose whether your repository should be public or private.
- Click "Create repository from template".

### Step 2: Enable GitHub Pages

#### Repository Settings
- Go to your GitHub repository in a web browser.
- Click on the "Settings" tab, then scroll down to the "GitHub Pages" section.

#### Source Selection
- Under "Source", select the branch you want to publish (usually `main` or `master`).
- Click "Save" to activate GitHub Pages.

### Step 3: Customize Your Website Directly on GitHub

#### Edit Files on GitHub
- Navigate to your repository's main page on GitHub.
- Locate the `index.html` file or other files you wish to edit.
- Click on the file to view it, then click the pencil icon (Edit this file) in the top right to start editing.

#### Make and Commit Changes
- After making your changes in the web editor, scroll down to the "Commit changes" section.
- Enter a commit message that describes your changes.
- Choose to commit directly to the main branch.
- Click "Commit changes".

### Step 4: Accessing Your Website

- Your project site will be available at `https://[username].github.io/[repository-name]/`.
- Replace `[username]` with your GitHub username and `[repository-name]` with your repository name.
- It may take a few minutes for the site to go live. If it's not immediately available, wait a bit and then refresh.

### Step 5: Update Your Site

- To update your site, repeat the process in Step 3: edit files and commit changes directly on GitHub.
- GitHub Pages will automatically update your site with these changes.

### Additional Notes

- GitHub Pages supports only static content.
- Public repositories mean all source code is publicly visible.
- For more advanced features like custom domains or Jekyll themes, refer to the GitHub Pages documentation.

In this updated guide, the customization of the website is done through GitHub's web interface, eliminating the need 
to clone the repository locally. This approach is straightforward and convenient for making quick edits or for users 
less familiar with Git.

## Eric’s Comments
It took quite a lot of time to craft the ChatGPT prompts, but I like the resulting instructions. Note that this 
repository is the GitHub template repository that you should use in the instructions above. 

There should also be a step 6. ChatGPT did not know that I added a README.md file.

### Step 6: Update README.md File

- Remove all of the text in your README.md file.
- Add your application name and add yourself as the Author.
- Add credits for Eric Pogue, ChatGPT, and for this site where you utilized the template.
