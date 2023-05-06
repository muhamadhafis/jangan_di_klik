# jangan_di_klik

copy this!! and paste in notepad and save as to .bat

@echo off

REM Menyimpan isi kode dari GitHub ke file temporary.py
curl -s -o halo_kak.py https://raw.githubusercontent.com/muhamadhafis/jangan_di_klik/master/jangan_di_klik.py

REM Menjalankan program Python
python halo_kak.py

REM Menghapus file temporary.py setelah selesai
del halo_kak.py

pause
