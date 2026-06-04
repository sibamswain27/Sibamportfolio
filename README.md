# Sibamportfolio
<!DOCTYPE html>
<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport"
        content="width=device-width, initial-scale=1.0">

    <title>Modern Portfolio Website</title>

    <!-- Bootstrap 5 CDN -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
        rel="stylesheet">

    <!-- Bootstrap Icons -->
    <link rel="stylesheet"
        href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">

    <style>

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
        }

        /* HERO SECTION */

        .hero {

            min-height: 100vh;

            background:
                linear-gradient(rgba(0,0,0,0.6),
                rgba(0,0,0,0.6)),
                url('https://images.unsplash.com/photo-1498050108023-c5249f4df085');

            background-size: cover;

            background-position: center;

            color: white;

            display: flex;

            align-items: center;

            text-align: center;
        }

        .hero h1 {
            font-size: 60px;
            font-weight: bold;
        }

        .hero p {
            font-size: 20px;
        }

        /* SERVICES */

        .service-box {

            padding: 30px;

            border-radius: 10px;

            transition: 0.3s;

            background: white;

            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
        }

        .service-box:hover {

            transform: translateY(-10px);
        }

        .service-box i {

            font-size: 40px;

            color: #0d6efd;
        }

        /* PROJECTS */

        .project-card {

            overflow: hidden;

            border-radius: 10px;
        }

        .project-card img {

            transition: 0.5s;
        }

        .project-card:hover img {

            transform: scale(1.1);
        }

        /* CONTACT */

        .contact-box {

            background: white;

            padding: 30px;

            border-radius: 10px;

            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
        }

        /* FOOTER */

        footer {

            background: #111;

            color: white;

            padding: 20px;

            text-align: center;
        }

    </style>

</head>

<body>

    <!-- NAVBAR -->

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">

        <div class="container">

            <a class="navbar-brand fw-bold"
                href="#">

                Sagar Portfolio
            </a>

            <button class="navbar-toggler"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#navbarNav">

                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse"
                id="navbarNav">

                <ul class="navbar-nav ms-auto">

                    <li class="nav-item">
                        <a class="nav-link"
                            href="#home">

                            Home
                        </a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link"
                            href="#services">

                            Services
                        </a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link"
                            href="#projects">

                            Projects
                        </a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link"
                            href="#contact">

                            Contact
                        </a>
                    </li>

                </ul>

            </div>

        </div>

    </nav>

    <!-- HERO SECTION -->

    <section class="hero"
        id="home">

        <div class="container">

            <h1>
                Hello, I'm sibam swain
            </h1>

            <p class="mt-3">
                Frontend Developer | Web Designer | Tech Enthusiast
            </p>

            <a href="#projects"
                class="btn btn-primary btn-lg mt-4">

                Explore My Work
            </a>

        </div>

    </section>

    <!-- SERVICES SECTION -->

    <section class="py-5"
        id="services">

        <div class="container">

            <h2 class="text-center mb-5">
                My Services
            </h2>

            <div class="row g-4">

                <div class="col-md-4">

                    <div class="service-box text-center">

                        <i class="bi bi-code-slash"></i>

                        <h4 class="mt-3">
                            Web Development
                        </h4>

                        <p>
                            Creating responsive and modern websites using HTML, CSS, Bootstrap and JavaScript.
                        </p>

                    </div>

                </div>

                <div class="col-md-4">

                    <div class="service-box text-center">

                        <i class="bi bi-phone"></i>

                        <h4 class="mt-3">
                            Responsive Design
                        </h4>

                        <p>
                            Designing websites that work perfectly on mobile, tablet and desktop screens.
                        </p>

                    </div>

                </div>

                <div class="col-md-4">

                    <div class="service-box text-center">

                        <i class="bi bi-lightbulb"></i>

                        <h4 class="mt-3">
                            UI/UX Ideas
                        </h4>

                        <p>
                            Building clean user-friendly interfaces for better user experience.
                        </p>

                    </div>

                </div>

            </div>

        </div>

    </section>

    <!-- PROJECTS SECTION -->

    <section class="py-5 bg-light"
        id="projects">

        <div class="container">

            <h2 class="text-center mb-5">
                Featured Projects
            </h2>

            <div class="row g-4">

                <div class="col-md-4">

                    <div class="card project-card shadow">

                        <img src="https://via.placeholder.com/400x250"
                            class="card-img-top">

                        <div class="card-body">

                            <h5 class="card-title">
                                Student Management
                            </h5>

                            <p class="card-text">
                                Student data management frontend system.
                            </p>

                        </div>

                    </div>

                </div>

                <div class="col-md-4">

                    <div class="card project-card shadow">

                        <img src="https://via.placeholder.com/400x250"
                            class="card-img-top">

                        <div class="card-body">

                            <h5 class="card-title">
                                Online Quiz
                            </h5>

                            <p class="card-text">
                                Interactive quiz application using JavaScript.
                            </p>

                        </div>

                    </div>

                </div>

                <div class="col-md-4">

                    <div class="card project-card shadow">

                        <img src="https://via.placeholder.com/400x250"
                            class="card-img-top">

                        <div class="card-body">

                            <h5 class="card-title">
                                Portfolio Website
                            </h5>

                            <p class="card-text">
                                Responsive portfolio design project.
                            </p>

                        </div>

                    </div>

                </div>

            </div>

        </div>

    </section>

    <!-- CONTACT SECTION -->

    <section class="py-5"
        id="contact">

        <div class="container">

            <h2 class="text-center mb-5">
                Contact Me
            </h2>

            <div class="row justify-content-center">

                <div class="col-md-8">

                    <div class="contact-box">

                        <form id="contactForm">

                            <div class="mb-3">

                                <label class="form-label">
                                    Name
                                </label>

                                <input type="text"
                                    id="name"
                                    class="form-control">
                            </div>

                            <div class="mb-3">

                                <label class="form-label">
                                    Email
                                </label>

                                <input type="email"
                                    id="email"
                                    class="form-control">
                            </div>

                            <div class="mb-3">

                                <label class="form-label">
                                    Message
                                </label>

                                <textarea rows="5"
                                    id="message"
                                    class="form-control"></textarea>
                            </div>

                            <button type="submit"
                                class="btn btn-primary">

                                Send Message
                            </button>

                        </form>

                    </div>

                </div>

            </div>

        </div>

    </section>

    <!-- FOOTER -->

    <footer>

        © 2026 Modern Portfolio Website | Designed by Sagar Singh

    </footer>

    <!-- Bootstrap JS -->

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

    <!-- JavaScript -->

    <script>

        document.getElementById("contactForm")
        .addEventListener("submit",
        function(event) {

            event.preventDefault();

            let name =
            document.getElementById("name").value.trim();

            let email =
            document.getElementById("email").value.trim();

            let message =
            document.getElementById("message").value.trim();

            let emailPattern =
            /^[^\s@]+@[^\s@]+\.[^\s@]+$/;

            if(name === "" ||
                email === "" ||
                message === "") {

                alert("Please fill all fields");
                return;
            }

            if(!emailPattern.test(email)) {

                alert("Please enter valid email");
                return;
            }

            alert("Message Sent Successfully");

            document.getElementById("contactForm")
            .reset();

        });

    </script>

</body>

</html>
