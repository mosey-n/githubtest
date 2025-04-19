# githubtest

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moses Nicolass - Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #1a202c 0%, #2d3748 100%);
            color: #e2e8f0;
            scroll-behavior: smooth;
        }
        .project-card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .project-card:hover {
            transform: scale(1.05);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
        }
        .back-to-top {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: #4a90e2;
            padding: 12px;
            border-radius: 50%;
            display: none;
            transition: opacity 0.3s;
        }
        .back-to-top.show {
            display: block;
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <section class="min-h-screen flex items-center justify-center bg-gradient-to-br from-blue-900 to-indigo-900">
        <div class="text-center" data-aos="fade-up">
            <h1 class="text-5xl md:text-6xl font-bold mb-4">Moses Nicolass</h1>
            <p class="text-xl md:text-2xl mb-6">
                <span id="typed-text"></span>
            </p>
            <a href="#about" class="bg-blue-500 hover:bg-blue-600 text-white px-6 py-3 rounded-full font-semibold transition">Explore My Work</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="container mx-auto px-6 py-16" data-aos="fade-up">
        <h2 class="text-4xl font-bold mb-6 text-center">About Me</h2>
        <div class="flex flex-col md:flex-row items-center bg-gray-800 p-8 rounded-lg">
            <img src="https://via.placeholder.com/200" alt="Moses Nicolass" class="w-48 h-48 rounded-full mb-6 md:mb-0 md:mr-8">
            <p class="text-lg">
                Hi, I'm Moses Nicolass, a Biomedical Science student at the University of Waterloo with a passion for leveraging data-driven insights in finance. I have experience leading projects, conducting research, and applying technical skills in Python, R, and HTML. My goal is to secure a finance internship where I can apply my analytical mindset and leadership experience to contribute to strategic financial solutions.
            </p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-16 bg-gray-900" data-aos="fade-up">
        <div class="container mx-auto px-6">
            <h2 class="text-4xl font-bold mb-6 text-center">Projects</h2>
            <div id="projects-container" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Static MLSE Project -->
                <div class="project-card p-6 rounded-lg shadow-lg">
                    <h3 class="text-xl font-semibold mb-2 text-blue-400">MLSE Case Competition</h3>
                    <p class="text-gray-300 mb-4">Led a team to deliver a data-driven company pitch using Canva, Figma, and Google Scholar. Managed timelines and created visually appealing materials.</p>
                    <a href="https://github.com/mosey-n" target="_blank" class="text-blue-500 hover:underline">View Project Details</a>
                </div>
                <!-- GitHub projects populated by JavaScript -->
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="container mx-auto px-6 py-16" data-aos="fade-up">
        <h2 class="text-4xl font-bold mb-6 text-center">Skills</h2>
        <ul class="flex flex-wrap justify-center gap-4">
            <li class="bg-blue-500 text-white px-4 py-2 rounded-full hover:bg-blue-600 transition">Python</li>
            <li class="bg-blue-500 text-white px-4 py-2 rounded-full hover:bg-blue-600 transition">R</li>
            <li class="bg-blue-500 text-white px-4 py-2 rounded-full hover:bg-blue-600 transition">HTML</li>
            <li class="bg-blue-500 text-white px-4 py-2 rounded-full hover:bg-blue-600 transition">Dr.Racket</li>
            <li class="bg-blue-500 text-white px-4 py-2 rounded-full hover:bg-blue-600 transition">C/C++</li>
            <li class="bg-blue-500 text-white px-4 py-2 rounded-full hover:bg-blue-600 transition">Canva</li>
            <li class="bg-blue-500 text-white px-4 py-2 rounded-full hover:bg-blue-600 transition">Figma</li>
            <li class="bg-blue-500 text-white px-4 py-2 rounded-full hover:bg-blue-600 transition">Adobe Creative Cloud</li>
            <li class="bg-blue-500 text-white px-4 py-2 rounded-full hover:bg-blue-600 transition">Microsoft 365</li>
            <li class="bg-blue-500 text-white px-4 py-2 rounded-full hover:bg-blue-600 transition">Google Sheets</li>
            <li class="bg-blue-500 text-white px-4 py-2 rounded-full hover:bg-blue-600 transition">Digital Marketing</li>
        </ul>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-gradient-to-br from-blue-900 to-indigo-900 py-16" data-aos="fade-up">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-4xl font-bold mb-6">Get in Touch</h2>
            <p class="text-lg mb-6">I'm excited to explore finance internship opportunities. Feel free to reach out!</p>
            <div class="flex justify-center space-x-6">
                <a href="mailto:minicola8@uwaterloo.ca" class="text-blue-400 hover:text-blue-300 transition">Email</a>
                <a href="https://github.com/mosey-n" target="_blank" class="text-blue-400 hover:text-blue-300 transition">GitHub</a>
                <a href="https://linkedin.com/in/moessnicolass" target="_blank" class="text-blue-400 hover:text-blue-300 transition">LinkedIn</a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-400 py-4 text-center">
        <p>© 2025 Moses Nicolass. All rights reserved.</p>
    </footer>

    <!-- Back to Top Button -->
    <a href="#" class="back-to-top" title="Back to Top">
        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 10l7-7m0 0l7 7m-7-7v18"></path>
        </svg>
    </a>

    <!-- JavaScript -->
    <script>
        // Initialize AOS
        AOS.init({ duration: 1000, once: true });

        // Typed.js for hero section
        new Typed('#typed-text', {
            strings: ['Biomedical Science Student', 'Aspiring Finance Intern', 'Data-Driven Problem Solver'],
            typeSpeed: 50,
            backSpeed: 30,
            backDelay: 2000,
            loop: true
        });

        // Fetch GitHub Repos
        async function fetchGitHubRepos() {
            const username = 'mosey-n';
            const response = await fetch(`https://api.github.com/users/${username}/repos?sort=updated&per_page=5`);
            const repos = await response.json();
            const container = document.getElementById('projects-container');

            if (Array.isArray(repos)) {
                repos.forEach(repo => {
                    const card = document.createElement('div');
                    card.className = 'project-card p-6 rounded-lg shadow-lg';
                    card.innerHTML = `
                        <h3 class="text-xl font-semibold mb-2 text-blue-400">${repo.name}</h3>
                        <p class="text-gray-300 mb-4">${repo.description || 'No description available.'}</p>
                        <a href="${repo.html_url}" target="_blank" class="text-blue-500 hover:underline">View on GitHub</a>
                    `;
                    container.appendChild(card);
                });
            } else {
                container.innerHTML += '<p class="text-center text-gray-400">Unable to load GitHub projects. Please visit my GitHub for more.</p>';
            }
        }

        // Back to Top Button
        const backToTop = document.querySelector('.back-to-top');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 300) {
                backToTop.classList.add('show');
            } else {
                backToTop.classList.remove('show');
            }
        });

        // Fetch repos on load
        document.addEventListener('DOMContentLoaded', fetchGitHubRepos);
    </script>
</body>
</html>
