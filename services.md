---
layout: default
title: Services
---

<div class="services-page">
    <div class="services-header">
        <h1>Our Services</h1>
        <p class="subtitle">Comprehensive AI Chatbot Solutions for Your Business</p>
    </div>

    <div class="services-grid">
        <div class="service-card planning">
            <div class="service-content">
                <h2>Planning & Strategy</h2>
                <p class="description">Strategic consultation and analysis to design the perfect chatbot solution.</p>
                
                <div class="features-list">
                    <h3>What's Included:</h3>
                    <ul>
                        <li>Requirements Analysis</li>
                        <li>Business Goals Alignment</li>
                        <li>User Journey Mapping</li>
                        <li>Technical Feasibility Study</li>
                        <li>ROI Projections</li>
                    </ul>
                </div>

                <div class="benefits">
                    <p>Ensure your chatbot solution aligns perfectly with your business objectives and user needs.</p>
                </div>
            </div>
        </div>

        <div class="service-card design">
            <div class="service-content">
                <h2>Design & Development</h2>
                <p class="description">Custom chatbot creation with advanced AI capabilities.</p>
                
                <div class="features-list">
                    <h3>What's Included:</h3>
                    <ul>
                        <li>Custom AI Model Training</li>
                        <li>Conversation Flow Design</li>
                        <li>UI/UX Development</li>
                        <li>Multi-platform Integration</li>
                        <li>Testing & Optimization</li>
                    </ul>
                </div>

                <div class="benefits">
                    <p>Get a sophisticated, intelligent chatbot that represents your brand and serves your customers effectively.</p>
                </div>
            </div>
        </div>

        <div class="service-card hosting">
            <div class="service-content">
                <h2>Hosting & Integration</h2>
                <p class="description">Secure, reliable cloud hosting with seamless integration.</p>
                
                <div class="features-list">
                    <h3>What's Included:</h3>
                    <ul>
                        <li>Cloud Infrastructure Setup</li>
                        <li>24/7 Monitoring</li>
                        <li>Security Management</li>
                        <li>Performance Optimization</li>
                        <li>Scalability Management</li>
                    </ul>
                </div>

                <div class="benefits">
                    <p>Ensure your chatbot operates reliably with maximum uptime and optimal performance.</p>
                </div>
            </div>
        </div>

        <div class="service-card maintenance">
            <div class="service-content">
                <h2>Maintenance & Support</h2>
                <p class="description">Ongoing support and continuous improvement of your chatbot.</p>
                
                <div class="features-list">
                    <h3>What's Included:</h3>
                    <ul>
                        <li>Regular Updates</li>
                        <li>Performance Analytics</li>
                        <li>Technical Support</li>
                        <li>Content Updates</li>
                        <li>AI Model Refinement</li>
                    </ul>
                </div>

                <div class="benefits">
                    <p>Keep your chatbot performing at its best with continuous improvements and expert support.</p>
                </div>
            </div>
        </div>
    </div>

    <div class="process-section">
        <h2>Our Process</h2>
        <div class="process-steps">
            <div class="step">
                <div class="step-number">1</div>
                <h3>Consultation</h3>
                <p>Initial meeting to understand your needs and objectives</p>
            </div>
            <div class="step">
                <div class="step-number">2</div>
                <h3>Planning</h3>
                <p>Detailed strategy and solution design</p>
            </div>
            <div class="step">
                <div class="step-number">3</div>
                <h3>Development</h3>
                <p>Custom chatbot creation and testing</p>
            </div>
            <div class="step">
                <div class="step-number">4</div>
                <h3>Deployment</h3>
                <p>Launch and integration with your platforms</p>
            </div>
            <div class="step">
                <div class="step-number">5</div>
                <h3>Support</h3>
                <p>Ongoing maintenance and optimization</p>
            </div>
        </div>
    </div>

    <div class="cta-section">
        <h2>Ready to Get Started?</h2>
        <p>Transform your customer experience with our AI chatbot solutions</p>
        <a href="/contact" class="cta-button">Contact Us</a>
    </div>
</div>

<style>
.services-page {
    max-width: 1200px;
    margin: 0 auto;
    padding: 2rem 1rem;
}

.services-header {
    text-align: center;
    margin-bottom: 4rem;
}

.services-header h1 {
    color: var(--secondary-color);
    margin-bottom: 1rem;
    font-size: 2.5rem;
}

.subtitle {
    color: var(--text-color);
    font-size: 1.2rem;
    opacity: 0.8;
}

.services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin-bottom: 4rem;
}

.service-card {
    background: white;
    border-radius: 8px;
    box-shadow: 0 2px 15px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
    overflow: hidden;
}

.service-card:hover {
    transform: translateY(-5px);
}

.service-content {
    padding: 2rem;
}

.service-card h2 {
    color: var(--primary-color);
    margin-bottom: 1rem;
    font-size: 1.5rem;
}

.description {
    color: var(--text-color);
    margin-bottom: 1.5rem;
}

.features-list {
    margin: 1.5rem 0;
}

.features-list h3 {
    color: var(--secondary-color);
    margin-bottom: 1rem;
    font-size: 1.1rem;
}

.features-list ul {
    list-style: none;
    padding: 0;
}

.features-list li {
    margin-bottom: 0.5rem;
    padding-left: 1.5rem;
    position: relative;
}

.features-list li:before {
    content: "→";
    position: absolute;
    left: 0;
    color: var(--primary-color);
}

.benefits {
    margin-top: 1.5rem;
    padding-top: 1.5rem;
    border-top: 1px solid #eee;
}

.process-section {
    margin: 4rem 0;
    text-align: center;
}

.process-section h2 {
    color: var(--secondary-color);
    margin-bottom: 2rem;
}

.process-steps {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 2rem;
}

.step {
    flex: 1;
    min-width: 200px;
    padding: 1.5rem;
    text-align: center;
}

.step-number {
    width: 40px;
    height: 40px;
    background: var(--primary-color);
    color: white;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0 auto 1rem;
    font-weight: bold;
}

.cta-section {
    text-align: center;
    margin-top: 4rem;
    padding: 3rem;
    background: var(--secondary-color);
    border-radius: 8px;
    color: white;
}

.cta-section h2 {
    margin-bottom: 1rem;
}

.cta-section p {
    margin-bottom: 2rem;
}

.cta-button {
    display: inline-block;
    background: var(--primary-color);
    color: white;
    padding: 1rem 2rem;
    border-radius: 4px;
    text-decoration: none;
    font-weight: 500;
    transition: background-color 0.3s ease;
}

.cta-button:hover {
    background: darken(var(--primary-color), 10%);
}

@media (max-width: 768px) {
    .services-header h1 {
        font-size: 2rem;
    }

    .services-grid {
        grid-template-columns: 1fr;
    }

    .process-steps {
        flex-direction: column;
    }

    .step {
        width: 100%;
    }
}
</style>