<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ummah Movers Kenya | Professional Relocation Services</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        :root {
            --primary: #0d6efd;
            --secondary: #198754;
            --accent: #ffc107;
            --dark: #212529;
            --light: #f8f9fa;
            --gray: #6c757d;
        }

        body {
            background-color: #f5f7fa;
            color: #333;
            line-height: 1.6;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }

        /* Header Styles */
        header {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }

        .logo {
            display: flex;
            align-items: center;
        }

        .logo h1 {
            font-size: 1.8rem;
            color: var(--primary);
        }

        .logo span {
            color: var(--secondary);
        }

        nav ul {
            display: flex;
            list-style: none;
        }

        nav ul li {
            margin-left: 25px;
        }

        nav ul li a {
            text-decoration: none;
            color: var(--dark);
            font-weight: 500;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: var(--primary);
        }

        .btn {
            display: inline-block;
            background-color: var(--primary);
            color: white;
            padding: 12px 25px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s;
            border: none;
            cursor: pointer;
        }

        .btn:hover {
            background-color: #0b5ed7;
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        .btn-secondary {
            background-color: var(--secondary);
        }

        .btn-secondary:hover {
            background-color: #157347;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1504384764586-bb4cdc1707b0?ixlib=rb-4.0.3&auto=format&fit=crop&w=1950&q=80');
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            align-items: center;
            color: white;
            text-align: center;
            margin-top: 70px;
        }

        .hero-content {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
            line-height: 1.2;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 30px;
            opacity: 0.9;
        }

        .hero-btns {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }

        /* Services Section */
        .section {
            padding: 80px 0;
        }

        .section-title {
            text-align: center;
            margin-bottom: 50px;
        }

        .section-title h2 {
            font-size: 2.5rem;
            color: var(--dark);
            margin-bottom: 15px;
        }

        .section-title p {
            color: var(--gray);
            max-width: 700px;
            margin: 0 auto;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .service-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.1);
        }

        .service-icon {
            background-color: var(--primary);
            color: white;
            font-size: 2.5rem;
            height: 100px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .service-content {
            padding: 25px;
        }

        .service-content h3 {
            margin-bottom: 15px;
            color: var(--dark);
        }

        /* About Section */
        .about {
            background-color: var(--light);
        }

        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 50px;
            align-items: center;
        }

        .about-text h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            color: var(--dark);
        }

        .about-text p {
            margin-bottom: 20px;
            color: var(--gray);
        }

        .about-image {
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }

        .about-image img {
            width: 100%;
            height: auto;
            display: block;
        }

        /* Testimonials */
        .testimonials {
            background: linear-gradient(to right, var(--primary), var(--secondary));
            color: white;
        }

        .testimonials .section-title h2,
        .testimonials .section-title p {
            color: white;
        }

        .testimonial-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .testimonial-card {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
            border-radius: 10px;
            padding: 30px;
            border: 1px solid rgba(255,255,255,0.2);
        }

        .testimonial-text {
            font-style: italic;
            margin-bottom: 20px;
            position: relative;
        }

        .testimonial-text::before {
            content: """;
            font-size: 4rem;
            position: absolute;
            top: -20px;
            left: -15px;
            opacity: 0.2;
        }

        .testimonial-author {
            display: flex;
            align-items: center;
        }

        .author-image {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            overflow: hidden;
            margin-right: 15px;
            background-color: var(--accent);
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            color: var(--dark);
        }

        .author-info h4 {
            margin-bottom: 5px;
        }

        .author-info p {
            font-size: 0.9rem;
            opacity: 0.8;
        }

        /* Contact Section */
        .contact-container {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 50px;
        }

        .contact-info h3 {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: var(--dark);
        }

        .contact-details {
            margin-bottom: 30px;
        }

        .contact-item {
            display: flex;
            margin-bottom: 20px;
        }

        .contact-icon {
            width: 50px;
            height: 50px;
            background-color: var(--primary);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
            flex-shrink: 0;
        }

        .contact-text h4 {
            margin-bottom: 5px;
        }

        .contact-form .form-group {
            margin-bottom: 20px;
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
        }

        .contact-form textarea {
            height: 150px;
            resize: vertical;
        }

        /* Footer */
        footer {
            background-color: var(--dark);
            color: white;
            padding: 60px 0 30px;
        }

        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            margin-bottom: 40px;
        }

        .footer-column h3 {
            font-size: 1.5rem;
            margin-bottom: 20px;
            position: relative;
            padding-bottom: 10px;
        }

        .footer-column h3::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 50px;
            height: 2px;
            background-color: var(--accent);
        }

        .footer-column ul {
            list-style: none;
        }

        .footer-column ul li {
            margin-bottom: 10px;
        }

        .footer-column ul li a {
            color: #aaa;
            text-decoration: none;
            transition: color 0.3s;
        }

        .footer-column ul li a:hover {
            color: white;
        }

        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 20px;
        }

        .social-links a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            background-color: rgba(255,255,255,0.1);
            border-radius: 50%;
            color: white;
            transition: all 0.3s;
        }

        .social-links a:hover {
            background-color: var(--primary);
            transform: translateY(-3px);
        }

        .copyright {
            text-align: center;
            padding-top: 30px;
            border-top: 1px solid rgba(255,255,255,0.1);
            color: #aaa;
            font-size: 0.9rem;
        }

        /* Responsive Design */
        @media (max-width: 992px) {
            .about-content,
            .contact-container {
                grid-template-columns: 1fr;
            }
            
            .about-image {
                order: -1;
            }
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .hero-btns {
                flex-direction: column;
                align-items: center;
            }
            
            nav ul {
                display: none;
            }
            
            .mobile-menu-btn {
                display: block;
            }
        }

        @media (max-width: 576px) {
            .section {
                padding: 60px 0;
            }
            
            .section-title h2 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container header-container">
            <div class="logo">
                <h1>Ummah <span>Movers</span></h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#testimonials">Testimonials</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
            <a href="#contact" class="btn">Get Quote</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-content">
            <h1>Reliable Moving & Transportation Services in Kenya</h1>
            <p>Professional relocation solutions for individuals, families, and businesses across Kenya and beyond. Safe, efficient, and stress-free moving experience.</p>
            <div class="hero-btns">
                <a href="#services" class="btn">Our Services</a>
                <a href="#contact" class="btn btn-secondary">Book Now</a>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="section" id="services">
        <div class="container">
            <div class="section-title">
                <h2>Our Moving Services</h2>
                <p>We offer comprehensive relocation solutions tailored to meet your specific needs</p>
            </div>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-home"></i>
                    </div>
                    <div class="service-content">
                        <h3>Residential Moving</h3>
                        <p>Professional home relocation services including packing, transportation, and unpacking for families and individuals.</p>
                    </div>
                </div>
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-building"></i>
                    </div>
                    <div class="service-content">
                        <h3>Commercial Moving</h3>
                        <p>Efficient office and business relocation with minimal disruption to your operations.</p>
                    </div>
                </div>
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-globe-africa"></i>
                    </div>
                    <div class="service-content">
                        <h3>International Shipping</h3>
                        <p>Global shipping services for personal belongings and business equipment to destinations worldwide.</p>
                    </div>
                </div>
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-car"></i>
                    </div>
                    <div class="service-content">
                        <h3>Vehicle Transportation</h3>
                        <p>Safe and secure transportation of cars, motorcycles, and other vehicles across Kenya.</p>
                    </div>
                </div>
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-box"></i>
                    </div>
                    <div class="service-content">
                        <h3>Storage Solutions</h3>
                        <p>Secure temporary and long-term storage facilities for your belongings during transitions.</p>
                    </div>
                </div>
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-couch"></i>
                    </div>
                    <div class="service-content">
                        <h3>Specialized Items</h3>
                        <p>Expert handling of pianos, antiques, artwork, and other fragile or valuable items.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="section about" id="about">
        <div class="container">
            <div class="about-content">
                <div class="about-text">
                    <h2>About Ummah Movers</h2>
                    <p>Founded in Nairobi, Ummah Movers has become Kenya's most trusted relocation partner. With over 10 years of experience, we've helped thousands of families and businesses move with confidence and ease.</p>
                    <p>Our team of professional movers is trained in the latest packing techniques and safety protocols. We understand that moving can be stressful, which is why we handle every detail with care and precision.</p>
                    <p>At Ummah Movers, we believe in building long-term relationships with our clients based on trust, reliability, and exceptional service.</p>
                    <a href="#contact" class="btn">Contact Us Today</a>
                </div>
                <div class="about-image">
                    <img src="https://images.unsplash.com/photo-1504384764586-bb4cdc1707b0?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Moving Truck">
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="section testimonials" id="testimonials">
        <div class="container">
            <div class="section-title">
                <h2>What Our Clients Say</h2>
                <p>Hear from satisfied customers who trusted Ummah Movers with their relocation needs</p>
            </div>
            <div class="testimonial-grid">
                <div class="testimonial-card">
                    <div class="testimonial-text">
                        <p>The team at Ummah Movers made our international move seamless. They handled our fragile items with such care and professionalism. Highly recommended!</p>
                    </div>
                    <div class="testimonial-author">
                        <div class="author-image">AM</div>
                        <div class="author-info">
                            <h4>Amina Mohamed</h4>
                            <p>International Relocation</p>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="testimonial-text">
                        <p>Moving our office was stressful, but Ummah Movers took care of everything. They were punctual, efficient, and respectful of our equipment.</p>
                    </div>
                    <div class="testimonial-author">
                        <div class="author-image">JK</div>
                        <div class="author-info">
                            <h4>James Kimani</h4>
                            <p>Business Owner</p>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="testimonial-text">
                        <p>I've used several moving companies, but none compare to Ummah Movers. Their attention to detail and customer service is unmatched in Kenya.</p>
                    </div>
                    <div class="testimonial-author">
                        <div class="author-image">SP</div>
                        <div class="author-info">
                            <h4>Sarah Patel</h4>
                            <p>Residential Client</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="section" id="contact">
        <div class="container">
            <div class="section-title">
                <h2>Contact Us</h2>
                <p>Get in touch for a free quote or to schedule your move</p>
            </div>
            <div class="contact-container">
                <div class="contact-info">
                    <h3>Get In Touch</h3>
                    <div class="contact-details">
                        <div class="contact-item">
                            <div class="contact-icon">
                                <i class="fas fa-map-marker-alt"></i>
                            </div>
                            <div class="contact-text">
                                <h4>Our Location</h4>
                                <p>123 Mombasa Road, Industrial Area, Nairobi, Kenya</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <div class="contact-icon">
                                <i class="fas fa-phone-alt"></i>
                            </div>
                            <div class="contact-text">
                                <h4>Phone Number</h4>
                                <p>+254 700 000 000<br>+254 711 111 111</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <div class="contact-icon">
                                <i class="fas fa-envelope"></i>
                            </div>
                            <div class="contact-text">
                                <h4>Email Address</h4>
                                <p>info@ummahmovers.co.ke<br>support@ummahmovers.co.ke</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <div class="contact-icon">
                                <i class="fas fa-clock"></i>
                            </div>
                            <div class="contact-text">
                                <h4>Working Hours</h4>
                                <p>Monday - Friday: 8:00 AM - 6:00 PM<br>Saturday: 9:00 AM - 4:00 PM</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="contact-form">
                    <form>
                        <div class="form-group">
                            <input type="text" placeholder="Your Name" required>
                        </div>
                        <div class="form-group">
                            <input type="email" placeholder="Your Email" required>
                        </div>
                        <div class="form-group">
                            <input type="tel" placeholder="Your Phone">
                        </div>
                        <div class="form-group">
                            <input type="text" placeholder="Moving Date">
                        </div>
                        <div class="form-group">
                            <textarea placeholder="Your Message" required></textarea>
                        </div>
                        <button type="submit" class="btn">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>Ummah Movers</h3>
                    <p>Your trusted partner for professional relocation and transportation services across Kenya and beyond.</p>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-linkedin-in"></i></a>
                    </div>
                </div>
                <div class="footer-column">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#services">Services</a></li>
                        <li><a href="#about">About Us</a></li>
                        <li><a href="#testimonials">Testimonials</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Our Services</h3>
                    <ul>
                        <li><a href="#">Residential Moving</a></li>
                        <li><a href="#">Commercial Moving</a></li>
                        <li><a href="#">International Shipping</a></li>
                        <li><a href="#">Vehicle Transportation</a></li>
                        <li><a href="#">Storage Solutions</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Contact Info</h3>
                    <ul>
                        <li><i class="fas fa-map-marker-alt"></i> 123 Mombasa Road, Nairobi</li>
                        <li><i class="fas fa-phone"></i> +254 700 000 000</li>
                        <li><i class="fas fa-envelope"></i> info@ummahmovers.co.ke</li>
                        <li><i class="fas fa-clock"></i> Mon-Fri: 8AM-6PM</li>
                    </ul>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2023 Ummah Movers Kenya. All Rights Reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Sticky header
        window.addEventListener('scroll', function() {
            const header = document.querySelector('header');
            header.classList.toggle('sticky', window.scrollY > 0);
        });

        // Form submission
        const contactForm = document.querySelector('.contact-form form');
        if (contactForm) {
            contactForm.addEventListener('submit', function(e) {
                e.preventDefault();
                alert('Thank you for your message! We will get back to you soon.');
                this.reset();
            });
        }
    </script>
</body>
</html>
