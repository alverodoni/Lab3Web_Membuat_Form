# Lab3Web_Membuat_Form
Nama: Doni Alvero <p>
Nim: 312410663 <P>
Kelas: TI.24.A.5 <P>
Jurusan: Teknik Informatika <p>
Mata Kuliah: Pemograman Web 1 <p>

### Link Web yang dibuat
file:///C:/xampp/htdocs/Lab3Web/Labweb3.html

### Tahap 1: Membuat Ordered List
***Deskripsi:**
Halaman ini adalah contoh dasar dari materi pembelajaran HTML Lanjutan yang berfokus pada struktur dan penamaan daftar berurutan.
<img width="1918" height="1017" alt="Membuat Ordered List" src="https://github.com/user-attachments/assets/5c0eb2c1-2731-44d2-9edf-e5276126cbb1" />
***code:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat List</h1>
</header>
</body>
</html>
<section id="order-list">
<h2>Ordered List</h2>
<ol>
<li>Pemrograman Web</li>
<li>Sistem Informasi</li>
<li>Basis Data 2</li>
</ol>
</section>


### Tahap 2: Membuat Unorderd List
***Deskripsi:**
Halaman ini menyajikan contoh visual yang membandingkan dua elemen daftar dasar dalam HTML (`<ol>`) yang memberikan penomoran (berurutan) dan (`<ul>`) yang menggunakan simbol bullet (tidak berurutan). Kontennya menunjukkan contoh mata kuliah &  Mempelajari cara menggunakan CSS untuk meningkatkan estetika dan kegunaan formulir HTML. Fokus utamanya adalah bagaimana styling sederhana (seperti warna hijau pada border dan tombol) dapat membuat antarmuka pengguna (UI) menjadi lebih profesional dan menarik dibandingkan tampilan default browser.
<img width="1912" height="1010" alt="Membuat Unorderd List" src="https://github.com/user-attachments/assets/cade8ec8-f724-4174-b712-819fdca83ed6" /> 

### Tahap 3: Membuat Description List
***Deskripsi:**
Gambar ini menunjukkan cara membuat struktur data kompleks menggunakan elemen daftar HTML. Secara khusus, Description List (`<dl>, <dt>`), (`<dd>`) digunakan untuk memetakan istilah (`<dt>, misalnya: Fakultas Teknik`) dengan definisi atau sub-item terkait (`<dd>, misalnya: Teknik Industri`), menjadikannya ideal untuk menu, glosarium, atau struktur kategori-subkategori.
<img width="1918" height="1015" alt="Membuat Description List" src="https://github.com/user-attachments/assets/7f02c9d7-de18-4224-8c3f-ecf3b3f7fe28" />

### Tahap 4: Membuat Tabel Mengatur Margin dan Padding
***Deskripsi:**
Tujuan dari materi ini adalah untuk mengajarkan bagaimana CSS dapat digunakan untuk mentransformasi formulir HTML yang fungsional menjadi elemen antarmuka pengguna (UI) yang estetis, terstruktur, dan profesional, meningkatkan interaksi pengguna secara keseluruhan & Materi ini mengajarkan cara menggunakan elemen HTML (`<table>, <tr>, <th>, <td>`) untuk membuat struktur data yang rapi dan mudah dibaca. Tabel sangat penting untuk menyajikan data yang memiliki hubungan kategorikal, seperti daftar mata kuliah atau data pelanggan.
<img width="1918" height="1012" alt="Membuat Tabel" src="https://github.com/user-attachments/assets/83328482-47b5-4391-b3e8-8f1f6ed30a4e" />

### Tahap 5: Menggabungkan Sel Data
***Deskripsi:**
Materi ini mengajarkan integrasi antara Struktur HTML dan Desain CSS untuk menciptakan formulir yang tidak hanya berfungsi (mengumpulkan data) tetapi juga estetis dan user-friendly & Materi ini mencakup cara membuat tabel HTML dasar (`<table>, <tr>, <th>, <td>`) untuk menyajikan data terstruktur, dan dilanjutkan dengan teknik lanjutan seperti menggabungkan sel untuk mengoptimalkan presentasi data.
<img width="1916" height="1007" alt="Menggabungkan Sel Data" src="https://github.com/user-attachments/assets/ee611698-0846-475e-af88-1464fff4ef86" />

