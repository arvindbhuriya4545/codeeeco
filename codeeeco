<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Codeeeco Infotech - Innovative Software Solutions</title>
  <style>
    /* Reset */
    *, *::before, *::after {
      margin: 0; padding: 0; box-sizing: border-box;
    }
    body {
      font-family: 'Poppins', sans-serif;
      background: #0f111a;
      color: #e1e1e6;
      line-height: 1.6;
      scroll-behavior: smooth;
    }
    a {
      color: #8257e6;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    header {
      position: fixed;
      width: 100%;
      background: #1f213a;
      padding: 20px 50px;
      top: 0;
      left: 0;
      z-index: 1000;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 0 20px rgba(0,0,0,0.3);
    }
    header .logo {
      font-weight: 700;
      font-size: 1.8rem;
      color: #8257e6;
      letter-spacing: 2px;
      cursor: default;
    }
    nav ul {
      display: flex;
      list-style: none;
      gap: 30px;
    }
    nav ul li a {
      font-weight: 600;
      font-size: 1rem;
      padding: 10px;
      transition: color 0.3s;
    }
    nav ul li a:hover {
      color: #d4c1ff;
    }

    main {
      padding-top: 100px;
      max-width: 1200px;
      margin: 0 auto;
      padding-left: 20px;
      padding-right: 20px;
    }
    /* Hero */
    .hero {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 6rem;
      gap: 2rem;
      flex-wrap: wrap;
    }
    .hero-text {
      max-width: 600px;
    }
    .hero-text h1 {
      font-size: 3rem;
      font-weight: 700;
      margin-bottom: 1rem;
      color: #8257e6;
      line-height: 1.2;
    }
    .hero-text p {
      font-size: 1.2rem;
      margin-bottom: 2rem;
      color: #c3b9ff;
    }
    .btn-primary {
      display: inline-block;
      background: #8257e6;
      padding: 1rem 2.5rem;
      border-radius: 8px;
      font-weight: 700;
      color: white;
      font-size: 1rem;
      cursor: pointer;
      border: none;
      transition: background-color 0.3s ease;
      text-transform: uppercase;
      letter-spacing: 1.5px;
    }
    .btn-primary:hover {
      background: #6b46c1;
    }
    .hero-image {
      max-width: 500px;
      flex-shrink: 0;
    }
    .hero-image img {
      width: 100%;
      border-radius: 20px;
      box-shadow: 0 10px 30px rgba(130, 87, 230, 0.5);
    }

    /* Sections style */
    section {
      margin-bottom: 5rem;
    }
    section h2 {
      font-size: 2.5rem;
      color: #8257e6;
      margin-bottom: 2rem;
      border-bottom: 3px solid #8257e6;
      display: inline-block;
      padding-bottom: 6px;
      font-weight: 700;
    }
    /* About */
    #about p {
      font-size: 1.1rem;
      color: #bfb9d8;
      max-width: 700px;
      line-height: 1.6;
    }
    /* Services grid */
    .services-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(280px,1fr));
      gap: 2.5rem;
    }
    .service-card {
      background: #1f213a;
      border-radius: 15px;
      padding: 2rem;
      box-shadow: 0 5px 20px rgba(130, 87, 230, 0.3);
      transition: transform 0.3s ease;
      cursor: default;
      overflow-y: auto;
      max-height: 550px;
    }
    .service-card:hover {
      transform: translateY(-10px);
      box-shadow: 0 10px 40px rgba(130, 87, 230, 0.5);
    }
    .service-card h3 {
      color: #d9caff;
      margin-bottom: 1rem;
      font-weight: 700;
      font-size: 1.3rem;
    }
    .service-card p,
    .service-card ul {
      color: #c3b9ff;
      font-size: 1rem;
      line-height: 1.4;
    }
    .service-card ul {
      padding-left: 1.3rem;
      margin-bottom: 1rem;
    }
    .service-card ul li {
      margin-bottom: 0.3rem;
    }

    /* Contact */
    #contact form {
      max-width: 600px;
      background: #1f213a;
      padding: 2.5rem;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(130, 87, 230, 0.4);
    }
    #contact label {
      display: block;
      margin-bottom: 0.4rem;
      font-weight: 600;
      color: #c3b9ff;
      font-size: 1rem;
    }
    #contact input,
    #contact textarea {
      width: 100%;
      padding: 12px 15px;
      border-radius: 8px;
      border: none;
      margin-bottom: 1.5rem;
      font-size: 1rem;
      background: #2a2c4a;
      color: white;
      resize: vertical;
    }
    #contact input::placeholder,
    #contact textarea::placeholder {
      color: #928fba;
    }
    #contact button {
      background: #8257e6;
      color: white;
      padding: 1rem 2.5rem;
      font-weight: 700;
      border-radius: 8px;
      border: none;
      cursor: pointer;
      font-size: 1.1rem;
      transition: background-color 0.3s ease;
      text-transform: uppercase;
      letter-spacing: 1.5px;
    }
    #contact button:hover {
      background: #6b46c1;
    }

    /* Footer */
    footer {
      background: #1f213a;
      padding: 1.5rem;
      text-align: center;
      font-size: 0.9rem;
      color: #bfb9d8;
      border-top: 1px solid #2a2c4a;
    }
    footer a {
      color: #8257e6;
    }
    footer a:hover {
      text-decoration: underline;
    }

    /* Responsive */
    @media(max-width: 768px) {
      .hero {
        flex-direction: column;
        text-align: center;
      }
      .hero-image {
        max-width: 90%;
        margin: 2rem auto 0;
      }
      header {
        padding: 20px 20px;
      }
      nav ul {
        gap: 15px;
      }
    }
  </style>
