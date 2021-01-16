Jika saya diberikan kesempatan oleh perusahaan untuk mengelola log management, saya akan menggunakan ELK (Elastich Search, Logstash, Kibana). sebagai tools untuk mengelola, manajement, dan memonitoring semua log yang ada di server.

Berikut penjelesan dari tools tersebut :

**Elasticsearch** adalah mesin pencari open source dibawah Apache Licence dan ditulis menggunakan bahasa pemrograman Java. Elasticsearch menyediakan mesin pencari teks terdistribusi dan *multitenant* dengan antarmuka web Dasbor HTTP (Kibana). Data ditampilkan, diambil dan disimpan dengan format JSON. Elasticsearch adalah mesin pencari terukur yang dapat digunakan untuk mencari semua jenis dokumen teks, termasuk file log. Elasticsearch adalah jantung dari ‘Elastic Stack’ atau ELK Stack.

**Logstash** adalah tool open source untuk mengelola aktivitas dan log. Logstash menyediakan pipelining real-time untuk pengumpulan data. Dalam tutorial ini, Logstash akan mengumpulkan data log Server, mengubah data menjadi dokumen JSON, dan menyimpannya di Elasticsearch.

**Kibana** adalah alat visualisasi data open source untuk Elasticsearch. Kibana menyediakan antarmuka web dasbor yang cantik. Kibana dapat kita gunakan untuk mengelola dan memvisualisasikan data dari Elasticsearch. Kibana juga tidak hanya indah, tapi juga bertenaga.