### Tahap 6: Membuat Form
***Deskripsi:**
Materi ini mengajarkan bahwa meskipun HTML menyediakan struktur (`<form>, <input>`), CSS adalah kunci untuk mentransformasi formulir menjadi antarmuka pengguna (UI) yang estetis & mudah digunakan
<img width="1918" height="1010" alt="Membuat Form" src="https://github.com/user-attachments/assets/c88f7ac1-9f6b-412f-b0ad-ae2606f2a8e0" />

### Tahap 7: Menambahkan Style pada Form
***Deskripsi:**
Materi ini mengajarkan bahwa meskipun struktur HTML (`<form>, <input>`) menangani fungsionalitas, CSS adalah komponen krusial yang mengubah formulir menjadi Antarmuka Pengguna (UI) yang menarik, modern, dan mudah digunakan.
<img width="1918" height="1017" alt="Menabahkan Style pada Form" src="https://github.com/user-attachments/assets/9223f02d-070b-400d-92a7-919f03ef9a31" />

### Tahap 8: hasilnya sebelum & sesudah
***Deskripsi:**
Materi ini mengajarkan Anda untuk membuat website yang tidak hanya berfungsi, tetapi juga terlihat bagus dan mudah digunakan oleh siapa saja. Anda bisa menyusun informasi dengan rapi (Tabel & List) dan membuat pengguna betah berinteraksi (Formulir dengan desain keren).
<img width="1917" height="1015" alt="Jadi" src="https://github.com/user-attachments/assets/489af364-6ecc-46cf-8332-6c5b5472f314" />
<img width="1917" height="1013" alt="hasil" src="https://github.com/user-attachments/assets/90fb70ae-86ca-403e-afc7-62d197dcedfd" />

