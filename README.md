**CARA MENAMBAH KAPASITAS IGPU/APU VRAM DI COLORFUL BATTLE-AX A520M-K M.2 V14**
### **Disclaimer - mengutak-atik bios dengan cara ini terutama untuk mengubah setting yang di hidden bisa membuat pc bermasalah seperti tidak bisa booting, no display, hang/freeze, blue screen dan sebagainya, jadi do with your own risk**
**catatan : mencopot baterai cmos atau mereset bios ke default akan membuat pengaturan custom ini menghilang jadi jika terjadi maka harus di setting ulang.**
### **alat yang di butuhkan**
- **Rufus - https://github.com/pbatard/rufus/releases/download/v4.10/rufus-4.10p.exe**  
- **Flashdisk minimal 4gb** 
- **file efi - https://github.com/user-attachments/files/22551201/EFI.zip**

### **langkah-langkah**
- **pertama format flashdisk sesuai di gambar - pastikan tidak ada data di flashdisknya karena akan di format**  
- **<img width="483" height="551" alt="Screenshot_1" src="https://github.com/user-attachments/assets/2eda9be3-7e9c-4eff-af61-eefb83a505c9" />**  
- **download file efi dari link di atas lalu extract ke flashdisk**  
- **<img width="1138" height="650" alt="Screenshot_2" src="https://github.com/user-attachments/assets/f3e4e5ff-9470-43ec-aace-a49c5126c78d" />**  
- **kemudian restart pc dan boot dari flashdisk colorful biasanya menggunakan F11 sebagai boot menu**  
- ![IMG20250926092235](https://github.com/user-attachments/assets/811e2b09-1902-48ec-b940-ab22c9dad29f)**
- **ketika sudah muncul seperti ini pencet spasi**
- ![IMG20250926092250](https://github.com/user-attachments/assets/21c6661d-6c3a-4f72-9c85-1f4a450ecd41)**
- **lalu akan muncul sebagai berikut pilih modGRUBShell.efi dengan tombol panah atas bawah di keyboard lalu pencet enter**
- ![IMG20250926092300](https://github.com/user-attachments/assets/2d560e07-4c6b-452b-9d82-97b89c715908)
- **jika sudah masuk ke ModGRUBShellnya ketik value untuk vramnya disini untuk cotoh adalah 2GB silahkan pilih sesuai kebutuhan jadi kurang lebih seperti ini**  
- **<img width="715" height="307" alt="Screenshot_3" src="https://github.com/user-attachments/assets/0c2e3a7f-938f-4612-b146-8d96d54d088c" />**
- **ketikan perintah di modGRUBSHELL.efi**
- ![IMG20250926092420](https://github.com/user-attachments/assets/af5a597a-b7d4-4755-bfd0-881d8598d334)
- **jika cara diatas tidak berhasil bisa coba yang ini**
- ![IMG20250926092359](https://github.com/user-attachments/assets/d9885954-355a-47f5-943d-5672ae3da5b0)
- **jika sudah selesai ketik reboot**
- ![IMG20250926092439](https://github.com/user-attachments/assets/8ca212ba-094e-4ee8-8bd2-20ee93f8c0b9)


---

