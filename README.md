# Lab3web
Nama : Tiara Putri

NIM  : 312210064

Kelas : TI.22.A.1

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Instruksi Praktikum|[Click Here](#Instruksi-Praktikum)|
|2|Praktikum|[Click Here](#praktikum)|
|3|Pertanyaan dan Tugas|[Click Here](#Pertanyaan-dan-Tugas)|

## Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama Lab3Web
3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
4. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org

## Praktikum
**1. Membuat Ordered List & Undordered List**

```
<section id="order-list">
  <h2>Ordered List</h2>
  <ol>
    <li>Pemrograman Web</li>
    <li>Sistem Informasi</li>
    <li>Basis Data 2</li>
  </ol>
</section>
```
![1](https://github.com/tiaraputriiiiii/Lab3web/assets/115775237/2adc582b-3357-4a31-91e7-eee115eb3f9d)

```
<section id="unorder-list">
  <h2>Unordered List</h2>
  <ul type="square">
    <li>Jaringan Komputer</li>
    <li>Struktur Data</li>
    <li>Algoritma &amp; Pemrograman</li>
  </ul>
</section>
```

![2](https://github.com/tiaraputriiiiii/Lab3web/assets/115775237/4984849f-e722-47cb-a419-d0ccbb7be046)

**2. Membuat Description List**

```
<section id="unorder-list">
  <h2>Description List</h2>
  <dl>
    <dt>Fakultas Teknik</dt>
    <dd>Teknik Industri</dd>
    <dd>Teknik Informatika</dd>
    <dd>Teknik Lingkungan</dd>
    <dt>Fakultas Ekonomi dan Bisnis</dt>
    <dd>Akuntansi</dd>
    <dd>Manajemen</dd>
    <dd>Bisnis Digital</dd>
  </dl>
</section>
```

![3](https://github.com/tiaraputriiiiii/Lab3web/assets/115775237/3288f74f-b292-4317-bcbe-424735dfb2d5)

**3. Membuat Table**

```
<table border="1" cellpadding="4" cellspacing="0">
  <thead>
    <tr>
      <th>No.</th>
      <th>Fakultas</th>
      <th>Program Studi</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1.</td>
      <td>Teknik</td>
      <td>Teknik Informatika</td>
    </tr>
    <tr>
      <td>2.</td>
      <td>Teknik</td>
      <td>Teknik Industri</td>
    </tr>
    <tr>
      <td>3.</td>
      <td>Teknik</td>
      <td>Teknik Lingkungan</td>
    </tr>
  </tbody>
</table>
```

![4](https://github.com/tiaraputriiiiii/Lab3web/assets/115775237/3386d5b8-55d0-4025-94d5-77554704db66)

**4. Membuat Margin dan Padding**

```
<table border="1" cellpadding="4" cellspacing="0"></table>
```

![5](https://github.com/tiaraputriiiiii/Lab3web/assets/115775237/424676e7-ada2-4af6-af50-ee5e182bfac8)

**5. Menggabungkan Sel Data**

```
<tr>
  <td>1.</td>
  <td rowspan="3">Teknik</td>
  <td>Teknik Informatika</td>
</tr>
```

![6](https://github.com/tiaraputriiiiii/Lab3web/assets/115775237/e11021a8-469e-4d4f-ab3b-d79cf0dab3d2)

**6. Membuat Form**

```
<form action="proses.php" method="post">
  <fieldset>
    <legend>Data Pelanggan</legend>
    <p>
      <label for="nama">Nama</label>
      <input type="text" id="nama" name="nama" />
    </p>
    <p>
      <label for="alamat">Alamat</label>
      <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
    </p>
    <p>
      <label>Jenis Kelamin</label>
      <input id="jk_l" type="radio" name="kelamin" value="L" /><label for="jk_l"
        >Laki-laki</label
      >
      <input id="jk_p" type="radio" name="kelamin" value="P" /><label
        qafor="jk_p"
        >Perempuan</label
      >
    </p>
    <p><input type="submit" value="Login" /></p>
  </fieldset>
</form>
```

![7](https://github.com/tiaraputriiiiii/Lab3web/assets/115775237/deca52cc-40c2-4f6f-93bf-0b6b9fc5528e)

**7. Menambahkan Style**

```
<style>
        form p > label {
            display: inline-block;
            width: 100px;
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
```

![8](https://github.com/tiaraputriiiiii/Lab3web/assets/115775237/2b0a768d-b9dd-4e0b-88d9-c4757bd9771c)

**8. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org**

![validasi jigsaw](https://github.com/tiaraputriiiiii/Lab3web/assets/115775237/c219c8be-3c39-4624-84d4-2bd30e3394ae)

## Pertanyaan dan Tugas
1. Buatlah form yang menampilkan **dropdown** menu dan **listbox** dengan *multiple selection.*

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tugas Form Dropdown and Listbox</title>
    <link rel="style3" href="style3.css">
</head>

<body>
    <nav>
        <a href="lab3_list.html">List HTML</a>
        <a href="lab3_tabel.html">Tabel HTML</a>
        <a href="lab3_form.html">Form HTML</a>
        <a href="lab3_tugas.html">Form Dropdown & Listbox</a>
    </nav>
    <header>
        <h1>Form Dropdown & Listbox</h1>
    </header>

    <form class="form_tugas">
        <label for="dropdown">Pilih salah satu buah:</label>
        <select name="dropdown" id="dropdown">
            <option value="apel">Apel</option>
            <option value="jeruk">Jeruk</option>
            <option value="durian">Durian</option>
            <option value="mangga">Mangga</option>
            <option value="semangak">Semangka</option>
        </select>

        <br><br>

        <label for="listbox">Pilih beberapa buah:</label>
        <select name="buah[]" multiple id="listbox">
            <option value="apel">Apel</option>
            <option value="jeruk">Jeruk</option>
            <option value="durian">Durian</option>
            <option value="mangga">Mangga</option>
            <option value="semangka">Semangka</option>
            <option value="kelapa">Kelapa</option>
            <option value="anggur">Anggur</option>
            <option value="melon">Melon</option>
            <option value="pepaya">Pepaya</option>
            <option value="nanas">Nanas</option>
        </select>

        <br>

        <input type="submit" value="Submit" id="input_tugas">
    </form>
</body>

</html>
```

```
body {
  font-family: Tahoma;
}

h1 {
  margin-top: 50px;
  text-align: center;
  color: darkcyan;
}

.tabel {
  margin: 20px auto;
}

form p > label {
  display: inline-block;
  width: 100px;
}

form input[type="text"],
form textarea {
  border: 1px solid #197a43;
}

form input[type="submit"] {
  border: 1px solid #197a43;
  background-color: #197a43;
  color: #ffffff;
  font-weight: bold;
  padding: 5px 15px;
  border-radius: 10px;
}

form input[type="submit"]:hover {
  background-color: #3d9a38;
  cursor: pointer;
}

nav {
  background-color: #4dacd1c5;
  padding: 10px;
  position: fixed;
  top: 0px;
  right: 0px;
  left: 0px;
  text-align: center;
}

nav a {
  color: #fff;
  text-decoration: none;
  padding: 2px 4px;
  font-size: 13px;
}

nav a:hover {
  color: #3399c2;
}

nav a:active {
  color: #7da8b9;
}

/* Style untuk form dropdown & listbox */
.form_tugas {
  max-width: 400px;
  margin: 0 auto;
  padding: 20px;
  border: 1px solid #ccc;
  background-color: #f9f9f9;
  border-radius: 5px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

/* Style untuk label */
.form_tugas label {
  display: block;
  font-weight: bold;
  margin-bottom: 5px;
}

/* Style untuk select dropdown dan listbox */
.form_tugas select {
  width: 100%;
  padding: 10px;
  margin-bottom: 10px;
  border: 1px solid #ccc;
  border-radius: 3px;
}

/* Style untuk tombol Submit */
.form_tugas #input_tugas {
  background-color: #007bff;
  color: #fff;
  padding: 5px 15px;
  border: none;
  border-radius: 6px;
  cursor: pointer;
}

.form_tugas #input_tugas:hover {
  background-color: #4dacd1;
}
```

![9](https://github.com/tiaraputriiiiii/Lab3web/assets/115775237/b5e48faa-8ad0-4d81-8d6a-eaf7119d5427)

## Finish, Terima Kasih

