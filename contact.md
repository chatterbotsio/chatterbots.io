---
layout: default
title: Contact Us
---

<div class="contact-page">
    <div class="contact-header">
        <h1>Contact Us</h1>
        <p>Ready to transform your customer experience with AI? Get in touch with us.</p>
    </div>

    <div class="contact-grid">
        <div class="contact-form-container">
            <form id="contact-form" class="contact-form" action="https://formspree.io/f/mrbbvqgb" method="POST">
                <div class="form-group">
                    <label for="name">Name</label>
                    <input type="text" id="name" name="name" required>
                </div>

                <div class="form-group">
                    <label for="phone">Phone</label>
                    <input type="phone" id="phone" name="phone">
                </div>

                <div class="form-group">
                    <label for="company">Company</label>
                    <input type="text" id="company" name="company">
                </div>

                <div class="form-group">
                    <label for="message">Message</label>
                    <textarea id="message" name="message" rows="5" required></textarea>
                </div>

                <button type="submit" class="submit-button">Send Message</button>
            </form>
        </div>

        <div class="contact-info">
            <div class="info-card">
                <h3>IT Monger LLC</h3>
                <p>Custom AI chatbot planning, design, hosting and maintenance solutions.</p>
                
                <div class="contact-details">
                    <h4>Email</h4>
                    <p><a href="mailto:contact@chatterbots.io">contact@chatterbots.io</a></p>
                    
                    <h4>Follow Us</h4>
                    <div class="social-links">
                        <a href="https://github.com/chatterbotsio" target="_blank" rel="noopener">GitHub</a>
                        <a href="https://linkedin.com/company/itmonger" target="_blank" rel="noopener">LinkedIn</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<style>
.contact-page {
    padding: 2rem 0;
    max-width: 1200px;
    margin: 0 auto;
}

.contact-header {
    text-align: center;
    margin-bottom: 3rem;
}

.contact-header h1 {
    color: var(--secondary-color);
    margin-bottom: 1rem;
}

.contact-grid {
    display: grid;
    grid-template-columns: 3fr 2fr;
    gap: 3rem;
    padding: 0 1rem;
}

.contact-form {
    background: white;
    padding: 2rem;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.form-group {
    margin-bottom: 1.5rem;
}

.form-group label {
    display: block;
    margin-bottom: 0.5rem;
    color: var(--secondary-color);
    font-weight: 500;
}

.form-group input,
.form-group textarea {
    width: 100%;
    padding: 0.75rem;
    border: 1px solid #ddd;
    border-radius: 4px;
    font-size: 1rem;
    transition: border-color 0.3s ease;
}

.form-group input:focus,
.form-group textarea:focus {
    outline: none;
    border-color: var(--primary-color);
}

.submit-button {
    background: var(--primary-color);
    color: white;
    border: none;
    padding: 1rem 2rem;
    border-radius: 4px;
    font-size: 1rem;
    font-weight: 500;
    cursor: pointer;
    transition: background-color 0.3s ease;
    width: 100%;
}

.submit-button:hover {
    background: darken(var(--primary-color), 10%);
}

.info-card {
    background: var(--secondary-color);
    color: white;
    padding: 2rem;
    border-radius: 8px;
    height: fit-content;
}

.info-card h3 {
    margin-bottom: 1rem;
    font-size: 1.5rem;
}

.contact-details {
    margin-top: 2rem;
}

.contact-details h4 {
    margin: 1.5rem 0 0.5rem;
    color: rgba(255, 255, 255, 0.9);
}

.contact-details a {
    color: white;
    text-decoration: none;
    transition: opacity 0.3s ease;
}

.contact-details a:hover {
    opacity: 0.8;
}

.social-links {
    display: flex;
    gap: 1rem;
}

@media (max-width: 768px) {
    .contact-grid {
        grid-template-columns: 1fr;
    }
    
    .contact-form {
        padding: 1.5rem;
    }
}
</style>

<script>
document.getElementById('contact-form').addEventListener('submit', function(e) {
    e.preventDefault();
    
    // Add form submission logic here
    // You can use Formspree, Netlify Forms, or your own backend
    
    // Example using Fetch API
    fetch(this.action, {
        method: 'POST',
        body: new FormData(this),
        headers: {
            'Accept': 'application/json'
        }
    })
    .then(response => {
        if (response.ok) {
            alert('Message sent successfully!');
            this.reset();
        } else {
            alert('Error sending message. Please try again.');
        }
    })
    .catch(error => {
        console.error('Error:', error);
        alert('Error sending message. Please try again.');
    });
});
</script>
