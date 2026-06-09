<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kuryedostu</title>
    <style>
        /* Genel Tasarım Ayarları */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f7f6;
            color: #333;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        /* Header ve Logo Alanı */
        header {
            background-color: #ffffff;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            padding: 20px 0;
            text-align: center;
        }

        .logo h1 {
            font-size: 2.5rem;
            color: #ff6b6b;
            font-weight: 800;
            letter-spacing: -1px;
            text-transform: lowercase;
        }

        .logo h1 span {
            color: #2f3640;
        }

        /* Menü Sayfaları */
        nav {
            margin-top: 15px;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 25px;
        }

        nav ul li a {
            text-decoration: none;
            color: #57606f;
            font-weight: 600;
            font-size: 1.1rem;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: #ff6b6b;
        }

        /* Ana İçerik ve Harita Alanı */
        main {
            flex: 1;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 40px 20px;
        }

        .map-container {
            width: 100%;
            max-width: 1000px;
            background: #ffffff;
            padding: 15px;
            border-radius: 12px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        /* Harita Kutusu */
        .map-box {
            width: 100%;
            height: 500px;
            border-radius: 8px;
            margin-bottom: 20px;
            overflow: hidden;
            border: none;
        }

        .map-box iframe {
            width: 100%;
            height: 100%;
            border: none;
        }

        /* Lokasyon Ekle Butonu */
        .add-location-btn {
            background-color: #ff6b6b;
            color: white;
            border: none;
            padding: 14px 28px;
            font-size: 1.1rem;
            font-weight: 600;
            border-radius: 30px;
            cursor: pointer;
            box-shadow: 0 4px 15px rgba(255, 107, 107, 0.4);
            transition: all 0.3s ease;
            text-decoration: none;
            display: inline-block;
        }

        .add-location-btn:hover {
            background-color: #ee5253;
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(255, 107, 107, 0.6);
        }

        /* Footer (Alt Bilgi) */
        footer {
            background-color: #2f3640;
            color: #ffffff;
            text-align: center;
            padding: 15px 0;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">
            <h1>kurye<span>dostu</span></h1>
        </div>
        <nav>
            <ul>
                <li><a href="#ana-sayfa">Anasayfa</a></li>
                <li><a href="#hizmetler">Hizmetlerimiz</a></li>
                <li><a href="#hakkimizda">Hakkımızda</a></li>
                <li><a href="#iletisim">İletişim</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <div class="map-container">
            <div class="map-box" id="mapBox">
                <iframe id="googleMap" src="https://maps.google.com/maps?q=Turkey&t=&z=6&ie=UTF8&iwloc=&output=embed"></iframe>
            </div>

            <button class="add-location-btn" onclick="konumumuCek()">
                📍 Konumumu Haritada Göster
            </button>
        </div>
    </main>

    <footer>
        <p>© 2026 kuryedostu. Tüm Hakları Saklıdır.</p>
    </footer>

    <script>
        function konumumuCek() {
            if (navigator.geolocation) {
                // Tarayıcıdan canlı konum istiyoruz
                navigator.geolocation.getCurrentPosition(function(position) {
                    var lat = position.coords.latitude;
                    var lon = position.coords.longitude;
                    
                    // Google Maps embed linkini kullanıcının enlem ve boylamına göre güncelliyoruz
                    var yeniHaritaUrl = "https://maps.google.com/maps?q=" + lat + "," + lon + "&t=&z=15&ie=UTF8&iwloc=&output=embed";
                    
                    // Haritayı ekrana basıyoruz
                    document.getElementById('googleMap').src = yeniHaritaUrl;
                }, function(error) {
                    alert("Konum izni reddedildi veya konum alınamadı. Lütfen tarayıcı ayarlarından konum izni verin.");
                });
            } else {
                alert("Tarayıcınız konum bulma özelliğini desteklemiyor.");
            }
        }

        // Sayfa açıldığında kullanıcıya hiç sormadan direkt konumu çekmeye çalışmasını istiyorsanız alttaki satırın başındaki // işaretlerini kaldırabilirsiniz.
        // window.onload = konumumuCek;
    </script>

</body>
</html>
