# Introductions
Follow the instructions below to create your own Introductions webpage using GitHub Pages. 

### Prerequisites
- A GitHub Account
- An interest in HTML and CSS

### Instructions

#### Utilize this repository as a template to create your Introductions website.
##### Step 1: Keep this page open, and log into your GitHub account using a separate browser tab.

##### Step 2: Utilize this repository as a template to create a new repository in your GitHub account named “introductions”:
- Click on the "Use this template" button above.
- Name your repository “introductions” (all lower case).
- Verify your new repository is public.

##### Step 3: Verify that your newly created repository includes a file named “index.html” that looks like
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
#### Publish your website with GitHub Pages
##### Step 4: Update your repository settings:
- Click on the “Setting” tab above.
- Scroll down and select the "GitHub Pages" item.
- Under "Source", select the branch to publish (usually `main` or `master`).
- Click "Save" to activate GitHub Pages.

##### Step 5: Test Your Website
- Your project site will be available at `https://[username].github.io/[repository-name]/`.
- For example, my website would be available at `https://ericjpogue.github.io/introductions/`.
- Replace `[username]` with your GitHub username and `[repository-name]` with your repository name (”introductions”).
- It may take a few minutes for the site to go live. If it's not immediately available, wait a bit and then refresh.

#### Update the website with your full name
##### Step 6: Replace “[Your Full Name]” with your full name:
- For example, I would replace “[Your Full Name]” with “Eric Pogue” (Notice that you should also remove the "[" and "]" symbols)
- Navigate to your repository's main page on GitHub.
- Locate the `index.html` file or other files you wish to edit.
- Click on the file to view it and then click the pencil icon (Edit this file) in the top right to start editing.
- Modify “[Your Full Name]” with your first and last name.
- After making your changes, scroll down to the "Commit changes" section.
- Accept the commit message.
- Choose to commit directly to the main branch.
- Click "Commit changes".

##### Step 7: Test your website using the same steps identified in Step 5. 

#### Repeat steps 6 and 7 over and over until all placeholders have been replaced with your informaiton (i.e. “[Your Preferred Name]”). 
Note you can change as many or few of the placeholders as you would like before committing and testing the changes. However, you should
always test after the last change. 

## Next steps:
= Additional GitHub Page information can be found at [GitHub Pages](https://pages.github.com/). Also, there is a 5-minute 
[Hello World with GitHub Pages](https://www.lewis.education/?cpsc=sp24-cpsc-20000-002#/activity/hello-world-web-part-1)
video tutorial that your might be helpful. 
- Did you notice that the template fails to style the “Fun Fact” section? Can you fix that?
- Replace all README.md file contents with something appropriate.

### Credits:
Eric Pogue with the help of ChatGPT created this repository as a template for your "Introductions" website.
- Add your application name and add yourself as the Author.
- Add credits for Eric Pogue, ChatGPT, and for this site where you utilized the template.
