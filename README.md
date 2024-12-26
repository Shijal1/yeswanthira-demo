<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shijal Mishra | Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <!-- Header with navigation -->
    <header>
        <nav>
            <div class="nav-brand">Shijal Mishra</div>
            <div class="nav-menu">
                <a href="#home" class="active">Home</a>
                <a href="#about">About</a>
                <a href="#skills">Skills</a>
                <a href="#projects">Projects</a>
                <a href="#contact">Contact</a>
            </div>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home" class="home">
        <div class="home-content">
            <img src="C:\Users\Lenovo\OneDrive\Desktop\Pictures\shijal.jpg" alt="Shijal Mishra" class="profile-img">
            <h1>Hi, I'm Shijal Mishra</h1>
            <p>Frontend Developer </p>
            <a href="#projects" class="cta-btn">View My Work</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <h2>About Me</h2>
        <div class="about-content">
            <img src="C:\Users\Lenovo\Downloads\barcelona\me.jpg" alt="Shijal Mishra" class="about-img">
            <p>I am a passionate web developer with a strong focus on creating intuitive, user-friendly websites. With a background in both frontend and backend development, I specialize in HTML, CSS, JavaScript, and modern frameworks like React.js. My goal is to bring designs to life and create seamless user experiences that delight visitors.I am a problem solver at heart. With a strong foundation in web development, I am always looking for creative solutions to technical challenges. My expertise lies in building responsive websites, creating interactive user interfaces, and optimizing performance. I am constantly exploring new frameworks and tools to enhance my work and deliver the best possible results for my clients </p>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <h2>My Skills</h2>
        <div class="skills-content">
            <div class="skill">
                <h3>HTML5/CSS3</h3>
                <div class="progress-bar">
                    <div class="progress" style="width: 95%"></div>
                </div>
            </div>
            <div class="skill">
                <h3>JavaScript</h3>
                <div class="progress-bar">
                    <div class="progress" style="width: 90%"></div>
                </div>
            </div>
            <div class="skill">
                <h3>React.js</h3>
                <div class="progress-bar">
                    <div class="progress" style="width: 85%"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects">
        <h2>My Projects</h2>
        <div class="project-card">
            <img src="C:\Users\Lenovo\Downloads\barcelona\website-development-project-plan.webp" alt="Project 1">
            <div class="project-info">
                <h3>Project 1</h3>
                <p>In this project, I built a fully-functional e-commerce website for a small business, allowing customers to browse products, add them to a shopping cart, and proceed to checkout with an integrated payment gateway. The website is built using React for dynamic content and Node.js for the backend, ensuring a fast, secure, and user-friendly shopping experience. I also implemented a content management system (CMS) so the client can easily manage inventory and track orders</p>
                <a href="#">View Live</a>
                <a href="#">View Source Code</a>
            </div>
        </div>
        <!-- Add more projects as needed -->
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Get In Touch</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Shijal Mishra</p>
        <div class="social-links">
            <a href="https://github.com/Shijal1" target="_blank">GitHub: Shijal1</a> | 
            <a href="https://instagram.com/ok_sir44" target="_blank">Instagram: @oksir_44</a>
        </div>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
