<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anthony Waweru Wandimi</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            @apply bg-gray-50 text-gray-800;
        }
        .section-title {
            @apply text-3xl font-bold text-center mb-12 text-gray-900;
        }
    </style>
</head>
<body>

    <!-- Header & Navigation -->
    <header class="bg-white sticky top-0 z-50 shadow-sm p-4">
        <nav class="container mx-auto flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-gray-900">Anthony Waweru Wandimi</a>
            <div class="hidden md:flex space-x-6">
                <a href="#about" class="hover:text-indigo-600 transition-colors">About</a>
                <a href="#portfolio" class="hover:text-indigo-600 transition-colors">Portfolio</a>
                <a href="#contact" class="hover:text-indigo-600 transition-colors">Contact</a>
            </div>
            <!-- Mobile Menu Button -->
            <button id="mobile-menu-button" class="md:hidden p-2 rounded-md hover:bg-gray-200 focus:outline-none focus:ring-2 focus:ring-indigo-500">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </nav>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden">
            <div class="flex flex-col items-center mt-4 space-y-4">
                <a href="#about" class="w-full text-center py-2 hover:bg-gray-100 transition-colors rounded-lg">About</a>
                <a href="#portfolio" class="w-full text-center py-2 hover:bg-gray-100 transition-colors rounded-lg">Portfolio</a>
                <a href="#contact" class="w-full text-center py-2 hover:bg-gray-100 transition-colors rounded-lg">Contact</a>
            </div>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section class="bg-indigo-600 text-white py-24 text-center rounded-b-3xl shadow-xl">
            <div class="container mx-auto px-4">
                <h1 class="text-4xl sm:text-5xl md:text-6xl font-extrabold mb-4 animate-fade-in-up">Hello, I'm Anthony Waweru Wandimi</h1>
                <p class="text-xl sm:text-2xl mb-8 opacity-90 animate-fade-in-up delay-100">A passionate Software Developer specializing in building modern web applications.</p>
                <a href="#portfolio" class="bg-white text-indigo-600 font-bold py-3 px-8 rounded-full shadow-lg hover:shadow-2xl hover:scale-105 transition-all duration-300">View My Work</a>
            </div>
        </section>

        <!-- About Me Section -->
        <section id="about" class="py-20 px-4">
            <div class="container mx-auto">
                <h2 class="section-title">About Me</h2>
                <div class="flex flex-col md:flex-row items-center justify-center space-y-8 md:space-y-0 md:space-x-12">
                    <img src="https://placehold.co/300x300/E5E7EB/4B5563?text=Profile+Photo" alt="Profile Photo" class="w-48 h-48 rounded-full shadow-lg">
                    <div class="max-w-xl text-center md:text-left">
                        <p class="mb-4 text-gray-600">I am a dedicated software developer with a strong foundation in front-end and back-end technologies. I enjoy solving complex problems and creating intuitive, dynamic user experiences. My goal is to build innovative solutions that make a real-world impact.</p>
                        <p class="text-gray-600">I'm always learning and staying up-to-date with the latest industry trends to deliver high-quality, scalable products.</p>
                        <div class="mt-6">
                            <h3 class="text-xl font-semibold mb-2">Skills & Tools</h3>
                            <div class="flex flex-wrap justify-center md:justify-start gap-3">
                                <span class="bg-indigo-100 text-indigo-800 text-sm font-medium px-4 py-2 rounded-full shadow-md">JavaScript</span>
                                <span class="bg-indigo-100 text-indigo-800 text-sm font-medium px-4 py-2 rounded-full shadow-md">React</span>
                                <span class="bg-indigo-100 text-indigo-800 text-sm font-medium px-4 py-2 rounded-full shadow-md">Python</span>
                                <span class="bg-indigo-100 text-indigo-800 text-sm font-medium px-4 py-2 rounded-full shadow-md">Tailwind CSS</span>
                                <span class="bg-indigo-100 text-indigo-800 text-sm font-medium px-4 py-2 rounded-full shadow-md">Node.js</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Portfolio/Projects Section -->
        <section id="portfolio" class="bg-gray-100 py-20 px-4">
            <div class="container mx-auto">
                <h2 class="section-title">My Projects</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Project 1 -->
                    <div class="bg-white rounded-xl shadow-lg hover:shadow-2xl transition-shadow duration-300 overflow-hidden">
                        <img src="https://placehold.co/600x400/D1D5DB/111827?text=Project+1" alt="Project 1" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <h3 class="text-xl font-bold mb-2 text-gray-900">E-commerce Platform</h3>
                            <p class="text-gray-600 mb-4">A full-stack e-commerce site with user authentication, product listings, and a shopping cart.</p>
                            <a href="#" class="inline-block bg-indigo-600 text-white font-semibold py-2 px-6 rounded-full hover:bg-indigo-700 transition-colors">View Project</a>
                        </div>
                    </div>
                    <!-- Project 2 -->
                    <div class="bg-white rounded-xl shadow-lg hover:shadow-2xl transition-shadow duration-300 overflow-hidden">
                        <img src="https://placehold.co/600x400/D1D5DB/111827?text=Project+2" alt="Project 2" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <h3 class="text-xl font-bold mb-2 text-gray-900">Weather Dashboard</h3>
                            <p class="text-gray-600 mb-4">A simple web app that displays real-time weather data using a third-party API.</p>
                            <a href="#" class="inline-block bg-indigo-600 text-white font-semibold py-2 px-6 rounded-full hover:bg-indigo-700 transition-colors">View Project</a>
                        </div>
                    </div>
                    <!-- Project 3 -->
                    <div class="bg-white rounded-xl shadow-lg hover:shadow-2xl transition-shadow duration-300 overflow-hidden">
                        <img src="https://placehold.co/600x400/D1D5DB/111827?text=Project+3" alt="Project 3" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <h3 class="text-xl font-bold mb-2 text-gray-900">Personal Blog Site</h3>
                            <p class="text-gray-600 mb-4">A personal blog platform with a content management system and responsive design.</p>
                            <a href="#" class="inline-block bg-indigo-600 text-white font-semibold py-2 px-6 rounded-full hover:bg-indigo-700 transition-colors">View Project</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Testimonials Section -->
        <section class="py-20 px-4">
            <div class="container mx-auto">
                <h2 class="section-title">What My Clients Say</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-4xl mx-auto">
                    <!-- Testimonial 1 -->
                    <div class="bg-white p-8 rounded-xl shadow-md border border-gray-200">
                        <p class="italic text-gray-600 mb-4">"Anthony is an excellent developer. His attention to detail and ability to deliver on time exceeded our expectations. We highly recommend him!"</p>
                        <p class="font-semibold text-gray-800">- Jane Doe, CEO of Tech Solutions Inc.</p>
                    </div>
                    <!-- Testimonial 2 -->
                    <div class="bg-white p-8 rounded-xl shadow-md border border-gray-200">
                        <p class="italic text-gray-600 mb-4">"Working with Anthony was a fantastic experience. He is a great communicator and a skilled problem-solver. The final product was exactly what we envisioned."</p>
                        <p class="font-semibold text-gray-800">- John Smith, Marketing Manager</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="bg-indigo-600 text-white py-20 px-4 rounded-t-3xl shadow-xl">
            <div class="container mx-auto text-center">
                <h2 class="text-3xl font-bold mb-4">Get in Touch</h2>
                <p class="text-xl mb-8 opacity-90">I am currently available for new projects. Let's build something great together!</p>
                <form class="max-w-lg mx-auto space-y-4">
                    <input type="text" placeholder="Your Name" class="w-full px-4 py-3 rounded-lg focus:outline-none focus:ring-2 focus:ring-indigo-300 text-gray-900">
                    <input type="email" placeholder="Your Email" class="w-full px-4 py-3 rounded-lg focus:outline-none focus:ring-2 focus:ring-indigo-300 text-gray-900">
                    <textarea placeholder="Your Message" rows="5" class="w-full px-4 py-3 rounded-lg focus:outline-none focus:ring-2 focus:ring-indigo-300 text-gray-900"></textarea>
                    <button type="submit" class="w-full bg-white text-indigo-600 font-bold py-3 px-8 rounded-full shadow-lg hover:scale-105 transition-transform duration-300">Send Message</button>
                </form>
                <div class="mt-8">
                    <p class="font-semibold mb-2">Email:</p>
                    <div class="flex justify-center items-center">
                        <span id="email-text" class="text-lg mr-2">awaweru834@gmail.com</span>
                        <button id="copy-button" class="bg-indigo-500 hover:bg-indigo-400 p-2 rounded-full transition-colors">
                            <svg class="w-4 h-4 text-white" fill="currentColor" viewBox="0 0 24 24"><path d="M16 1H4c-1.1 0-2 .9-2 2v14h2V3h12V1zm3 4H8c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h11c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2zm0 16H8V7h11v14z"/></svg>
                        </button>
                    </div>
                    <div id="copy-message" class="mt-2 text-sm text-gray-200 hidden">Email copied!</div>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-300 py-6 text-center">
        <div class="container mx-auto">
            <p>&copy; 2024 Anthony Waweru Wandimi. All rights reserved.</p>
        </div>
    </footer>

    <script>
        // Mobile menu functionality
        document.getElementById('mobile-menu-button').addEventListener('click', function() {
            const mobileMenu = document.getElementById('mobile-menu');
            mobileMenu.classList.toggle('hidden');
        });

        // Copy email to clipboard
        document.getElementById('copy-button').addEventListener('click', function() {
            const emailText = document.getElementById('email-text').textContent;
            const tempInput = document.createElement('input');
            tempInput.value = emailText;
            document.body.appendChild(tempInput);
            tempInput.select();
            document.execCommand('copy');
            document.body.removeChild(tempInput);

            // Show a temporary message
            const copyMessage = document.getElementById('copy-message');
            copyMessage.classList.remove('hidden');
            setTimeout(() => {
                copyMessage.classList.add('hidden');
            }, 2000);
        });
    </script>
</body>
</html>

