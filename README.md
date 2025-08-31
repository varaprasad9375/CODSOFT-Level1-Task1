*Proposer*:G.Shivanarayana Varaprasad.
*Company/Organization*:CODSOFT
*Project ID*:BY25RY210648
*Timeline*: 4 Weeks
*Domain*:Web Development

#CODE

#HTML...

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VARA PRASAD - Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@700&family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
</head>
<body>

    <header id="home">
        <div class="header-content">
            <h1>VARA PRASAD</h1>
            <p class="tagline">Web Developer & Innovator</p>
            <nav>
                <ul>
                    <li><a href="#about" data-target="about">About</a></li>
                    <li><a href="#skills" data-target="skills">Skills</a></li>
                    <li><a href="#projects" data-target="projects">Projects</a></li>
                    <li><a href="#resume" data-target="resume">Resume</a></li>
                    <li><a href="#contact" data-target="contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div id="cinematic-overlay">
        <span class="cinematic-title">PORTFOLIO</span>
        <audio controls autoplay id="backgroung-audio"  loop>
            
    <source src="rocky-178151.mp3.mp3" type="audio/mpeg">

        </audio> 

    </div>

    <main>
        <section id="about" class="active">
            <div class="about-content">
                <div class="profile-image">
                    <img src="https://i.pinimg.com/736x/49/d2/6c/49d26cc1fa64ee09c429102c3d67cf7e.jpg" alt="Vara Prasad Profile Icon" id="profile-icon">
                </div>
                <div class="bio">
                    <h2>About Me</h2>
                    <p>Hello! I'm a passionate web developer with a knack for creating innovative and user-friendly digital experiences. With a strong foundation in HTML, CSS, and JavaScript, I enjoy tackling complex problems and building beautiful, functional websites. My expertise extends to frameworks and libraries, and I'm always eager to learn new technologies to stay ahead in the dynamic world of web development. Outside of coding, I enjoy playing video games and exploring new tech gadgets.</p>
                </div>
            </div>
        </section>

        <section id="projects">
            <h2>My Projects</h2>
            <div class="project-card-full">
                <h3>1. Building page for games</h3>
                <p>Created a dynamic web page for discovering and learning about video games. Features include game trailers, reviews, and a community forum. This project demonstrates my skills in creating interactive and engaging user interfaces.</p>
            </div>
            <div class="project-card-full">
                <h3>2. Coding Skills Showcase</h3>
                <p>This section showcases my proficiency in various programming languages and data structures. I have strong skills in *Python* for backend development, *Java* for robust applications, and a solid understanding of *Data Structures and Algorithms in C* for efficient problem-solving.</p>
            </div>
            <div class="project-card-full">
                <h3>3. Innovative Web Pages for Clients</h3>
                <p>Developed a portfolio of innovative and responsive websites for various clients. My focus is on delivering a modern, seamless user experience with optimized performance and clean, maintainable code. Each project is a testament to my dedication to client satisfaction and cutting-edge web design.</p>
            </div>
        </section>

        <section id="skills">
            <h2>My Skills</h2>
            <div class="skills-grid">
                <div class="skill-item">
                    <h3>Frontend</h3>
                    <ul>
                        <li>HTML5</li>
                        <li>CSS3</li>
                        <li>JavaScript</li>
                        <li>React</li>
                    </ul>
                </div>
                <div class="skill-item">
                    <h3>Backend</h3>
                    <ul>
                        <li>Node.js</li>
                        <li>Express.js</li>
                        <li>Python</li>
                        <li>Java</li>
                    </ul>
                </div>
                <div class="skill-item">
                    <h3>Databases & More</h3>
                    <ul>
                        <li>MongoDB</li>
                        <li>MySQL</li>
                        <li>Git & GitHub</li>
                        <li>Data Structures & Algorithms in C</li>
                    </ul>
                </div>
            </div>
        </section>

        <section id="resume">
            <h2>Resume</h2>
            <p>Download my full resume in PDF format to learn more about my experience and skills.</p>
            <a href="#" class="btn-download" target="_blank">Download Resume</a>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Let's connect! I'm always open to new opportunities and collaborations.</p>
            <p><strong>Email:</strong> vara96@gmail.com</p>
            <p><strong>Phone:</strong> +91 xxxxxxxx96</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 VARA PRASAD. All Rights Reserved.</p>
    </footer>

    <script src="script.js"></script>

