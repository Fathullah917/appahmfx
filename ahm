<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Mobile Apps Landing Page</title>
    <link href="00;60" rel="stylesheet" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"
    />

    <style>
      /* --- CSS Styling dimulai di sini --- */

      /* Import Google Fonts (redundant if linked above, but harmless) */
      @import url("");

      /* CSS Variables */
      :root {
        --primary-color: #ffa500; /* Orange color for highlight */
        --text-color: #ffffff;
        --dark-blue: #1a202c; /* Example dark blue for background, adjust as needed */
        --light-gray: #e2e8f0;
        --button-bg: #4a5568; /* Darker gray for buttons */
        --button-text: #ffffff;
      }

      /* Base Styles */
      body {
        margin: 0;
        font-family: "Open Sans", sans-serif;
        color: var(--text-color);
        background-color: var(--dark-blue); /* Default background, will be overridden by hero image */
        overflow-x: hidden;
        scroll-behavior: smooth; /* Smooth scrolling for anchor links */
      }

      .container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 0 20px;
      }

      /* Navbar */
      .navbar {
        background-color: transparent;
        padding: 20px 0;
        position: absolute;
        width: 100%;
        z-index: 1000;
      }

      .navbar .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
      }

      .logo {
        font-family: "Montserrat", sans-serif;
        font-weight: 700;
        font-size: 24px;
        color: var(--text-color);
        display: flex;
        align-items: center;
      }

      .logo i {
        margin-right: 10px;
        color: var(--primary-color);
      }

      .nav-links ul {
        list-style: none;
        margin: 0;
        padding: 0;
        display: flex;
      }

      .nav-links ul li {
        margin-left: 40px;
      }

      .nav-links ul li a {
        color: var(--text-color);
        text-decoration: none;
        font-weight: 600;
        font-size: 16px;
        transition: color 0.3s ease;
      }

      .nav-links ul li a:hover {
        color: var(--primary-color);
      }

      /* Hero Section */
      .hero-section {
        position: relative;
        width: 100%;
        height: 100vh; /* Full viewport height */
        display: flex;
        align-items: center;
        /* Ganti dengan path gambar latar belakang ponsel Anda */
        /* Saya menggunakan placeholder dari Unsplash sebagai contoh */
        background-image: url("backg.jpg");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        overflow: hidden;
      }

      .hero-image-overlay {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        /* Gradient from dark left to transparent right */
        background: linear-gradient(
          to right,
          rgba(0, 0, 0, 0.7) 0%,
          rgba(0, 0, 0, 0.2) 60%,
          rgba(0, 0, 0, 0) 100%
        );
        /* Adjust gradient to match the image's lighting */
      }

      .hero-section .container {
        position: relative;
        z-index: 10; /* Ensure content is above the overlay */
      }

      .hero-content {
        max-width: 600px; /* Adjust as needed */
        text-align: left;
        padding-left: 50px; /* Posisikan konten sedikit ke kanan dari kiri */
      }

      .hero-content h1 {
        font-family: "Montserrat", sans-serif;
        font-weight: 700;
        font-size: 80px; /* Adjust font size as needed */
        margin-bottom: 10px;
        line-height: 1;
      }

      .hero-content h1 .highlight {
        color: var(--primary-color);
      }

      .hero-content .subtitle {
        font-size: 20px;
        font-weight: 600;
        color: var(--light-gray);
        margin-bottom: 20px;
      }

      .hero-content .description {
        font-size: 16px;
        line-height: 1.6;
        margin-bottom: 40px;
        max-width: 450px; /* Limit description width */
      }

      .navigation-buttons {
        display: flex;
        gap: 20px;
      }

      .btn {
        background-color: var(--button-bg);
        color: var(--button-text);
        border: none;
        padding: 15px 30px;
        font-size: 16px;
        font-weight: 600;
        border-radius: 5px;
        cursor: pointer;
        transition: background-color 0.3s ease;
        display: flex;
        align-items: center;
        gap: 10px;
      }

      .btn:hover {
        background-color: #384252; /* A slightly darker shade for hover */
      }

      .btn-previous {
        background-color: var(--primary-color); /* For the previous button, match highlight color */
      }

      .btn-previous:hover {
        background-color: #e69500; /* A slightly darker shade for hover */
      }

      /* Footer Bottom Text */
      .footer-bottom-text {
        position: absolute;
        bottom: 20px;
        left: 0;
        width: 100%;
        text-align: right; /* Align text to the right as in the image */
        padding-right: 50px; /* Add some padding from the right edge */
        box-sizing: border-box;
        font-size: 14px;
        color: rgba(255, 255, 255, 0.7); /* Slightly faded white */
        z-index: 10; /* Ensure it's above the background image */
      }

      .footer-bottom-text .container {
        display: flex;
        justify-content: flex-end; /* Align content to the right */
      }

      .footer-bottom-text p {
        max-width: 500px; /* Limit width to mimic the image */
        text-align: left; /* Keep text aligned left within its box */
      }

      /* --- Responsive adjustments (basic) --- */
      @media (max-width: 768px) {
        .navbar .container {
          flex-direction: column;
          align-items: flex-start;
        }

        .nav-links ul {
          margin-top: 15px;
          flex-direction: column;
          align-items: flex-start;
        }

        .nav-links ul li {
          margin: 10px 0;
        }

        .hero-content {
          text-align: center;
          padding: 0 20px;
        }

        .hero-content h1 {
          font-size: 50px;
        }

        .navigation-buttons {
          justify-content: center;
        }

        .footer-bottom-text {
          text-align: center;
          padding-right: 20px;
          padding-left: 20px;
        }

        .footer-bottom-text .container {
          justify-content: center;
        }
      }

      @media (max-width: 480px) {
        .hero-content h1 {
          font-size: 40px;
        }

        .btn {
          padding: 12px 20px;
          font-size: 14px;
        }
      }

      /* --- CSS Styling berakhir di sini --- */
    </style>
  </head>
  <body>
    <header class="navbar">
      <div class="container">
        <div class="logo">
          <i class="fas fa-cube"></i> AhmadFx Group
        </div>
        <nav class="nav-links">
          <ul>
            <li><a href="#hero-section">Home</a></li>
            <li><a href="#about-us-section">About Us</a></li>
            <li><a href="#services-section">Service</a></li>
            <li>
              <a
                href="https://www.instagram.com/your_instagram_username"
                target="_blank"
                rel="noopener noreferrer"
                >Contact</a
              >
            </li>
          </ul>
        </nav>
      </div>
    </header>

    <section class="hero-section" id="hero-section">
      <div class="container">
        <div class="hero-content">
          <h1>
            MOBILE <span class="highlight">APPS</span>
          </h1>
          <p class="subtitle">
            Empowering Financial Decisions with Smart Data and Sound Finance.
          </p>
          <p class="description">
            Mobile apps are often thought of as the opposite of a desktop app
            running on a desktop computer, and a web app running on the device's
            web browser.
          </p>
          <div class="navigation-buttons">
            <button class="btn btn-previous">
              <i class="fas fa-chevron-left"></i> PREVIOUS
            </button>
            <button class="btn btn-next">
              NEXT <i class="fas fa-chevron-right"></i>
            </button>
          </div>
        </div>
      </div>
      <div class="hero-image-overlay"></div>
    </section>

    <section
      id="about-us-section"
      style="
        height: 500px;
        background-color: #2d3748;
        padding-top: 100px;
        text-align: center;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
      "
    >
      <div class="container">
        <h2
          style="
            color: white;
            font-family: 'Montserrat', sans-serif;
          "
        >
          About Us
        </h2>
        <p
          style="
            color: lightgray;
            max-width: 600px;
            margin-top: 20px;
          "
        >
          Kami adalah tim yang berdedikasi dalam mengembangkan solusi aplikasi
          mobile inovatif. Dengan pengalaman bertahun-tahun, kami siap membantu
          Anda mewujudkan ide-ide digital.
        </p>
      </div
