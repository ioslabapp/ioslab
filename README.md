<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="IOSLAB - Crafting Exceptional iPhone Apps. Premium native iOS development with Swift and SwiftUI.">
    <meta name="theme-color" content="#000000">
    <title>IOSLAB - Premium iOS App Development</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="navbar-container">
            <div class="logo">IOSLAB</div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#apps">Apps</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#why">Why Us</a></li>
                <li><a href="#contact" class="nav-cta">Contact</a></li>
            </ul>
            <div class="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <h1 class="hero-title">Crafting Exceptional iPhone Apps.</h1>
            <p class="hero-subtitle">Premium native iOS development with Swift and SwiftUI. Elegant. Fast. Privacy-first.</p>
            <div class="hero-cta">
                <a href="#contact" class="btn btn-primary">Start Your Project</a>
                <a href="#apps" class="btn btn-secondary">View Our Work</a>
            </div>
        </div>
        <div class="hero-visual">
            <div class="iphone-frame">
                <div class="iphone-screen"></div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="section-container">
            <div class="about-content">
                <h2 class="section-title">About IOSLAB</h2>
                <p class="about-text">
                    IOSLAB is a modern software studio specializing in native iOS development. We create elegant, high-performance applications that embody Apple's philosophy of simplicity and precision.
                </p>
                <p class="about-text">
                    With expertise in Swift, SwiftUI, and App Store publishing, we transform innovative ideas into world-class iPhone applications. Our focus is on delivering products that users love and businesses trust.
                </p>
                <div class="about-stats">
                    <div class="stat">
                        <div class="stat-number">50+</div>
                        <div class="stat-label">Apps Published</div>
                    </div>
                    <div class="stat">
                        <div class="stat-number">10M+</div>
                        <div class="stat-label">Total Downloads</div>
                    </div>
                    <div class="stat">
                        <div class="stat-number">4.8★</div>
                        <div class="stat-label">Avg. Rating</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Featured Apps Section -->
    <section id="apps" class="apps">
        <div class="section-container">
            <h2 class="section-title">Featured Applications</h2>
            <div class="apps-grid">
                <div class="app-card">
                    <div class="app-icon">
                        <div class="icon-placeholder productivity"></div>
                    </div>
                    <h3 class="app-name">TaskFlow Pro</h3>
                    <p class="app-description">Intelligent task management with AI-powered scheduling and seamless iCloud sync.</p>
                    <a href="https://apps.apple.com" target="_blank" class="app-link">
                        <span>View on App Store</span>
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M7 17L17 7M17 7H7M17 7V17"></path>
                        </svg>
                    </a>
                </div>

                <div class="app-card">
                    <div class="app-icon">
                        <div class="icon-placeholder health"></div>
                    </div>
                    <h3 class="app-name">WellnessTrack</h3>
                    <p class="app-description">Privacy-first health tracking with real-time insights and intelligent wellness recommendations.</p>
                    <a href="https://apps.apple.com" target="_blank" class="app-link">
                        <span>View on App Store</span>
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M7 17L17 7M17 7H7M17 7V17"></path>
                        </svg>
                    </a>
                </div>

                <div class="app-card">
                    <div class="app-icon">
                        <div class="icon-placeholder finance"></div>
                    </div>
                    <h3 class="app-name">SecureVault</h3>
                    <p class="app-description">Military-grade encryption for secure note storage and password management on-device.</p>
                    <a href="https://apps.apple.com" target="_blank" class="app-link">
                        <span>View on App Store</span>
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M7 17L17 7M17 7H7M17 7V17"></path>
                        </svg>
                    </a>
                </div>

                <div class="app-card">
                    <div class="app-icon">
                        <div class="icon-placeholder creativity"></div>
                    </div>
                    <h3 class="app-name">SketchLine</h3>
                    <p class="app-description">Professional illustration app with advanced brush engine and seamless Apple Pencil integration.</p>
                    <a href="https://apps.apple.com" target="_blank" class="app-link">
                        <span>View on App Store</span>
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M7 17L17 7M17 7H7M17 7V17"></path>
                        </svg>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <div class="section-container">
            <h2 class="section-title">Our Services</h2>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">
                        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
                            <rect x="2" y="3" width="20" height="18" rx="2"></rect>
                            <path d="M2 9h20"></path>
                        </svg>
                    </div>
                    <h3>Native iOS Development</h3>
                    <p>Custom iPhone and iPad applications built with Swift for optimal performance and user experience.</p>
                </div>

                <div class="service-card">
                    <div class="service-icon">
                        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
                            <path d="M12 2L2 7L2 12C2 16.5 12 22 12 22s10-5.5 10-10V7L12 2Z"></path>
                        </svg>
                    </div>
                    <h3>SwiftUI Design</h3>
                    <p>Modern declarative UI development with SwiftUI for beautiful, responsive interfaces across all Apple devices.</p>
                </div>

                <div class="service-card">
                    <div class="service-icon">
                        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
                            <circle cx="12" cy="12" r="10"></circle>
                            <path d="M12 6v6l4 2"></path>
                        </svg>
                    </div>
                    <h3>AI Integration</h3>
                    <p>Implement machine learning and on-device AI using Core ML, Create ML, and natural language processing.</p>
                </div>

                <div class="service-card">
                    <div class="service-icon">
                        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
                            <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2z"></path>
                            <path d="M12 6v6l4.25 2.25"></path>
                        </svg>
                    </div>
                    <h3>App Store Publishing</h3>
                    <p>End-to-end App Store submission, optimization, and marketing strategies to maximize visibility and downloads.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Why Choose IOSLAB -->
    <section id="why" class="why-choose">
        <div class="section-container">
            <h2 class="section-title">Why Choose IOSLAB</h2>
            <div class="reasons-grid">
                <div class="reason">
                    <h4>Apple-Quality Standards</h4>
                    <p>We follow Apple's human interface guidelines and design principles for premium user experiences.</p>
                </div>
                <div class="reason">
                    <h4>Performance-First</h4>
                    <p>Optimized code, minimal battery drain, and lightning-fast load times are built into every project.</p>
                </div>
                <div class="reason">
                    <h4>Privacy-Centric</h4>
                    <p>On-device processing, encrypted data, and transparent data practices in all applications.</p>
                </div>
                <div class="reason">
                    <h4>Expert Team</h4>
                    <p>Seasoned iOS developers with years of experience shipping successful apps on the App Store.</p>
                </div>
                <div class="reason">
                    <h4>Full Service</h4>
                    <p>From concept to launch: design, development, testing, and App Store publication in one partnership.</p>
                </div>
                <div class="reason">
                    <h4>Ongoing Support</h4>
                    <p>Continuous updates, maintenance, and feature additions to keep your app competitive and modern.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="section-container">
            <h2 class="section-title">Let's Build Something Amazing</h2>
            <p class="contact-subtitle">Reach out to discuss your iOS app idea or explore how IOSLAB can help your business.</p>
            
            <div class="contact-content">
                <div class="contact-form-wrapper">
                    <form class="contact-form" id="contactForm">
                        <div class="form-group">
                            <label for="name">Full Name</label>
                            <input type="text" id="name" name="name" required>
                        </div>
                        <div class="form-group">
                            <label for="email">Email Address</label>
                            <input type="email" id="email" name="email" required>
                        </div>
                        <div class="form-group">
                            <label for="company">Company</label>
                            <input type="text" id="company" name="company">
                        </div>
                        <div class="form-group">
                            <label for="message">Message</label>
                            <textarea id="message" name="message" rows="6" required></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Send Message</button>
                    </form>
                </div>

                <div class="contact-info">
                    <div class="contact-item">
                        <h4>Email</h4>
                        <a href="mailto:hello@ioslab.dev">hello@ioslab.dev</a>
                    </div>
                    <div class="contact-item">
                        <h4>Connect</h4>
                        <div class="social-links">
                            <a href="https://linkedin.com/company/ioslab" target="_blank" title="LinkedIn">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                                    <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.225 0z"/>
                                </svg>
                            </a>
                            <a href="https://twitter.com/ioslab" target="_blank" title="Twitter">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                                    <path d="M23.953 4.57a10 10 0 01-2.825.775 4.958 4.958 0 002.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 00-8.384 4.482C7.69 8.095 4.067 6.13 1.64 3.162a4.822 4.822 0 00-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 01-2.228-.616v.06a4.923 4.923 0 003.946 4.827 4.996 4.996 0 01-2.212.085 4.936 4.936 0 004.604 3.417a9.867 9.867 0 01-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 007.557 2.209c9.053 0 13.998-7.496 13.998-13.985 0-.21 0-.42-.015-.63A9.935 9.935 0 0024 4.59z"/>
                                </svg>
                            </a>
                            <a href="https://github.com/ioslab" target="_blank" title="GitHub">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                                    <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.6.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v 3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/>
                                </svg>
                            </a>
                        </div>
                    </div>
                    <div class="contact-item">
                        <h4>Based In</h4>
                        <p>San Francisco, California</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="footer-content">
            <p>&copy; 2024 IOSLAB. All rights reserved.</p>
            <div class="footer-links">
                <a href="#about">Privacy</a>
                <a href="#about">Terms</a>
                <a href="#contact">Contact</a>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
