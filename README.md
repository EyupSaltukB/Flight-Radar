# Flight Radar (React + Vite)

Redux toolkit ile canlı uçuş radar ekranı.
Harita ve Liste sayfalarına sahiptir.
Uçakların canlı hareketleri gözlemlenebilir.
Uçakların detaylı bilgilerine sahip açılı kapanır detay ekranı.
Sayfalama yapısı için react-paginate kütüphanesi eklendi.
Haritalama için react-leaflet kütüphanesi eklendi.

#  Kaynaklar

Rapid API: 
- https://rapidapi.com/apidojo/api/flight-radar1

- Uçuş Koordinat Alanı;
Soldan: 34.047182, 24.992627
Sağdan: 42.705437, 44.549525

# Kütüphaneler

- @reduxjs/toolkit
- thunk (toolkit ile beraber)
- axios (veri istekleri)
- react-paginate (sayfalama)
- react-leaflet (harita)


# Yol Haritası

- Liste Görünümü -> ListView
- Harita Görünümü -> MapView
- İki dosya arası geçiş -> App.jsx'de

# Ekran Görüntüleri

<img width="1440" alt="screen-2" src="https://github.com/EyupSaltukB/Flight-Radar/assets/129687853/6a6d09e2-919a-42ef-84f4-463188720c71">
<img width="1440" alt="screen-4" src="https://github.com/EyupSaltukB/Flight-Radar/assets/129687853/df420678-9aff-43cf-90f4-b270ebe68133">
<img width="1440" alt="screen-5" src="https://github.com/EyupSaltukB/Flight-Radar/assets/129687853/aa38d4f3-b3c4-4d0d-aaf3-672c4d19c6ef">
<img width="1440" alt="screen-3" src="https://github.com/EyupSaltukB/Flight-Radar/assets/129687853/ea6af943-2e09-4da9-b9a2-3dd5f710abf3">
<img width="1440" alt="screen-1" src="https://github.com/EyupSaltukB/Flight-Radar/assets/129687853/44210068-d1ff-47cd-89c3-41bac41024db">

# Video

# GIF

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
