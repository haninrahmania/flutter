 1. Jelaskan apa yang dimaksud dengan stateless widget dan stateful widget dan jelaskan perbedaan dari keduanya.

 -->Stateless widget merupakan widget yang tidak bisa berubah-ubah, sedangkan stateful widget merupakan widget
 yang dapat berubah-ubah.

 2. Sebutkan widget apa saja yang kamu pakai di proyek kali ini dan jelaskan fungsinya.

 --> *Text = Display string dalam satu baris.
     *Material App = sebagai root dari aplikasi.
     *Row = Display children dalam format horizontal.
     *Column = Display children dalam format vertikal.
     *Scaffold = menyediakan struktur dasar dan styling dalam aplikasi.
     *AppBar = display toolbar widgets, seperti title dan actions.
     
 3. Apa fungsi dari setState()? Jelaskan variabel apa saja yang dapat terdampak dengan fungsi tersebut.

 --> Fungsi dari setState() adalah untuk merencanakan suatu pembaruan ke suatu state objek komponen yang nantinya ketika state berubah maka komponen akan merespon dengan me-render ulang. Variabel yang dapat berdampak dengan fungsi tersebut adalah variabel yang diganti pada fungsi tersebut.

 4. Jelaskan perbedaan antara const dengan final.

 --> Const mengharuskan variabel harus dinialisasi pada saat kompilasi, nilai bersifat konstan dan secara langsung/eksplisit sehingga pada saat kompilasi variabel const sudah memiliki nilai. Ssedangkan final tidak mengharuskan variabel untuk memiliki nilai secara langsung/eksplisit pada saat kompilasi.

 5. Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas.

 --> 1.  Melakukan perintah flutter create counter_7.
     2.  Mengimplementasikan widget-widget yang diperlukan oleh programnya ke dalam file yang telah disediakan.
     3.  Menambahkan fungsi untuk logika penambahan serta pengurangan dan menambahkan variabel untuk mengubah text yang menyatakan  
         bilangan itu genap atau ganjil.