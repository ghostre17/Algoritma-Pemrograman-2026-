# Modul 2
## I/O pada Golang

*Input*

```go
fmt.Print() //Akan mengeluarkan ouput tanpa enter/tidak pindah line
fmt.Println() //Akan mengeluarkan ouput dengan enter/pindah line
fmt.Printf() //Akan mengeluarkan output dengan format yang dapat dimasuki oleh variabel
```

### Contoh implementasi:

*fmt.Print()*
```go
fmt.Print("Hello World")
fmt.Print("Hello World")
// Output
Hello WorldHello World //Line tidak berpindah/enter
```

*fmt.Println()*

```go
fmt.Println("Hello World")
fmt.Println("Hello World")
// Output
Hello World
Hello World //Line berpindah/enter
```

*fmt.Printf()*

```go
greet <- "Hello World"
fmt.Printf("%s", greet)
fmt.Printf("%s", greet)
```

*format fmt.Printf():*
- %v general (bisa semua tipe data)
- %t boolean (true/false)
- %s string  ("Hello World"/suatu kalimat string)
- %d integer (1, 2, 3)
- %f float   (17.5)
*Output*
```go
fmt.Scan() //Memasukkan nilai ke dalam variabel tanpa enter
fmt.Scanln() //Memasukkan nilai ke dalam variabel dengan enter
```

### Contoh implementasi:

```go
angka : integer
fmt.Scan(&angka) //Terminal code editor akan meminta input dari user
```

```go
angka : integer
fmt.Scanln(&angka) //Terminal code editor akan meminta input dari user
```

## Variabel & Tipe Data

Variabel adalah penyimpanan data sesuai dengan tipe data yang telah ditentukan

*Tipe Data:*
- String (Kumpulan kata)
- Integer (Bilangan bulat)
- Boolean (True or False)
- Float (Bilangan desimal)
- Char (Simbol)

Variabel dapat dioperasikan sesuai tipe datanya, seperti `string` yang dapat ditambahkan dengan sesama `string` yang akan menginputkan sebuah string.

*String*

```go
"Hello" + "Hello" = "HelloHello"
```

*int*

```go
1 + 1 = 2
```

*Float*

```go
1.1 + 1.1 = 2.2
```

*Contoh:*

```go
//Deklarasi tanpa assign
var angka int
var huruf rune
var kata string

//Deklrasi langsung assign
var angka int = 3
var huruf rune = 'A' //Rune adalah char di golang
var kata string = "Udah immo blom?"

//Deklarasi langsung assign tanpa tipe data (:=) tetapi nilai harus langsung dimasukkan
angka := 3
huruf := 'A'
kata := "Udah immo blom?"
```
