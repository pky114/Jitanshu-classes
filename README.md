<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jitanshu Classes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }

        header {
            background-color: #0078D7;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #005bb5;
            padding: 10px 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            text-align: center;
            padding: 50px 20px;
            background: url('https://via.placeholder.com/1920x500') no-repeat center center/cover;
            color: white;
        }

        .hero h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 1.2em;
        }

        .features {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }

        .feature {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            margin: 10px;
            padding: 20px;
            width: 300px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .feature h3 {
            color: #0078D7;
            margin-bottom: 15px;
        }

        .cta {
            text-align: center;
            margin: 40px 0;
        }

        .cta a {
            background-color: #0078D7;
            color: white;
            text-decoration: none;
            padding: 15px 30px;
            border-radius: 5px;
            font-size: 1.2em;
        }

        .cta a:hover {
            background-color: #005bb5;
        }

        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 10px 0;
        }

        .form-container {
            max-width: 500px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .form-container h3 {
            margin-bottom: 20px;
        }

        .form-container form input,
        .form-container form textarea,
        .form-container form button {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        .form-container form button {
            background-color: #0078D7;
            color: white;
            font-size: 1em;
            border: none;
        }

        .form-container form button:hover {
            background-color: #005bb5;
        }

        .testimonial {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            margin: 10px;
            padding: 20px;
            width: 300px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Jitanshu Classes</h1>
        <p>Your Path to Academic Excellence</p>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#features">Features</a>
        <a href="#courses">Courses</a>
        <a href="#login">Login</a>
        <a href="#contact">Contact Us</a>
    </nav>

    <section class="hero">
        <h2>Welcome to Jitanshu Classes</h2>
        <p>Join the best learning platform for students and teachers.</p>
    </section>

    <section id="features" class="features">
        <div class="feature">
            <h3>Online Classes</h3>
            <p>Attend live and interactive online classes from the comfort of your home.</p>
        </div>
        <div class="feature">
            <h3>Study Material</h3>
            <p>Access high-quality study materials and resources anytime, anywhere.</p>
        </div>
        <div class="feature">
            <h3>Performance Tracking</h3>
            <p>Monitor your progress with detailed performance reports.</p>
        </div>
    </section>

    <section id="login" class="form-container">
        <h3>Login / Signup</h3>
        <form>
            <input type="text" placeholder="Enter your email" required>
            <input type="password" placeholder="Enter your password" required>
            <button type="submit">Login</button>
        </form>
        <p>Don't have an account? <a href="#">Sign up</a></p>
    </section>

    <section id="courses" class="features">
        <div class="feature">
            <h3>Mathematics</h3>
            <p>Learn basic to advanced mathematics with our expert teachers.</p>
        </div>
        <div class="feature">
            <h3>Science</h3>
            <p>Explore the world of physics, chemistry, and biology.</p>
        </div>
        <div class="feature">
            <h3>Languages</h3>
            <p>Master new languages with interactive sessions.</p>
        </div>
    </section>

    <section id="testimonials" class="features">
        <div class="testimonial">
            <p>"Jitanshu Classes helped me achieve my academic goals! Highly recommended." - Student</p>
        </div>
        <div class="testimonial">
            <p>"The platform is user-friendly, and the teachers are fantastic." - Parent</p>
        </div>
    </section>

    <section id="contact" class="form-container">
        <h3>Contact Us</h3>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="4" required></textarea>
            <button type="submit">Submit</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Jitanshu Classes. All Rights Reserved.</p>
    </footer>
</body>
</html>
