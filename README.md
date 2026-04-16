<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <title>Sibervatan Bilet Sitesi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background-color: #f4f6f8;
        }
        h1, h2 {
            color: #333;
        }
        .container {
            max-width: 900px;
            margin: auto;
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        ul {
            line-height: 1.8;
        }
        .card {
            margin-bottom: 15px;
            padding: 10px;
            border-left: 4px solid #007BFF;
            background: #f9f9f9;
        }
        .role {
            font-weight: bold;
            color: #007BFF;
        }
    </style>
</head>
<body>

<div class="container">

    <h1>Sibervatan Bilet Sitesi</h1>
    <p><strong>Yusuf Yazıcı - Yavuzlar Takımı Görevi</strong></p>

    <h2>Kurulum Adımları</h2>
    <ol>
        <li>Dosyayı indirin ve ZIP’ten çıkartın.</li>
        <li>Klasörün konumuna gidin.</li>
        <li>Docker’ı çalıştırın.</li>
        <li>Klasörde sağ tıklayıp terminal açın.</li>
        <li><code>docker-compose up -d</code> komutunu çalıştırın.</li>
        <li><strong>http://localhost:5501</strong> adresine gidin.</li>
    </ol>

    <h2>Admin Kullanıcılar</h2>

    <div class="card">
        <p><strong>admin1</strong></p>
        <p>Mail: admin@bilet.com</p>
        <p>Şifre: admin_12345</p>
        <p class="role">Rol: Admin</p>
    </div>

    <div class="card">
        <p><strong>admin2</strong></p>
        <p>Mail: admin2@bilet.com</p>
        <p>Şifre: admin_09876</p>
        <p class="role">Rol: Admin</p>
    </div>

    <h2>Firma Adminleri</h2>

    <div class="card">
        <p><strong>Hasan Hüsrev Koç</strong></p>
        <p>Mail: hasankoc@gmail.com</p>
        <p>Şifre: hasanhusrev123</p>
        <p class="role">Firma: ÖZ Şarkışla</p>
    </div>

    <div class="card">
        <p><strong>Taha Öztürk</strong></p>
        <p>Mail: tahaozturk@gmail.com</p>
        <p>Şifre: tahaozturk_1453</p>
        <p class="role">Firma: Hamiyet Koç</p>
    </div>

    <div class="card">
        <p><strong>Mehmet Güçyetmez</strong></p>
        <p>Mail: baframehmet55@baframail.com</p>
        <p>Şifre: baframehmet123.123</p>
        <p class="role">Firma: Bafra Turizm</p>
    </div>

    <div class="card">
        <p><strong>Hamdi Ferah</strong></p>
        <p>Mail: hamdiferah@hadanamail.com</p>
        <p>Şifre: hamdiadana01adana</p>
        <p class="role">Firma: Has Adana Seyahat</p>
    </div>

    <div class="card">
        <p><strong>Polat Elmas</strong></p>
        <p>Mail: polatelmas25@esadasmail.com</p>
        <p>Şifre: elmasAS25esadas</p>
        <p class="role">Firma: Esadaş</p>
    </div>

    <div class="card">
        <p><strong>Sude Naz Çakmak</strong></p>
        <p>Mail: sudenazcakmak@abozkurt.com</p>
        <p>Şifre: adanasudenaz01bozkurt</p>
        <p class="role">Firma: Adana Bozkurt Seyahat</p>
    </div>

    <div class="card">
        <p><strong>Burak Aslan</strong></p>
        <p>Mail: burakaslan58@ozsarkislamail.com</p>
        <p>Şifre: OZburakASLAN.58</p>
        <p class="role">Firma: ÖZ Şarkışla</p>
    </div>

    <h2>Normal Kullanıcılar</h2>

    <div class="card">
        <p><strong>Ahmet Kaya</strong></p>
        <p>Mail: ahmetkaya44@gmail.com</p>
        <p>Şifre: Malatya_Gulu_44</p>
    </div>

    <div class="card">
        <p><strong>Aleyna Gök</strong></p>
        <p>Mail: aleynaakoz@gmail.com</p>
        <p>Şifre: 123456</p>
    </div>

</div>

</body>
</html>
