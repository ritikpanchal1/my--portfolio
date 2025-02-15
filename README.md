<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>ritik's - Portfolio</title>

 
    <script src="https://cdn.tailwindcss.com"></script>

   
    <link rel="stylesheet" href="styles/styles.css">
</head>

<body class="font-sans bg-gray-50">

    <header class="bg-blue-600 text-white py-4">
        <nav class="max-w-screen-xl mx-auto flex justify-between items-center px-4">
            <h1 class="text-3xl font-bold">Ritik Panchal</h1>
            <ul class="flex space-x-4">
                <li><a href="#about" class="hover:text-blue-200">About</a></li>
                <li><a href="#skills" class="hover:text-blue-200">Skills</a></li>
                <li><a href="#projects" class="hover:text-blue-200">Projects</a></li>
                <li><a href="#contact" class="hover:text-blue-200">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about" class="bg-white py-12">
        <article class="max-w-screen-lg mx-auto text-center">
            <h2 class="text-4xl font-semibold mb-4">About Me</h2>
            <p class="text-lg text-gray-700">Hi, I'm Ritik Panchal, a passionate web developer with a love for creating clean, user-friendly websites. I specialize in front-end development using HTML5, CSS, and JavaScript.</p>
        </article>
    </section>

    <section id="skills" class="bg-gray-100 py-12">
        <article class="max-w-screen-lg mx-auto text-center">
            <h2 class="text-4xl font-semibold mb-6">Skills</h2>
            <ul class="grid grid-cols-2 md:grid-cols-4 gap-8">
                <li class="bg-white p-6 rounded-lg shadow-lg">
                    <h3 class="text-2xl font-semibold mb-2">HTML</h3>
                    <p class="text-gray-600">Experienced in building responsive and semantic web pages.</p>
                </li>
                <li class="bg-white p-6 rounded-lg shadow-lg">
                    <h3 class="text-2xl font-semibold mb-2">CSS</h3>
                    <p class="text-gray-600">Proficient in using Tailwind CSS and Grid for modern web layouts.</p>
                </li>
                <li class="bg-white p-6 rounded-lg shadow-lg">
                    <h3 class="text-2xl font-semibold mb-2">JavaScript</h3>
                    <p class="text-gray-600">Experienced with vanilla JS and frameworks like React.</p>
                </li>
                <li class="bg-white p-6 rounded-lg shadow-lg">
                    <h3 class="text-2xl font-semibold mb-2">Git & GitHub</h3>
                    <p class="text-gray-600">Comfortable using version control to manage code collaboration.</p>
                </li>
            </ul>
        </article>
    </section>

    
    <section id="contact" class="bg-blue-600 text-white py-12">
        <article class="max-w-screen-lg mx-auto text-center">
            <h2 class="text-4xl font-semibold mb-6">Contact</h2>
            <p class="text-lg mb-6">Feel free to reach out to me through the form below:</p>
            <form action="#" method="post" class="max-w-lg mx-auto">
                <input type="text" name="name" placeholder="Your Name" class="w-full p-4 mb-4 rounded-lg border border-gray-300">
                <input type="email" name="email" placeholder="Your Email" class="w-full p-4 mb-4 rounded-lg border border-gray-300">
                <textarea name="message" placeholder="Your Message" rows="4" class="w-full p-4 mb-4 rounded-lg border border-gray-300"></textarea>
                <button type="submit" class="w-full py-3 bg-blue-700 text-white rounded-lg">Send Message</button>
            </form>
        </article>
    </section>

    <footer class="bg-gray-800 text-white py-4">
        <p class="text-center">&copy; 2025 Ritik panchal. All rights reserved.</p>
    </footer>

</body>

</html>
