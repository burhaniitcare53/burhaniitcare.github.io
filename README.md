# burhaniitcare.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Burhani IT Care - Laptop Repair in Pune</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Segoe UI', Arial, sans-serif; line-height: 1.6; color: #333; }
        
        header {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://via.placeholder.com/1920x600') center/cover;
            color: white;
            text-align: center;
            padding: 120px 20px 80px;
        }
        header h1 { font-size: 3rem; margin-bottom: 10px; }
        header p { font-size: 1.3rem; }

        .nav {
            background: #0f172a;
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        .nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 30px;
        }
        .nav a { color: white; text-decoration: none; font-weight: 500; }

        .section { padding: 60px 20px; }
        .container { max-width: 1200px; margin: auto; }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            margin-top: 30px;
        }
        .service-card {
            background: white;
            border-radius: 12px;
            padding: 25px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            text-align: center;
            transition: 0.3s;
        }
        .service-card:hover { transform: translateY(-10px); }

        .contact-bar {
            background: #1e40af;
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 1.2rem;
        }
        .btn {
            background: #22c55e;
            color: white;
            padding: 14px 32px;
            border: none;
            border-radius: 50px;
            font-size: 1.1rem;
            cursor: pointer;
            margin-top: 15px;
        }
        footer { background: #0f172a; color: #ccc; text-align: center; padding: 30px; }
    </style>
</head>
<body>

    <!-- Navigation -->
    <nav class="nav">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <header>
        <h1>Burhani IT Care</h1>
        <p>Expert Laptop, Computer & Printer Repair in Pune</p>
        <p style="margin-top:20px; font-size:1.5rem;"><strong>NIBM • Kondhwa • Pune</strong></p>
        <button class="btn" onclick="window.location.href='https://wa.me/917020388752'">📞 Book Now on WhatsApp</button>
    </header>

    <!-- Services -->
    <section class="section" style="background:#f8fafc;">
        <div class="container">
            <h2 style="text-align:center; margin-bottom:40px; font-size:2.2rem;">Our Services</h2>
            <div class="services-grid">
                <div class="service-card">
                    <h3>💻 Laptop Repair</h3>
                    <p>Screen replacement, Keyboard, Battery, Motherboard, Overheating, Water Damage</p>
                </div>
                <div class="service-card">
                    <h3>🖥️ Computer Repair</h3>
                    <p>Desktop, Software Installation, Virus Removal, Windows Installation</p>
                </div>
                <div class="service-card">
                    <h3>🖨️ Printer Repair</h3>
                    <p>All brands - Sales, Service & Toner Refilling</p>
                </div>
                <div class="service-card">
                    <h3>Data Recovery</h3>
                    <p>Hard Drive & SSD Data Recovery</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Bar -->
    <div class="contact-bar">
        📍 Shop No. 9, La Ventana, NIBM Road, Kondhwa, Pune - 411048<br>
        📞 <strong>7020388752</strong> &nbsp;&nbsp; | &nbsp;&nbsp; ⏰ Open 10 AM - 8 PM
        <br><br>
        <button class="btn" style="background:white; color:#1e40af;" onclick="window.location.href='https://wa.me/917020388752'">Chat on WhatsApp Now</button>
    </div>

    <footer>
        <p>&copy; 2026 Burhani IT Care - Laptop Service Pune | All Rights Reserved</p>
    </footer>
</body>
</html>