</body>
</html>

#CSS>>

/* General Body and Text Styling */
body {
    font-family: 'Poppins', sans-serif;
    line-height: 1.6;
    background-color: #f4f4f9;
    color: #333;
    margin: 0;
    padding: 0;
    overflow-x: hidden;
}

h1, h2, h3 {
    font-family: 'Oswald', sans-serif;
    font-weight: 700;
    color: #2c3e50;
    margin-bottom: 0.5em;
    text-transform: uppercase;
    letter-spacing: 2px;
}

/* Heading Effects for Cinematic Feel */
h1 {
    color: #fff;
    text-shadow: -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000, 1px 1px 0 #000, 2px 2px 0 #4a4a4a, 3px 3px 0 #666;
}
h2 {
    text-shadow: -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000, 1px 1px 0 #000, 2px 2px 0 #bfbfbf;
}

/* Section and Main Layout */
section {
    padding: 60px 20px;
    max-width: 1200px;
    margin: 20px auto;
    background-color: #fff;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    border-radius: 8px;
    transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out, opacity 0.5s ease-out, visibility 0.5s ease-out;
    opacity: 0;
    visibility: hidden;
    transform: translateY(20px);
}

section.active {
    opacity: 1;
    visibility: visible;
    transform: translateY(0);
}

/* Header and Navigation */
header {
    background: #3498db;
    color: #fff;
    text-align: center;
    padding: 100px 20px;
    position: relative;
    overflow: hidden;
    animation: fadeIn 1s ease-in-out;
}
.header-content h1 { font-size: 3.5em; }
.header-content .tagline {
    font-size: 1.3em;
    font-style: italic;
    color: #ecf0f1;
    margin-top: 10px;
    opacity: 0;
    animation: taglineFadeIn 1.5s ease-out 1s forwards;
}

nav ul {
    list-style: none;
    padding-top: 30px;
    display: flex;
    justify-content: center;
    gap: 25px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-weight: 600;
    font-size: 1.2em;
    position: relative;
    padding: 5px 0;
    transition: color 0.3s;
    opacity: 0;
    animation: navLinkFadeIn 0.8s ease-out forwards;
}
/* Staggered animation for nav links */
nav li:nth-child(1) a { animation-delay: 1.2s; }
nav li:nth-child(2) a { animation-delay: 1.4s; }
nav li:nth-child(3) a { animation-delay: 1.6s; }
nav li:nth-child(4) a { animation-delay: 1.8s; }
nav li:nth-child(5) a { animation-delay: 2.0s; }

nav a::after {
    content: '';
    position: absolute;
    width: 0;
    height: 3px;
    display: block;
    margin-top: 5px;
    background: #fff;
    transition: width 0.3s ease;
}
nav a:hover::after { width: 100%; }

/* Profile and Bio */
.about-content {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    gap: 40px;
    text-align: center;
}
.profile-image img {
    width: 280px;
    height: 280px;
    border-radius: 50%;
    object-fit: cover;
    border: 8px solid #f39c12;
    box-shadow: 0 0 25px rgba(0,0,0,0.3), 0 0 0 15px rgba(243, 156, 18, 0.3);
    cursor: pointer;
    transition: transform 0.4s ease-in-out, box-shadow 0.4s ease-in-out;
}
.profile-image img:hover {
    transform: scale(1.05) rotate(5deg);
    box-shadow: 0 0 30px rgba(0,0,0,0.4), 0 0 0 20px rgba(243, 156, 18, 0.4);
}
.bio {
    flex: 1;
    min-width: 300px;
    text-align: left;
}
.bio h2 { text-align: center; }

