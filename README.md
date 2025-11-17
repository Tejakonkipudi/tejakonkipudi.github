<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Teja&Ko Company | Expert Invoice Processing Services</title>
    
    <!-- SEO Optimization: Description and Keywords -->
    <meta name="description" content="Teja&Ko Company provides dedicated freelance invoice processing, accounts payable (AP) management, and 24-hour reconciliation services. Achieve 99.9% accuracy and significant cost reduction for your business.">
    <meta name="keywords" content="invoice processing, accounts payable, freelance AP team, expense management, invoice reconciliation, financial services, Teja&Ko Company">
    <meta name="author" content="Teja&Ko Company">

    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Configure Tailwind to use Inter font -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        'primary': '#0D47A1', // Dark Blue
                        'secondary': '#00B8D4', // Cyan/Teal
                        'light-bg': '#F4F7FC', // Very light gray/blue
                    }
                }
            }
        }
    </script>
    <!-- Add Inter font -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet">
    <style>
        /* Smooth scrolling for internal links */
        html {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body class="font-sans text-gray-800 bg-white">

    <!-- Navigation Bar -->
    <header class="sticky top-0 z-50 bg-white shadow-md">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-extrabold text-primary tracking-tight">
                Teja&Ko <span class="text-secondary">Company</span>
            </a>
            <nav class="hidden md:flex space-x-8">
                <a href="#services" class="text-lg font-medium text-gray-600 hover:text-primary transition duration-300">Services</a>
                <a href="#benefits" class="text-lg font-medium text-gray-600 hover:text-primary transition duration-300">Benefits</a>
                <a href="#about" class="text-lg font-medium text-gray-600 hover:text-primary transition duration-300">Our Team</a>
                <a href="#contact" class="px-4 py-2 bg-secondary text-white rounded-lg shadow-md hover:bg-opacity-90 transition duration-300">Get Quote</a>
            </nav>

            <!-- Mobile Menu Button -->
            <button id="menu-button" class="md:hidden p-2 rounded-lg text-primary hover:bg-light-bg transition duration-300">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </div>
        <!-- Mobile Menu (Hidden by Default) -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t border-gray-100">
            <a href="#services" class="block py-3 px-4 text-center text-lg text-gray-700 hover:bg-light-bg transition duration-300 border-b">Services</a>
            <a href="#benefits" class="block py-3 px-4 text-center text-lg text-gray-700 hover:bg-light-bg transition duration-300 border-b">Benefits</a>
            <a href="#about" class="block py-3 px-4 text-center text-lg text-gray-700 hover:bg-light-bg transition duration-300 border-b">Our Team</a>
            <a href="#contact" class="block py-4 px-4 text-center text-lg bg-secondary text-white hover:bg-opacity-90 transition duration-300">Get Quote</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-light-bg py-16 md:py-24">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold text-primary mb-4 leading-tight">
                Streamline Your Finances. <br class="hidden sm:inline">Invoice Processing, <span class="text-secondary">Perfected.</span>
            </h1>
            <p class="text-xl md:text-2xl text-gray-600 max-w-3xl mx-auto mb-8">
                Your dedicated freelance team for fast, accurate, and secure accounts payable management. Stop worrying about paperwork and start focusing on growth.
            </p>
            <a href="#contact" class="inline-block px-10 py-4 text-lg font-semibold bg-primary text-white rounded-xl shadow-lg hover:bg-opacity-90 transition duration-300 transform hover:scale-105">
                Start Your Free Consultation
            </a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16 md:py-20">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold text-center text-primary mb-10">Our Core Invoice Processing Services</h2>
            <div class="grid md:grid-cols-3 gap-8">

                <!-- Service 1: Data Capture & Entry -->
                <div class="bg-white p-6 rounded-xl shadow-lg hover:shadow-2xl transition duration-500 transform hover:-translate-y-1 border border-gray-100">
                    <div class="text-secondary mb-4">
                        <svg class="w-10 h-10" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 13h6m-3-3v6m5 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path></svg>
                    </div>
                    <h3 class="text-xl font-semibold text-primary mb-3">Automated Data Entry</h3>
                    <p class="text-gray-600">Fast and accurate extraction of key invoice data (vendor, amount, date, line items) using intelligent OCR tools, minimizing manual errors.</p>
                </div>

                <!-- Service 2: Three-Way Matching -->
                <div class="bg-white p-6 rounded-xl shadow-lg hover:shadow-2xl transition duration-500 transform hover:-translate-y-1 border border-gray-100">
                    <div class="text-secondary mb-4">
                        <svg class="w-10 h-10" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.102A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.056L2 6m0 0v14a2 2 0 002 2h16a2 2 0 002-2V6M6 6h12"></path></svg>
                    </div>
                    <h3 class="text-xl font-semibold text-primary mb-3">Reconciliation & Matching</h3>
                    <p class="text-gray-600">Verification of invoices against purchase orders and receiving reports to ensure transaction integrity and prevent fraudulent or erroneous payments.</p>
                </div>

                <!-- Service 3: Audit & Compliance -->
                <div class="bg-white p-6 rounded-xl shadow-lg hover:shadow-2xl transition duration-500 transform hover:-translate-y-1 border border-gray-100">
                    <div class="text-secondary mb-4">
                        <svg class="w-10 h-10" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 21h7a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-5.414-5.414A1 1 0 0012.586 3H7a2 2 0 00-2 2v14a2 2 0 002 2zm1-14v2h4m2 0v2"></path></svg>
                    </div>
                    <h3 class="text-xl font-semibold text-primary mb-3">Reporting & Compliance</h3>
                    <p class="text-gray-600">Generating timely reports for cash flow visibility and ensuring all processes adhere to relevant tax and financial compliance standards.</p>
                </div>

            </div>
        </div>
    </section>

    <!-- Why Choose Us / Benefits Section -->
    <section id="benefits" class="bg-primary text-white py-16 md:py-20">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold text-center mb-10">Why Trust Teja&Ko with Your AP?</h2>
            <div class="grid md:grid-cols-4 gap-8">
                
                <div class="text-center p-4">
                    <div class="text-secondary mb-3">
                        <svg class="w-12 h-12 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                    </div>
                    <p class="text-3xl font-extrabold">99.9%</p>
                    <p class="text-lg opacity-80 mt-1">Accuracy Guarantee</p>
                </div>
                
                <div class="text-center p-4">
                    <div class="text-secondary mb-3">
                        <svg class="w-12 h-12 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                    </div>
                    <p class="text-3xl font-extrabold">24-Hour</p>
                    <p class="text-lg opacity-80 mt-1">Processing Turnaround</p>
                </div>

                <div class="text-center p-4">
                    <div class="text-secondary mb-3">
                        <svg class="w-12 h-12 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v3h8z"></path></svg>
                    </div>
                    <p class="text-3xl font-extrabold">Enterprise</p>
                    <p class="text-lg opacity-80 mt-1">Data Security</p>
                </div>
                
                <div class="text-center p-4">
                    <div class="text-secondary mb-3">
                        <svg class="w-12 h-12 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8a1 1 0 000-2 1 1 0 000 2zM21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                    </div>
                    <p class="text-3xl font-extrabold">30%+</p>
                    <p class="text-lg opacity-80 mt-1">Cost Reduction</p>
                </div>

            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="py-16 md:py-20 bg-light-bg">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:flex lg:items-center lg:space-x-12">
                <div class="lg:w-1/2">
                    <h2 class="text-3xl font-bold text-primary mb-4">Meet Your Dedicated AP Team</h2>
                    <p class="text-gray-600 text-lg mb-6">
                        We are a collective of highly skilled financial and administrative freelancers, specializing exclusively in accounts payable processes. We understand that invoice processing isn't just data entry—it's the backbone of healthy cash flow.
                    </p>
                    <ul class="space-y-3 text-gray-700">
                        <li class="flex items-start">
                            <span class="text-secondary mr-3 mt-1">&#10003;</span>
                            <p><strong>Certified Experts:</strong> Decades of combined experience in various accounting software (QuickBooks, SAP, Oracle).</p>
                        </li>
                        <li class="flex items-start">
                            <span class="text-secondary mr-3 mt-1">&#10003;</span>
                            <p><strong>Flexible Scalability:</strong> Easily adjust our capacity to match your peak invoicing periods without long-term commitment.</p>
                        </li>
                        <li class="flex items-start">
                            <span class="text-secondary mr-3 mt-1">&#10003;</span>
                            <p><strong>Process Optimization:</strong> We don't just process; we identify bottlenecks and suggest improvements to your overall AP workflow.</p>
                        </li>
                    </ul>
                </div>
                <!-- Placeholder Image (Finance Theme) -->
                <div class="lg:w-1/2 mt-10 lg:mt-0">
                    <img src="https://placehold.co/600x400/0D47A1/FFFFFF?text=Teja%26Ko+Management+Team" 
                         alt="Team managing finances" 
                         class="rounded-xl shadow-2xl w-full h-auto object-cover"
                         onerror="this.onerror=null;this.src='https://placehold.co/600x400/0D47A1/FFFFFF?text=Teja%26Ko+Experts';">
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action / Contact Form -->
    <section id="contact" class="py-16 md:py-20">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-secondary p-8 md:p-12 rounded-2xl shadow-xl text-white text-center">
                <h2 class="text-3xl font-bold mb-3">Ready to Reclaim Your Time?</h2>
                <p class="text-xl mb-8 opacity-90">
                    Schedule a quick, no-obligation discussion to see how the Teja&Ko Company fits your needs.
                </p>
                
                <form class="max-w-lg mx-auto space-y-4">
                    <!-- Note: For a live website, you would connect this form's submission to a backend service like Formspree or your host's email service. -->
                    <input type="text" placeholder="Your Name" required class="w-full p-3 rounded-lg text-gray-800 focus:ring-2 focus:ring-primary focus:outline-none">
                    <input type="email" placeholder="Work Email" required class="w-full p-3 rounded-lg text-gray-800 focus:ring-2 focus:ring-primary focus:outline-none">
                    <textarea rows="4" placeholder="Tell us briefly about your current invoicing volume or challenge..." class="w-full p-3 rounded-lg text-gray-800 focus:ring-2 focus:ring-primary focus:outline-none"></textarea>
                    <button type="submit" class="w-full py-3 bg-primary text-white text-lg font-semibold rounded-lg shadow-md hover:bg-opacity-90 transition duration-300 transform hover:scale-[1.01]">
                        Submit for Custom Quote
                    </button>
                    <p class="text-sm opacity-70 pt-2">We respect your privacy. No spam, ever.</p>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8 text-center md:flex md:justify-between md:items-center">
            <p class="mb-4 md:mb-0">&copy; 2025 Teja&Ko Company. All rights reserved.</p>
            <div class="flex justify-center space-x-6">
                <a href="#services" class="text-gray-400 hover:text-white transition duration-300">Services</a>
                <a href="#about" class="text-gray-400 hover:text-white transition duration-300">Team</a>
                <a href="mailto:info@teja-ko.com" class="text-gray-400 hover:text-white transition duration-300">Email Us</a>
            </div>
        </div>
    </footer>

    <!-- JavaScript for Mobile Menu Toggle -->
    <script>
        document.getElementById('menu-button').addEventListener('click', function() {
            const mobileMenu = document.getElementById('mobile-menu');
            mobileMenu.classList.toggle('hidden');
        });

        // Hide mobile menu when a link is clicked
        document.getElementById('mobile-menu').querySelectorAll('a').forEach(link => {
            link.addEventListener('click', function() {
                document.getElementById('mobile-menu').classList.add('hidden');
            });
        });
    </script>

</body>
</html>
