## Tugas Praktikum 5

### Nama : Sinta Hardianti Wijaya

### NIM : 312210342

### Kelas : TI. 22. A3

## Soal 

![soal praktikum 5](https://user-images.githubusercontent.com/115516473/202902959-c3fcb229-46b2-4716-96ff-c8cf6cf12f64.png)

### > Gunakan While untuk memasukkan data secara berulang dan masukkan ```input()```

```
data = []
stop = False

while(not stop):
    nama = input("Nama : ")
    nim = input("NIM : ")
    tugas = int(input("Nilai Tugas : "))
    uts = int(input("Nilai UTS : "))
    uas = int(input("Nilai UAS : "))
    akhir = (tugas * 30/100) + (uts * 35/100) + (uas * 35/100)
```

### > Gunakan perintah ```.append()``` untuk menambahkan elemen ke dalam list 

```
data.append([nama,nim,tugas,uts,uas,int(akhir)])
```

### >
