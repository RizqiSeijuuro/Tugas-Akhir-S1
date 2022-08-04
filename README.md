<h1 align='center'>Tugas Akhir S1 Teknik Fisika UGM</h1>

<p align="center">
  <img src="https://github.com/RizqiSeijuuro/Tugas-Akhir-S1/blob/main/Logo%20UGM.png" width=600>
</p>

## Introduction

Topik Penelitian: Pengaruh Jari-jari dan Luas Reflektor Cekung terhadap Intensitas Ultraviolet <br>
Dosen Pembimbing 1: Prof. Dr. Ir. Agus Budhie Wijatna, M.Si., IPM. <br>
Dosen Pembimbing 2: Dr. Nur Abdillah Siddiq, S.T. <br>

## File Descriptions
    
* <strong>[ Data Penelitian TA ](https://github.com/RizqiSeijuuro/Tugas-Akhir-S1/tree/main/Data%20Penelitian%20TA)</strong>: Folder berisi semua data hasil eksperimen
    * <strong>KalibrasiDenganMatahari.csv</strong>: data pengukuran intensitas UV dari Matahari (Uji Kalibrasi)
    * <strong>KalibrasiDenganLampu.csv</strong>: data pengukuran intensitas UV dari Lampu Phillips TUV 6W (Uji Kalibrasi)
    * <strong>Konsistensi.csv</strong>: data pengukuran intensitas UV dari Lampu Phillips TUV 6W (Uji Konsistensi)
    * <strong>Variasi Jari-jari Kelengkungan Reflektor/R10 D10.csv</strong>: data pengukuran UV menggunakan reflektor dengan jari-jari kelengkungan 10 cm dan diameter luas 10 cm
    * <strong>Variasi Jari-jari Kelengkungan Reflektor/R12 D10.csv</strong>: data pengukuran UV menggunakan reflektor dengan jari-jari kelengkungan 12 cm dan diameter luas 10 cm
    * <strong>Variasi Jari-jari Kelengkungan Reflektor/R14 D10.csv</strong>: data pengukuran UV menggunakan reflektor dengan jari-jari kelengkungan 14 cm dan diameter luas 10 cm
    * <strong>Variasi Jari-jari Kelengkungan Reflektor/R16 D10.csv</strong>: data pengukuran UV menggunakan reflektor dengan jari-jari kelengkungan 16 cm dan diameter luas 10 cm
    * <strong>Variasi Jari-jari Kelengkungan Reflektor/R18 D10.csv</strong>: data pengukuran UV menggunakan reflektor dengan jari-jari kelengkungan 18 cm dan diameter luas 10 cm
    * <strong>Variasi Diameter Bola Reflektor/R10 D6.csv</strong>: data pengukuran UV menggunakan reflektor dengan jari-jari kelengkungan 10 cm dan diameter luas 6 cm
    * <strong>Variasi Diameter Bola Reflektor/R10 D7.csv</strong>: data pengukuran UV menggunakan reflektor dengan jari-jari kelengkungan 10 cm dan diameter luas 7 cm
    * <strong>Variasi Diameter Bola Reflektor/R10 D8.csv</strong>: data pengukuran UV menggunakan reflektor dengan jari-jari kelengkungan 10 cm dan diameter luas 8 cm
    * <strong>Variasi Diameter Bola Reflektor/R10 D9.csv</strong>: data pengukuran UV menggunakan reflektor dengan jari-jari kelengkungan 10 cm dan diameter luas 9 cm
    * <strong>Variasi Diameter Bola Reflektor/R10 D10.csv</strong>: data pengukuran UV menggunakan reflektor dengan jari-jari kelengkungan 10 cm dan diameter luas 10 cm
    * <strong>Efek UVC/Tempe_Sebelum.jpg</strong>: citra pigmen warna pada tempe sebelum perlakuan
    * <strong>Efek UVC/Tempe_Sesudah.jpg</strong>: citra pigmen warna pada tempe sesudah perlakuan
    * <strong>Efek UVC/Tahu_Sebelum.jpg</strong>: citra pigmen warna pada tahu sebelum perlakuan
    * <strong>Efek UVC/Tahu_Sesudah.jpg</strong>: citra pigmen warna pada tahu sesudah perlakuan
* <strong>[ Analisis Data Kalibrasi.ipynb ](https://github.com/RizqiSeijuuro/Tugas-Akhir-S1/blob/main/Analisis%20Data%20Kalibrasi.ipynb)</strong>: notebook dengan analisis data hasil pengukuran intensitas UV menggunakan Sensor UV Meter dan UVC Meter Terstandar
* <strong>[ Analisis Data Konsistensi.ipynb ](https://github.com/RizqiSeijuuro/Tugas-Akhir-S1/blob/main/Analisis%20Data%20Konsistensi.ipynb)</strong>: notebook dengan analisis data uji konsistensi UV dari lampu
* <strong>[ Analisis Data Variasi Jari-jari Kelengkungan Reflektor.ipynb ](https://github.com/RizqiSeijuuro/Tugas-Akhir-S1/blob/main/Analisis%20Data%20Variasi%20Jari-jari%20Kelengkungan%20Reflektor.ipynb)</strong>: notebook dengan hasil analisis regresi dari data variasi jari-jari kelengkungan reflektor
* <strong>[ Analisis Data Variasi Diameter (Luas) Reflektor.ipynb ](https://github.com/RizqiSeijuuro/Tugas-Akhir-S1/blob/main/Analisis%20Data%20Variasi%20Diameter%20(Luas)%20Reflektor.ipynb)</strong>: notebook dengan hasil analisis regresi dari data variasi diameter (luas) reflektor
* <strong>[ Analisis RGB pada Tempe dan Tahu.ipynb ](https://github.com/RizqiSeijuuro/Tugas-Akhir-S1/blob/main/Analisis%20RGB%20pada%20Tempe%20dan%20Tahu.ipynb)</strong>: notebook dengan hasil analisis efek UVC terhadap tahu dan tempe sebagai jaringan tisu mirip manusia
</details>

## Kesimpulan & Saran

<a name="Kesimpulan"></a>
#### Kesimpulan

- Jari-jari kelengkungan dan luas reflektor memiliki hubungan yang sangat kuat dengan iradiasi yang terukur pada sensor. Koefisien determinasi yang diperoleh untuk variabel jari-jari kelengkungan reflektor dan iradiasi UV adalah 0,97318 dengan persamaan model y = -0.0141x + 0.3004. Sementara itu, koefisien determinasi untuk variabel luas reflektor dan iradiasi UV adalah 0,96230 dengan persamaan model y = 0.0008x- 0.0724.
- Hasil optimasi jari-jari kelengkungan reflektor menunjukkan bahwa jari-jari kelengkungan 10 cm menunjukkan nilai iradiasi yang paling besar dibanding jari-jari kelengkungan lainnya. Hasil optimasi luas reflektor dengan luas 100π cm2 yang menunjukkan nilai iradiasi yang paling besar.
- Paparan dari sumber UVC dengan reflektor yang memiliki jari-jari kelengkungan 10 cm dan luas 100π cm2 mampu merusak molekul pada pigmen warna sehingga terjadi efek pemudaran warna pada material tahu dan tempe.


</details>

<a name="Saran"></a>
#### Saran

- Efek paparan sinar UVC sebaiknya dilakukan eksperimen terhadap virus atau bakteri nyata.
- Instrumen untuk mengukur parameter efek paparan sinar UVC terhadap material tiruan yang mirip jaringan manusia sebaiknya ditambah agar variabel terikat maupun bebas dapat dikuantifikasi secara lebih baik.
- Penggunaan aluminium sebagai pelapis reflector sebaiknya menggunakan cairan untuk meminimalkan hamburan

</details>
