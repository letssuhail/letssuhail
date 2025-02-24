<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Suhail's GitHub Profile</title>
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <style>
        /* Google Font */
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');

        /* Global Styles */
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: #121212;
            color: #fff;
            text-align: center;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }

        .container {
            max-width: 600px;
            background: rgba(255, 255, 255, 0.1);
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0px 0px 20px rgba(255, 255, 255, 0.2);
            backdrop-filter: blur(10px);
            animation: fadeIn 1.5s ease-in-out;
        }

        /* Heading Animation */
        .typing-text::after {
            content: "|";
            display: inline-block;
            animation: blink 0.7s infinite;
        }

        @keyframes blink {
            50% { opacity: 0; }
        }

        /* Social Icons */
        .social-icons {
            margin-top: 15px;
        }

        .social-icons a {
            display: inline-block;
            margin: 8px;
            font-size: 24px;
            color: #fff;
            text-decoration: none;
            transition: transform 0.3s ease, color 0.3s ease;
        }

        .social-icons a:hover {
            transform: scale(1.2);
            color: #1DB954; /* Spotify Green for effect */
        }

        /* Footer */
        footer {
            margin-top: 20px;
            font-size: 14px;
            opacity: 0.7;
        }

        footer a {
            color: #1DB954;
            text-decoration: none;
            font-weight: bold;
        }

        /* Fade-in Animation */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="typing-text">Hi there, I'm Suhail 👋</h1>
        <p>🚀 Flutter & Node.js Developer | Passionate about building great apps!</p>
        
        <h3>📌 About Me</h3>
        <p>
            💡 Tech Enthusiast | 💻 Freelancer | 📱 Mobile App Dev | 🌍 Open-Source Contributor  
        </p>

        <h3>🌍 Connect with Me</h3>
        <div class="social-icons">
            <a href="https://github.com/letssuhail" class="github" target="_blank" aria-label="GitHub">
                <i class="fab fa-github"></i>
            </a>
            <a href="https://www.linkedin.com/in/your_linkedin_handle" class="linkedin" target="_blank" aria-label="LinkedIn">
                <i class="fab fa-linkedin-in"></i>
            </a>
            <a href="https://www.instagram.com/your_instagram_handle" class="instagram" target="_blank" aria-label="Instagram">
                <i class="fab fa-instagram"></i>
            </a>
            <a href="https://twitter.com/your_twitter_handle" class="twitter" target="_blank" aria-label="Twitter">
                <i class="fab fa-twitter"></i>
            </a>
            <a href="mailto:your@email.com" class="email" target="_blank" aria-label="Email">
                <i class="fas fa-envelope"></i>
            </a>
        </div>

        <footer>
            <p>🚀 Created with ❤️ by <a href="https://github.com/letssuhail" target="_blank">Suhail</a></p>
        </footer>
    </div>
</body>
</html>
