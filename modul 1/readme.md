# Modul 1 — Running Program di Golang & I/O, Tipe Data, Variabel

## Tujuan Pembelajaran

Setelah menyelesaikan modul ini, peserta mampu:

- Mengenal bahasa pemrograman Go (Golang)

- Menulis program Go sederhana

- Menjalankan program Go menggunakan perintah `go run` dan `go build`

---

## Materi

### Apa itu Go?

Go (atau Golang) adalah bahasa pemrograman open-source yang:

- **Cepat** dan efisien seperti C/C++

- **Mudah dipahami** seperti Python

- Banyak dipakai untuk aplikasi backend, sistem, hingga cloud services

### Struktur Dasar Program Go

- Setiap file Go diawali dengan `package main`

- Import `fmt` yang biasa di sebut format untuk input output `import "fmt"`

- Fungsi utama adalah `func main()`

- Untuk menampilkan output, gunakan `fmt.Println() atau fmt.Printf() atau fmt.Print()`

### Contoh Program

Buat file bernama `hello.go`:

```go
package main

import "fmt"

func main() {

    fmt.Println("Hello, World")

}
```

- `package main` adalah deklarasi bahwa file/code tersebut bagian dari main, jika package main memiliki `func main` maka dia akan executable
- `import` membawa library ke dalam source file supaya dapat digunakan
- `fmt` standard library Go yang menyediakan fungsi-fungsi untuk formatting dan I/O, termasuk output ke terminal.
- `func main` fungsi utama di golang yang akan diexecute/dijalankan
- `fmt.Println()` fungsi dari library fmt/formatting untuk output


## Soal Latihan
### 1. Perkenalan Diri
Buatlah program Go untuk memperkenalkan diri kalian dengan struktur:
- Nama
- NIM
- Kenapa memilih informatika
```go
package main

import "fmt"

func main() {

    //nama
    //NIM
    //kenapa memilih informatika

}
```

### 2. Harapan di masa depan
Buatlah program Go untuk mencetak kartu list harapan masa depan 1-5.
```go
package main

import "fmt"

func main() {

    //==========================
    //|1. sisen depan immo     |
    //|2. sisen depan radiant  |
    //|3. sisen depan conqueror|
    //|4. sisen depan when yah |
    //|5. sisen depan waras    |
    //==========================


}
```