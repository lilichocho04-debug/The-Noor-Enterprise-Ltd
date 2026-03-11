<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Noor Enterprise Ltd. | Sell, Buy & Maintenance</title>
    
    <!-- Libraries for "Big & Modern" feel -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

    <style>
        :root {
            --primary: #2ECC71;
            --secondary: #27AE60;
            --dark: #0a0b0c;
            --card-bg: rgba(255, 255, 255, 0.03);
            --border: rgba(255, 255, 255, 0.08);
            --text: #f8f9fa;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Plus Jakarta Sans', sans-serif; }
        body { background: var(--dark); color: var(--text); overflow-x: hidden; }
        
        /* Smooth Scroll */
        html { scroll-behavior: smooth; }

        /* Modern Navigation */
        nav {
            position: fixed; top: 0; width: 100%; z-index: 2000;
            padding: 20px 8%; background: rgba(10, 11, 12, 0.8);
            backdrop-filter: blur(15px); border-bottom: 1px solid var(--border);
            display: flex; justify-content: space-between; align-items: center;
        }
        .logo { font-size: 1.5rem; font-weight: 800; color: var(--primary); letter-spacing: -1px; }
        .logo span { color: white; font-weight: 300; }

        /* Hero Section */
        .hero {
            height: 100vh; display: flex; align-items: center; justify-content: center;
            text-align: center; background: linear-gradient(to bottom, rgba(10,11,12,0.6), var(--dark)),
            url('https://images.unsplash.com/photo-1558981285-6f0c94958bb6?q=80&w=2000&auto=format&fit=crop');
            background-size: cover; background-position: center; padding: 0 5%;
        }
        .hero-content h1 { font-size: clamp(2.5rem, 8vw, 5rem); line-height: 1; margin-bottom: 20px; }
        .hero-content p { font-size: 1.2rem; color: #ccc; max-width: 800px; margin: auto; margin-bottom: 40px; }

        /* Service Cards (Sell, Buy, Maintain) */
        .service-grid {
            display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px; margin-top: -100px; position: relative; z-index: 10;
        }
        .service-card {
            background: rgba(20, 22, 24, 0.95); padding: 50px 30px; border-radius: 30px;
            border: 1px solid var(--border); text-align: center; transition: 0.4s;
            backdrop-filter: blur(10px);
        }
        .service-card:hover { transform: translateY(-10px); border-color: var(--primary); }
        .service-card i { font-size: 3rem; color: var(--primary); margin-bottom: 20px; }
        .service-card h3 { font-size: 1.5rem; margin-bottom: 15px; }

        /* Inventory & Modern Features */
        .section { padding: 100px 8%; }
        .badge { background: var(--primary); color: black; padding: 5px 12px; border-radius: 50px; font-size: 0.7rem; font-weight: 800; position: absolute; top: 20px; right: 20px; }
        
        .product-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 30px; }
        .product-card { background: var(--card-bg); border-radius: 25px; padding: 20px; border: 1px solid var(--border); position: relative; }
        .product-card img { width: 100%; border-radius: 15px; margin-bottom: 20px; }

        /* Maintenance Booking */
        .booking-container {
            background: linear-gradient(135deg, #1a1c1e 0%, #0a0b0c 100%);
            padding: 60px; border-radius: 40px; border: 1px solid var(--border);
            display: flex; flex-wrap: wrap; gap: 40px; align-items: center;
        }
        .booking-form { flex: 1; min-width: 300px; }
        input, select, textarea { 
            width: 100%; padding: 15px; margin-bottom: 15px; background: rgba(255,255,255,0.05); 
            border: 1px solid var(--border); color: white; border-radius: 12px;
        }

        /* Leadership Section (Staff) */
        .management { background: #050505; padding: 100px 8%; text-align: center; }
        .staff-flex { display: flex; justify-content: center; flex-wrap: wrap; gap: 40px; margin-top: 50px; }
        .staff-item { max-width: 350px; background: var(--card-bg); padding: 40px; border-radius: 30px; border: 1px solid var(--border); }
        .staff-img { width: 100px; height: 100px; background: var(--primary); border-radius: 50%; margin: 0 auto 20px; display: flex; align-items: center; justify-content: center; font-size: 2.5rem; }

        /* Buttons */
        .btn { padding: 16px 35px; border-radius: 50px; font-weight: 700; text-decoration: none; display: inline-block; transition: 0.3s; border: none; cursor: pointer; }
        .btn-primary { background: var(--primary); color: #000; }
        .btn-primary:hover { box-shadow: 0 0 30px rgba(46, 204, 113, 0.4); transform: scale(1.05); }

        /* Footer */
        footer { padding: 80px 8%; background: #000; border-top: 1px solid var(--border); }

        @media (max-width: 768px) {
            .hero-content h1 { font-size: 3rem; }
            .section { padding: 60px 5%; }
        }
    </style>
</head>
<body>

<nav>
    <div class="logo">THE NOOR <span>ENTERPRISE LTD.</span></div>
    <div class="nav-links">
        <a href="#services" style="color:white; text-decoration:none; margin-left:20px; font-size:0.9rem;">Services</a>
        <a href="#inventory" style="color:white; text-decoration:none; margin-left:20px; font-size:0.9rem;">Inventory</a>
    </div>
</nav>

<!-- Hero -->
<section class="hero">
    <div class="hero-content" data-aos="zoom-in">
        <h1 class="logo">THE NOOR <span>ENTERPRISE LTD.</span></h1>
        <p>Sylhet's Premier Hub for Electric Mobility. We specialize in selling high-performance Tom Toms, buying used vehicles, and providing world-class maintenance.</p>
        <div style="display: flex; gap: 20px; justify-content: center;">
            <a href="#inventory" class="btn btn-primary">Browse Stock</a>
            <a href="#maintenance" class="btn" style="border: 1px solid white; color: white;">Book Service</a>
        </div>
    </div>
</section>

<!-- Service Hub -->
<section class="section" id="services">
    <div class="service-grid">
        <div class="service-card" data-aos="fade-up" data-aos-delay="100">
            <i class="fas fa-shopping-cart"></i>
            <h3>Sell</h3>
            <p>Direct authorized dealer of the latest 48V & 60V E-Rickshaws with official warranty.</p>
        </div>
        <div class="service-card" data-aos="fade-up" data-aos-delay="200">
            <i class="fas fa-hand-holding-dollar"></i>
            <h3>Buy & Trade-In</h3>
            <p>Sell us your old Tom Tom or trade it in for a brand new model at the best market price.</p>
        </div>
        <div class="service-card" data-aos="fade-up" data-aos-delay="300">
            <i class="fas fa-tools"></i>
            <h3>Maintenance</h3>
            <p>Professional battery diagnostics, motor tuning, and genuine spare parts replacement.</p>
        </div>
    </div>
</section>

<!-- Inventory -->
<section class="section" id="inventory">
    <div style="margin-bottom: 50px;">
        <h2 style="font-size: 2.5rem;">New Arrivals</h2>
        <p style="color: var(--primary);">Fresh stock just arrived from factory</p>
    </div>
    
    <div class="product-grid">
        <!-- Model 1 -->
        <div class="product-card" data-aos="fade-up">
            <span class="badge">IN STOCK</span>
            <img src="https://images.unsplash.com/photo-1594145070243-71822c15975e?q=80&w=800&auto=format&fit=crop" alt="Elite">
            <h3>Noor Elite 60V</h3>
            <p style="color:#888; margin: 10px 0;">Heavy duty motor, 6-passenger luxury seating.</p>
            <h2 style="color: var(--primary); margin-bottom: 20px;">৳ 1,75,000</h2>
            <a href="https://wa.me/8801774943024" class="btn btn-primary" style="width: 100%; text-align: center;">Order on WhatsApp</a>
        </div>

        <!-- Model 2 -->
        <div class="product-card" data-aos="fade-up" data-aos-delay="100">
            <span class="badge" style="background: #e74c3c; color: white;">ONLY 2 LEFT</span>
            <img src="https://images.unsplash.com/photo-1619451422367-e7a5a9d601c3?q=80&w=800&auto=format&fit=crop" alt="Cargo">
            <h3>Noor Heavy Cargo</h3>
            <p style="color:#888; margin: 10px 0;">Industrial grade chassis with 800KG payload.</p>
            <h2 style="color: var(--primary); margin-bottom: 20px;">৳ 1,45,000</h2>
            <a href="https://wa.me/8801774943024" class="btn btn-primary" style="width: 100%; text-align: center;">Order on WhatsApp</a>
        </div>

        <!-- Model 3 (Buy/Exchange Feature) -->
        <div class="product-card" style="border: 2px dashed var(--primary);" data-aos="fade-up" data-aos-delay="200">
            <div style="padding: 20px; text-align: center;">
                <i class="fas fa-sync" style="font-size: 3rem; color: var(--primary); margin-bottom: 20px;"></i>
                <h3>Exchange Program</h3>
                <p style="color:#888; margin-bottom: 20px;">Bring your old vehicle to our Fenchuganj branch for an instant valuation.</p>
                <a href="mailto:marufahmed.bd@yahoo.com?subject=Exchange Inquiry" class="btn" style="border: 1px solid var(--primary); color: var(--primary);">Get Valuation</a>
            </div>
        </div>
    </div>
</section>

<!-- Maintenance Section -->
<section class="section" id="maintenance">
    <div class="booking-container" data-aos="zoom-in-up">
        <div style="flex: 1;">
            <h2 style="font-size: 3rem; margin-bottom: 20px;">Professional <br><span style="color: var(--primary);">Maintenance</span></h2>
            <ul style="list-style: none; color: #aaa;">
                <li style="margin-bottom: 10px;"><i class="fas fa-check-circle color: var(--primary)"></i> Computerized Battery Testing</li>
                <li style="margin-bottom: 10px;"><i class="fas fa-check-circle"></i> Original Motor Coil Rewinding</li>
                <li style="margin-bottom: 10px;"><i class="fas fa-check-circle"></i> Brake & Suspension Safety Check</li>
            </ul>
        </div>
        <div class="booking-form">
            <form action="mailto:marufahmed.bd@yahoo.com" method="GET">
                <input type="text" placeholder="Your Name" required>
                <input type="text" placeholder="Phone Number" required>
                <select>
                    <option>Battery Service</option>
                    <option>Motor Repair</option>
                    <option>Full Maintenance</option>
                </select>
                <textarea placeholder="Describe the issue..."></textarea>
                <button type="submit" class="btn btn-primary" style="width: 100%;">Schedule Repair</button>
            </form>
        </div>
    </div>
</section>

<!-- Leadership (Staff) -->
<section class="management" id="staff">
    <h2 style="font-size: 2.5rem;">The Management Team</h2>
    <p style="color: #666;">Driving excellence in every transaction.</p>
    
    <div class="staff-flex">
        <div class="staff-item" data-aos="fade-right">
            <div class="staff-img"><i class="fas fa-user-tie"></i></div>
            <h3>Abdul Noor</h3>
            <p>General Manager</p>
            <p style="color: #888; font-size: 0.9rem; margin-top: 15px;">Lead visionary managing enterprise operations and divisional growth.</p>
        </div>
        <div class="staff-item" data-aos="fade-left">
            <div class="staff-img"><i class="fas fa-user-gear"></i></div>
            <h3>Mamun Ahmed</h3>
            <p>Assistant Manager</p>
            <p style="color: #888; font-size: 0.9rem; margin-top: 15px;">Technical expert overseeing customer support and maintenance logistics.</p>
        </div>
    </div>
</section>

<!-- Footer -->
<footer>
    <div style="display: flex; flex-wrap: wrap; justify-content: space-between; gap: 40px;">
        <div style="max-width: 400px;">
            <div class="logo" style="margin-bottom: 20px;">THE NOOR <span>ENTERPRISE LTD.</span></div>
            <p style="color: #666;">North Fenchuganj, Maijgao Bazaar, Fenchuganj, Sylhet. Bangladesh's most trusted name in E-Mobility.</p>
        </div>
        <div>
            <h4 style="margin-bottom: 20px;">Contact Us</h4>
            <p style="color: #aaa; margin-bottom: 10px;"><i class="fas fa-phone"></i> +8801774943024</p>
            <p style="color: #aaa;"><i class="fas fa-envelope"></i> marufahmed.bd@yahoo.com</p>
        </div>
    </div>
    <div style="text-align: center; margin-top: 80px; padding-top: 30px; border-top: 1px solid var(--border); color: #444; font-size: 0.8rem;">
        &copy; 2024 The Noor Enterprise Ltd. | Designed for Excellence.
    </div>
</footer>

<!-- Floating Action Buttons -->
<div style="position: fixed; bottom: 30px; right: 30px; display: flex; flex-direction: column; gap: 15px; z-index: 1000;">
    <a href="https://wa.me/8801774943024" style="background:#25D366; width:60px; height:60px; border-radius:50%; display:flex; align-items:center; justify-content:center; color:white; font-size:1.5rem; box-shadow:0 10px 20px rgba(0,0,0,0.3);"><i class="fab fa-whatsapp"></i></a>
</div>

<!-- Scripts -->
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>
    AOS.init({ duration: 1000, once: true });
</script>

</body>
</html>
