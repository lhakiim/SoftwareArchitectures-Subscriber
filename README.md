# SoftwareArchitectures-Subscriber
# Tutorial 9

> What is amqp?

AMQP (Advanced Message Queuing Protocol) adalah protokol standar terbuka untuk pertukaran pesan (messaging) antar aplikasi atau sistem. Protokol ini dirancang untuk memungkinkan komunikasi yang andal, efisien, dan aman antara komponen-komponen perangkat lunak.

> What does it mean? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for?

**guest:guest (Bagian username:password)**

Guest pertama  = Username.
Ini adalah nama pengguna untuk mengautentikasi ke broker AMQP (biasanya RabbitMQ.
Guest kedua = Password

guest:guest adalah kredensial default di RabbitMQ untuk akses lokal.

**localhost:5672 (Bagian host:port)**

localhost = Host/alamat server.
Menunjukkan bahwa broker AMQP berjalan di mesin yang sama/localhost. Jika broker ada di server lain, ini akan berupa alamat IP atau nama domain.

5672 = Port jaringan.
Ini adalah port default untuk koneksi AMQP. Port alternatif:

