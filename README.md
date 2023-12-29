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

## The next prompt given to ChatGPT was:
Describe how to use GitHub pages to deploy an introductions website using a GitHub repository as a template.

## ChatGPT responded with:
```
Deploying an introductory website using a GitHub repository as a template on GitHub Pages involves several straightforward steps. Here's how to do it:

### Step 1: Find a Suitable Template Repository

First, you need to find a GitHub repository that has been set up as a template for introductory websites. You can search on GitHub for repositories tagged with "template" and related to personal or introduction websites.

### Step 2: Create a New Repository from the Template

Once you find a suitable template:

1. Open the template repository.
2. Click on the "Use this template" button. This is typically located near the top right of the repository page, next to the "Clone or download" button.
3. In the new page, enter a name for your new repository. If you want a user site, name it `[username].github.io`, where `[username]` is your GitHub username. For a project site, you can choose any name.
4. Optionally, you can add a description.
5. Choose whether the new repository will be public or private.
6. Click "Create repository from template".

### Step 3: Customize Your Website

After creating your new repository:

1. Clone the repository to your local machine using Git, or you can edit files directly on GitHub.
2. Customize the HTML, CSS, and other files in your repository to fit your content and style. The main file you'll likely want to edit first is the `index.html`.
3. Commit and push your changes. If you're working directly on GitHub, you can commit the changes right there.

### Step 4: Enable GitHub Pages

1. Go to your new repository on GitHub.
2. Click the "Settings" tab of your repository.
3. Scroll down to the "GitHub Pages" section.
4. Under "Source", select a branch to deploy. Usually, this will be the `main` or `master` branch.
5. Click "Save". GitHub Pages will now deploy your site.

### Step 5: Accessing Your Website

- Your site will be available at `https://[username].github.io` if it's a user site, or at `https://[username].github.io/[repository-name]` for a project site.
- It might take a few minutes for the site to go live. If it doesn’t show up immediately, wait for a bit and then refresh the page.

### Step 6: Update Your Site

- To update your site, make changes to your files and push them to your GitHub repository. GitHub Pages will automatically reflect these changes.

### Tips and Additional Information

- GitHub Pages supports static content only. Dynamic server-side scripts like PHP or Python won't work.
- Your repository (including source code) is publicly visible, especially if your repository is public.
- Explore additional GitHub Pages features like custom domains, Jekyll for blogging, or adding custom 404 pages.

By following these steps, you can quickly set up a personal introductory website using a template on GitHub Pages, which is an excellent way to showcase your profile, portfolio, or resume.
```

