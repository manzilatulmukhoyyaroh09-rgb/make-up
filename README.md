<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elysia - Kosmetik Lokal</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #fff; color: #333; }
        header { background-color: #fff; padding: 20px 50px; border-bottom: 1px solid #eee; display: flex; justify-content: space-between; align-items: center; }
        .logo { font-size: 32px; font-weight: bold; color: #ff69b4; }
        .menu { list-style: none; display: flex; gap: 25px; margin: 0; }
        .menu a { text-decoration: none; color: #333; font-size: 15px; }
        .hero { padding: 60px 50px; display: flex; align-items: center; justify-content: space-between; background-color: #fff0f5; }
        .hero img { max-width: 500px; border-radius: 10px; }
        .hero-text h1 { color: #ff1493; font-size: 36px; margin-bottom: 20px; }
        .hero-text p { font-size: 16px; line-height: 1.6; }
        .products { padding: 60px 50px; text-align: center; background-color: #fff; }
        .products h2 { color: #ff69b4; }
        .product-grid { display: grid; grid-template-columns: repeat(4, 1fr); gap: 40px; margin-top: 40px; }
        .product { text-align: center; background: #fff; padding: 20px; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); }
        .product img { width: 180px; height: 240px; object-fit: cover; border-radius: 10px; }
        .price { color: #ff1493; font-weight: bold; font-size: 18px; margin: 10px 0; }
        button { background-color: #ff69b4; color: white; border: none; padding: 12px 24px; border-radius: 30px; cursor: pointer; font-size: 14px; }
        button:hover { background-color: #ff1493; }
        .auth-section { display: flex; height: 600px; }
        .register { background-color: #ffc0cb; padding: 50px; width: 50%; }
        .login { background-color: #fdfd96; padding: 50px; width: 50%; display: flex; flex-direction: column; justify-content: center; align-items: center; }
        .register h2, .login h2 { color: #ff1493; text-align: center; }
        input { width: 100%; padding: 12px; margin: 10px 0; border: none; border-radius: 5px; }
        .cart-section { background-color: #ff69b4; color: white; padding: 60px; text-align: center; }
        .cart-section img { width: 150px; margin: 20px 0; }
        .skin-analyzer { background-color: #fdfd96; padding: 80px; text-align: center; }
        .skin-analyzer h1 { color: #ff69b4; font-size: 40px; }
        .skin-analyzer img { width: 250px; margin: 30px 0; }
        .ig-gallery { display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin: 40px 0; }
        .ig-gallery img { width: 200px; height: 200px; object-fit: cover; border-radius: 10px; }
        footer { background-color: #fff0f5; padding: 50px; text-align: center; }
        footer input { padding: 12px; width: 300px; border: 1px solid #ff69b4; border-radius: 30px 0 0 30px; }
        footer button { border-radius: 0 30px 30px 0; margin-left: -5px; }
    </style>
</head>
<body>

    <header>
        <div class="logo">Elysia</div>
        <ul class="menu">
            <li><a href="#">Make Up</a></li>
            <li><a href="#">Skin Care</a></li>
            <li><a href="#">Beauty 101</a></li>
            <li><a href="#">Promo</a></li>
            <li><a href="#">Skin Analyzer</a></li>
            <li><a href="#">Market</a></li>
            <li><a href="#">Login</a></li>
            <li><a href="#">Keranjang (0)</a></li>
        </ul>
    </header>

    <section class="hero">
        <img src="https://thumbs.dreamstime.com/b/flat-lay-image-pink-beauty-skincare-cosmetics-arranged-aesthetically-light-pastel-blue-background-composition-393845149.jpg" alt="Produk Kosmetik Pink Aesthetic">
        <div class="hero-text">
            <h1>Tampil Lebih Percaya Diri Setiap Hari</h1>
            <p>Temukan produk-produk berkualitas yang dirancang untuk menyempurnakan kecantikan alami kamu.</p>
            <p><strong>Tentang Kami</strong><br>
            Elysia adalah brand kosmetik lokal Indonesia yang menyediakan berbagai macam produk make up dan skin care berkualitas tinggi, aman untuk kulit, dan cocok untuk berbagai jenis kulit. Kami fokus pada bahan alami dan trend terkini.</p>
            <a href="#" style="color: #ff1493; font-weight: bold;">Baca Selengkapnya →</a>
        </div>
    </section>

    <section class="auth-section">
        <div class="register">
            <h2>REGISTER</h2>
            <form>
                <input type="text" placeholder="FULLNAME"><br>
                <input type="text" placeholder="AGE"><br>
                <input type="text" placeholder="GENDER"><br>
                <input type="text" placeholder="PHONE"><br>
                <input type="text" placeholder="ADDRESS"><br>
                <input type="text" placeholder="USERNAME"><br>
                <input type="password" placeholder="PASSWORD"><br>
                <button type="submit">SUBMIT</button>
            </form>
        </div>
        <div class="login">
            <h2>LOG IN</h2>
            <form>
                <input type="text" placeholder="Username" style="width:60%;"><br>
                <input type="password" placeholder="Password" style="width:60%;"><br>
                <button type="button">Register</button>
            </form>
        </div>
    </section>

    <section class="products">
        <h2>Pilihan Terbaik</h2>
        <button>SEMUA PRODUK</button>
        <div class="product-grid">
            <div class="product">
                <img src="https://lippielust.com/wp-content/uploads/2016/11/IMG_9626.jpg" alt="Creamatte Liquid Lipstick">
                <p>Creamatte Liquid Lipstick</p>
                <p class="price">Rp 52.000</p>
                <button>Tambah ke Keranjang</button>
            </div>
            <div class="product">
                <img src="https://images.stockcake.com/public/c/7/b/c7b634c9-06c2-408d-8771-3032c0ace886_large/elegant-makeup-display-stockcake.jpg" alt="Water Bright Glow">
                <p>Water Bright Glow Toner</p>
                <p class="price">Rp 42.000</p>
                <button>Tambah ke Keranjang</button>
            </div>
            <div class="product">
                <img src="https://media.istockphoto.com/id/2249256695/photo/pink-tools-and-accessories-for-womens-makeup.jpg?s=612x612&w=is&k=20&c=Y422weurCyPfna0SpZKfs4T7VI8-1aQWYSWPSdych-k=" alt="Glossy Cheek Oil">
                <p>Glossy Cheek Oil Autumn Blush</p>
                <p class="price">Rp 48.000</p>
                <button>Tambah ke Keranjang</button>
            </div>
            <div class="product">
                <img src="https://thumbs.dreamstime.com/b/elegant-display-various-cosmetics-arranged-soft-pink-background-daylight-array-featuring-lipsticks-blushes-341537727.jpg" alt="Airy Surprise Tint">
                <p>Airy Surprise Tint</p>
                <p class="price">Rp 45.000</p>
                <button>Tambah ke Keranjang</button>
            </div>
        </div>
    </section>

    <section class="cart-section">
        <h2>keranjang belanja</h2>
        <img src="https://lippielust.com/wp-content/uploads/2016/11/IMG_9626.jpg" alt="Creamatte">
        <p>creamatte liquid lipstick</p>
        <p>Rp. 52.000</p>
        <p>Voucher subtotal ongkir Gratis</p>
        <p>Total Rp. 52.000</p>
        <button>Beli Sekarang</button>
    </section>

    <section class="hero" style="background-color:#fff;">
        <img src="https://thumbs.dreamstime.com/b/flat-lay-various-pink-makeup-products-brushes-background-showcasing-cosmetics-like-lipstick-eyeshadow-palette-blush-394345040.jpg" alt="Upgrade Koleksi Make Up">
        <div class="hero-text">
            <p>Saatnya upgrade koleksi make up kamu !+<br>
            Dapatkan promo menarik dan rekomendasi produk sesuai kebutuhan kulitmu.</p>
        </div>
    </section>

    <section class="skin-analyzer">
        <h2>check your skin</h2>
        <h1>SKIN ANALYZER</h1>
        <p>Kenali kulitmu dalam 1 menit</p>
        <img src="https://is1-ssl.mzstatic.com/image/thumb/Purple211/v4/b7/75/a4/b775a433-59ea-7cd3-fefd-870f3e4cb405/AppIcon-0-0-1x_U007emarketing-0-11-0-85-220.png/1200x630wa.png" alt="Camera Icon Skin Analyzer">
        <p>Tipe Kulit: Kering • Berminyak • Kombinasi • Sensitif</p>
        <p>Concern Utama: Kusam • Jerawat • Pori-pori • Noda hitam • Kerutan • Kulit kendur</p>
    </section>

    <section class="cart-section">
        <h2>pesanan saya</h2>
        <img src="https://lippielust.com/wp-content/uploads/2016/11/IMG_9626.jpg" alt="Creamatte">
        <p>creamatte liquid lipstick pesanan di antar</p>
        <p>Total 1 produk : Rp. 52.000</p>
        <h2>TERIMA KASIH SUDAH BERBELANJA</h2>
    </section>

    <footer>
        <p>IKUTI INSTAGRAM KAMI</p>
        <div class="ig-gallery">
            <img src="https://thrivecausemetics.com/cdn/shop/articles/Holiday-2025_Chi_Editorial_Promise_1277-7997x5334-b19ac8b_1372b585-8b13-4baf-a40c-b705f7ecf04b.jpg?v=1763757315&width=2048" alt="IG1">
            <img src="https://lookaside.instagram.com/seo/google_widget/crawler/?media_id=2900315567002685255" alt="IG2">
            <img src="https://www.women.com/img/gallery/the-drastic-way-makeup-trends-have-changed-from-2015-to-2025/intro-1736909622.jpg" alt="IG3">
            <img src="https://lookaside.instagram.com/seo/google_widget/crawler/?media_id=3238124040768977698" alt="IG4">
        </div>
        <p>Subscribe to our Newsletter</p>
        <input type="email" placeholder="E-mail Anda">
        <button>Berlangganan</button>
        <p>Follow Us: Facebook • Twitter • Instagram</p>
    </footer>

</body>
</html>
