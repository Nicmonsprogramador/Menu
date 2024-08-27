# Top Rank Solutions - Menú Tipo Hamburguesa

Este proyecto implementa un menú de navegación tipo hamburguesa para la empresa "Top Rank Solutions". El menú permite navegar entre diferentes secciones de una página web: Home, About, Services y Contact. La implementación utiliza HTML, CSS y JavaScript para una experiencia de usuario responsiva y accesible.

## Contenido

- `index.html`: Estructura HTML del menú y las secciones de la página.
- `styles.css`: Estilos CSS para el menú y las secciones.
- `script.js`: Funcionalidad JavaScript para el menú tipo hamburguesa.

## Estructura del Proyecto

### 1. `index.html`

Este archivo contiene la estructura de la página, incluyendo el menú tipo hamburguesa y las secciones de contenido.

#### Estructura del archivo:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Top Rank Solutions</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <nav class="navbar">
        <div class="menu-toggle" id="menu-toggle">
            <div class="bar"></div>
            <div class="bar"></div>
            <div class="bar"></div>
        </div>
        <ul class="nav-list" id="nav-list">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="home">
        <div class="section-content">
            <h1>Welcome to Top Rank Solutions</h1>
            <p>Your partner in achieving digital excellence.</p>
        </div>
    </section>

    <section id="about">
        <div class="section-content">
            <h1>About Us</h1>
            <p>Top Rank Solutions is a leading provider of digital marketing and web development services...</p>
        </div>
    </section>

    <section id="services">
        <div class="section-content">
            <h1>Our Services</h1>
            <div class="service-item">
                <h2>SEO</h2>
                <p>Enhance your online visibility with our comprehensive SEO strategies.</p>
            </div>
            <div class="service-item">
                <h2>PPC Advertising</h2>
                <p>Maximize your ROI with targeted PPC campaigns.</p>
            </div>
            <div class="service-item">
                <h2>Web Design</h2>
                <p>Create a stunning online presence with our web design services.</p>
            </div>
            <div class="service-item">
                <h2>Content Marketing</h2>
                <p>Engage your audience with high-quality content.</p>
            </div>
            <div class="service-item">
                <h2>Social Media Management</h2>
                <p>Boost your brand's presence on social media platforms.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="section-content">
            <h1>Contact Us</h1>
            <p>We'd love to hear from you! Reach out to us using the contact details below or fill out the form.</p>
            <div class="contact-details">
                <div class="contact-item">
                    <h2>Email</h2>
                    <p><a href="mailto:info@topranksolutions.com">info@topranksolutions.com</a></p>
                </div>
                <div class="contact-item">
                    <h2>Phone</h2>
                    <p><a href="tel:+1234567890">+1 234 567 890</a></p>
                </div>
                <div class="contact-item">
                    <h2>Address</h2>
                    <p>123 Business Avenue, Suite 456,<br>City, State, 12345</p>
                </div>
            </div>
            <form class="contact-form" action="your-server-endpoint" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="5" required></textarea>

                <but