/* Skills and Projects Layout */
.skills-grid, .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
    text-align: center;
}
.project-card-full {
    background: #fdfdfd;
    border: 1px solid #ddd;
    border-left: 5px solid #3498db;
    border-radius: 8px;
    padding: 30px;
    margin-bottom: 25px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    transition: all 0.3s ease;
}
.project-card-full:hover {
    transform: translateX(5px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    border-left-color: #f39c12;
}
.project-card-full h3 {
    color: #34495e;
    font-family: 'Poppins', sans-serif;
    text-transform: none;
    letter-spacing: normal;
    text-shadow: none;
    font-weight: 600;
}
.skill-item {
    background: #ecf0f1;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
}
.skill-item:hover { transform: scale(1.05); }
.skill-item ul {
    list-style: none;
    padding-top: 10px;
}

/* Resume and Contact */
.btn-download {
    display: inline-block;
    background: #e74c3c;
    color: #fff;
    padding: 15px 30px;
    text-decoration: none;
    border-radius: 5px;
    transition: background 0.3s ease, transform 0.2s ease;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 1px;
}
.btn-download:hover {
    background: #c0392b;
    transform: scale(1.05);
}
#contact p { margin: 10px 0; }
footer {
    text-align: center;
    padding: 20px;
    background: #2c3e50;
    color: #fff;
    margin-top: 20px;
}

/* Cinematic Overlay and Title */
#cinematic-overlay {
    position: fixed;
    top: 0; left: 0; right: 0; bottom: 0;
    background: #000;
    display: flex;
    align-items: center;
    justify-content: center;
    z-index: 9999;
    opacity: 0;
    pointer-events: none;
    transition: opacity 0.3s;
}

#cinematic-overlay.active {
    opacity: 1;
    pointer-events: all;
}

.cinematic-title {
    color: #fff;
    font-family: Impact, 'Oswald', Arial Black, sans-serif;
    font-size: 8vw;
    font-weight: 900;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    text-align: center;
    text-shadow: 0 0 40px #fff, 0 0 10px #fff;
    transform: scaleX(0.2);
    opacity: 0;
    animation: rocky-title-zoom 1.2s cubic-bezier(0.4,0,0.2,1) forwards;
}

#cinematic-overlay:not(.active) .cinematic-title {
    animation: Dissolve;
    transform: scaleX(0.2);
    opacity: 0;
}

@keyframes rocky-title-zoom {
    0% {
        transform: scaleX(0.2);
        opacity: 0;
        letter-spacing: 1.5em;
    }
    40% {
        opacity: 1;
        letter-spacing: 0.5em;
    }
    80% {
        transform: scaleX(1.15);
        letter-spacing: 0.15em;
    }
    100% {
        transform: scaleX(1);
        opacity: 1;
        letter-spacing: 0.15em;
    }
}

