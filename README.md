<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Makadamia Desa Buntu</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Makadamia Desa Buntu</h1>
    <p>Kacang Premium dari Lereng Sindoro – Wonosobo</p>
  </header>

  <section class="hero">
    <img src="makadamia.jpg" alt="Kacang Makadamia Desa Buntu" />
  </section>

  <section class="description">
    <h2>Tentang Produk</h2>
    <p>
      Ditanam secara alami di Desa Buntu, Kejajar – Wonosobo, kacang makadamia ini kaya lemak sehat,
      bebas kolesterol, dan sangat cocok sebagai camilan sehat maupun bahan masakan premium.
    </p>
  </section>

  <section class="pricing">
    <h2>Varian & Harga</h2>
    <table>
      <tr><th>Varian</th><th>Isi</th><th>Harga</th></tr>
      <tr><td>Makadamia Whole (Utuh)</td><td>100g</td><td>Rp 65.000</td></tr>
      <tr><td>Makadamia Roasted</td><td>250g</td><td>Rp 150.000</td></tr>
      <tr><td>Makadamia Unsalted</td><td>500g</td><td>Rp 280.000</td></tr>
      <tr><td>Minyak Makadamia</td><td>100ml</td><td>Rp 95.000</td></tr>
    </table>
  </section>

  <section class="order">
    <h2>Pesan Sekarang</h2>
    <a href="https://wa.me/6281234567890?text=Halo%20saya%20ingin%20pesan%20Makadamia" target="_blank" class="btn">Chat via WhatsApp</a>
    <p>📦 Pengiriman dari Wonosobo • Estimasi 1–3 hari kerja</p>
  </section>

  <footer>
    <p>&copy; 2025 Makadamia Desa Buntu • Website by UMKM Digital Wonosobo</p>
  </footer>
</body>
</html>

body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #f7f7f7;
  color: #333;
}

header {
  background: #7B3F00;
  color: white;
  padding: 2rem;
  text-align: center;
}

.hero img {
  width: 100%;
  max-height: 400px;
  object-fit: cover;
}

section {
  padding: 2rem;
  max-width: 900px;
  margin: auto;
}

.description p {
  font-size: 1.1rem;
  line-height: 1.6;
}

.pricing table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 1rem;
}

.pricing th,
.pricing td {
  border: 1px solid #ccc;
  padding: 0.75rem;
  text-align: left;
}

.pricing th {
  background-color: #ddd;
}

.order {
  text-align: center;
}

.btn {
  display: inline-block;
  padding: 1rem 2rem;
  background-color: #27ae60;
  color: white;
  font-weight: bold;
  text-decoration: none;
  border-radius: 6px;
  margin-top: 1rem;
}

footer {
  background: #333;
  color: white;
  padding: 1rem;
  text-align: center;
  font-size: 0.9rem;
}
