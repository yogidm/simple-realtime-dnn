# simple-realtime-dnn

## Deskripsinya sih simple

Tinggal clone saja repository ini di folder kalian, lalu buka terminal, tujukan ke folder clone ini lalu

```
python3 main_realtime.py
```

Selamat mecoba... :D 


Tested in
- Ubuntu 18.04
- Python 3.6.8
- Opencv 4.1.0

Tested in Windows 10
- install Python 3.6.x (kalo 3.7 bakalan error) <b> --> Beri centang untuk Add Path Python 3.6 waktu instalasi ya... </b>
- Masuk `cmd`
- install opencv via `pip3`
```
pip3 install opencv-python
```
- Siap digunakan. 

---

Untuk mengubah addres dari kamera, ubah `cap=cv2.VideoCapture(0)` pada line ke-2 kode `main-realtime.py` menjadi 1 atau 2 atau 3 sesuai dengan address kamera kalian. 

- optional install keras dan sebagainya. (nggak wajib kalo cuman menjalankan) di link berikut
https://github.com/hsekia/learning-keras/wiki/How-to-install-Keras-to-Ubuntu-18.04

---
Modified from [rdeepc](https://github.com/rdeepc/ExploreOpencvDnn) by [yogidm](https://github.com/yogidm)

