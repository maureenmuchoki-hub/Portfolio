<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <script src="https://cdn.tailwindcss.com"></script>

    <link rel="stylesheet" href="style.css">
</head>

<body class="bg-gray-100 text-gray-800">

    <!-- NAVIGATION -->
    <nav class="bg-gray-900 text-white py-4">
        <div class="max-w-6xl mx-auto flex justify-between items-center px-6">
            <h1 class="text-lg font-semibold">Maureen Muchoki</h1>
            <ul class="flex space-x-6 text-sm">
                <li><a href="#about" class="hover:text-green-400">About</a></li>
                <li><a href="#skills" class="hover:text-green-400">Skills</a></li>
                <li><a href="#contact" class="hover:text-green-400">Contact</a></li>
            </ul>
        </div>
    </nav>

    <section id="about" class="bg-gray-200 text-center">
        <div class="max-w-4xl mx-auto px-6">

            <img src="c:\Users\Admin\Pictures\My Profile..JPG"
                 alt="Profile photo"
                 style="
                    width: 180px;
                    height: 180px;
                    border-radius: 50%;
                    border: 3px solid #22c55e;
                    object-fit: cover;
                    display: block;
                    margin: 0 auto;
            ">
        

            <h2 class="text-[2xl] font-bold mt-10">
                Hi, I’m Maueen 👋
            </h2>

            <p class="text-green-600 font-medium mt-10">
                Junior Web Developer
            </p>

            <p class="max-w-xl mx-auto mt-4 text-gray-700 text-sm leading-relaxed">
                I’m a passionate web developer based in Nairobi, Kenya.
                I love building beautiful websites and learning new technologies.
                Currently studying HTML, CSS, and JavaScript to create amazing user experiences.
            </p>

        </div>
    </section>

    <section id="skills" class="bg-gray-900 text-white">
        <div class="max-w-5xl mx-auto px-6">
            <h2 class="text-center text-xl font-bold mb-14">My Skills</h2>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">

                <div class="bg-gray-800 p-6 rounded-lg text-center skill-card">
                    <div class="text-3xl mb-3">🌐</div>
                    <h3 class="text-green-400 font-semibold">HTML</h3>
                    <p class="text-gray-400 text-sm mt-2">
                        Semantic markup and page structure
                    </p>
                </div>

                <div class="bg-gray-800 p-6 rounded-lg text-center skill-card">
                    <div class="text-3xl mb-3">🎨</div>
                    <h3 class="text-green-400 font-semibold">CSS</h3>
                    <p class="text-gray-400 text-sm mt-2">
                        Styling, layout, and animations
                    </p>
                </div>

                <div class="bg-gray-800 p-6 rounded-lg text-center skill-card">
                    <div class="text-3xl mb-3">⚡</div>
                    <h3 class="text-green-400 font-semibold">JavaScript</h3>
                    <p class="text-gray-400 text-sm mt-2">
                        Interactive features and logic
                    </p>
                </div>

                <div class="bg-gray-800 p-6 rounded-lg text-center skill-card">
                    <div class="text-3xl mb-3">📱</div>
                    <h3 class="text-green-400 font-semibold">Responsive Design</h3>
                    <p class="text-gray-400 text-sm mt-2">
                        Mobile-friendly websites
                    </p>
                </div>

            </div>
        </div>
    </section>

    <!-- CONTACT SECTION -->
    <section id="contact" class="bg-gray-200">
        <div class="max-w-md mx-auto px-6">
            <h2 class="text-center text-xl font-bold mb-8">Contact Me</h2>

            <form class="space-y-4">

                <div>
                    <label class="block text-sm mb-1">Name</label>
                    <input type="text"
                           class="form-input"
                           placeholder="Your name">
                </div>

                <div>
                    <label class="block text-sm mb-1">Email</label>
                    <input type="email"
                           class="form-input"
                           placeholder="you@example.com">
                </div>

                <div>
                    <label class="block text-sm mb-1">Message</label>
                    <textarea rows="4"
                              class="form-input"
                              placeholder="Write your message here..."></textarea>
                </div>

                <button class="btn-primary w-full">
                    Send Message
                </button>

            </form>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-gray-900 text-gray-400 text-center py-4 text-sm">
        © 2025 Maureen Muchoki. Built with ❤️ and Tailwind CSS.
    </footer>

</body>
</html># Portfolio
