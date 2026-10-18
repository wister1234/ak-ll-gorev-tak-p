# Odak — Akıllı Görev ve Proje Takip Uygulaması

React + Vite + saf CSS ile geliştirilmiş, tarayıcıda çalışan görev yönetimi uygulaması.

## Özellikler
- Görev ekleme, listeleme, güncelleme ve silme (CRUD)
- Görevleri tamamlandı/aktif olarak işaretleme
- Metin arama, durum ve öncelik filtreleri
- Öncelik, kategori, açıklama ve bitiş tarihi
- Toplam, tamamlanan, aktif ve yüksek öncelikli görev istatistikleri
- İlerleme yüzdesi ve mobil uyumlu arayüz
- `localStorage` ile verilerin tarayıcıda kalıcı tutulması

## Kurulum
Node.js 18 veya üzeri gereklidir.

```bash
npm install
npm run dev
```

Tarayıcıda terminalde gösterilen adresi açın (genellikle `http://localhost:5173`).

## Üretim
```bash
npm run build
npm run preview
```

## GitHub ve Netlify
1. Bu klasörü yeni bir **public** GitHub deposuna yükleyin (`node_modules` ve `dist` hariç).
2. Netlify > Add new project > Import an existing project > GitHub üzerinden depoyu seçin.
3. Build command: `npm run build`; Publish directory: `dist`.
4. Oluşan Netlify adresini ve GitHub depo bağlantısını teslim formuna ekleyin.

## Teknolojiler
React 18, Vite 6, JavaScript (JSX), saf CSS, lucide-react, Web Storage API.

## Veri saklama
Veriler yalnızca kullanıcının tarayıcısındaki localStorage alanında saklanır. Sunucu veya kullanıcı hesabı bulunmaz. İlk açılışta dört örnek görev gösterilir; bunlar değiştirilebilir ve silinebilir.

## Proje yapısı
- `src/components/TaskModal.jsx`: ekleme/güncelleme formu
- `src/pages/App.jsx`: ana sayfa, CRUD ve filtreleme
- `src/interfaces/task.js`: görev veri yapısı açıklaması ve sabitler
- `src/style.css`: responsive tasarım

## Ekran görüntüsü
`ekran-goruntusu.png` dosyası proje kök dizinindedir.
