# 🌐 Basic JavaScript ES6

| Objectives                                  | Key Result                                                     | Time Goal |
| ------------------------------------------- | -------------------------------------------------------------- | --------- |
| **1) Memahami Dasar JavaScript**            | 1.1 Memahami fungsi JavaScript dalam pengembangan website      | 5 menit   |
|                                             | 1.2 Membuat file `script.js` dan menghubungkannya ke HTML      | 5 menit   |
|                                             | 1.3 Menjalankan JavaScript pertama menggunakan `console.log()` | 5 menit   |
| **2) Memahami Variabel dan Tipe Data**      | 2.1 Menggunakan `let`, `const`, dan memahami perbedaannya      | 10 menit  |
|                                             | 2.2 Mengenal tipe data String, Number, Boolean, Array, Object  | 15 menit  |
|                                             | 2.3 Mencoba operasi aritmatika dan manipulasi string           | 10 menit  |
| **3) Menguasai Percabangan dan Perulangan** | 3.1 Menggunakan `if`, `else if`, dan `else`                    | 15 menit  |
|                                             | 3.2 Menggunakan `switch case`                                  | 10 menit  |
|                                             | 3.3 Menggunakan `for`, `while`, dan `for...of`                 | 20 menit  |
| **4) Menguasai Function dan ES6 Modern**    | 4.1 Membuat Function biasa                                     | 10 menit  |
|                                             | 4.2 Menggunakan Arrow Function                                 | 15 menit  |
|                                             | 4.3 Menggunakan Template Literal                               | 10 menit  |
|                                             | 4.4 Menggunakan Destructuring Array dan Object                 | 20 menit  |
|                                             | 4.5 Menggunakan Spread Operator                                | 15 menit  |
| **5) Interaksi dengan DOM**                 | 5.1 Mengambil elemen menggunakan `querySelector()`             | 15 menit  |
|                                             | 5.2 Mengubah isi HTML menggunakan JavaScript                   | 15 menit  |
|                                             | 5.3 Menambahkan Event Listener pada tombol                     | 20 menit  |
|                                             | 5.4 Membuat interaksi sederhana pada halaman web               | 20 menit  |
| **6) Implementasi Nyata JavaScript**        | 6.1 Membuat aplikasi To-Do List sederhana                      | 1-2 jam   |

## **Total Estimasi Waktu: ± 4 Jam**

## 1) Memahami Dasar JavaScript

### 1.1 Memahami fungsi JavaScript dalam pengembangan website

JavaScript digunakan untuk membuat halaman web menjadi interaktif, seperti validasi form, animasi, manipulasi elemen HTML, dan komunikasi dengan server.

Referensi:

* MDN JavaScript Guide
* JavaScript.info

### 1.2 Membuat file script.js dan menghubungkannya ke HTML

```html
<script src="script.js"></script>
```

### 1.3 Menjalankan JavaScript pertama

```javascript
console.log("Hello World!");
```

---

## 2) Memahami Variabel dan Tipe Data

### 2.1 Menggunakan let dan const

```javascript
let nama = "Mustafa";
const kampus = "Universitas";
```

### 2.2 Mengenal tipe data dasar

```javascript
let umur = 20;
let mahasiswa = true;
let hobi = ["Coding", "Gaming"];
```

### 2.3 Operasi sederhana

```javascript
let a = 10;
let b = 5;

console.log(a + b);
```

---

## 3) Menguasai Percabangan dan Perulangan

### 3.1 Percabangan if-else

```javascript
let nilai = 80;

if (nilai >= 75) {
    console.log("Lulus");
} else {
    console.log("Tidak Lulus");
}
```

### 3.2 Switch Case

```javascript
let hari = "Senin";

switch (hari) {
    case "Senin":
        console.log("Hari Kerja");
        break;
}
```

### 3.3 Perulangan For

```javascript
for (let i = 1; i <= 5; i++) {
    console.log(i);
}
```

---

## 4) Menguasai Function dan ES6 Modern

### 4.1 Function Dasar

```javascript
function salam() {
    console.log("Halo");
}
```

### 4.2 Arrow Function

```javascript
const salam = () => {
    console.log("Halo");
};
```

### 4.3 Template Literal

```javascript
const nama = "Mustafal";

console.log(`Halo ${nama}`);
```

### 4.4 Destructuring

```javascript
const mahasiswa = {
    nama: "Mustafal",
    umur: 20
};

const { nama, umur } = mahasiswa;
```

---

## 5) Interaksi dengan DOM

### 5.1 Mengambil Elemen

```javascript
const judul = document.querySelector("h1");
```

### 5.2 Mengubah Isi Elemen

```javascript
judul.textContent = "Belajar JavaScript";
```

### 5.3 Event Listener

```javascript
const tombol = document.querySelector("button");

tombol.addEventListener("click", () => {
    alert("Tombol ditekan");
});
```

---

## 6) Implementasi Nyata JavaScript

### 6.1 Membuat To-Do List Sederhana

Fitur:

* Menambah tugas
* Menghapus tugas
* Menandai tugas selesai
* Menyimpan data sementara selama halaman aktif

Target hasil akhir:

* Memahami penggunaan DOM
* Memahami Event Listener
* Memahami Array dan Function
* Menggabungkan HTML, CSS, dan JavaScript dalam satu proyek
