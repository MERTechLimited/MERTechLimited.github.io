<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MERTech Limited | Dive Tech & ROV Services</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        :root {
            --marine-dark: #001f3f;
            --marine-blue: #0074D9;
            --safety-orange: #FF851B;
        }
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: #333; }
        .hero {
            background: linear-gradient(rgba(0,31,63,0.8), rgba(0,31,63,0.8)), url('https://images.unsplash.com/photo-1582967788606-a171c1080cb0?auto=format&fit=crop&q=80&w=1600');
            background-size: cover; background-position: center;
            color: white; padding: 100px 0; text-align: center;
        }
        .section-title { border-bottom: 3px solid var(--safety-orange); display: inline-block; margin-bottom: 30px; }
        .card { border: none; transition: 0.3s; box-shadow: 0 4px 15px rgba(0,0,0,0.1); }
        .card:hover { transform: translateY(-5px); }
        .btn-orange { background-color: var(--safety-orange); color: white; font-weight: bold; }
        .btn-orange:hover { background-color: #e67616; color: white; }
        footer { background: var(--marine-dark); color: white; padding: 40px 0; }
    </style>
</head>
<body>

    <nav class="navbar navbar-dark bg-dark sticky-top">
        <div class="container">
            <span class="navbar-brand mb-0 h1">MERTech Limited</span>
            <span class="text-light d-none d-md-block">Subsea Technical Solutions</span>
        </div>
    </nav>

    <header class="hero">
        <div class="container">
            <h1 class="display-3 fw-bold">MERTech Limited</h1>
            <p class="lead mb-4">Professional Dive Technician & ROV Piloting Services</p>
            <a href="#contact" class="btn btn-orange btn-lg">Available for Deployment</a>
        </div>
    </header>

    <section class="container my-5 py-5" id="services">
        <div class="text-center">
            <h2 class="section-title">Core Competencies</h2>
        </div>
        <div class="row g-4 mt-2">
            <div class="col-md-6">
                <div class="card h-100 p-4">
                    <h3>Dive Technician</h3>
                    <p>Expert maintenance and repair of offshore dive systems to IMCA standards.</p>
                    <ul>
                        <li>Saturation & Surface Supplied Systems</li>
                        <li>Hydraulic & Pneumatic Troubleshooting</li>
                        <li>LARS & Winch Maintenance</li>
                        <li>Gas Reclamation Systems</li>
                    </ul>
                </div>
            </div>
            <div class="col-md-6">
                <div class="card h-100 p-4">
                    <h3>ROV Piloting & Tech</h3>
                    <p>High-precision piloting and technical support for subsea robotic systems.</p>
                    <ul>
                        <li>Work Class & Observation Class Operations</li>
                        <li>Fiber Optic & Electrical Diagnostics</li>
                        <li>Subsea Tooling Integration</li>
                        <li>IRM (Inspection, Repair & Maintenance)</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <section class="bg-light py-5">
        <div class="container text-center">
            <h4 class="text-muted mb-4">Certified & Compliant</h4>
            <p class="mb-0"><strong>IMCA</strong> Logged | <strong>OPITO</strong> BOSIET / FOET | <strong>ENG1</strong> Medical</p>
        </div>
    </section>

    <section class="container my-5 py-5" id="contact">
        <div class="row justify-content-center">
            <div class="col-md-6 text-center">
                <h2 class="section-title">Contact MERTech</h2>
                <p>Inquire about availability for upcoming projects or global offshore mobilizations.</p>
                <div class="mt-4">
                    <p class="fs-4">📧 <a href="mailto:info@mertechlimited.com" class="text-decoration-none text-dark">info@mertechlimited.com</a></p>
                    <p class="fs-5 text-muted">Based in the UK | Global Deployment</p>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container text-center">
            <p>&copy; 2026 MERTech Limited. All rights reserved.</p>
            <small class="text-muted">Specialist Subsea Engineering & Support</small>
        </div>
    </footer>

</body>
</html>
