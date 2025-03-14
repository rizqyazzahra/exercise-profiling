Nama: Rizqya Az Zahra Putri

NPM: 2306244936

Kelas: B

## Module 5 - Java Profiling

#### /all-student
Sebelum melakukan _profiling_
![Image](https://github.com/user-attachments/assets/82e7b51b-42b5-4561-82c1-7302a2d154f3)
![Image](https://github.com/user-attachments/assets/f4b75ea5-e9fe-49c9-aae2-3eab34de53b8)

Setelah melakukan _profiling_
![Image](https://github.com/user-attachments/assets/a2d11e36-2960-44c1-ac23-1315056084e6)
![Image](https://github.com/user-attachments/assets/2600d8fe-1064-434a-9464-531627c6862c)

#### /all-student-name
Sebelum melakukan _profiling_
![Image](https://github.com/user-attachments/assets/aee29fc8-d8c9-4451-9ed7-d8bcb0d9dc44)
![Image](https://github.com/user-attachments/assets/5456647e-5fb0-4698-8d9a-e31225715fca)

Setelah melakukan _profiling_
![Image](https://github.com/user-attachments/assets/de8e03ce-9274-4b9d-b75a-28bd4dcbe86a)
![Image](https://github.com/user-attachments/assets/0f0befb7-88b8-45c5-a0f3-eae4060931ca)

#### /highest-gpa
Sebelum melakukan _profiling_
![Image](https://github.com/user-attachments/assets/447637a8-ab92-4150-b8c1-bd719e9b9d93)
![Image](https://github.com/user-attachments/assets/47f017f8-0704-411d-82dd-ca36c367a486)

Setelah melakukan _profiling_
![Image](https://github.com/user-attachments/assets/f4c75dc7-a47a-4f47-a7cb-efb747fa5b6d)
![Image](https://github.com/user-attachments/assets/c5b6f2c3-f0d5-4de3-86d9-e58cd1c37c07)

## Reflection
1. > What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?
  Perbedaan utama antara pengujian kinerja dengan JMeter dan profiling dengan IntelliJ Profiler dalam optimasi kinerja aplikasi terletak pada fokus dan cara analisisnya, di mana JMeter digunakan untuk melakukan uji beban dan stres dengan mensimulasikan banyak pengguna serta mengukur respons aplikasi dalam skenario dunia nyata, sedangkan IntelliJ Profiler lebih berfokus pada analisis mendalam terhadap penggunaan CPU, memori, dan thread dalam kode aplikasi untuk mengidentifikasi bottleneck atau masalah performa di tingkat kode dan runtime.

2. > How does the profiling process help you in identifying and understanding the weak points in your application?
   Proses profiling membantu mengidentifikasi dan memahami titik lemah dalam aplikasi dengan menganalisis penggunaan CPU, memori, dan aktivitas thread secara mendetail selama runtime, sehingga memungkinkan kita untuk mendeteksi bottleneck, kebocoran memori, serta kode yang tidak efisien yang dapat memperlambat kinerja aplikasi. Dengan ini, kita dapat melakukan optimasi yang lebih tepat sasaran, seperti mengurangi penggunaan sumber daya yang berlebihan, memperbaiki algoritma yang lambat, atau meningkatkan efisiensi pemrosesan, sehingga aplikasi menjadi lebih cepat, stabil, dan hemat sumber daya.

3. > Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?
   Menurut saya, IntelliJ Profiler sangat efektif dalam membantu menganalisis dan mengidentifikasi bottleneck. Dengan IntelliJ Profiler, kita dapat melihat bagian kode yang paling banyak mengonsumsi sumber daya, mendeteksi kebocoran memori, serta memahami pola eksekusi aplikasi secara visual melalui grafik dan laporan yang interaktif. Kemampuannya dalam memberikan insight berbasis data memungkinkan kita untuk melakukan optimasi yang lebih tepat sasaran, sehingga meningkatkan efisiensi dan performa aplikasi secara keseluruhan.
   
4. > What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?
   Salah satu tantangan dalam pengujian performa dan profiling adalah membaca dan menganalisis hasil tes untuk menentukan langkah optimasi yang tepat, terutama ketika berhadapan dengan data kompleks dari alat pengujian atau profiling. Saya mengatasinya dengan membandingkan hasil tes dari berbagai skenario untuk menemukan pola, memvisualisasikan data agar lebih mudah dipahami, serta menguji perubahan secara bertahap untuk memastikan setiap optimasi memberikan dampak positif. Dengan pendekatan ini, saya dapat mengidentifikasi bottleneck secara lebih efektif dan melakukan optimasi yang lebih terarah serta berkelanjutan.
   
5. > What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?
   Keuntungan utama menggunakan IntelliJ Profiler adalah efisiensinya dalam mendeteksi masalah performa tanpa memerlukan alat tambahan. Profiler secara otomatis mengurutkan metode berdasarkan waktu eksekusi, sehingga saya dapat dengan cepat menemukan bottleneck dalam kode tanpa analisis manual yang rumit. Selain itu, fitur visualisasi data yang interaktif membantu saya memahami pola eksekusi aplikasi dengan lebih jelas, memungkinkan saya untuk mengidentifikasi dan mengoptimalkan bagian kode yang paling banyak mengonsumsi sumber daya. Dengan pendekatan ini, proses debugging dan optimasi performa menjadi lebih cepat dan akurat.
   
6. > How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?
   Jika hasil profiling dengan IntelliJ Profiler tidak sepenuhnya konsisten dengan hasil menggunakan JMeter, saya menangani situasi ini dengan membandingkan kembali skenario pengujian untuk memastikan keduanya berjalan dalam kondisi yang sebanding. Saya akan memeriksa apakah lingkungan uji, jumlah beban, dan data yang digunakan dalam JMeter mencerminkan kondisi dunia nyata yang sama dengan saat profiling dilakukan.

7. > What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?
   Setelah menganalisis hasil dari pengujian kinerja dan profiling, saya menerapkan strategi optimasi seperti memperbaiki algoritma yang tidak efisien (saya lakukan pada method `findStudentWithHighestGpa` yaitu mengganti `findAll()` menjadi `findFirstByOrderByGpaDesc()`, mengoptimalkan penggunaan memori, dan mengurangi operasi yang memakan banyak sumber daya, yang saya lakukan pada method `getAllStudentsWithCourses` karena pada method tersebut program mengambil daftar mahasiswa terlebih dahulu.