</head>
<body>

<header>
  <div class="logo">Codeeeco Infotech</div>
  <nav>
    <ul>
      <li><a href="#home" onclick="scrollToSection(event, 'home')">Home</a></li>
      <li><a href="#about" onclick="scrollToSection(event, 'about')">About</a></li>
      <li><a href="#services" onclick="scrollToSection(event, 'services')">Services</a></li>
      <li><a href="#pricing" onclick="scrollToSection(event, 'pricing')">Pricing</a></li>
      <li><a href="#contact" onclick="scrollToSection(event, 'contact')">Contact</a></li>
    </ul>
  </nav>
</header>

<main>
  <section id="home" class="hero">
    <div class="hero-text">
      <h1>Build Your Future with Cutting-Edge Tech Solutions</h1>
      <p>Codeeeco Infotech delivers high-quality software development, cloud solutions, and consulting services tailored to your business goals.</p>
      <button class="btn-primary" onclick="scrollToSection(event, 'contact')">Contact Us</button>
    </div>
    <div class="hero-image">
      <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?auto=format&fit=crop&w=800&q=80" alt="Technology Illustration" />
    </div>
  </section>

  <section id="about">
    <h2>About Codeeeco Infotech</h2>
    <p>We are a passionate team of developers and consultants dedicated to empowering businesses with innovative technology. Our solutions are designed to improve efficiency, increase revenue, and drive digital transformation across industries.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services-grid">
      <div class="service-card">
        <h3>Custom Software Development</h3>
        <p>Tailored applications designed to your business needs using the latest technologies and frameworks for scalability and performance.</p>
      </div>
      <div class="service-card">
        <h3>Cloud Solutions & Hosting</h3>
        <p>Reliable cloud hosting, migration, and infrastructure management to keep your business online and secure 24/7.</p>
      </div>
      <div class="service-card">
        <h3>Web Development</h3>
        <p>Responsive, SEO-friendly websites and eCommerce platforms built to attract, engage, and convert your visitors.</p>
      </div>
      <div class="service-card">
        <h3>Technical Consulting</h3>
        <p>Expert guidance to streamline your IT projects and ensure smooth adoption of new technologies and best practices.</p>
      </div>
    </div>
  </section>

  <!-- Pricing Plans Section -->
  <section id="pricing">
    <h2>Pricing Plans</h2>
    <div class="services-grid">
      <!-- Standard Plan -->
      <div class="service-card">
        <h3>Standard Plan</h3>
        <p><strong>Web Development Standard Package</strong></p>
        <p><del>₹10,000</del> <strong>₹7,999</strong></p>
        <p>( + 18% GST ₹1440 )</p>
        <ul>
          <li>5 pages Website</li>
          <li>1 Year Free Domain Name ( .com .in .org )</li>
          <li>1 Year Free Cloud Hosting</li>
          <li>Dynamic Website ( Premium Design )</li>
          <li>Admin Access</li>
          <li>Lifetime 24/7 Free Hosting Support</li>
          <li>Unlimited Images & Videos Upload</li>
          <li>Free SSL Certificates</li>
          <li>5 Free Email Id</li>
          <li>SEO Friendly Website</li>
          <li>100% Responsive Website</li>
          <li>Live Chat Integration</li>
          <li>Payment Gateway Integration</li>
          <li>Social Media Integration</li>
          <li>Call Button Integration</li>
          <li>WhatsApp Button Integration</li>
          <li>Inquiry Form</li>
          <li>1 Year Free Technical Support For Website</li>
          <li>Annual Renewal For Hosting Rs.3000.</li>
        </ul>
        <button class="btn-primary" onclick="alert('Call Now: +919409541641')">Call Now</button>
      </div>

      <!-- Premium Plan -->
      <div class="service-card">
        <h3>Premium Plan</h3>
        <p><strong>Web Development Premium Package</strong></p>
        <p><del>₹20,000</del> <strong>₹13,999</strong></p>
        <p>( + 18% GST ₹2520 )</p>
        <ul>
          <li>12 pages Website</li>
          <li>1 Year Free Domain Name ( .com .in .org )</li>
          <li>1 Year Free Cloud Hosting</li>
          <li>1 Year Free Designer Logo (3 samples)</li>
          <li>Dynamic Website ( Premium Design )</li>
          <li>Admin Access</li>
          <li>Google Search Console Setup</li>
          <li>Lifetime 24/7 Free Hosting Support</li>
          <li>Unlimited Images & Videos Upload</li>
          <li>Free SSL Certificates</li>
          <li>10 Free Email Id</li>
          <li>SEO Friendly Website</li>
          <li>100% Responsive Website</li>
          <li>Live Chat Integration</li>
          <li>Payment Gateway Integration</li>
          <li>Social Media Integration</li>
          <li>Call Button Integration</li>
          <li>WhatsApp Button Integration</li>
          <li>Inquiry Form</li>
          <li>Woocommerce Features</li>
          <li>1 Year Free Technical Support For Website</li>
          <li>Annual Renewal For Hosting Rs.3000.</li>
        </ul>
        <button class="btn-primary" onclick="alert('Call Now: +919409541641')">Call Now</button>
      </div>

      <!-- Custom Plan -->
      <div class="service-card">
        <h3>Custom Plan</h3>
        <p><strong>Web Development Pro Package</strong></p>
        <p>₹ ??? <strong>₹ ????</strong></p>
        <p>( + 18% GST Applicable )</p>
        <ul>
          <li>Pages: According to Requirement</li>
          <li>1 Year Free Domain Name ( .com .in .org )</li>
          <li>1 Year Free Cloud Hosting</li>
          <li>Dynamic Website</li>
          <li>Admin Access</li>
          <li>Google Search Console Setup</li>
          <li>Lifetime 24/7 Free Hosting Support</li>
          <li>Unlimited Images & Videos Upload</li>
          <li>Free SSL Certificates</li>
          <li>10 Free Email Id</li>
          <li>SEO Friendly Website</li>
          <li>100% Responsive Website</li>
          <li>Live Chat Integration</li>
          <li>Payment Gateway Integration</li>
          <li>Social Media Integration</li>
          <li>Call Button Integration</li>
          <li>WhatsApp Button Integration</li>
          <li>Inquiry Form</li>
          <li>Woocommerce Features</li>
          <li>1 Year 24/7 Free Support For Website</li>
          <li>Annual Renewal Rs.4000</li>
        </ul>
        <button class="btn-primary" onclick="alert('Call Now: +919409541641')">Call Now</button>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form id="contact-form" action="mailto:codeeecoinfotech@gmail.com" method="POST" enctype="text/plain">
      <label for="name">Name</label>
      <input type="text" id="name" name="Name" placeholder="Your full name" required />
      <label for="email">Email</label>
      <input type="email" id="email" name="Email" placeholder="Your email address" required />
      <label for="message">Message</label>
      <textarea id="message" name="Message" rows="6" placeholder="Write your message here" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>
</main>

<footer>
  &copy; 2025 Codeeeco Infotech. All rights reserved. | Email: <a href="mailto:codeeecoinfotech@gmail.com">codeeecoinfotech@gmail.com</a>
</footer>

<script>
  // Smooth scroll to sections
  function scrollToSection(event, sectionId) {
    event.preventDefault();
    document.getElementById(sectionId).scrollIntoView({behavior: 'smooth'});
  }
</script>

</body>
</html>

