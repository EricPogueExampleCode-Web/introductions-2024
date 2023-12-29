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
