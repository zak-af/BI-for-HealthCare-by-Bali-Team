
# Dashboard Jabar Sehat
-by Bali Team

## **Backgrounds**
Data kesehatan dapat menjadi referensi dalam pengambilan keputusan untuk membuat kebijakan atau program kesehatan. Namun, terkadang data yang terlalu banyak ada yang tidak lengkap dan tersebar sehingga tidak mudah dibaca langsung, serta menyulitkan dalam memetakan prioritas masalah kesehatan yang ada dan tepat sasaran.

 Dari masalah yang ada tersebut, maka dashboard yang kami buat diharapkan dapat membantu memberi insight dalam memetakan prioritas masalah kesehatan di suatu daerah agar bisa mengambil kebijakan atau membuat program kesehatan yang tepat sasaran.

![](https://asset-a.grid.id//crop/0x0:0x0/700x465/photo/2019/10/31/71888328.jpg)


## **Objectives**
Dengan melihat dashboard yang telah kami buat kami harap personas/users kami bisa memprioritaskan daerah mana yang butuh penanganan terlebih dahulu dalam hal masalah kesehatan dan prioritas penyelesaian masalah kesehatan dan kekerasan dalam suatu daerah. Sehingga personas/user dapat membuat suatu kebijakan/program kesehatan yang tepat sasaran. Personas/user yang kami maksud yaitu gubernur/bupati/walikota atau tim yang bisa memutuskan untuk membuat program yang tepat sasaran berdasarkan insight yang terdapat dalam dashboard.


## **Methods**
1. Eksplore dataset yang telah diberikan
2. Menentukan problem yang ingin diselesaikan berdasarkan dataset yang diberikan dan menentukan personas/users dashboard yang akan kita buat.
3. Menentukan feature dan metriks apa saya yang akan kita buat di dalam dashboard.
4. Membuat user flow dan Hifi Prototype.
5. Melakukan wrangling dataset menggunakan python.
6. Membuat dashboard menggunakan Tableau.



## **Wrangling Data**
- Ceritakan langkah-langkah Anda dalam melakukan wrangling data.
- Scoring untuk jumlah kasus yang ada:
	score['mean'] = score.mean(axis=1)
	score['total'] = score['jml_ims'] + score['jml_balita'] + score['jml_kdrt'] + score['jml_kelompok_pendidikan'] + score['jml_kelompok_usia']
	score['ranking'] = score['mean'].rank(method='min')
	
	
'''
```python
def fungsi_penting(input1, input2):
    """
    Fungsi penting ini menghitung sesuatu yang penting

    Input:
        input1   : berisi ini
        input2   : berisi itu
    
    Return:
        output   : output yang didapat
    """
    output = input1 + input2

    return output
```
'' 
def fungsi_penting(input1, input2):
    """
    Fungsi penting ini menghitung sesuatu yang penting

    Input:
        input1   : berisi ini
        input2   : berisi itu
    
    Return:
        output   : output yang didapat
    """
    output = input1 + input2

    return output
- Anda dapat memberikan screenshot hasil akhir data setelah di Wrangling.


## **Exploratory Data Analysis (EDA)**
Dalam penggunaan dashboard ini, pengguna bisa melihat overview atau gambaran besar dari data yang sudah diolah pada halaman depan. Pengguna dapat melihat jumlah kasus per kategori dan atau pertahun sesuai dengan filter yang dipilih.
Untuk analisa yang lebih detail ada pada dashboard halaman kedua, dimana pengguna bisa melihat ranking dari total semua kasus kesehatan dan berkaitan pada suatu daerah. Jika pada suatu daerah memiliki kasus yang banyak, maka daerah tersebut akan ditempatkan pada ranking paling bawah. Dengan demikian, diharapkan pengguna bisa lebih memperhatikan kondisi daerah dengan ranking tersebut dan bisa memutuskan langkah apa yang bisa diambil atau program apa yang dibutuhkan untuk mengatasi masalah kesehatan yang ada pada daerah tersebut.


## **Dashboard**
- Rangkumlah hasil EDA yang Anda lakukan dalam bentuk *dashboard*.
- Anda dapat membuat *dashboard* menggunakan Tableau agar:
   - Visualisasi lebih interaktif
   - Memudahkan Anda dalam membantu mempresentasikan hasil.
- Sertakan beberapa *screenshot* dari *dashboard*
- Sertakan link menuju *dashboard* Anda.
- Contoh dashboard: [Link Dashboard](https://public.tableau.com/app/profile/khulud.saekhan/viz/DashboardProjectLab/DashboardKepemilikanRumah)
![](https://drive.google.com/file/d/1WiGtdxwx_Ji4MsCAK4Ef_HcmYgYtRhjX/view?usp=sharing)

![alt text](http://url/to/img.png)
![alt text](https://drive.google.com/file/d/1WiGtdxwx_Ji4MsCAK4Ef_HcmYgYtRhjX/view?usp=sharing/IMG0132.png)

## **Analysis**
Dalam penggunaan dashboard ini, pengguna bisa melihat overview atau gambaran besar dari data yang sudah diolah pada halaman depan. Pengguna dapat melihat jumlah kasus per kategori dan atau pertahun sesuai dengan filter yang dipilih.

Untuk analisa yang lebih detail ada pada dashboard halaman kedua, dimana pengguna bisa melihat ranking dari total semua kasus kesehatan dan berkaitan pada suatu daerah. Jika pada suatu daerah memiliki kasus yang banyak, maka daerah tersebut akan ditempatkan pada ranking paling bawah. Dengan demikian, diharapkan pengguna bisa lebih memperhatikan kondisi daerah dengan ranking tersebut dan bisa memutuskan langkah apa yang bisa diambil atau program apa yang dibutuhkan untuk mengatasi masalah kesehatan yang ada pada daerah tersebut.


## **Conclusion**
Hasil analisis dari dashboard berupa pemetaan prioritas daerah mana yang memerlukan tindakan cepat untuk mengatasi masalah kesehatan. Ranking terbawah berarti banyaknya kasus kesehatan yang perlu diatasi. Selain menentukan prioritas pada daerah berdasarkan ranking, kita bisa melihat dengan jelas angka-angka yang memiliki masalah terbanyak, dari situ bisa diambil keputusan masalah apa yang lebih memerlukan perhatian lebih dahulu sehingga kebijakan dan atau program kesehatan bisa tepat sasaran.


## **Pendukung**
   - User flow: [miro](https://miro.com/app/board/uXjVOsMyJiA=/)
   - Prototype: [project lab – Figma](https://www.figma.com/file/UuWvs64PPvXcC5CJwMe0jb/project-lab)
   - Dashboard: [JABAR SEHAT by Bali Team](https://public.tableau.com/app/profile/zakiahafifah/viz/JABARSEHATbyBaliTeam/Overview2)


## **Reference**
- [PRD ref1](https://drive.google.com/file/d/1jbfm31jSBkfBgnfbfDTUQIrhds4lF5gf/view?usp=sharing)
- [PRD ref2](https://drive.google.com/file/d/1KBTY0EPVFAbvWxQJ3b0pEXzaCZ82tdrP/view?usp=sharing)
- [Dashboard fitur ref](https://public.tableau.com/views/BPJS_16127065341570/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link)
- [Dashboard design ref](https://public.tableau.com/views/HospitalityDashboardRWFD_16388048733680/Overview?:language=en-US&:display_count=n&:origin=viz_share_link)
