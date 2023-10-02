# Kel4_sistemTerdistribusi
Kelompok 4 Sistem Terdistribusi TRPL3C

Manajemen Sumber Daya dalam Lingkungan Terdistribusi adalah sistem pengelolaan sumber daya seperti file data lainnya melalui
sistem terdistribusi yang tujuan utamanya adalah memastikan bahwa pengguna/klien dapat mengakses sumber daya jarak 
jauh dengan kemudahan yang dapat diaksesnya sumber daya lokal.

Penyeimbangan beban adalah aspek penting dari sistem terdistribusi yang bertujuan untuk mengoptimalkan pemanfaatan sumber daya, meminimalkan waktu respons, dan menghindari kelebihan beban server. 
Namun, beberapa tantangan muncul dalam merancang dan memilih mekanisme penyeimbangan beban yang tepat untuk sistem terdistribusi berdasarkan jaringan area lokal atau komputasi awan. Pendekatan realistis terhadap strategi penyeimbangan beban diperlukan dalam mengatasi distribusi beban kerja yang tidak seimbang, peningkatan latensi dan overhead, masalah skalabilitas, dan kompleksitas dalam merancang algoritma penyeimbangan beban. 
Selain itu, penerapan praktik terbaik seperti metrik pemantauan yang tepat, penyeimbang beban berbasis cloud, redundansi, mekanisme failover, tinjauan rutin, dan optimalisasi strategi dapat memastikan penyeimbangan beban yang efektif. Penting untuk selalu mengetahui perkembangan terkini dalam algoritma penyeimbangan beban untuk mencapai ketersediaan tinggi dan kinerja sistem yang optimal.

-----

Sistem terdistribusi adalah proses pengaturan dan pengelolaan semua sumber daya yang tersedia dalam lingkungan yang terdiri dari beberapa komputer atau server yang saling terhubung. 
Tujuan utama manajemen sumber daya adalah untuk memastikan penggunaan sumber daya yang efisien dan optimal, sehingga sistem dapat berjalan dengan baik.
Terdapat beberapa manajemen sumber daya, yaitu :
1. Manajemen Sumber Daya Proses
2. Manajemen Sumber Daya Jaringan
3. Manajemen Beban dan Manajemen Failover
4. Manajemen Sumber Daya Penyimpanan
5. Manajemen Sumber Daya Terkait Keamanan

Sistem terdistribusi memiliki beberapa kelebihan, seperti bebas untuk menambah file atau sumber daya tanpa diketahui oleh user (dalam rangkan meningkatkan kinerja),
concurrency transparency, dan failure transparency. 

Beberapa tantangan dalam sistem terdistribusi meliputi latensi, penskalaan, pemahaman atas API, kegagalan dalam sistem terdistribusi dapat terjadi dalam banyak cara, dan kesulitan dalam membangun perangkat lunak. 
Kelemahan pada sistem terdistribusi adalah kesulitan dalam membangun perangkat lunak.

-----

RPC merupakan metode komputasi terdistribusi yang memungkinkan program komputer memanggil prosedur pada sistem jarak jauh seperti pemanggilan prosedur lokal.
Keuntungan RPC termasuk kompatibilitas dengan berbagai bahasa pemrograman, kemampuan untuk digunakan di lingkungan lokal dan terdistribusi, kemampuan untuk mengabstrakkan detail komunikasi jaringan, dan dukungan untuk model berorientasi proses dan berorientasi utas.
Salah satu masalah RPC adalah implementasi yang tidak konsisten, arsitektur perangkat keras yang tidak fleksibel, dan biaya yang meningkat karena prosedur yang dilakukan jarak jauh.
Secara keseluruhan, RPC adalah alat yang berguna untuk membuat aplikasi berbasis klien-server terdistribusi yang memungkinkan program berkomunikasi secara transparan dengan pengguna melalui jaringan.
