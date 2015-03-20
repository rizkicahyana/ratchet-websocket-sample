# ratchet-websocket-sample

Simple Ratchet Websocket example for you. Built with JQuery, Ratchet WebSocket, and PHP. Serangkaian contoh yang saya tulis ini dapat Anda gunakan untuk keperluan ngulik websocket dan PHP. Bagi Anda yang akan mencobanya untuk produksi, disarankan untuk mencari lebih lanjut informasi yang berkenaan dengan proses deployment websocket menggunakan Ratchet di [http://socketo.me](http://socketo.me).

Di dalam folder vendor terdapat library Ratchet WebSocket, sedangkan di dalam folder src terdapat file - file contoh dari aplikasi websocket yang saya tulis. Saat ini baru ada contoh untuk tingkat basic. Berikut adalah langkah - langkah instalasi yang perlu Anda perhatikan:

* 1. Pastikan Anda sudah menginstall Apache dan PHP di mesin Anda.
* 2. Kemudian pastikan Anda memasang PHP CLI dengan mengatur PATH-nya di environment variable jika Anda menggunakan Windows, atau pasang melalui package manager distro Linux yang Anda gunakan.
* 3. Taruh project ini di htdocs atau folder web Anda, kemudian nyalakan file wsengine.php dengan menggunakan PHP-CLI
* 4. Akseslah contoh aplikasi yang ada di project ini misalkan http://localhost/ratchet-websocket-sample/src/basic/chat.html
* 5. Pastikan Anda menggunakan dua browser atau dua window browser untuk melihat efeknya. Anda juga dapat menggunakan lebih dari dua windows untuk menguji aplikasi dan proses yang terjadi. Pastikan Anda menggunakan Developer Tools yang terdapat di browser yang Anda gunakan untuk melihat proses yang ditampilkan di console.log()

Berikut adalah screenshot dari beberapa aplikasi yang ada di project ini:

![](https://dl.dropboxusercontent.com/u/54840757/picture/ratchet-websocket-sample/Selection_035.png)

![](https://dl.dropboxusercontent.com/u/54840757/picture/ratchet-websocket-sample/Selection_034.png)

![](https://dl.dropboxusercontent.com/u/54840757/picture/ratchet-websocket-sample/Selection_032.png)

Semoga bermanfaat :D