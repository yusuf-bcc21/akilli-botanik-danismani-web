# Akıllı Botanik Danışmanı Web 🌿

Bu proje, **Burdur Mehmet Akif Ersoy Üniversitesi (MAKÜ)** bünyesinde yürüttüğüm akademik çalışmalar ve girişimcilik vizyonum doğrultusunda geliştirilmiş, **Akıllı Saksı (Smart Planter)** sistemi için modern bir web arayüzüdür. Bitki bakım süreçlerini dijitalleştirerek kullanıcıların verileri kolayca izlemesini sağlar.

## 🚀 Kullanılan Teknolojiler

* **Frontend:** [React](https://react.dev/)
* **Build Aracı:** [Vite](https://vitejs.dev/)
* **3D Modelleme:** Projede `public/saksi.glb` dosyasında bulunan 3D model, üç boyutlu görselleştirme için kullanılmıştır.
* **Stil:** Modüler CSS (`App.css`, `index.css`)

## 🛠️ Kurulum ve Çalıştırma

Projeyi yerel ortamınızda ayağa kaldırmak için aşağıdaki adımları izleyebilirsiniz:

### 1. Bağımlılıkları Yükleyin
Proje dizinine terminal üzerinden gidin ve gerekli paketleri yükleyin:
```
npm install
```

### 2. Çevresel Değişkenleri (.env) Ayarlayın
Hata almamak için ana dizinde bir `.env` dosyası oluşturun ve API anahtarınızı Vite standartlarına uygun şekilde ekleyin:

```
VITE_GEMINI_API_KEY=buraya_api_anahtarinizi_yazin
```

### 3. Uygulamayı Başlatın
Geliştirme sunucusunu çalıştırmak için:

```
npm run dev
```

## 📁 Proje Yapısı

* `public/`: 3D modeller ve ikonlar gibi statik dosyalar.
* `src/`: Uygulama kaynak kodları, React bileşenleri ve stil dosyaları.
* `.gitignore`: `.env` ve `node_modules` gibi hassas veya gereksiz dosyaların Git'e yüklenmesini engeller.
