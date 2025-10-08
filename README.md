# Lab3Web_Membuat_Form
Nama: Doni Alvero <p>
Nim: 312410663 <P>
Kelas: TI.24.A.5 <P>
Jurusan: Teknik Informatika <p>
Mata Kuliah: Pemograman Web 1 <p>

### Tahap 1: Membuat Ordered List
Halaman ini adalah contoh dasar dari materi pembelajaran HTML Lanjutan yang berfokus pada struktur dan penamaan daftar berurutan.
<img width="1918" height="1017" alt="Membuat Ordered List" src="https://github.com/user-attachments/assets/5c0eb2c1-2731-44d2-9edf-e5276126cbb1" />

### Tahap 2: Membuat Unorderd List
Halaman ini menyajikan contoh visual yang membandingkan dua elemen daftar dasar dalam HTML '<ol>' yang memberikan penomoran (berurutan) dan '<ul>' yang menggunakan simbol bullet (tidak berurutan). Kontennya menunjukkan contoh mata kuliah.
<img width="1912" height="1010" alt="Membuat Unorderd List" src="https://github.com/user-attachments/assets/cade8ec8-f724-4174-b712-819fdca83ed6" />



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