### Kode Pemrograman
```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Pelanggan Keren</title>
    <style>
        /* CSS untuk tampilan yang bagus dan menarik */
        body { 
            font-family: Arial, sans-serif; 
            background-color: #f4f7f6; 
            margin: 20px; 
            padding: 0;
            display: flex; /* Menggunakan Flexbox untuk pusatkan konten */
            flex-direction: column;
            align-items: center;
        }
        h1 { 
            color: #333; 
            border-bottom: 2px solid #007bff; 
            padding-bottom: 10px; 
            margin-bottom: 20px; 
            width: 100%;
            max-width: 400px;
            text-align: center;
        }
        
        form { 
            max-width: 400px; /* Lebar form sesuai gambar */
            width: 90%;
            padding: 20px; 
            background: #fff; 
            border-radius: 8px; 
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1); 
            margin-bottom: 30px;
        }
        fieldset { 
            border: 1px solid #ddd; 
            padding: 20px; 
            border-radius: 6px; 
        }
        legend { 
            font-size: 1.2em; 
            font-weight: bold; 
            color: #007bff; 
            padding: 0 10px; 
        }

        /* Tata Letak Input */
        form p { 
            display: flex; 
            flex-direction: column; /* Ubah menjadi kolom agar label di atas input */
            margin-bottom: 15px; 
        }

        form p > label { 
            display: block; 
            width: 100%;
            color: #555; 
            font-weight: bold; 
            margin-bottom: 5px; /* Jarak antara label dan input */
        }

        /* Gaya untuk input teks dan select */
        form input[type="text"], form textarea, form select { 
            padding: 10px; 
            border: 1px solid #197a43; /* Warna border sesuai gambar */
            border-radius: 4px;
            /* Penyesuaian lebar untuk semua field */
            width: 100%; 
            box-sizing: border-box; /* Penting agar padding tidak menambah lebar */
        }
        form textarea {
            resize: vertical;
        }

        /* Tata Letak Jenis Kelamin */
        .radio-group {
            display: flex;
            gap: 15px;
            margin-top: 5px;
        }

        /* Tombol Login */
        form input[type="submit"] {
            border: 1px solid #197a43;
            background-color: #197a43;
            color: #ffffff;
            font-weight: bold;
            padding: 8px 20px;
            border-radius: 4px;
            cursor: pointer;
            transition: background-color 0.3s;
            margin-top: 15px;
        }
        form input[type="submit"]:hover {
            background-color: #116834;
        }

        /* Gaya Bagian Hasil */
        #hasilContainer {
            max-width: 400px;
            width: 90%;
            padding: 20px;
            background: #e6ffe6; 
            border: 1px solid #197a43;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            text-align: left;
            margin-top: 20px;
            display: none; 
        }

        #hasilContainer h3 {
            color: #197a43;
            margin-top: 0;
            border-bottom: 1px solid #197a43;
            padding-bottom: 10px;
        }

        #hasilContainer p {
            margin: 5px 0;
            line-height: 1.5;
        }
        #hasilContainer strong {
            display: inline-block;
            width: 130px;
        }

    </style>
</head>
<body>
<header>
    <h1>Membuat Form</h1>
</header>

<form id="dataPelangganForm" action="proses.php" method="post">
    <fieldset>
        <legend>Data Mahasiswa</legend>
        <p>
            <label for="nama">Nama</label>
            <input type="text" id="nama" name="nama"> 
        </p>
        <p>
            <label for="alamat">Alamat</label>
            <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
        </p>
        
        <p>
            <label for="fakultas">Fakultas</label>
            <select id="fakultas" name="fakultas">
                <option value="Teknik">Teknik</option>
            </select>
        </p>
        
        <p>
            <label for="program_studi">Program Studi</label>
            <select id="program_studi" name="program_studi">
                <option value="Teknik Informatika">Teknik Informatika</option>
                <option value="Teknik Industri">Teknik Industri</option>
                <option value="Teknik Lingkungan">Teknik Lingkungan</option>
                <option value="Teknik Elektro">Teknik Elektro</option>
                <option value="Ilmu Komunikasi">Ilmu Komunikasi</option>
            </select>
        </p>
        
        <p>
            <label>Jenis Kelamin</label>
            <span class="radio-group">
                <input id="jk_l" type="radio" name="kelamin" value="Laki-laki" checked /><label
                for="jk_l">Laki-laki</label>
                <input id="jk_p" type="radio" name="kelamin" value="Perempuan" /><label
                for="jk_p">Perempuan</label>
            </span>
        </p>
        <p><input type="submit" value="Login"></p>
    </fieldset>
</form>

<div id="hasilContainer">
    <h3>Data Berhasil Diterima! ✅</h3>
    <p><strong>Nama:</strong> <span id="outNama"></span></p>
    <p><strong>Alamat:</strong> <span id="outAlamat"></span></p>
    <p><strong>Fakultas:</strong> <span id="outFakultas"></span></p>
    <p><strong>Program Studi:</strong> <span id="outProdi"></span></p>
    <p><strong>Jenis Kelamin:</strong> <span id="outKelamin"></span></p>
</div>

<script>
    // 1. Ambil elemen form
    const form = document.getElementById('dataPelangganForm');
    const hasilContainer = document.getElementById('hasilContainer');

    // 2. Tambahkan event listener untuk menangani submit form
    form.addEventListener('submit', function(event) {
        // Hentikan aksi default form
        event.preventDefault(); 

        // 3. Ambil nilai dari input form yang sudah ada
        const nama = document.getElementById('nama').value;
        const alamat = document.getElementById('alamat').value;
        const kelaminRadio = document.querySelector('input[name="kelamin"]:checked');
        const kelamin = kelaminRadio ? kelaminRadio.value : 'Tidak Dipilih';
        
        // 3. Ambil nilai dari input baru (Select/Dropdown)
        const fakultas = document.getElementById('fakultas').value;
        const prodi = document.getElementById('program_studi').value;

        // 4. Tampilkan data ke dalam elemen hasil (Diperbarui)
        document.getElementById('outNama').textContent = nama;
        document.getElementById('outAlamat').textContent = alamat;
        document.getElementById('outFakultas').textContent = fakultas; // Output Fakultas
        document.getElementById('outProdi').textContent = prodi;       // Output Program Studi
        document.getElementById('outKelamin').textContent = kelamin;

        // 5. Tampilkan kontainer hasil
        hasilContainer.style.display = 'block';

        // Opsional: Gulir ke bagian hasil
        hasilContainer.scrollIntoView({ behavior: 'smooth' });
    });
</script>

</body>
</html>


