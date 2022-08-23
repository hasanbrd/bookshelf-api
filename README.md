# Bookshelf API

Bookshelf API merupakan proyek akhir dari kelas Belajar Membuat Aplikasi Back-End untuk Pemula dari Dicoding.
 

## Cara Menjalankan

Proyek ini memerlukan [npm](https://treehouse.github.io/installation-guides/mac/node-mac.html) untuk menjalankannya.

```bash
npm run start
```

## Daftar API

```javascript
1. addBook
Method : POST
URL : /books

2. getAllBooks
Method : GET
URL: /books

3. getBookById
Method : GET
URL: /books/{bookId}

4. editBookById
Method : PUT
URL: /books/{bookId}

5. deleteBookById
Method : DELETE
URL: /books/{bookId}
```

## NB
- Menggunakan port:8000
- Menggunakan framework Hapi
- Sudah menerapkan CORS
- Sudah menggunakan eslint (airbnb)