/* Keyframe Animations */
@keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
@keyframes taglineFadeIn { to { opacity: 1; } }
@keyframes navLinkFadeIn {
    from { opacity: 0; transform: translateY(-10px); }
    to { opacity: 1; transform: translateY(0); }
}
@keyframes cinematicReveal {
    0% { opacity: 0; transform: scale(0.9) translateY(50px); box-shadow: 0 0 0 rgba(0,0,0,0); }
    70% { opacity: 1; transform: scale(1.02) translateY(-10px); box-shadow: 0 10px 20px rgba(0,0,0,0.2); }
    100% { opacity: 1; transform: scale(1) translateY(0); box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
}

/* Initial hidden state for sections */
main section {
    opacity: 0;
    visibility: hidden;
    height: 0;
    padding: 0 20px;
    margin-top: 0;
    margin-bottom: 0;
    transform: translateY(20px);
    overflow: hidden;
}

main section.active {
    opacity: 1;
    visibility: visible;
    height: auto;
    padding: 60px 20px;
    margin-top: 20px;
    margin-bottom: 20px;
    transform: translateY(0);
    overflow: visible;
}

/* Responsive adjustments */
@media (max-width: 768px) {
    .header-content h1 { font-size: 2.5em; }
    .header-content .tagline { font-size: 1em; }
    nav ul {
        flex-direction: column;
        gap: 10px;
    }
    .about-content {
        flex-direction: column;
        text-align: center;
    }
    .profile-image img {
        width: 200px;
        height: 200px;
    }
    .bio { text-align: center; }
    section { padding: 40px 15px; }
}

/* New cinematic animation for the reveal */
@keyframes cinematicReveal {
    0% { opacity: 0; transform: scale(0.9) translateY(50px); box-shadow: 0 0 0 rgba(0,0,0,0); }
    70% { opacity: 1; transform: scale(1.02) translateY(-10px); box-shadow: 0 10px 20px rgba(0,0,0,0.2); }
    100% { opacity: 1; transform: scale(1) translateY(0); box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
}

/* Apply the animation when the about section is active */
#about.active {
    animation: cinematicReveal 2s ease-in-out;
}



JAVA SCRIPT>>
// Wait for the entire page to load before running the script
document.addEventListener('DOMContentLoaded', function() {
    const navLinks = document.querySelectorAll('nav a');
    const allSections = document.querySelectorAll('main section');
    const profileIcon = document.getElementById('profile-icon');
    const cinematicOverlay = document.getElementById('cinematic-overlay');
    const transitionAudio = document.getElementById('transition-audio');
    const backgroundAudio = document.getElementById('background-audio');
    let aboutSectionVisible = true;
    let overlayTimeout = null;

    // Function to show a specific section and hide others
    function showSection(targetId) {
        allSections.forEach(section => {
            section.classList.toggle('active', section.id === targetId);
        });
    }

    // Handler for navigation links
    navLinks.forEach(link => {
        link.addEventListener('click', function(event) {
            event.preventDefault();
            const targetId = this.getAttribute('data-target');
            showSection(targetId);
            document.getElementById(targetId).scrollIntoView({ behavior: 'smooth' });
            aboutSectionVisible = (targetId === 'about');
        });
    });

    // Handler for profile icon click
    if (profileIcon) {
        profileIcon.addEventListener('click', function() {
            // Check if the overlay is already active to prevent multiple clicks
            if (cinematicOverlay.classList.contains('active')) {
                return;
            }

            // Show the overlay
            cinematicOverlay.classList.add('active');

            // Play background music (now starts with the transition)
            if (backgroundAudio) {
                backgroundAudio.play().catch(err => {
                    console.error('Background audio play error:', err);
                });
            }

            // Play transition audio from the start
            if (transitionAudio) {
                transitionAudio.currentTime = 0;
                transitionAudio.play().catch(err => {
                    console.error('Transition audio play error:', err);
                });
            }

            // Clear any existing timeout before setting a new one
            if (overlayTimeout) {
                clearTimeout(overlayTimeout);
            }

            // Hide overlay and show the 'about' section after 20 seconds
            overlayTimeout = setTimeout(() => {
                cinematicOverlay.classList.remove('active');
                if (transitionAudio) transitionAudio.pause();
                showSection('about');
                document.getElementById('about').scrollIntoView({ behavior: 'smooth' });
                aboutSectionVisible = true;
            }, 20000); // 20 seconds
        });
    }

    // Allow closing overlay with ESC key
    document.addEventListener('keydown', function(event) {
        if (event.key === 'Escape') {
            if (cinematicOverlay.classList.contains('active')) {
                cinematicOverlay.classList.remove('active');
                if (transitionAudio) transitionAudio.pause();
                showSection('about');
                document.getElementById('about').scrollIntoView({ behavior: 'smooth' });
                aboutSectionVisible = true;
                if (overlayTimeout) clearTimeout(overlayTimeout);
            }
        }
    });

    // Make the about section visible when the page loads
    document.getElementById('about').classList.add('active');
});


