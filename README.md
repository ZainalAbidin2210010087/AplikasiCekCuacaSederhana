# AplikasiCekCuacaSederhana

AplikasiCekCuacaSederhana adalah aplikasi desktop sederhana yang menampilkan informasi cuaca berdasarkan kota yang dipilih oleh pengguna. Aplikasi ini menggunakan API dari OpenWeatherMap untuk mengambil data cuaca, yang mencakup deskripsi cuaca, suhu, dan ikon cuaca. Pengguna dapat memilih kota, melihat informasi cuaca terbaru, dan menyimpannya ke dalam file teks.

#NAMA  : ZAINAL ABIDIN
#NPM   : 2210010087 
#KELAS : 5B NONREG BANJARMASIN

---

## Fitur

1. **Cek Cuaca Berdasarkan Kota**: Pengguna dapat memasukkan nama kota atau memilih dari daftar (Jakarta, Bandung, Surabaya) untuk mendapatkan data cuaca.
2. **Tampilkan Informasi Cuaca**: Menampilkan deskripsi cuaca, suhu dalam derajat Celsius, dan ikon cuaca yang relevan.
3. **Simpan Data Cuaca**: Pengguna dapat menyimpan informasi cuaca yang ditampilkan ke dalam file `weather_data.txt`.
   
## Cara Menggunakan

1. Jalankan aplikasi, antarmuka utama akan muncul.
2. Pilih kota dari dropdown atau masukkan nama kota di kolom teks.
3. Tekan tombol **CEK CUACA** untuk mengambil informasi cuaca dari API.
4. Informasi cuaca (deskripsi dan suhu) akan ditampilkan di area teks, serta ikon cuaca.
5. Untuk menyimpan informasi cuaca, tekan tombol **SIMPAN DATA**. Data akan disimpan dalam file `weather_data.txt`.

## Teknologi yang Digunakan

- **Java Swing**: Untuk antarmuka pengguna grafis.
- **API OpenWeatherMap**: Untuk mengambil data cuaca secara online.
- **JSON**: Untuk parsing data JSON yang diterima dari API.

## Keunggulan

- **Antarmuka Sederhana**: Mudah digunakan dengan antarmuka yang intuitif.
- **Menyimpan Data**: Memungkinkan pengguna menyimpan data cuaca dalam file teks.
- **Ikon Cuaca**: Menampilkan ikon cuaca yang mencerminkan kondisi saat ini.

## Cara Menjalankan Program

1. **Persyaratan**: Pastikan Anda sudah memiliki **Java** (JDK) dan **koneksi internet** (untuk mengambil data cuaca).
2. **Mendapatkan API Key**:
   - Buat akun di [OpenWeatherMap](https://openweathermap.org/).
   - Dapatkan API key Anda.
   - Ganti `apiKey` dalam kode dengan API key Anda sendiri.
3. **Kompilasi dan Jalankan**:
   - Simpan kode dalam file `WeatherAppFrame.java`.
   - Buka terminal atau command prompt dan navigasikan ke direktori tempat file disimpan.
   - Jalankan perintah berikut:
     ```bash
     javac WeatherAppFrame.java
     java WeatherAppFrame
     ```

Setelah itu, aplikasi siap digunakan!
