<div align="center">

<!-- Header Banner Horror Style (Otomatis Animasi Teks) -->
<img src="https://readme-typing-svg.demolab.com?font=Cinzel&weight=700&size=42&duration=3000&pause=1500&color=D62828&center=true&vCenter=true&width=700&height=70&lines=E+T+E+R+N+A+L+++F+E+A+R;SURVIVAL+HORROR+PROJECT" alt="Eternal Fear Title" />

**True First-Person Survival Horror | Unity 2022.3 LTS (URP) | Modular C# Architecture**

<p>
  <img src="https://img.shields.io/badge/Engine-Unity%202022.3%20LTS-0D1117?style=for-the-badge&logo=unity&logoColor=white" />
  <img src="https://img.shields.io/badge/Pipeline-URP-5A189A?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Language-C%23-1B4332?style=for-the-badge&logo=csharp&logoColor=white" />
  <img src="https://img.shields.io/badge/3D%20Modeling-Blender-E87D0D?style=for-the-badge&logo=blender&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-In%20Development-9B111E?style=for-the-badge" />
</p>

<br/>

> *"Denyut nadi mulai tidak beraturan. Di balik lorong gelap ini, setiap peluru yang tersisa adalah batas tipis antara hidup dan kehampaan."*

</div>

---

## 🩸 Tentang Proyek

**Eternal Fear** adalah proyek game **True First-Person Survival Horror** yang terinspirasi oleh atmosfer mencekam serta mekanik taktis dari *Resident Evil 7: Biohazard* dan *Resident Evil 2 Remake*.

Seluruh sistem gameplay dibangun dari nol menggunakan pendekatan **Decoupled Component-Based Architecture** di Unity — memisahkan sensor input, fisika karakter, sistem kamera *True First-Person*, manajemen senjata, inventori grid, hingga kecerdasan buatan musuh agar mudah dikembangkan ke skala penuh.

> *Catatan: Source code & aset berada pada repositori privat selama masa pengembangan aktif. Repositori ini berfungsi sebagai dokumentasi publik dan showcase fitur.*

---

## 🧠 Sorotan Sistem & Rekayasa Teknis

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🎥 True First-Person & Camera Engineering</h3>
      <ul>
        <li><b>Camera-Relative Arm Lock:</b> Penguncian presisi kedua lengan dan senjata terhadap arah kamera pada sudut ekstrem (<code>-85°</code> hingga <code>+80°</code>) dengan zero parallax miss.</li>
        <li><b>3-Pillar Anti-Clipping:</b> Capsule Boundary Clamp + Realtime SphereCast Probe + URP Dual-Camera Weapon Rendering agar senjata mustahil menembus dinding.</li>
        <li><b>Dynamic Sway & Headbob Separation:</b> Inersia bobot tangan halus bebas singularitas gimbal serta pemisahan goyangan kamera dan senjata.</li>
        <li><b>Quick Turn 180°:</b> Putar balik taktis seketika untuk menghindar dari sergapan belakang.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🎒 RE-Style Grid Inventory & EKG Monitor</h3>
      <ul>
        <li><b>Grid Management (4x2):</b> Mendukung <i>Move</i>, <i>Equip</i>, <i>Use</i>, <i>Discard</i>, serta <i>Combine</i> (mengisi magazen & menggabungkan stack amunisi).</li>
        <li><b>3D Examine Studio:</b> Ruang inspeksi 3D terisolasi untuk memutar dan memeriksa detail objek (M1911, Ammo Box, First Aid Spray) 360°.</li>
        <li><b>Procedural EKG Oscilloscope:</b> Monitor detak jantung real-time (<code>CALM</code>, <code>ANXIOUS</code>, <code>TERRIFIED</code>, <code>NO PULSE</code>) yang bereaksi langsung terhadap HP pemain.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🔫 Tactical Gunplay & Interaction</h3>
      <ul>
        <li><b>M1911 Combat Cycle:</b> Magazen 7 peluru, <i>dry-fire</i> saat kosong, <i>fire bloom</i> dinamis, hentakan kamera, ejeksi selongsong, & HUD minimalis.</li>
        <li><b>Tactical Door & Body-Breach:</b> Pintu dapat dibuka perlahan untuk mengintip atau didobrak fisik saat karakter berlari.</li>
        <li><b>Proximity & Raycast Marker:</b> Penanda interaksi 3D <code>[F]</code> yang peka terhadap jarak dan frustum kamera.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🧟 Zombie AI, Health & Death Sequence</h3>
      <ul>
        <li><b>AI State Machine:</b> <code>Patrol → Investigate → Chase → Attack → Downed</code> dengan sensor penglihatan FOV dan sensor pendengaran suara tembakan.</li>
        <li><b>Physiological Damage Response:</b> Efek kilatan darah, <i>i-frames</i>, audio detak jantung panik di bawah 30% HP, & item medis <i>First Aid Spray</i>.</li>
        <li><b>Procedural FPS Death Collapse:</b> Kamera dan kedua lengan terkulai jatuh ke lantai, layar memudar ke hitam, suara flatline, & UI <b>YOU ARE DEAD</b>.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🛠️ Tech Stack & Tools

<p>
  <img src="https://img.shields.io/badge/Unity%202022.3%20LTS-000000?style=flat-square&logo=unity&logoColor=white" />
  <img src="https://img.shields.io/badge/Universal%20Render%20Pipeline-5A189A?style=flat-square" />
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white" />
  <img src="https://img.shields.io/badge/Cinemachine-007ACC?style=flat-square" />
  <img src="https://img.shields.io/badge/Unity%20New%20Input%20System-1E90FF?style=flat-square" />
  <img src="https://img.shields.io/badge/Blender-F5792A?style=flat-square&logo=blender&logoColor=white" />
  <img src="https://img.shields.io/badge/Visual%20Studio-5C2D91?style=flat-square&logo=visual-studio&logoColor=white" />
</p>

---

## 🎮 Skema Kontrol

| Aksi | Keyboard & Mouse | Gamepad |
| :--- | :--- | :--- |
| **Bergerak** | `W` `A` `S` `D` | Left Stick |
| **Lari (Sprint)** | `Shift` | L3 |
| **Membidik (Aim)** | `Klik Kanan (Hold)` | `LT` / `L2` |
| **Menembak** | `Klik Kiri` | `RT` / `R2` |
| **Reload** | `R` | `X` / `Square` |
| **Quick Turn 180°** | `Q` | `Analog Bawah` + `A` / `Cross` |
| **Interaksi / Pickup** | `F` | `A` / `Cross` |
| **Inventory & EKG** | `Tab` | `Y` / `Triangle` |

---

## 📸 Cuplikan Gameplay *(Coming Soon)*

> *Tambahkan screenshot atau rekaman GIF/MP4 gameplay (M1911 Aim, Grid Inventory + EKG, 3D Examine, & Death Collapse) dengan men-drag gambar langsung ke editor README di GitHub!*

---

<div align="center">

### 👤 Pengembang

**M. Wahyu Agus Dwianto**  
*Game Developer • Unity C# • Survival Horror Enthusiast*

<!-- Ganti link di bawah dengan akun asli Anda, atau hapus yang tidak diperlukan -->
<p>
  <a href="https://github.com/USERNAME_ANDA"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="mailto:EMAIL_ANDA@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

</div>
