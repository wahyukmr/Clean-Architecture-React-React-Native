**_Clean architecture_** adalah cara mengatur kode dalam aplikasi supaya lebih mudah diubah, diperbaiki, dan diuji. Ini dilakukan dengan membagi kode menjadi beberapa bagian yang masing-masing punya tugas tertentu dan tidak saling bergantung satu sama lain.

Apa saja lapisan-lapisan dalam _clean architecture_? Bayangkan aplikasi seperti sebuah rumah:

1. **Inti (_Entities_)**: Seperti fondasi rumah, bagian ini berisi aturan dan logika dasar yang tidak berubah.
2. **Logika Aplikasi (_Use Cases_)**: Ini seperti kerangka rumah yang menentukan bagaimana rumah dibangun sesuai dengan aturan dari fondasi (Entities).
3. **Antarmuka (_Interface Adapters_)**: Ini adalah jendela dan pintu rumah yang menghubungkan bagian dalam rumah dengan dunia luar, seperti bagaimana aplikasi berkomunikasi antara pengguna dan data.
4. **Detail Eksternal (_frameworks and Drivers_)**: Ini adalah dekorasi dan perabot rumah yang bisa diubah tanpa mengganggu struktur utama, seperti tampilan aplikasi atau cara menyimpan data.

Prinsip utamanya adalah memastikan bagian penting di dalam rumah (logika dan aturan dasar) tidak tergantung pada hal-hal yang ada di luar (seperti tampilan atau database). Ini membuat aplikasi lebih kuat dan fleksibel terhadap perubahan.

> Kita tidak selalu perlu menggunakan architecture yang kompleks. Misalnya jika hanya sebagai seorang developer di sebuah perusahaan.

Lima pola _clean architecture_ yang umum dalam React Native:

1. **_Layered Architecture_**: membagi aplikasi menjadi beberapa lapisan seperti: presentation, application, domain, dan infrastructure.
2. **_MVC (Model View Controller)_**
3. **_MVVM (Model-View-View-Model)_**
4. **_Monolithic_**
5. **_MVP (Model View Presenter)_**
