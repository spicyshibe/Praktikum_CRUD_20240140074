# Laporan Praktikum Spring Boot - Manajemen User

Repositori ini berisi proyek tugas praktikum pengembangan backend menggunakan framework Spring Boot. Proyek ini mengimplementasikan sistem manajemen data user dengan arsitektur yang terstruktur (Controller, Service, Repository, Mapper, dan DTO).

## 🚀 Fitur & Alur Kerja
1.  **Project Initialization**: Inisialisasi Spring Boot dengan Gradle/Maven.
2.  **Database Integration**: Koneksi dengan MySQL Server.
3.  **Data Modeling**: Pembuatan Entity dan Data Transfer Object (DTO).
4.  **Validation & Mapping**: Implementasi validasi input dan pemetaan object menggunakan MapStruct.
5.  **Service Logic**: Implementasi logika bisnis pada layer service.
6.  **REST API**: Pembuatan endpoint controller untuk interaksi klien.

## 🛠️ Teknologi yang Digunakan
* **Java 17/21**
* **Spring Boot 3.x**
* **Spring Data JPA**: Persistensi data SQL.
* **MySQL Driver**: Database connector.
* **Lombok**: Mengurangi boilerplate code.
* **Bean Validation**: Validasi data input.
* **MapStruct**: Object mapping (Entity <-> DTO).

---

## 📸 Dokumentasi 

### 1. Halaman Utama
<img width="1710" height="1112" alt="Screenshot 2026-03-03 at 12 36 02" src="https://github.com/user-attachments/assets/9d62cfcc-ddcf-4690-8b29-b1fd158d3a93" />

### 2. Tambah Data
<img width="1710" height="1112" alt="Screenshot 2026-03-03 at 12 36 45" src="https://github.com/user-attachments/assets/7aeb8fba-fca2-4cf2-a7d3-d8df97416a15" />

### 4. Data Baru




---

## 🏃 Cara Menjalankan
1.  Clone repositori ini.
2.  Sesuaikan konfigurasi database di `src/main/resources/application.properties`.
3.  Jalankan perintah `./gradlew bootRun` atau `mvn spring-boot:run`.
4.  Aplikasi akan berjalan di `http://localhost:8080`.

---
*Dibuat untuk memenuhi Tugas Praktikum Pemrograman Backend.*
