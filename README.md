<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Resume</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f4f4f4;
            color: #333;
        }

        .resume {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        /* Header */
        header {
            text-align: center;
            margin-bottom: 20px;
        }

        header h1 {
            font-size: 2.5em;
            margin: 0;
        }

        header p {
            margin: 5px 0;
            color: #555;
        }

        /* Section Styles */
        section {
            margin-bottom: 20px;
        }

        section h2 {
            font-size: 1.5em;
            border-bottom: 2px solid #333;
            padding-bottom: 5px;
            margin-bottom: 10px;
        }

        ul {
            list-style: disc;
            padding-left: 20px;
        }

        ul li {
            margin-bottom: 5px;
        }

        /* Job Details */
        .job {
            margin-bottom: 15px;
        }

        .job h3 {
            margin: 0;
            font-size: 1.2em;
        }

        .job p {
            margin: 5px 0;
            color: #555;
        }

        /* Education */
        .education p {
            margin: 0;
            color: #555;
        }
    </style>
</head>
<body>
    <div class="resume">
        <header>
            <h1>Patel Raksha</h1>
            <p>Web Developer | rakshu@gmail.com | +91 9978453722 | LinkedIn: /Patel Raksha</p>
        </header>
        <section class="profile">
            <h2>Profile</h2>
            <p>A dedicated web developer with a passion for creating visually appealing and functional websites.</p>
        </section>
        <section class="skills">
            <h2>Skills</h2>
            <ul>
                <li>HTML, CSS, JavaScript</li>
                <li>React, Vue.js</li>
                <li>Node.js, Express</li>
                <li>MySQL, MongoDB</li>
                <li>Version Control (Git)</li>
            </ul>
        </section>
        <section class="experience">
            <h2>Experience</h2>
            <div class="job">
                <h3>Frontend Developer</h3>
                <p>XYZ Company | Jan 2021 - Present</p>
                <ul>
                    <li>Developed responsive websites using HTML, CSS, and JavaScript.</li>
                    <li>Collaborated with cross-functional teams to deliver high-quality projects.</li>
                    <li>Optimized code for maximum performance and scalability.</li>
                </ul>
            </div>
            <div class="job">
                <h3>Junior Developer</h3>
                <p>ABC Company | Jun 2022 - Dec 2023</p>
                <ul>
                    <li>Implemented new features for client websites.</li>
                    <li>Tested and debugged code to ensure error-free performance.</li>
                </ul>
            </div>
        </section>
        <section class="education">
            <h2>Education</h2>
            <p>Bachelor of Science in Computer Science | University of Somewhere | 2023</p>
        </section>
    </div>
</body>
</html>
