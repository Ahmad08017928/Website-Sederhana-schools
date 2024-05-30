## Dokumentasi

 ## Penjelasan Kode
*Bagian HTML*
1. Doctype dan Tag Dasar
   ```html
   <!DOCTYPE html>
   <html lang="id">
   ```
   Menentukan jenis dokumen HTML5 dan bahasa halaman sebagai Bahasa Indonesia.

2. *Kepala Dokumen*
   ```html
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Website Sederhana</title>
   ```
   Berisi metadata tentang dokumen seperti karakter encoding, viewport, dan judul halaman.

3. *Gaya Internal*
   ```html
   <style>
       /* CSS di sini */
   </style>
   ```
   Gaya CSS didefinisikan secara internal dalam tag `<style>`.

4. *Badan Dokumen*
   ```html
   <body>
       <!-- Konten di sini -->
   </body>
   ```
   Bagian ini berisi semua konten yang akan ditampilkan di halaman web.

5. *Header*
   ```html
   <header>
       <h1>Selamat Datang di Website Sederhana Saya</h1>
   </header>
   ```
   Bagian header ini berisi judul utama website dengan latar belakang gambar.

6. *Main Content*
   ```html
   <main>
       <section>
           <h2>Tentang Saya</h2>
           <p>Halo, nama saya [Nama Anda]. Saya sedang belajar membuat website sederhana menggunakan HTML dan CSS.</p>
           <p>Saya tertarik dengan pemrograman dan ingin menjadi web developer yang handal.</p>
       </section>
       <section>
           <h2>Gambar Favorit Saya</h2>
           <img src="https://images.unsplash.com/photo-1593642532973-d31b6557fa68?crop=entropy&cs=tinysrgb&fit=crop&fm=jpg&h=300&q=80&w=300" alt="Contoh Gambar">
       </section>
   </main>
   ```
   Konten utama berisi dua bagian: satu tentang diri Anda dan satu lagi untuk gambar favorit Anda.

7. *Footer*
   ```html
   <footer>
       <p>&copy; 2024 [Nama Anda]. Semua Hak Dilindungi.</p>
   </footer>
   ```
   Bagian footer ini menampilkan hak cipta.

## Bagian CSS

1. *Gaya Dasar*
   ```css
   body {
       font-family: Arial, sans-serif;
       line-height: 1.6;
       margin: 0;
       padding: 0;
       background-color: #f4f4f4;
   }
   ```
   Menetapkan font, tinggi baris, margin, padding, dan warna latar belakang untuk seluruh halaman.

2. *Header*
   ```css
   header {
       background-image: url('https://images.unsplash.com/photo-1499346030926-9a72daac6c63?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1350&q=80');
       background-size: cover;
       background-position: center;
       color: #fff;
       padding: 60px 0;
       text-align: center;
   }
   ```
   Menetapkan gambar latar belakang, ukuran latar, posisi, warna teks, padding, dan penyelarasan teks untuk header.

3. *Main Content*
   ```css
   main {
       padding: 20px;
   }
   h1, h2 {
       color: #333;
   }
   p {
       color: #666;
   }
   img {
       display: block;
       margin: 0 auto;
   }
   ```
   Menetapkan padding untuk bagian utama, warna teks untuk judul dan paragraf, serta pengaturan gambar agar berada di tengah.

4. *Footer*
   ```css
   footer {
       background: #333;
       color: #fff;
       text-align: center;
       padding: 10px 0;
       position: absolute;
       bottom: 0;
       width: 100%;
   }
   ```
   Menetapkan warna latar belakang, warna teks, penyelarasan teks, padding, dan posisi untuk footer.# Website-Sederhana-schools
