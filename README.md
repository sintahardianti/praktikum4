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

### > Untuk melakukan perulangan input yang ingin digunakan untuk menambahakan data atau tidak (y/t)

```
tanya = input('Tambahkan Data (y/t) ?')
    if (tanya == 't'):
        stop = True
```

### > Umtuk tampilan datanya 

```
print("==================================================================")
print("| No |    Nama      |  NIM  | Tugas |  UTS  |  UAS  |  Akhir |")
print("==================================================================")

i = 0

for nilai in data:
    i += 1
    print("| {no}  | {nama:12s} | {nim:5s} | {tugas:5d} | {uts:5d} | {uas:5d} | {akhir:6.2f} |".format(no=i, nama=nilai[0], nim=nilai[1], tugas=nilai[2],uts=nilai[3],uas=nilai[4],akhir=nilai[5]))

print("==================================================================")
```

### > Hasilnya seperti ini

![hasil praktikum 4](https://user-images.githubusercontent.com/115516473/202904298-32c45cf8-c3f4-4b7d-a3a5-049054b0d9ba.png)

### > Flowchartnya 

<img width="227" alt="flow" src="https://user-images.githubusercontent.com/115516473/202904337-6dd62f02-fab8-4991-9335-d2fce04fbba3.png">

