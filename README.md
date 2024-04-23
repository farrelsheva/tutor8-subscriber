### Questions 
1. what is *amqp*?
amqp atau Advanced Message Queuing Protocol adalah sebuah application layer protocol untuk middleware yang message-oriented. Tujuan utamanya adalah untuk mengirimkan pesan antar aplikasi atau sistem dengan efisien dan aman.

2. what it means? guest:guest@localhost:5672 , what is the first quest, and what is the second guest, and what is localhost:5672 is for?

guest:guest@localhost:5672 adalah sebuah URI koneksi yang digunakan pada messaging protocol seperti amqp. setiap bagian dari URI tersebut memiliki arti sebagai berikut:
- guest: merupakan username yang digunakan untuk koneksi ke server
- guest: merupakan password yang digunakan untuk koneksi ke server
- localhost merupakan alamat server yang digunakan, dalam kasus ini 'localhost' merupakan mesin yang menjalankan aplikasi
- 5672 merupakan port yang digunakan untuk koneksi ke server