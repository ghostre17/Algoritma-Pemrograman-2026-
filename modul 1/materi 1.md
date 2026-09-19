# 🐹 Modul 1 — Running Program di Golang

## 🎯 Tujuan Pembelajaran

Setelah menyelesaikan modul ini, peserta mampu:

- Mengenal bahasa pemrograman Go (Golang)
- Menulis program Go sederhana
- Menjalankan program Go menggunakan perintah `go run` dan `go build`

---

## 📘 Materi

### Apa itu Go?

Go (atau Golang) adalah bahasa pemrograman open-source yang:

- **Cepat** dan efisien seperti C/C++ ⚡
- **Mudah dipahami** seperti Python ✅
- Banyak dipakai untuk aplikasi backend, sistem, hingga cloud services ☁️

### Struktur Dasar Program Go

- Setiap file Go diawali dengan `package main`
- Fungsi utama adalah `func main()`
- Untuk menampilkan output, gunakan `fmt.Println()`

### Contoh Program

Buat file bernama `hello.go`:

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World! from Go 🚀")
}
```

