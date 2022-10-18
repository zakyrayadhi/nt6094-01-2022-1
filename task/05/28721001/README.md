# nim
1. Ganti nim dia atas dengan NIM Anda, seperti 99921001.
2. Hanya berkas ini yang akan diperiksa, sehingga bila ada jawaban yang tercantum pada berkas lain, tautan dari berkas ini ke berkas lain tersebut harus dibuat dan tercantum pada berkas ini.
3. Kerjakan yang diberikan berikut ini.


## soal 0
Pelajari
+ [Dasar-dasar cara menulis dan memformat berkas Markdown di Github](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)<br>(akan diterapkan pada tautan **Jawaban** di bawah setiap soal dan isi berkas yang dirujukanya),
+ [Dasar-dasar sintaks Mermaid untuk membuat diagram alir di GitHub](https://mermaid-js.github.io/mermaid/#/flowchart)<br>
(akan digunakan pada saat membuat digram alir proses pengerjaan artikel ilmiah),
+ [Cara menulis persamaan matematika dengan Markdown di GitHub](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)<br>
(akan dimanfaatkan saat menampilkan persamaan matematika yang digunakan).


## soal 1
Bagaimana Anda dapat menentukan suatu jurnal termasuk dalam kategori Q4, Q3, Q2, atau Q1? Jelaskan dan cantumkan tautan ke sumber yang diperlukan.

## jawaban : 
untuk menentukan suatu jurnal termasuk ke dalam kategori Q4, Q3,Q2, dan Q1 dibutuhkan data percentile dari jurnal tersebut. data ini ditampilkan oleh scopus. Data quartile ini diambil berdasarkan pengaruh jurnal tersebut kepada jurnal lain yang berarti berdasarkan jumlah perhitungan cite score dari jurnal-jurnal yang ada pada scopus. cite score adalah nilai dari suatu jurnal berdasarkan jumlah berapa banyak jurnal tersebut dirujuk oleh jurnal lain. Q1 menandakan jurnal terindeks scopus dengan pengaruh plaing besar sedang Q4 menandakan tingkatan jurnal paling rendah. source: https://xerpihan.id/blog/2983/tingkatan-jurnal-q1-q2-q3-q4/


## soal 2
Tuliskan empat jurnal bidang Anda, yang mungkin kelak akan menjadi target Anda mengirimkan artikel ilmiah, dengan masing-masing termasuk dalam kategori Q4, Q3, Q2, dan Q1. Cantumkan pula tautan ke jurnal-jurnal tersebut dan situs web lain yang menyatakan bahwa jurnal-jurnal tersebut termasuk dalam kategori yang dimaksud.

## Jawaban : Jurnal akan dimasukkan ke dalam:
1.	Nanoscience and Technology (https://www.scopus.com/sourceid/21100216986)(Q4)
2.	Nano biomedicine and Engineering (https://www.scopus.com/sourceid/19900195033) (Q3)
3.	Microfluidics and Nanofluidics  dan Micromachines (https://www.scopus.com/sourceid/130141) dan (https://www.scopus.com/sourceid/21100229176)  (Q2)
4.	Nanotechnology (https://www.scopus.com/sourceid/110040)  (Q1) 

## soal 3
Jelaskan apa yang dimasksud dengan struktur organisasi suatu artikel ilmiah IMRaD? Cantumkan rujukan yang Anda gunakan untuk menjelaskan.

## Jawaban: 
Struktur jurnal IMRaD merupakan singkatan dari Introduction, Method, Result and Discussion yang banyak digunakan oleh penulis artikel ilmiah karena struktur ini banyak diterima oleh jurnal ilmiah bereputasi. https://matematika.fmipa.unesa.ac.id/2183/mengenal-struktur-imrad-dan-tips-menulis-judul-artikel-ilmiah-yang-baik/


## soal 4
Terkait dengan struktur artikel limiah menurut IMRaD, buat diagram alir dengan Mermaid untuk menggambarkan urut-rutan bagian yang dikerjakan dan iterasi yang diperlukan. Cantumkan rujukan yang digunakan.

flowchart TD
	A((Title))-->B[[Abstract]]
	B--> C[\Introduction/]
	C--> D [[study site]]
	D--> E [[Methods]]
	E--> F [[Result]]
	F--> G [/Discussion\]
	G--> H [[Conclusions]]
	H--> I [[Acknowlegments]]
	I --> J [[References]]

source: https://www.researchgate.net/figure/Diagrammatic-representation-of-the-IMRAD-structure-of-research-papers-modified-from-a_fig1_257616774

## soal 5
Cantumkan sebuah persamaan utama yang akan digunakan dalam penelitian Anda, dapat dalam bagian teori, pengambilan data, pengolahan data, ataupun analisis.

Persamaan utama yang digunakan pada penelitian saya adalah persamaan navier stokes
```math
\frac{\partial(\rho e)}{\partial t} + \overrightarrow{\nabla}\cdot((\rho e + p)\overrightarrow{u}) = \overrightarrow{\nabla}\cdot(\overline{\overline{\tau}}\cdot\overrightarrow{u}) + \rho\overrightarrow{f}\overrightarrow{u} + \overrightarrow{\nabla}\cdot(\overrightarrow{\dot{q}})+r \end{equation}
```


## soal 6
Apakah yang dimaksud dengan jurnal pemangsa? Apakah yang dimaksud dengan penerbit pemangsa? Apakah perbedaannya dengan jurnal pemangsa? Jelaskan dengan memberikan rujukan yang digunakan.

## Jawaban
Jurnal predator—juga disebut jurnal penipuan, penipuan, atau pseudo-adalah publikasi yang mengklaim sebagai jurnal ilmiah yang sah, tetapi salah menggambarkan praktik penerbitannya (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7237319/)
Penerbit Pemangsa model bisnis penerbitan akademis yang mengenakan biaya penerbitan tulisan kepada penulis dan tidak memeriksa mutu dan keabsahan dari tulisan yang terkandung di dalamnya. Hal ini berbeda dengan penerbit berkaliber yang memiliki dewan redaksi yang memeriksa artikelnya. (https://id.wikipedia.org/wiki/Penerbit_pemangsa)


## soal 7
Apa yang dimaksud dengan jurnal akses terbuka? Jelaskan dengan memberikan rujukan yang digunakan.

## Jawaban
Publikasi Akses Terbuka bersifat digital, online, gratis, dan bebas dari sebagian besar pembatasan hak cipta dan lisensi (Suber 2012). Gerakan Akses Terbuka didasarkan pada filosofi bahwa pengetahuan yang diperoleh dari pendanaan publik harus dapat diakses secara bebas untuk kepentingan public (https://libguides.jcu.edu.au/openaccess)



## soal 8
Apakah ada kaitan antara jurnal pemangsa dengan jurnal akses terbuka? Jelaskan dengan memberikan rujukan yang digunakan.

## Jawaban
Jurnal pemangsa memiliki hubungan yang dekat dengan jurnal open access, hal ini dikarenakan kebanyakan jurnal pemangsa mengekploitasi jurnal open aceess. Jurnal pemangsa biasanya meminta bayaran untuk publikasi tanpa menyediakan sesi editorial dan layanan penerbitan yang berasosiasi dengan jurnal terpercaya (https://guides.umd.umich.edu/c.php?g=813057&p=5801511)


## soal 9
Apa yang dimaksud dengan pengindeks jurnal? Sebutkan beberapa di antaranya yang Anda kenal. Cantumkan rujukan yang digunakan.

## Jawaban
Pengindeks jurnal adalah Lembaga yang melakukan indeks terhadap jurnal yang terdaftar. Proses indeksisasi jurnal adalah metadata dan beberapa lembaga pengindeks full teks artikel jurnal pada data Data base eksternal. Manfaat jurnal terinfeksi adalah memungkinkan tingkat akses metadata jurnal semakin tinggi oleh pengguna. Salah satu Lembaga pengindeks jurnal international bereputasi adalah scopus, Thomson scientific dan the IEEE Explore digital Library. Parameternya pun berbeda-beda misalkan untuk scopus indeksnya Bernama source Normalized Impact per Paper (SNIP). (http://ekacandrasaputra.blogspot.com/2017/10/pengindeks-jurnal-online.html)


## soal 10
Apa yang dimaksud dengan h-indek? Jelaskan dengan memberikan rujukan yang digunakan. Hitunglah h-indeks seorang peneliti bila sitasi dari artike-artikel ilmiahnya adalah sebagai berikut.
``
```
paper =  29
citation =  [10, 5, 7, 8, 19, 5, 20, 6, 13, 10, 5, 6, 20, 20, 13, 17, 20, 17, 12, 18, 6, 9, 13, 12, 18, 9, 6, 6, 17]
```

## Jawaban
h-indek merupakan indeks yang menangkap hasil penelitian berdasarkan jumlah total publikasi dan jumlah total kutipan untuk karya-karya tersebut. Hal ini akan memberikan gambaran terfokus kinerja penelitian individu. H-indeks berguna untuk membandingkan peneliti dengan panjang karir yang sama dan mempunyai bidang yang sama juga. (https://subjectguides.uwaterloo.ca/calculate-academic-footprint/YourHIndex)
Untuk mengukur h-indeks kita perlu mengurutkan jumlah sitasi yang dilakukan dari jurnal tersebut dari yang terbanyak hingga terendah sehingga urutannya menjadi 
```
20, 20, 20, 20, 19, 18, 18, 17, 17, 17, 13, 13, 13, 12, 12, 10, 10, 9, 9, 8, 7, 6, 6, 6, 6, 6, 5, 5, 5
```
H indeks dihitung dengan jumlah jurnal (N) yang jika didaftar yang mempunyai sitasi lebih dari N sehingga pada kasus ini h-indeks dari penulis tersebut adalah 13, karena pada publikasi jurnal 14 hanya memiliki 12 sitasi. 
Source : https://www.muhclibraries.ca/training-and-consulting/guides-and-tutorials/whats-your-impact-calculating-your-h-index/
