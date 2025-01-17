---
layout: default
title: About Us
---

<div class="about-page">
    <div class="about-header">
        <h1>About Chatterbots.io</h1>
        <p class="subtitle">Transforming Customer Engagement Through AI Innovation</p>
    </div>

    <div class="about-grid">
        <div class="about-content">
            <div class="section mission">
                <h2>Our Mission</h2>
                <p>At Chatterbots.io, we're dedicated to revolutionizing how businesses connect with their customers through intelligent AI solutions. Our mission is to make advanced chatbot technology accessible, efficient, and impactful for businesses of all sizes.</p>
            </div>

            <div class="section company">
                <h2>About IT Monger LLC</h2>
                <p>IT Monger LLC is a technology company specializing in AI-driven solutions. With expertise in artificial intelligence and customer engagement platforms, we help businesses automate and enhance their customer interactions through sophisticated chatbot solutions.</p>
            </div>

            <div class="section services">
                <h2>What We Do</h2>
                <div class="services-grid">
                    <div class="service-card">
                        <h3>Planning</h3>
                        <p>Strategic consultation and requirements analysis to design the perfect chatbot solution for your business needs.</p>
                    </div>
                    <div class="service-card">
                        <h3>Design</h3>
                        <p>Custom chatbot development with intuitive interfaces and sophisticated conversation flows.</p>
                    </div>
                    <div class="service-card">
                        <h3>Hosting</h3>
                        <p>Secure, reliable cloud hosting with 24/7 monitoring and scalability.</p>
                    </div>
                    <div class="service-card">
                        <h3>Maintenance</h3>
                        <p>Continuous updates, performance optimization, and technical support to ensure optimal operation.</p>
                    </div>
                </div>
            </div>

            <div class="section why-us">
                <h2>Why Choose Us</h2>
                <div class="features-grid">
                    <div class="feature">
                        <h3>Expertise</h3>
                        <p>Deep understanding of AI and chatbot technologies</p>
                    </div>
                    <div class="feature">
                        <h3>Custom Solutions</h3>
                        <p>Tailored approaches for your specific needs</p>
                    </div>
                    <div class="feature">
                        <h3>Reliability</h3>
                        <p>Robust infrastructure with 99.9% uptime</p>
                    </div>
                    <div class="feature">
                        <h3>Support</h3>
                        <p>Dedicated technical support and maintenance</p>
                    </div>
                </div>
            </div>
        </div>

        <div class="cta-section">
            <a href="/contact" class="cta-button">Get Started</a>
        </div>
    </div>
</div>

<style>
.about-page {
    max-width: 1200px;
    margin: 0 auto;
    padding: 2rem 1rem;
}

.about-header {
    text-align: center;
    margin-bottom: 4rem;
}

.about-header h1 {
    color: var(--secondary-color);
    margin-bottom: 1rem;
    font-size: 2.5rem;
}

.subtitle {
    color: var(--text-color);
    font-size: 1.2rem;
    opacity: 0.8;
}

.section {
    margin-bottom: 4rem;
}

.section h2 {
    color: var(--secondary-color);
    margin-bottom: 1.5rem;
    font-size: 1.8rem;
}

.services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    margin-top: 2rem;
}

.service-card {
    background: white;
    padding: 1.5rem;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
}

.service-card:hover {
    transform: translateY(-5px);
}

.service-card h3 {
    color: var(--primary-color);
    margin-bottom: 1rem;
}

.features-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 2rem;
    margin-top: 2rem;
}

.feature {
    text-align: center;
    padding: 1.5rem;
    background: rgba(74, 144, 226, 0.1);
    border-radius: 8px;
    transition: background-color 0.3s ease;
}

.feature:hover {
    background: rgba(74, 144, 226, 0.15);
}

.feature h3 {
    color: var(--primary-color);
    margin-bottom: 0.5rem;
}

.cta-section {
    text-align: center;
    margin-top: 4rem;
    padding: 3rem;
    background: var(--secondary-color);
    border-radius: 8px;
    color: white;
}

.cta-section .cta-button {
    display: inline-block;
    background: var(--primary-color);
    color: white;
    padding: 1rem 2rem;
    border-radius: 4px;
    text-decoration: none;
    font-weight: 500;
    transition: background-color 0.3s ease;
}

.cta-section .cta-button:hover {
    background: darken(var(--primary-color), 10%);
}

@media (max-width: 768px) {
    .about-header h1 {
        font-size: 2rem;
    }

    .section h2 {
        font-size: 1.5rem;
    }

    .services-grid,
    .features-grid {
        grid-template-columns: 1fr;
        gap: 1rem;
    }

    .service-card,
    .feature {
        padding: 1rem;
    }
}
</style>