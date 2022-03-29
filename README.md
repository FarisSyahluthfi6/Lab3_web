# Lab3_web

| Nama= Faris Syahluthfi      | 
|-----------------------------|
| NIM= 312010034              |
|=============================| 
| Kelas= TI.20.A.1            |
|-----------------------------|
| Matkul= Pemrograman Web     |
|=============================|

## 1. Membuat Ordered List
![Membuat_List](screenshot/Membuat_List.PNG)

Ini adalah sebuah hasil dari texs Kodingan tag membuat Ordered List<p>
 Dan Ini Adalah program codingan dari tag Ordered List:

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body bgcolor="Gainsboro">
<header>
<h1><center>Membuat List Mata Kuliah</center></h1>

<section id="order-list">
    <h2>Nama Mata Kuliah</h2>
    <ol>
    <li>Pemrograman Web</li>
    <li>Sistem Basis Data</li>
    <li>Bisnis Elektronik</li>
    <li>Matematika Dsikrit</li>
    <li>Algoritma</li>
    </ol>
    </section>

</header>
</body>
</html>
```

## 2. Membuat Unorderd List
![Unorderd_List](screenshot/order_list.PNG)

Ini adalah sebuah hasil dari texs Kodingan tag membuat Unorderd List<p>
 Dan Ini Adalah program codingan dari tag membuat Unorderd List:

 ```html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body bgcolor="Gainsboro">
<header>
<h1><center>Membuat List Mata Kuliah</center></h1>

<section id="order-list">
    <h2>Nama Mata Kuliah</h2>
    <ol>
    <li>Pemrograman Web</li>
    <li>Sistem Basis Data</li>
    <li>Bisnis Elektronik</li>
    <li>Matematika Dsikrit</li>
    <li>Algoritma</li>
    </ol>
    </section>

    <section id="unorder-list">
        <h2>Unordered List</h2>
        <li>Pemrograman Web</li>
    <li>Sistem Basis Data</li>
    <li>Bisnis Elektronik</li>
    <li>Matematika Dsikrit</li>
    <li>Algoritma</li>
        </ul>
        </section>

</header>
</body>
</html>
 ```


## 3. Membuat Tabel
![Tabel](screenshot/Membuat_Tabel.PNG)

Ini adalah sebuah hasil dari texs Kodingan tag membuat Tabel<p>
 Dan Ini Adalah program codingan dari tag membuat Tabel:

## Contoh Kode
```Html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body bgcolor="grey">
<header>
<h1><center>Membuat Table</center></h1>
</header>
<p><b>DATA MAHASISWA UNIVERSITAS PELITA BANGSA</b></p>

<table border="1" cellpadding="6" cellspacing="0">
    <thead>
    <tr style="background-color: rgb(151, 35, 35);">
    <th>No.</th>
    <th>Nama</th>
    <th>Fakultas</th>
    <th>Program Studi</th>
    <th>Kelas</th>
    </tr>
    </thead>
    <tbody>
    <tr>
    <td>1.</td>
    <td>Faris</td>
    <td rowspan="3">Teknik</td>
    <td>Teknik Informatika</td>
    <td>Reguler Pagi</td>
    </tr>

    <tr>
    <td>2.</td>
    <td>Farhan</td>
    <td>Teknik Industri</td>
    <td>Reguler malam</td>
    </tr>

    <tr>
    <td>3.</td>
    <td>Farel</td>
    <td>Teknik Lingkungan</td>
    <td>Wekend</td>
    </tr>

    <tr>
        <td>4.</td>
        <td>Anisa</td>
        <td rowspan="3">Managemen</td>
        <td>Managemen Akuntansi</td>
        <td>Reguler Pagi</td>
        </tr>
    
        <tr>
        <td>5.</td>
        <td>Ayu</td>
        <td>Managemen Perkantoran</td>
        <td>Reguler malam</td>
        </tr>
    
        <tr>
        <td>6.</td>
        <td>Amel</td>
        <td>Managemen Bisnis</td>
        <td>Wekend</td>
        </tr>


    </tbody>
    </table>

</body>
</html>
```

## 4. Membuat Form
![Membuat_Form](screenshot/Membuat_Form.PNG)

Ini adalah sebuah hasil dari texs Kodingan tag Membuat Form<p>
 Dan Ini Adalah program codingan dari tag Membuat Form:

 ```html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body bgcolor="brown">
    <style>
        form p > label {
        display: inline-block;
        width: 100px;
        }

        h1 {
	    color: #f0e9ee;
        font-size: 20px;
        text-align: center;
        }

        label {
	    color: #f0e9ee;
        font-size: 15px;
        text-align: center;
        }

        p1 {
	    color: #f0e9ee;
        font-size: 20px;
        text-align: center;
        }

        legend {
	    color: #f0e9ee;
        font-size: 20px;
        text-align: center;
        }

        form input[type="text"], form textarea {
        border: 1px solid #197a43;
        }

        form input[type="submit"] {
        border: 1px solid #197a43;
        background-color: #197a43;
        color: #ffffff;
        font-weight: bold;
        padding: 5px 15px;
        }

        </style>

        
<header>
<h1><center>PENDAFTARAN MAHASISWA BARU UNIVERSITAS PELITA BANGSA</center></h1>

<form action="proses.php" method="post">
    <fieldset>
    <legend><center><b>Registrasi Mahasiswa</b></center></legend>
    <p1><center><i>SILAHKAN ISI DATA DISINI...</i></center></p1>

    <p>
        <label for="nama">Nama:</label>
        <input type="text" id="nama" name="nama">
    </p>

    <p>
        <label for="Tempat_Lahir">Tempat Lahir:</label>
        <input type="text" id="tempat_lahir" name="tempat_lahir">
    </p>

    <p>
        <label for="tgl_lahir">Tanggal Lahir:</label>
        <input type="date" name="tgl_lahir" required><br>
    </p>

    <p>
        <label for="alamat">Alamat:</label>
        <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
    </p>

    <p>
        <label>Jenis Kelamin:</label>
        <input id="jk_l" type="radio" name="kelamin" value="L" /><label
        for="jk_l">Laki-laki</label>
        <input id="jk_p" type="radio" name="kelamin" value="P" /><label
        for="jk_p">Perempuan</label>
    </p>

    <p>
        
            <label>Agama:</label>
            <select name="agama">
                <option value="islam">Islam</option>
                <option value="kristen">Kristen</option>
                <option value="hindu">Hindu</option>
                <option value="budha">Budha</option>
            </select>
        
    </p>

<p><input type="submit" value="DAFTAR"></p>
</fieldset>
</form>

</header>
</body>
</html>

```

