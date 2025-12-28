<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>M&T Clean – Mobile Auto-Innenreinigung</title>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<style>
body { margin:0; font-family:'Roboto',sans-serif; background:#f9f9f9; color:#333; scroll-behavior:smooth; }
header { background:#2E8B57; color:white; padding:25px 0; text-align:center; }
header h1 { margin:0; font-size:2.2em; }
nav { display:flex; justify-content:center; background:#3CB371; padding:10px 0; flex-wrap:wrap; }
nav a { color:white; margin:5px 15px; text-decoration:none; font-weight:700; }
nav a:hover { text-decoration:underline; }
.hero { background:url('https://images.unsplash.com/photo-1581092795361-bb8f8e9eaf3b') no-repeat center center/cover; height:350px; display:flex; justify-content:center; align-items:center; color:white; text-shadow:1px 1px 5px rgba(0,0,0,0.7); animation:fadeIn 2s ease-in; }
.hero h2 { font-size:2em; text-align:center; margin:0 20px; }
.content { max-width:1000px; margin:40px auto; padding:0 20px; }
.services, .testimonials { display:flex; flex-wrap:wrap; gap:20px; justify-content:center; }
.service, .testimonial { background:white; padding:20px; border-radius:8px; box-shadow:0 0 12px rgba(0,0,0,0.1); flex:1 1 280px; transition:transform 0.3s; }
.service:hover, .testimonial:hover { transform:translateY(-5px); }
.contact-form input, .contact-form textarea { width:100%; padding:10px; margin-bottom:10px; border-radius:5px; border:1px solid #ccc; }
.contact-form button { background:#3CB371; color:white; padding:10px 20px; border:none; border-radius:5px; cursor:pointer; }
.contact-form button:hover { background:#2E8B57; }
footer { background:#2E8B57; color:white; text-align:center; padding:20px 0; }
.map-container { width:100%; height:300px; margin:20px 0; border-radius:8px; overflow:hidden; }
.whatsapp-button { position:fixed; bottom:20px; right:20px; background:#25D366; color:white; border-radius:50%; width:60px; height:60px; text-align:center; font-size:30px; line-height:60px; box-shadow:0 4px 6px rgba(0,0,0,0.3); z-index:1000; }
.whatsapp-button:hover { background:#128C7E; }
@keyframes fadeIn { from {opacity:0} to {opacity:1} }
.paypal-button-container { text-align:center; margin-top:20px; }
</style>
</head>
<body>

<header>
<h1>M&T Clean</h1>
<p>Mobile Auto-Innenreinigung – sauber, schnell, flexibel</p>
</header>

<nav>
<a href="#services">Leistungen</a>
<a href="#about">Über uns</a>
<a href="#book">Termin buchen</a>
<a href="#reviews">Kunden</a>
<a href="#contact">Kontakt</a>
<a href="#map">Standort</a>
</nav>

<section class="hero">
<h2>Glänzende Sauberkeit für Ihr Auto – direkt vor Ort</h2>
</section>

<section class="content" id="services">
<h2>Unsere Leistungen</h2>
<div class="services">
<div class="service">
<h3>Komplett Innenreinigung</h3>
<p>Gründliche Reinigung von Sitzen, Teppichen, Armaturen und Fußraum – für ein gepflegtes Fahrzeug.</p>
<p>Preis: 50 €</p>
<div class="paypal-button-container">
<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
<input type="hidden" name="cmd" value="_xclick">
<input type="hidden" name="business" value="deine-email@paypal.de">
<input type="hidden" name="item_name" value="Komplett Innenreinigung">
<input type="hidden" name="amount" value="50.00">
<input type="hidden" name="currency_code" value="EUR">
<button type="submit">Jetzt bezahlen</button>
</form>
</div>
</div>
<div class="service">
<h3>Polster- & Lederpflege</h3>
<p>Sanfte Reinigung und Pflege von Stoff- oder Ledersitzen.</p>
<p>Preis: 30 €</p>
<div class="paypal-button-container">
<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
<input type="hidden" name="cmd" value="_xclick">
<input type="hidden" name="business" value="deine-email@paypal.de">
<input type="hidden" name="item_name" value="Polster- & Lederpflege">
<input type="hidden" name="amount" value="30.00">
<input type="hidden" name="currency_code" value="EUR">
<button type="submit">Jetzt bezahlen</button>
</form>
</div>
</div>
<div class="service">
<h3>Kofferraum & Stauraum</h3>
<p>Reinigung des gesamten Stauraums Ihres Fahrzeugs.</p>
<p>Preis: 20 €</p>
<div class="paypal-button-container">
<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
<input type="hidden" name="cmd" value="_xclick">
<input type="hidden" name="business" value="deine-email@paypal.de">
<input type="hidden" name="item_name" value="Kofferraum & Stauraum">
<input type="hidden" name="amount" value="20.00">
<input type="hidden" name="currency_code" value="EUR">
<button type="submit">Jetzt bezahlen</button>
</form>
</div>
</div>
</div>
</section>

<section class="content" id="about">
<h2>Über M&T Clean</h2>
<p>M&T Clean ist Ihr mobiler Profi für Auto-Innenreinigung. Wir kommen direkt zu Ihnen, bringen alles Equipment mit und sorgen dafür, dass Ihr Auto innen wieder wie neu aussieht. Schnell, gründlich und zuverlässig.</p>
</section>

<section class="content" id="book">
<h2>Termin buchen</h2>
<p>Wählen Sie Ihren Wunschtermin:</p>
<form class="contact-form">
<input type="text" name="name" placeholder="Ihr Name" required>
<input type="email" name="email" placeholder="Ihre E-Mail" required>
<input type="datetime-local" name="termin" required>
<textarea name="message" rows="4" placeholder="Zusätzliche Informationen"></textarea>
<button type="submit">Termin senden</button>
</form>
</section>

<section class="content" id="reviews">
<h2>Kundenbewertungen</h2>
<div class="testimonials">
<div class="testimonial">
<p>"Mein Auto sieht wieder aus wie neu! Super Service und sehr flexibel." – Anna K.</p>
</div>
<div class="testimonial">
<p>"Top Qualität, pünktlich und freundlich. Sehr zu empfehlen!" – Max T.</p>
</div>
<div class="testimonial">
<p>"Nie wieder Stress beim Autoputzen – M&T Clean kommt direkt zu mir." – Lisa M.</p>
</div>
</div>
</section>

<section class="content" id="map">
<h2>Standort</h2>
<p>Hier finden Sie uns:</p>
<div class="map-container">
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2417.123456789012!2d13.404954!3d52.520008!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47a8511234567890%3A0x123456789abcdef!2sM%26T+Clean!5e0!3m2!1sde!2sde!4v1700000000000!5m2!1sde!2sde" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
</div>
</section>

<section class="content" id="contact">
<h2>Kontakt</h2>
<p>Schreiben Sie uns oder rufen Sie direkt an:</p>
<p><strong>Telefon:</strong> +49 170 1234567</p>
<p><strong>Email:</strong> info@mt-clean.de</p>
<form class="contact-form">
<input type="text" name="name" placeholder="Ihr Name" required>
<input type="email" name="email" placeholder="Ihre E-Mail" required>
<textarea name="message" rows="5" placeholder="Ihre Nachricht" required></textarea>
<button type="submit">Nachricht senden</button>
</form>
</section>

<!-- WhatsApp Button -->
<a href="https://wa.me/491701234567" target="_blank" class="whatsapp-button" title="WhatsApp Kontakt">&#x2709;</a>

<footer>
<p>&copy; 2025 M&T Clean – Mobile Auto-Innenreinigung. Alle Rechte vorbehalten.</p>
</footer>

</body>
</html>
