# 🛍️ Eve Shop Clone - Nuxt 3 & Firebase Project

<p align="center">
  <img src="https://raw.githubusercontent.com/nuxt/modules/main/icons/firebase.svg" width="80" alt="Firebase Logo" />
  <img src="https://raw.githubusercontent.com/nuxt/modules/main/icons/nuxt.svg" width="80" alt="Nuxt Logo" />
</p>

<p align="center">
  <strong>Modern Web Teknolojileri ile Geliştirilmiş Full-Stack E-Ticaret Deneyimi</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Nuxt-3.14-green?style=for-the-badge&logo=nuxt.js" />
  <img src="https://img.shields.io/badge/Vue-3.x-brightgreen?style=for-the-badge&logo=vuedotjs" />
  <img src="https://img.shields.io/badge/Firebase-11.1-orange?style=for-the-badge&logo=firebase" />
  <img src="https://img.shields.io/badge/Pinia-State%20Management-yellow?style=for-the-badge" />
</p>

---

## 📖 Proje Özeti
Bu proje, popüler e-ticaret platformu **Eve Shop**'un kullanıcı arayüzünü ve temel işlevlerini temel alan bir klon uygulamadır. **Nuxt 3**'ün performanslı yapısı ile **Firebase**'in sunucusuz (serverless) gücünü birleştirerek; dinamik ürün listeleme, gerçek zamanlı veritabanı yönetimi ve güvenli kimlik doğrulama özelliklerini sunar.

## ✨ Öne Çıkan Özellikler
- **Serverless Mimari:** Arka plan yönetimi tamamen Firebase üzerinden sağlanmaktadır.
- **Gerçek Zamanlı Veritabanı:** Firestore entegrasyonu ile ürün ve kullanıcı verileri anlık olarak güncellenir.
- **Güvenli Kimlik Doğrulama:** Firebase Auth ile profesyonel giriş/kayıt sistemi.
- **Dinamik UI:** Responsive tasarım, ürün sliderları ve gelişmiş sepet mekanizması.
- **Merkezi Durum Yönetimi:** Pinia ile sepet ve üyelik verilerinin tutarlı yönetimi.

---

## 🛠️ Kullanılan Teknolojiler

| Katman | Teknoloji | Versiyon |
| :--- | :--- | :--- |
| **Framework** | **Nuxt 3** | ^3.14.1592 |
| **Frontend Library** | **Vue.js** | Latest |
| **Backend / DB** | **Firebase** | ^11.1.0 |
| **State Management** | **Pinia** | ^2.3.0 |
| **Ikonlar** | **FontAwesome** | ^6.7.1 |

---

## 📂 Proje Yapısı ve Bileşenler

Uygulama, modüler Vue bileşenleri (Components) üzerine inşa edilmiştir:

- **👤 Üyelik Yönetimi:** `LoginForm.vue`, `SignUp.vue`, `LogOut.vue`.
- **🛒 Alışveriş Bileşenleri:** `ProductSlider.vue`, `Sepet.vue`, `Carousel.vue`.
- **🎨 Arayüz Elemanları:** `Header.vue`, `Footer.vue`, `Menu.vue`, `Snowfall.vue`.
- **💬 Etkileşim:** `ChatBox.vue`, `Tabs.vue`, `DropdownMenu.vue`.

---

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
