# Modul 4 - For loop & Nested loop
## Penjelasan Loop
For loop adalah suatu perintah dalam pemrograman yang akan melakukan iterasi/looping/perulangan dengan jumlah yang telah ditentukan atau berdasarkan jumlah elemen dalam suatu data.

*Kegunaan Loop*
- Menghemat penulisan kode yang berulang
- Membuat struktur program lebih bersih
- Mempermudah penelusuran atau iterasi data dari struktur data
- Mengurangi risiko human error seperti salah ketik pengulangan

*Cara Kerja Loop*
Loop mempunyai 3 parameter yaitu:
- Variabel/Value
- Kondisi
- Iterasi

```go
for i := 1; i <=5; i++ {

}
```
- `i := 1` parameter pertama variabel/value
- `i <= 5` parameter kedua kondisi 
- `i++`    parameter ketiga iterasi (i++ akan bertambah 1 seiring iterasi)

Contoh implementasi:
```go
for i := 1; i <= 5; i++ {

    fmt.Println("Hello World") //Kode akan mengiutputkan 5 Hello World berdasarkan parameter kedua yang akan berhenti jika i > 5

}
```

```go
var nama string

for i := 1; i <= 5; i++ {

    fmt.Scan(&Nama) //Kode akan meminta 5 kali input dari user sesuai iterasi

}
```

## Nested Loop
Berbeda dari loop biasa, nested loop adalah looping yang ada didalam looping.

```go
for i := 1; i <=5; i++ {
    for j := 1; j <=5; j++ {

    }
}
```
*Penjelasan singkat*
Looping diluar dipergunakan untuk batch/kolom kebawah dan untuk loop yang didalam untuk baris
```go
***** // yang kesamping loop kedua
*
*
*
*
*
// yang kebawah loop pertama
```
