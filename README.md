<div align="center">

<img src="assets/banner.svg" alt="Muhamad Arya Praseptya, Software Engineer" width="100%">

</div>

> Saya lebih suka fitur yang benar-benar dipakai orang daripada fitur yang hanya jalan di laptop saya.

Lulusan Ilmu Komputer yang mengerjakan web dengan Laravel dan mobile dengan Flutter, dengan minat ke arah machine learning. Karya terbaru saya, LingoJoy, adalah aplikasi latihan pelafalan yang model suaranya berjalan langsung di ponsel, tanpa internet.

<br>

## Sekilas

<table>
  <tr><td><b>Berbasis di</b></td><td>Kabupaten Bogor, Jawa Barat</td></tr>
  <tr><td><b>Pendidikan</b></td><td>S1 Ilmu Komputer, Universitas Pakuan (2022 sampai 2026, IPK 3.46)</td></tr>
  <tr><td><b>Pengalaman</b></td><td>Magang sebagai Full-Stack Developer di PT Media Televisi Indonesia (Metro TV), Agustus sampai Oktober 2025</td></tr>
  <tr><td><b>Minat</b></td><td>Pengembangan perangkat lunak, analisis data, dan machine learning</td></tr>
  <tr><td><b>Cara kerja</b></td><td>Merancang antarmuka di Figma lebih dulu, baru menulis kode</td></tr>
  <tr><td><b>Di luar kode</b></td><td>Volunteer divisi keamanan di Festival MIPA 2024</td></tr>
  <tr><td><b>Terbuka untuk</b></td><td>Peran software engineer entry-level</td></tr>
</table>

<br>

## Alat yang saya pakai

<img src="assets/stack.svg" alt="PHP, Laravel, JavaScript, Dart, Flutter, Python, MySQL, SQLite, Firebase, Figma, Git, GitHub" width="100%">

Di luar daftar itu: speech recognition (Google ASR dan APC-LSTM), analisis dan visualisasi data, serta web scraping.

<br>

## Proyek

<table>
  <tr>
    <td width="33%" valign="top">
      <b>LingoJoy</b><br>
      <sub>Skripsi, 2026</sub><br><br>
      Aplikasi latihan pelafalan yang tetap bisa menilai suara tanpa internet. Google ASR saat online, model APC-LSTM di perangkat saat offline.<br><br>
      <code>Flutter</code> <code>Python</code> <code>APC-LSTM</code> <code>SQLite</code><br><br>
      <a href="https://github.com/Praseptya/LingoJoy">Kode sumber</a>
    </td>
    <td width="33%" valign="top">
      <b>Program Budgeting System</b><br>
      <sub>Magang di Metro TV, 2025</sub><br><br>
      Mengganti pengajuan anggaran produksi televisi yang manual dengan entri terstruktur, pelacakan biaya, dan persetujuan bertingkat.<br><br>
      <code>Laravel</code> <code>MySQL</code> <code>Figma</code><br><br>
      <a href="https://github.com/Praseptya/Program-Budgeting-System">Kode sumber</a>
    </td>
    <td width="33%" valign="top">
      <b>Discorso</b><br>
      <sub>Proyek akhir mata kuliah, tim 4 orang, 2025</sub><br><br>
      Aplikasi media sosial minimalis dengan feed, like, komentar, dark mode, serta fitur blokir dan laporkan pengguna.<br><br>
      <code>Flutter</code> <code>Firebase</code> <code>Figma</code><br><br>
      <a href="https://github.com/Praseptya/Discorso">Kode sumber</a>
    </td>
  </tr>
</table>

<details>
<summary><b>Bagaimana LingoJoy menilai pelafalan?</b></summary>

<br>

```mermaid
flowchart LR
    A([Kata diucapkan]) --> B{Ada koneksi?}
    B -- ya --> C[Google ASR]
    B -- tidak --> D[APC-LSTM di perangkat]
    C --> E[Kemiripan dengan kata target<br>Levenshtein Distance]
    D --> E
    E --> F[Skor keyakinan seketika]
    F --> G[(Progres di SQLite)]
```

Dua jalur pengenalan suara menghasilkan teks yang sama-sama dibandingkan dengan kata target, jadi pengguna mendapat umpan balik yang konsisten, online maupun offline.

</details>

Proyek lainnya ada di [daftar repositori saya](https://github.com/Praseptya?tab=repositories).

<br>

## Hubungi saya

<a href="mailto:m.arya.praseptya@gmail.com"><img src="assets/btn-email.svg" alt="Email"></a>
&nbsp;
<a href="https://www.linkedin.com/in/muhamad-arya-praseptya"><img src="assets/btn-linkedin.svg" alt="LinkedIn"></a>
<!-- Aktifkan setelah portfolio di-host, ganti URL-nya:
&nbsp;
<a href="https://URL-PORTFOLIO-ANDA"><img src="assets/btn-portfolio.svg" alt="Portfolio"></a>
-->
