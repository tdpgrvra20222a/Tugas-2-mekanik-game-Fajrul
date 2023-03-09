# Tugas-2-mekanik-game-Fajrul

- Ruang(space) 
	- Ruang game bersifat kontinu (posisi karakter dapat berada dimana saja selama dapat dijangkau oleh karakter)
	- Dimensi game berupa 3 dimensi
	- Lokasi-lokasi didalam game saling terhubung selama masih dalam lingkup 1 map
- Waktu(time)
	- Semua pemain bermain secara bersamaan atau kontinu
	- Batasan waktu permainan tergantung dengan skor permainan
	- Waktu didalam game bersarang (waktu menunggu respawn setelah tereliminasi, waktu tidak dapat ditembak setelah respawn)
	- Bisa dikontrol jika memainkan mode bomb mission dengan cara membeli defuse kit untuk mempercepat defuse

- Object(objek)
	- Bomb
		- Pada awal stage berbentuk tas dan terletak di tanah
		- Setelah diambil oleh karakter terorist akan berpindah ke punggung karakter tersebut
		- Ketika dipegang bentuk bom berubah menjadi bentuk bomb dan berada pada area planting maka bomb dapat diberi aksi untuk dipasang
		- Ketika aksi pemasangan dilakukan maka bomb akan mengeluarkan suara seperti tombol yang dipencet
		- Suara bomb akan semakin cepat seiring dengan waktu
	- Senjata
		- Dapat mempengaruhi kecepatan bergerak karakter sesuai dengan senjata yang dipegang
		- Dapat merespawn peluru yang meluncur ke depan jika masih memliki peluru
		- Ketika karakter pemengang senjata tereliminasi makan sesnjata akan terjatuh
- Action(aksi)
	- Aksi dasar
		- Membawa dan memasang bomb ke site 
		- Hanya teroris yang dapat membawa bomb
		- Ketika pembawa bomb tereliminasi maka bomb akan jatuh ke tanah
		- Defuse bomb hanya dapat dilakukan oleh counter teroris
	- Aksi strategis
		- Membawa bomb ke site melalui jalur yang tidak diprediksi oleh musuh
		- Mengeliminasi counter teroris yang menjaga site dengan mengandalkan jumlah
		- Menjaga site dengan mengambil posisi yang susah ditebak
- Rule(aturan)
	- Karakter bergerak sebanyak 250 unit perdetik jika menggunakan pisau
	- Kecepatan minimal sebanyak 195 unit perdetik
	- ekonimi yang ditentukan dari round sebelumnya
	- ![image](https://user-images.githubusercontent.com/38638257/223932618-8f6ece96-1ed7-407f-82d0-b0481becd2b7.png)

- Skill(keterampilan)
	- AIM(kemampuan kombinasi menggunakan keyboard dan mouse)
	- Mengelola informasi
	- Mind reader (Strategi yang dibuat untuk memenangkan round)
- Change(peluang) 
	- kordinat respown 
	- Recoil ketika menembak
