# introductions-2024
This repository was created by Eric Pogue and ChatGPT to be a template to create an "Introductions" website. 

## The prompt given to ChatGPT was:
Create a html and css based application that introduces yourself and include the following items:
    Your first and last name
    The name that you would prefer to be called if that is different from your first name
    Your current or most recent job title
    A summary of your current or most recent job responsibilities
    Your hobbies or special interests
    Your reasons for pursuing this degree
    Your reasons for taking this course
    A fun fact about yourself that will help your classmates remember you

## ChatGPT responded with:
As an AI, I don't have personal information such as a name, job title, or hobbies. However, I can create a template based on your request. You can fill in your personal details where necessary. Below is a basic HTML and CSS code to create a webpage introducing yourself:


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

You can replace the placeholders (like [Your Full Name]) with your personal information. This code provides a simple web page with sections for each of the items you've listed. The CSS is basic, providing a clean and readable layout. You can further customize the style and layout to fit your preferences.

##The next prompt given to ChatGPT was:
Describe how to use GitHub pages to deploy an introductions website.

## ChatGPT responded with:
Deploying an introductory website using GitHub Pages is a straightforward process. GitHub Pages allows you to host a website directly from a GitHub repository. Here's a step-by-step guide to get your introduction website live:

1. Create a GitHub Account
If you don't already have a GitHub account, go to GitHub and sign up.

2. Create a New Repository
After logging in, click the "+" icon in the upper-right corner and select "New repository".
Name your repository. For a user site, the repository must be named [username].github.io where [username] is your GitHub username. For a project site, it can be any name.
Choose if you want the repository to be public (anyone can see) or private (only you can access).
Initialize the repository with a README file (optional).
Click "Create repository".
3. Add Your Website Files
Clone the repository to your computer using Git, or use the GitHub interface to upload files.
Add your HTML, CSS, and any other files that make up your website. At least one file should be named index.html as it will be the entry point of your site.
Commit and push your changes if you're using Git.
4. Enable GitHub Pages
Go to your repository on GitHub.
Click on the "Settings" tab.
Scroll down to the "GitHub Pages" section.
Under "Source", select the branch you want to deploy (usually main or master).
Click "Save", and GitHub Pages will be activated.
5. Accessing Your Website
Once GitHub Pages is enabled, your site will be available at https://[username].github.io (for a user site) or https://[username].github.io/[repository] (for a project site).
It may take a few minutes for your site to be live. Refresh the page after a short while if it doesn't appear immediately.
6. Customizing and Updating
To update your site, simply make changes to your files and push them to the GitHub repository. GitHub Pages will automatically update your site.
You can also customize your domain, use Jekyll for blogging, or add custom 404 pages. Check the GitHub Pages documentation for more advanced features.
Additional Notes
GitHub Pages only supports static websites (HTML, CSS, and JavaScript). Server-side code (like PHP or Python) won't run.
Your website is public, and the source code is visible to anyone.
GitHub Pages is an excellent option for hosting simple personal, project, or portfolio websites. It's free and relatively easy to use, especially if you're already familiar with Git and GitHub.

