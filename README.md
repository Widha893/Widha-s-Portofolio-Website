## Portofolio Pribadi

Website portofolio statis sederhana yang menampilkan profil, pengalaman kerja, organisasi, pendidikan, dan skills.

### Cara Menjalankan

- **Buka langsung di browser**
  - Klik dua kali `index.html` atau buka lewat browser favorit kamu (Chrome/Edge/Firefox).

- **Menjalankan dengan server lokal (opsional, lebih nyaman untuk pengembangan)**
  - Jika punya Python:

    ```bash
    cd D:\firmware_engineer\work-apply
    python -m http.server 8000
    ```

  - Lalu buka `http://localhost:8000` di browser.

### Cara Mengedit Konten

- **Profil & info singkat**: edit bagian `<section id="about">` di `index.html`.
- **Pengalaman kerja**: edit/tambah elemen di `<section id="experience">`.
- **Organisasi**: edit/tambah di `<section id="organization">`.
- **Pendidikan**: edit/tambah kartu di `<section id="education">`.
- **Skills**: edit daftar di `<section id="skills">`.
- **Kontak (email, LinkedIn, GitHub)**: ubah link di `<section id="contact">`.

Ganti placeholder seperti `[Nama Kamu]`, `[email@contoh.com]`, `[link-linkedin]`, `[link-github]`, dsb. dengan data kamu sendiri.


