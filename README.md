# Satellite-Track

Uydu Takibi (Satellite Tracker)
Türkçe

Bu proje, Dünya'nın etrafında dönen Uluslararası Uzay İstasyonu'nu (ISS) gerçek zamanlı olarak takip etmek için Three.js ve Flask kullanılarak geliştirilmiştir. Proje, ISS'in enlem, boylam verilerini alır ve dünya üzerindeki hareketini görsel olarak simüle eder. Ayrıca, uyduya tıklanarak konum bilgileri ve ülke bilgisi gösterilir.
Özellikler

    Gerçek Zamanlı ISS Takibi: ISS'in enlem ve boylam verilerini alır, 3D Dünya modelinde hareketini gösterir.
    Zoom Kontrolü: Kamera yakınlaştırılabilir ve uzaklaştırılabilir.
    Uydu Bilgisi Gösterimi: Uyduya tıklanarak enlem, boylam ve bulunduğu ülke bilgisi görüntülenebilir.
    Mobil Uyumluluk: Responsive tasarım, mobil cihazlarla uyumlu.

Gereksinimler

    Flask: Sunucu tarafında veri sağlamak için.
    Three.js: 3D grafik ve animasyonlar için.
    OpenStreetMap Reverse Geocoding API: ISS'in bulunduğu konumun ülkesini almak için.

Kurulum

    Proje Dosyalarını İndirin: GitHub reposunu klonlayın veya ZIP olarak indirin.

git clone https://github.com/Keremcm/Satellite-Track.git

Gerekli Python Paketlerini Yükleyin:

pip install -r requirements.txt

Flask Sunucusunu Çalıştırın:

    python app.py

    Tarayıcıda http://localhost:5000 adresini ziyaret ederek projeyi görebilirsiniz.

Katkı

Katkılarınızı bekliyoruz! Projeyi geliştirmek için önerileriniz varsa, PR gönderebilirsiniz.
English

This project is developed using Three.js and Flask to track the International Space Station (ISS) in real-time orbiting Earth. The project retrieves ISS latitude and longitude data and simulates its movement on a 3D model of Earth. Additionally, users can click on the satellite to display its location and country information.
Features

    Real-Time ISS Tracking: Retrieves ISS's latitude and longitude data, displaying its movement on a 3D Earth model.
    Zoom Control: The camera can zoom in and out.
    Satellite Information Display: Click on the satellite to view latitude, longitude, and country information.
    Mobile Compatibility: Responsive design, works seamlessly on mobile devices.

Requirements

    Flask: For providing server-side data.
    Three.js: For 3D graphics and animations.
    OpenStreetMap Reverse Geocoding API: To get the country where the ISS is located.

Setup

    Download the Project Files: Clone the GitHub repository or download as a ZIP.

git clone https://github.com/Keremcm/Satellite-Track.git

Install Required Python Packages:

pip install -r requirements.txt

Run Flask Server:

    python app.py

    Open your browser and visit http://localhost:5000 to view the project.

Contributions

We welcome contributions! If you have suggestions for improving the project, feel free to send a pull request.
