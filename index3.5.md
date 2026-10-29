File: index.html
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alex Morgan - Personal Portfolio & Blog</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --accent-color: #3498db;
            --bg-color: #f8f9fa;
            --text-color: #333;
        }
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; line-height: 1.6; color: var(--text-color); background-color: var(--bg-color); }
        
        /* Header & Navigation */
        header { background: var(--primary-color); color: white; padding: 25px 20px; text-align: center; }
        header h1 { margin: 0; font-size: 2.2rem; }
        header p { margin: 5px 0 0; color: #bdc3c7; }
        
        nav { background: #34495e; padding: 12px; text-align: center; position: sticky; top: 0; z-index: 100; }
        nav a { color: white; text-decoration: none; margin: 0 15px; font-weight: bold; }
        nav a:hover { color: var(--accent-color); text-decoration: underline; }

        /* Main Container */
        .container { max-width: 900px; margin: 30px auto; padding: 0 20px; }
        
        section, article { background: white; padding: 25px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05); }
        h2 { color: var(--primary-color); border-bottom: 2px solid var(--accent-color); padding-bottom: 8px; margin-top: 0; }

        /* Profile & Images */
        .profile-flex { display: flex; align-items: center; gap: 20px; flex-wrap: wrap; }
        .profile-img { width: 180px; height: 180px; border-radius: 50%; object-fit: cover; border: 4px solid var(--accent-color); }

        /* Lists */
        ul, ol { padding-left: 20px; }
        li { margin-bottom: 8px; }

        /* Footer */
        footer { background: var(--primary-color); color: white; text-align: center; padding: 20px; margin-top: 40px; }
        footer p { margin: 5px 0; }
        footer a { color: var(--accent-color); text-decoration: none; }
        footer a:hover { text-decoration: underline; }
    </style>
</head>
<body>

    <!-- 1. Header with Name / Logo -->
    <header>
        <h1>Alex Morgan</h1>
        <p>Aspiring Web Developer & Tech Creator</p>
    </header>

    <!-- 2. Navigation Bar -->
    <nav>
        <a href="#about">About Me</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects & Blog</a>
        <a href="#links">Useful Links</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">

        <!-- 3. About Me Section -->
        <section id="about">
            <h2>About Me</h2>
            <div class="profile-flex">
                <img src="images/profile.jpg" alt="Portrait photo of Alex Morgan smiling in front of a modern workspace" class="profile-img" width="180" height="180">
                <div>
                    <p>Hello! I am a passionate student learning front-end web development. I love building clean, accessible, and user-friendly websites using HTML5 and CSS3.</p>
                    <p>When I'm not coding, you can find me reading tech blogs, exploring open-source projects, or sketching UI layouts.</p>
                </div>
            </div>
        </section>

        <!-- 4. Skills or Interests Section -->
        <section id="skills">
            <h2>Skills & Interests</h2>
            <p>Here are some of the key technologies and subjects I am currently studying:</p>
            <ul>
                <li><strong>Front-End Basics:</strong> HTML5 Semantic Tags, CSS3 Styling & Flexbox</li>
                <li><strong>Tools & Version Control:</strong> Git & GitHub</li>
                <li><strong>Accessibility:</strong> ARIA standards, Alt text, and keyboard navigation</li>
                <li><strong>Interests:</strong> UI/UX Design, JavaScript, and Responsive Web Design</li>
            </ul>
        </section>

        <!-- 5. Blog Posts or Projects Section -->
        <section id="projects">
            <h2>Projects & Blog Posts</h2>
            
            <article>
                <h3>Project 1: Semantic Portfolio Website</h3>
                <p><em>Published on October 20, 2026</em></p>
                <img src="images/project1.jpg" alt="Screenshot showing a clean web portfolio interface with navigation and cards" width="100%" height="auto" style="border-radius: 6px; margin: 10px 0;">
                <p>Designed and built a multi-section personal portfolio website using semantic HTML5 elements like <code>&lt;header&gt;</code>, <code>&lt;main&gt;</code>, and <code>&lt;footer&gt;</code>.</p>
            </article>

            <article>
                <h3>Blog: Why Clean Code Matters</h3>
                <p><em>Published on October 15, 2026</em></p>
                <p>Writing well-indented, semantic code not only helps search engines and screen readers index your content properly, but it also makes collaboration with other developers much smoother.</p>
            </article>
        </section>

        <!-- 6. Useful Links Section -->
        <section id="links">
            <h2>Useful Links</h2>
            <p>Here are some websites and resources that have helped me learn web development:</p>
            <ul>
                <li><a href="https://developer.mozilla.org" target="_blank" rel="noopener noreferrer">MDN Web Docs (HTML Reference)</a></li>
                <li><a href="https://github.com" target="_blank" rel="noopener noreferrer">GitHub (Code Repository)</a></li>
                <li><a href="https://www.w3.org" target="_blank" rel="noopener noreferrer">W3C Web Accessibility Guidelines</a></li>
            </ul>
        </section>

    </div>

    <!-- 8. Footer with Contact Details -->
    <footer id="contact">
        <h3>Get in Touch</h3>
        <p>Email: <a href="mailto:alex.morgan@example.com">alex.morgan@example.com</a></p>
        <p>GitHub: <a href="https://github.com" target="_blank" rel="noopener noreferrer">github.com/alex-morgan</a></p>
        <p>&copy; 2026 Alex Morgan. All rights reserved.</p>
    </footer>

</body>
</html>
How to Prepare Your Submission for GitHub:
Create your project folder on your computer named portfolio-project.

Inside that folder, create an images folder and add your images (profile.jpg and project1.jpg) with meaningful alt texts.

Save the code above as index.html in your project folder.

Push to GitHub:

Create a new public repository on GitHub.

Upload your index.html file and your images folder.

Copy the public repository link to submit along with your source code and screenshots!