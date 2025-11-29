<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Your Café — Home</title>
  <meta name="description" content="A cozy café serving handcrafted coffees and bites." />
  <style>
    /* Minimal, modern responsive styling */
    :root{
      --bg:#fff8f5; --accent:#8b4f2b; --muted:#6b6b6b; --card:#fff;
      --radius:16px;
    }
    *{box-sizing:border-box}
    body{font-family:Inter,system-ui,Segoe UI,Arial; margin:0; background:var(--bg); color:#222; line-height:1.45}
    .container{max-width:1100px;margin:0 auto;padding:24px}
    header{display:flex;align-items:center;justify-content:space-between;padding:12px 0}
    .brand{display:flex;gap:12px;align-items:center}
    .logo{width:56px;height:56px;border-radius:10px;background:linear-gradient(135deg,#fff 0,#f0e6df 100%);display:flex;align-items:center;justify-content:center;font-weight:700;color:var(--accent)}
    nav a{margin-left:18px;text-decoration:none;color:var(--muted);font-weight:600}
    .hero{display:flex;flex-wrap:wrap;gap:20px;align-items:center;padding:28px 0}
    .hero-left{flex:1;min-width:280px}
    .hero h1{font-size:2.2rem;margin:0 0 10px;color:var(--accent)}
    .hero p{margin:0 0 18px;color:var(--muted)}
    .btn{display:inline-block;padding:10px 18px;background:var(--accent);color:#fff;border-radius:10px;text-decoration:none;font-weight:700}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:18px;margin-top:18px}
    .card{background:var(--card);border-radius:12px;padding:14px;box-shadow:0 6px 20px rgba(0,0,0,0.06)}
    .menu-item{display:flex;gap:12px;align-items:center}
    .menu-item img{width:80px;height:60px;object-fit:cover;border-radius:8px}
    .locations .loc{display:flex;justify-content:space-between;align-items:center;padding:12px 0;border-bottom:1px dashed #eee}
    .gallery{display:grid;grid-template-columns:repeat(3,1fr);gap:8px}
    .gallery img{width:100%;height:160px;object-fit:cover;border-radius:8px}
    footer{padding:24px 0;color:var(--muted);font-size:0.95rem;border-top:1px solid #eee;margin-top:28px}
    @media(max-width:700px){ .hero{flex-direction:column} .gallery{grid-template-columns:repeat(2,1fr)} }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">CF</div>
        <div>
          <div style="font-weight:800;font-size:1.05rem">Your Café Name</div>
          <div style="font-size:0.86rem;color:var(--muted)">A Lot Can Happen Over Coffee</div>
        </div>
      </div>
      <nav>
        <a href="#menu">Menu</a><a href="#locations">Locations</a><a href="#gallery">Gallery</a><a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="hero">
      <div class="hero-left">
        <h1>Handcrafted coffees & cozy vibes</h1>
        <p>We serve freshly brewed single-origin coffees, signature drinks & light bites. Come for work, stay for conversations.</p>
        <a class="btn" href="#menu">View Menu</a>
        <a class="btn" style="background:#fff;color:var(--accent);border:1px solid #f0e0d6;margin-left:10px" href="#locations">Find a Café</a>
      </div>
      <div style="flex:1;min-width:260px">
        <div class="card">
          <h3 style="margin:0 0 8px">Today's Specials</h3>
          <div class="grid">
            <div class="card">
              <strong>Honey Latte</strong><div style="color:var(--muted);font-size:0.9rem">Espresso, honey & steamed milk</div>
            </div>
            <div class="card">
              <strong>Veg Platter</strong><div style="color:var(--muted);font-size:0.9rem">Assorted snacks to share</div>
            </div>
            <div class="card">
              <strong>Cold Brew</strong><div style="color:var(--muted);font-size:0.9rem">Slow-brewed, smooth & chilled</div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="menu">
      <h2 style="color:var(--accent)">Menu</h2>
      <div class="grid">
        <!-- sample menu card -->
        <div class="card">
          <h4 style="margin:0 0 8px">Hot Beverages</h4>
          <div class="menu-item">
            <img src="images/coffee-1.jpg" alt="Coffee">
            <div>
              <strong>Classic Cappuccino</strong><div style="color:var(--muted);font-size:0.95rem">₹120 — Espresso with milk foam</div>
            </div>
          </div>
          <div style="height:8px"></div>
          <div class="menu-item">
            <img src="images/coffee-2.jpg" alt="Coffee">
            <div>
              <strong>Espresso</strong><div style="color:var(--muted);font-size:0.95rem">₹90 — Single shot</div>
            </div>
          </div>
        </div>

        <div class="card">
          <h4 style="margin:0 0 8px">Cold Beverages</h4>
          <div class="menu-item">
            <img src="images/ice-latte.jpg" alt="Iced">
            <div>
              <strong>Iced Latte</strong><div style="color:var(--muted);font-size:0.95rem">₹140 — Espresso & chilled milk</div>
            </div>
          </div>
        </div>

        <div class="card">
          <h4 style="margin:0 0 8px">Snacks</h4>
          <div class="menu-item">
            <img src="images/sandwich.jpg" alt="Snack">
            <div>
              <strong>Veg Sandwich</strong><div style="color:var(--muted);font-size:0.95rem">₹150 — Grilled with fresh veggies</div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="locations" style="margin-top:28px">
      <h2 style="color:var(--accent)">Locations</h2>
      <div class="card locations">
        <div class="loc">
          <div>
            <strong>Downtown Outlet</strong><div style="color:var(--muted)">123 Main St, Your City — 8:00 AM - 10:00 PM</div>
          </div>
          <div><a href="#" class="btn">Get Directions</a></div>
        </div>
        <div class="loc">
          <div>
            <strong>Mall Outlet</strong><div style="color:var(--muted)">Shop 22, City Mall — 10:00 AM - 11:00 PM</div>
          </div>
          <div><a href="#" class="btn">Get Directions</a></div>
        </div>
      </div>
      <!-- Example Map iframe (replace with real embed and API key if needed) -->
      <div style="margin-top:12px" class="card">
        <h4 style="margin-top:0">Map</h4>
        <iframe width="100%" height="300" src="https://www.google.com/maps/embed?pb=" style="border:0;border-radius:10px"></iframe>
      </div>
    </section>

    <section id="gallery" style="margin-top:28px">
      <h2 style="color:var(--accent)">Gallery</h2>
      <div class="gallery card" style="padding:12px">
        <img src="images/gallery-1.jpg" alt="">
        <img src="images/gallery-2.jpg" alt="">
        <img src="images/gallery-3.jpg" alt="">
        <img src="images/gallery-4.jpg" alt="">
        <img src="images/gallery-5.jpg" alt="">
        <img src="images/gallery-6.jpg" alt="">
      </div>
    </section>

    <section id="contact" style="margin-top:28px">
      <h2 style="color:var(--accent)">Contact & Bookings</h2>
      <div class="grid">
        <div class="card">
          <strong>Email</strong>
          <div style="color:var(--muted)">hello@yourcafe.com</div>
          <div style="height:8px"></div>
          <strong>Phone</strong>
          <div style="color:var(--muted)">+91-XXXXXXXXXX</div>
        </div>
        <div class="card">
          <form id="contactForm" onsubmit="return submitForm(event)">
            <label for="name">Name</label><br>
            <input id="name" name="name" required style="width:100%;padding:8px;margin:6px 0;border-radius:6px;border:1px solid #eee"><br>
            <label for="email">Email</label><br>
            <input id="email" name="email" type="email" required style="width:100%;padding:8px;margin:6px 0;border-radius:6px;border:1px solid #eee"><br>
            <label for="msg">Message</label><br>
            <textarea id="msg" name="msg" rows="4" style="width:100%;padding:8px;margin:6px 0;border-radius:6px;border:1px solid #eee"></textarea><br>
            <button class="btn" type="submit">Send Message</button>
          </form>
        </div>
      </div>
    </section>

    <footer>
      <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
        <div>© <strong>Your Café</strong> • Crafted with care</div>
        <div style="color:var(--muted)">Follow us on <a href="#" style="color:var(--accent)">Instagram</a></div>
      </div>
    </footer>
  </div>

  <script>
    // Example: replace content from JSON (you would fetch a real JSON or embed it)
    // Basic contact form handler (client-side only)
    function submitForm(e){
      e.preventDefault();
      alert('Thanks! Your message has been received. Replace this with AJAX to your backend.');
      document.getElementById('contactForm').reset();
      return false;
    }
  </script>
</body>
</html>
