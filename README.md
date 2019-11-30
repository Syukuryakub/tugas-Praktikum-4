Dibawah ini adalah sintak List :

data=[]
while(True):
    nim=input("Masukan nim:")
    nama=input("Masukan nama:")
    tugas=int(input("Nilai tugas:"))
    uts=int(input("Nilai Uts:"))
    uas=int(input("Nilai Uas:"))
    akhir = (tugas*.3+uts*.35+uas*.35)
    data.append([nim,nama,tugas,uts,uas,akhir])
    ulangi=input("Tambah data (y/t)?")
    if ulangi == 't':
        break;

print("\nDaftar nama\n")
print("====================================================================")
print("  |     NIM     |     Nama     |  Tugas |  UTS   |  UAS  |  Akhir  |")
print("====================================================================")
for x in data :
    print("  |     {0:4s}    |     {1:8s} | {2:6} | {3:6} | {4:6}|  {5}   |  ".format(x[0], x[1], x[2], x[3], x[4],x[5]))
    
    Nih flowchartnya
    ![flowchart tugas 4](https://user-images.githubusercontent.com/56242226/69896983-15257100-1378-11ea-89e4-2d6b393d2c67.png)
    
    Algoritma nya yaitu :
    -langkah pertama itu Mulai
    -Selanjutnya input nim,nama,tugas,uts,uas
    -Masukan nilai akhir (tugas 30%, uts35%, uas35%)
    -input penambahan nomor
    -proses while (tambah data) jika ya maka data akan ditambah , jika tidak data akan selesai 
    -selanjutnya langkah for 
    - tampilkan Output list
    -selesai
    
