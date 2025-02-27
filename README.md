<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Krishna Institute</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
            transition: all 0.3s ease-in-out;
        }
        header {
            background: linear-gradient(90deg, #002147, #004aad);
            color: white;
            text-align: center;
            padding: 1rem 0;
            font-size: 1.5rem;
            font-weight: bold;
            letter-spacing: 1px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            background: #004aad;
            margin: 0;
        }
        nav ul li {
            margin: 0 20px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease-in-out;
            font-size: 1.1rem;
        }
        nav ul li a:hover {
            color: #ffcc00;
            text-shadow: 0 0 10px rgba(255, 204, 0, 0.7);
        }
        .hero {
            text-align: center;
            padding: 100px;
            background: url('https://source.unsplash.com/1600x900/?education,students') no-repeat center/cover;
            color: white;
            position: relative;
        }
        .hero::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.4);
        }
        .hero h2, .hero p, .hero .btn {
            position: relative;
            z-index: 1;
        }
        .btn {
            display: inline-block;
            padding: 12px 25px;
            background: #ffcc00;
            color: #002147;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            transition: all 0.3s;
            box-shadow: 0 4px 10px rgba(255, 204, 0, 0.5);
        }
        .btn:hover {
            background: #e6b800;
            transform: scale(1.1);
        }
        section {
            padding: 60px;
            text-align: center;
            background: white;
            margin: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        section:hover {
            transform: translateY(-5px);
        }
        #admissions {
            background: url('https://source.unsplash.com/1600x900/?students,success') no-repeat center/cover;
            color: white;
            padding: 80px;
            border-radius: 10px;
            position: relative;
        }
        #admissions::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            border-radius: 10px;
        }
        #admissions h2, #admissions p, #admissions .btn {
            position: relative;
            z-index: 1;
        }
        footer {
            background: #002147;
            color: white;
            text-align: center;
            padding: 15px;
            font-size: 1rem;
        }
    </style>
</head>
<body>
    <header>
        KRISHNA INSTITUTE
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#courses">Courses</a></li>
            <li><a href="#admissions">Admissions</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="home" class="hero">
        <h2>Empowering Education, Inspiring Success</h2>
        <p>Join Krishna Institute and take a step towards excellence.</p>
        <a href="#admissions" class="btn">Enroll Now</a>
    </section>
    <section id="about">
        <h2>About Us</h2>
        <p>Krishna Institute is a premier coaching institute dedicated to providing top-quality education for students aiming for academic excellence.</p>
    </section>
    <section id="courses">
        <h2>Our Courses</h2>
        <ul>
            <li>JEE & NEET Coaching</li>
            <li>Foundation Courses (Class 8-10)</li>
            <li>Board Exam Preparation</li>
            <li>Competitive Exam Training</li>
        </ul>
    </section>
    <section id="admissions">
        <h2>Admissions</h2>
        <p>Enroll now to secure your future. Limited seats available.</p>
        <a href="#contact" class="btn">Contact Us</a>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@krishnainstitute.com</p>
        <p>Phone: +91 9876543210</p>
        <p>Address: Krishna Institute, City Name, India</p>
    </section>
    <footer>
        <p>&copy; 2025 Krishna Institute. All Rights Reserved.</p>
    </footer>
</body>
</html>
