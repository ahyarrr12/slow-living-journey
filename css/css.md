# 🎨 Basic CSS

| Objectives                     | Key Result                                         | Time Goal |
| ------------------------------ | -------------------------------------------------- | --------- |
| **1) Memahami Dasar CSS**      | 1.1 Memahami fungsi CSS dalam mempercantik website | 5 menit   |
|                                | 1.2 Membuat file `style.css`                       | 5 menit   |
|                                | 1.3 Menghubungkan CSS ke HTML                      | 5 menit   |
| **2) Menguasai Selector CSS**  | 2.1 Menggunakan Element Selector                   | 10 menit  |
|                                | 2.2 Menggunakan Class Selector                     | 10 menit  |
|                                | 2.3 Menggunakan ID Selector                        | 10 menit  |
| **3) Menguasai Styling Dasar** | 3.1 Mengubah warna teks dan background             | 10 menit  |
|                                | 3.2 Mengatur ukuran dan jenis font                 | 15 menit  |
|                                | 3.3 Mengatur text alignment                        | 10 menit  |
| **4) Menguasai Box Model**     | 4.1 Menggunakan margin                             | 10 menit  |
|                                | 4.2 Menggunakan padding                            | 10 menit  |
|                                | 4.3 Menggunakan border                             | 10 menit  |
| **5) Menguasai Layout CSS**    | 5.1 Menggunakan Flexbox                            | 20 menit  |
|                                | 5.2 Mengatur posisi elemen                         | 15 menit  |
|                                | 5.3 Membuat Navigation Bar                         | 20 menit  |
| **6) Responsive Design**       | 6.1 Menggunakan Media Query                        | 20 menit  |
|                                | 6.2 Menyesuaikan tampilan mobile                   | 20 menit  |
| **7) Implementasi CSS**        | 7.1 Membuat styling website profil pribadi         | 1 jam     |

**Total Estimasi Waktu: ± 4 Jam**

---

# 1) Memahami Dasar CSS

### 1.1 Fungsi CSS

CSS (Cascading Style Sheets) digunakan untuk mengatur tampilan halaman web.

### 1.2 Membuat File CSS

```text
style.css
```

### 1.3 Menghubungkan ke HTML

```html
<link rel="stylesheet" href="style.css">
```

---

# 2) Menguasai Selector CSS

### Element Selector

```css
h1 {
  color: blue;
}
```

### Class Selector

```css
.judul {
  color: red;
}
```

### ID Selector

```css
#header {
  background-color: gray;
}
```

---

# 3) Menguasai Styling Dasar

### Warna

```css
body {
  background-color: #f5f5f5;
}
```

### Font

```css
p {
  font-size: 18px;
}
```

---

# 4) Menguasai Box Model

### Margin dan Padding

```css
.card {
  margin: 20px;
  padding: 15px;
}
```

### Border

```css
.card {
  border: 1px solid black;
}
```

---

# 5) Menguasai Layout CSS

### Flexbox

```css
.container {
  display: flex;
  gap: 10px;
}
```

### Navigation Bar

```css
nav {
  display: flex;
  justify-content: space-between;
}
```

---

# 6) Responsive Design

### Media Query

```css
@media (max-width: 768px) {
  .container {
    flex-direction: column;
  }
}
```

---

# 7) Implementasi CSS

Melakukan styling pada website profil pribadi yang dibuat pada materi HTML dengan menambahkan:

* Warna
* Font
* Layout
* Navigation Bar
* Responsive Design

Target: Website profil memiliki tampilan yang rapi, modern, dan responsif.
