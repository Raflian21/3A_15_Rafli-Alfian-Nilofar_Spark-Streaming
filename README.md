# Screenshot Output
![image](https://github.com/Raflian21/3A_15_Rafli-Alfian-Nilofar_Spark-Streaming/assets/95726593/9191d5ea-d26e-4c88-92e3-fe6f3dced59c)
![image](https://github.com/Raflian21/3A_15_Rafli-Alfian-Nilofar_Spark-Streaming/assets/95726593/23426510-67b7-4ef0-9a16-e7961317b534)
![image](https://github.com/Raflian21/3A_15_Rafli-Alfian-Nilofar_Spark-Streaming/assets/95726593/5be8b6c6-92fe-4cdd-b6ac-0207b8ba2817)
![image](https://github.com/Raflian21/3A_15_Rafli-Alfian-Nilofar_Spark-Streaming/assets/95726593/ed96f836-4ca1-49c2-9e52-401c34ee7bf9)
![image](https://github.com/Raflian21/3A_15_Rafli-Alfian-Nilofar_Spark-Streaming/assets/95726593/477f581e-b974-4288-8a07-26d9d0fd9879)
![image](https://github.com/Raflian21/3A_15_Rafli-Alfian-Nilofar_Spark-Streaming/assets/95726593/f3adf4f6-23a2-4485-b7a9-92eb919c1ce1)
![image](https://github.com/Raflian21/3A_15_Rafli-Alfian-Nilofar_Spark-Streaming/assets/95726593/3caaebfb-3f3d-4243-a886-886fa05e2a0d)

# Tugas
![image](https://github.com/Raflian21/3A_15_Rafli-Alfian-Nilofar_Spark-Streaming/assets/95726593/b3a7adfc-a19d-4165-a192-bd8a5991a2af)
First Header  | Second Header
------------- | -------------
      1       | sys.argv adalah sebuah daftar (list) dalam modul sys pada Python yang berisi argumen baris perintah yang diteruskan ke sebuah skrip.
sys.stderr adalah objek mirip file yang disediakan oleh modul sys pada Python. Objek ini digunakan untuk mencetak pesan kesalahan dan informasi traceback. Secara default, pesan kesalahan dicetak ke konsol, tetapi Anda dapat mengarahkan stderr ke aliran keluaran yang berbeda jika diperlukan.
StreamingContext adalah sebuah kelas dalam pustaka Apache Spark Streaming. Ini merupakan titik masuk utama untuk membuat DStreams (Discretized Streams) dalam aplikasi Spark Streaming.
sc adalah objek konteks Spark dalam Apache Spark. sc adalah objek utama yang digunakan untuk berinteraksi dengan Spark dan melakukan operasi-operasi pengolahan data pada RDD (Resilient Distributed Dataset) dalam lingkungan distribusi.
socketTextStream adalah metode dalam modul StreamingContext di Apache Spark Streaming. Metode ini digunakan untuk membuat DStream yang mengambil data dari koneksi socket TCP/IP.
reduceByKey adalah sebuah operasi dalam Apache Spark yang digunakan pada DStreams atau RDDs untuk menggabungkan nilai-nilai yang sama berdasarkan kunci (key).
lambda line adalah sebuah fungsi lambda dalam Python yang digunakan untuk mendefinisikan fungsi anonim sederhana.
awaitTermination adalah metode dalam StreamingContext di Apache Spark Streaming. Metode ini digunakan untuk memulai proses streaming dan menunggu hingga aplikasi dihentikan secara eksplisit oleh pengguna atau ada kesalahan. Metode ini membuat program tetap berjalan dan menunggu hingga pengguna secara manual menghentikan aplikasi streaming.
      2       | nc, lk untuk mengirimkan data ke Spark Streaming melalui koneksi socket TCP/IP
      3       | spark-submit adalah perintah baris perintah yang digunakan untuk mengirimkan aplikasi Spark ke cluster untuk dieksekusi.
master adalah parameter yang digunakan dengan spark-submit untuk menentukan lokasi atau alamat dari Spark master.
local adalah salah satu nilai yang dapat digunakan untuk parameter master saat menggunakan spark-submit. Ini menunjukkan bahwa aplikasi Spark akan dijalankan dalam mode lokal pada mesin tempat perintah spark-submit dieksekusi.  
      4       | ssc.checkpoint adalah metode yang digunakan dalam StreamingContext pada Apache Spark Streaming untuk mengatur titik kontrol (checkpointing).
parallelize adalah metode dalam SparkContext yang memungkinkan Anda membuat RDD (Resilient Distributed Dataset) dari koleksi data yang ada di memori pada driver program.
updateStateByKey adalah metode dalam DStream pada Apache Spark Streaming yang digunakan untuk melakukan operasi update state pada data streaming.
flatMap adalah operasi transformasi pada RDD atau DStream yang memungkinkan Anda untuk menerapkan fungsi pada setiap elemen dan menghasilkan nol, satu, atau beberapa elemen baru.
      5       | rdd.take(5) akan mengembalikan lima elemen pertama dari RDD tersebut dalam bentuk sebuah list atau koleksi.
transform adalah operasi transformasi pada RDD atau DStream dalam Apache Spark yang menghasilkan RDD atau DStream baru dengan menerapkan suatu transformasi pada setiap elemen.
rdd.sortByKey(False) adalah sebuah metode pada RDD dalam Apache Spark yang digunakan untuk mengurutkan elemen RDD berdasarkan kunci (key).

