# UDP-Socket-Programming-in-C-
Untuk compile dan run listener :  - gcc -o listener listener.c
                                  - ./listener
Untuk compile dan run talker   :  - gcc -o talker talker.c
                                  - ./talker [IP] [Pesan yang akan dikirim]
                                  - contoh : ./talker 192.168.1.1 "Hallo"
Buka aplikasi wireshark, untuk menganalisa paket yang mampu diterima tserver.
