<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pragathi Suthakar | Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Navbar hover underline */
    .nav-link {
      position: relative;
    }
    .nav-link::after {
      content: '';
      position: absolute;
      left: 0;
      bottom: -4px;
      width: 0%;
      height: 2px;
      background: linear-gradient(to right, #fbc2eb, #a6c1ee);
      transition: width 0.3s;
    }
    .nav-link:hover::after {
      width: 100%;
    }
    /* Scroll effect */
    .scrolled {
      background: rgba(255, 255, 255, 0.7);
      backdrop-filter: blur(12px);
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body class="m-0 p-0 font-sans bg-gradient-to-tr from-pink-100 via-purple-100 to-blue-100 text-gray-800">

  <!-- Navbar -->
  <nav id="navbar" class="fixed top-0 w-full z-50 transition duration-300">
    <div class="max-w-7xl mx-auto px-6 flex justify-between items-center h-16">
      <div class="text-2xl font-bold tracking-wide text-gray-900">Pragathi Suthakar</div>
      <ul class="flex space-x-6 text-gray-700 font-medium">
        <li><a href="#home" class="nav-link">Home</a></li>
        <li><a href="#about" class="nav-link">About</a></li>
        <li><a href="#skills" class="nav-link">Skills</a></li>
        <li><a href="#projects" class="nav-link">Projects</a></li>
        <li><a href="#contact" class="nav-link">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Hero -->
  <section id="home" class="h-screen flex flex-col items-center justify-center text-center px-6 bg-gradient-to-r from-pink-200 via-purple-200 to-blue-200">
    <h1 class="text-5xl md:text-6xl font-extrabold mb-4 text-gray-900">Hi, I'm <span class="text-purple-600">Pragathi Suthakar</span></h1>
    <p class="text-xl md:text-2xl max-w-2xl text-gray-700">2nd-year CSE student at SA Engineering College | MERN Stack Developer | Passionate about learning, building, and innovating.</p>
  </section>

  <!-- About -->
  <section id="about" class="min-h-screen flex flex-col items-center justify-center px-6 py-16">
    <div class="max-w-4xl text-center">
      <h2 class="text-4xl font-bold mb-8 text-gray-900">About Me</h2>
      <div class="backdrop-blur-md bg-white/40 p-8 rounded-2xl shadow-lg">
        <p class="text-lg leading-relaxed">I am currently pursuing my <strong>B.E. in Computer Science Engineering</strong> at <strong>SA Engineering College</strong>. As a <strong>2nd-year student</strong>, I specialize in <strong>MERN stack development</strong> and continuously work on enhancing my skills through projects and internships. I’m passionate about developing efficient, user-friendly web applications and love collaborating with teams to bring ideas to life. My soft skills include adaptability, teamwork, and strong communication, which help me thrive in professional environments.</p>
      </div>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills" class="min-h-screen flex flex-col items-center justify-center px-6 py-16 bg-gradient-to-tr from-blue-100 via-purple-100 to-pink-100">
    <h2 class="text-4xl font-bold mb-10 text-gray-900">Skills</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-6xl">
      <div class="p-6 rounded-xl backdrop-blur-md bg-white/40 border border-white/30 shadow-lg hover:scale-105 transition">
        <h3 class="text-2xl font-semibold mb-2">Technical Skills</h3>
        <ul class="list-disc list-inside text-left">
          <li>MERN Stack (MongoDB, Express.js, React.js, Node.js)</li>
          <li>HTML, CSS, JavaScript</li>
          <li>Java (OOP, basic projects)</li>
          <li>Git & GitHub</li>
        </ul>
      </div>
      <div class="p-6 rounded-xl backdrop-blur-md bg-white/40 border border-white/30 shadow-lg hover:scale-105 transition">
        <h3 class="text-2xl font-semibold mb-2">Soft Skills</h3>
        <ul class="list-disc list-inside text-left">
          <li>Communication</li>
          <li>Teamwork</li>
          <li>Adaptability</li>
          <li>Problem-Solving</li>
        </ul>
      </div>
      <div class="p-6 rounded-xl backdrop-blur-md bg-white/40 border border-white/30 shadow-lg hover:scale-105 transition">
        <h3 class="text-2xl font-semibold mb-2">Current Focus</h3>
        <ul class="list-disc list-inside text-left">
          <li>Working on internships in Web Development</li>
          <li>Learning advanced React & Next.js</li>
          <li>Exploring cloud platforms (AWS, Firebase)</li>
          <li>Enhancing coding problem-solving skills</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="min-h-screen flex flex-col items-center justify-center px-6 py-16">
    <h2 class="text-4xl font-bold mb-10 text-gray-900">Projects</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-5xl">
      <div class="relative p-6 rounded-xl backdrop-blur-md bg-white/40 border border-white/30 shadow-lg overflow-hidden group">
        <h3 class="text-2xl font-bold mb-2">Student Management System</h3>
        <p class="text-gray-700">A web-based project built with Node.js and MongoDB to manage student records, attendance, and performance tracking.</p>
        <div class="absolute inset-0 bg-purple-200/70 flex items-center justify-center opacity-0 group-hover:opacity-100 transition">
          <span class="text-gray-900 font-semibold">View Details</span>
        </div>
      </div>
      <div class="relative p-6 rounded-xl backdrop-blur-md bg-white/40 border border-white/30 shadow-lg overflow-hidden group">
        <h3 class="text-2xl font-bold mb-2">Portfolio Website</h3>
        <p class="text-gray-700">Personal responsive portfolio showcasing skills, projects, and contact details using React and TailwindCSS.</p>
        <div class="absolute inset-0 bg-pink-200/70 flex items-center justify-center opacity-0 group-hover:opacity-100 transition">
          <span class="text-gray-900 font-semibold">View Details</span>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="min-h-screen flex flex-col items-center justify-center px-6 py-16 bg-gradient-to-br from-purple-100 via-pink-100 to-blue-100">
    <h2 class="text-4xl font-bold mb-6 text-gray-900">Contact Me</h2>
    <p class="text-lg mb-6 text-gray-700">I am always open to internships, collaborations, and opportunities to learn and grow. Let’s connect!</p>
    <div class="space-y-4 text-lg">
      <p>Email: <a href="mailto:pragathisuthakar@example.com" class="underline text-purple-700">pragathisuthakar@example.com</a></p>
      <p>LinkedIn: <a href="https://linkedin.com/in/pragathisuthakar" class="underline text-purple-700">linkedin.com/in/pragathisuthakar</a></p>
      <p>GitHub: <a href="https://github.com/pragathisuthakar" class="underline text-purple-700">github.com/pragathisuthakar</a></p>
    </div>
  </section>

  <!-- Script for navbar scroll -->
  <script>
    const navbar = document.getElementById("navbar");
    window.addEventListener("scroll", () => {
      if (window.scrollY > 50) {
        navbar.classList.add("scrolled");
      } else {
        navbar.classList.remove("scrolled");
      }
    });
  </script>

</body>
</html>
