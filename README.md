# Primbon Scraper

## Instalation :
```
npm i primbon-scraper
```

## Usage:
```js
const primbon = require('primbon-scraper')
```

## Example
```js
const primbon = require('primbon-scraper')

//Arti Nama
primbon.artiNama('izo').then(res => {
    console.log(res)
})

//Tafsir Mimpi
primbon.tafsirMimpi('hantu').then(res => {
    console.log(res)
})

//Nama Pasangan
primbon.Jodoh('acil', 'manda').then(res => {
    console.log(res)
})

//Tanggal Jadian
primbon.tanggaljadi("01-07-2000").then(res => {
    console.log(res)
})

//Membaca Watak & Karakter Artis Indonesia
primbon.watakartis("Michelle Ziudith", "20-1-1995").then(res => {
    console.log(res)
})

//Ramalan Jodoh
primbon.ramalanjodoh("joe", "11-4-2003", "putri", "1-2-2005").then(res => {
    console.log(res)
})

//Ramalan Rejeki (Hoki)
primbon.rejekiweton("11-1-2000").then(res => {
    console.log(res)
})

//Kecocokan Nama
primbon.kecocokannama("angel", "18-5-2005").then(res => {
    console.log(res)
})

//Hari Baik
primbon.haribaik("1-1-2000").then(res => {
    console.log(res)
})

//Hari Larangan
primbon.harilarangan("1-1-2000").then(res => {
    console.log(res)
})

```
## Output Exemple

```js

//Arti Nama
Nama izo, memiliki arti: Ekspansif, visioner, petualang, menggunakan kebebasan dengan cara konstruktif.Anda tidak pernah mau tinggal diam dalam menjalani hidup. Selalu menemukan diri anda dalam kemajuan karir dan taraf hidup karena kerja keras sendiri. Travel, olahraga, atau petualangan adalah hal yang paling anda sukai. Dari waktu ke waktu, anda selalu merubah penampilan diri dan juga mengubah kepribadian anda kepada sesuatu yang lebih menunjang karir dan kemajuan pribadi. Anda selalu ingin mencari jawaban atas permasalahan dengan melacaknya sendiri. Anda mempunyai bakat menjadi detektif. Jagalah diri agar jangan sampai terlalu terpesona dengan cinta bahkan menjadi budak cinta. Karena anda cenderung menyukai lawan jenis (pasangan) begitu dalam sehingga terkadang tidak dapat menguasai diri anda sendiri. Anda termasuk orang yang agresif dalam menyikapi cinta. Anda juga termasuk orang yang gampang sekali cemburu.

//Tafsir Mimpi
Mimpi berbicara dengan hantu = Keuangan anda akan meningkat.
Mimpi melihat hantu = Segala usaha akan sukses dalam beberapa hari lagi.

//Kecocokan Nama Pasangan
{
  namaAnda: 'acil',
  namaPasangan: 'manda',
  positif: 'Tenang, Spiritualis, Cerdas',
  negatif: 'Terlalu tertutup, Pembohong, PengekangHubungan akan baik apabila Anda berusaha untuk tidak menutup diri (terlalu penyendiri). Pasangan Anda adalah orang yang sangat kekeluargaan dan perhatian terhadap Anda. Hanya saja, kadang-kadang pasangan selalu menegaskan sesuatu dengan cara bertanya apa yang sebenarnya ada di dalam hati, baik itu mengenai pandangan Anda tentang dirinya atau apapun yang terjadi dalam hubungan ini. Janganlah terlalu mendominasi keadaan untuk hal-hal yang kurang  perlu karena pasangan adalah orang yang sangat berpikir menggunakan logika, tetapi dia sangat produktif.',
  love: 'https://www.primbon.com/ramalan_kecocokan_cinta3.png'
}

//Tanggal Jadian
Karakteristik: Pembaharuan, Pemberani, Awal Dari Rencana, Egoistis
Hubungan ini akan dilandasi oleh sikap optimisme dengan hal-hal baru, membuka lembaran baru dari segala masalah yang sudah terjadi. Kedua belah pihak dianjurkan untuk bisa saling mengalah. Anda atau pasangan bisa jadi sangat mendominasi keadaan. Hindari saling mau menang sendiri, egoistis, serta emosi yang mudah tersulut dan tidak terkendali, Berusahalah untuk sling toleransi. Hindari kata-kata ataupun keputusan yang sifatnya emisional pada saat anda berdua sedang dalam keadaan kurang baik.

//Membaca Watak & Karakter Artis Indonesia
Membaca Karakter Selebriti Michelle ZiudithBerdasarkan Horoskop Jawa, Misteri Pranata Mangsa

Nama: Michelle Ziudith
Tanggal Lahir: 20 Januari 1995
Weton: Jumat Wage
Mongso: Kapitu
Wuku: Wuyu
...

//Ramalan Jodoh
HASIL RAMALAN PERJODOHAN UNTUK PASANGAN

joe
Tanggal Lahir: Jumat Pahing, 11 April 2003
putri
Tanggal Lahir: Selasa Wage, 1 Februari 2005
...

//Ramalan Rejeki (Hoki)
{  penjelasan: 'REJEKI (HOKI) MENURUT WETON\n' +
    '\n' +
    'Hari Lahir: Selasa Legi, Tgl. 11 Januari 2000\n' +    'Seseorang dengan weton ini jika berkeluarga cenderung kurang harmonis, yang mungkin disebabkan oleh pekerjaannya yang jauh dari rumah, atau suami-istri jarang ketemu karena kesibukan masing-masing. Selain itu, bila bekerja seringkali tidak betah dan inginnya keluar saja. Sehingga jika tidak hati-hati atau gegabah dalam membuat keputusan, maka hidupnya bisa gagal berantakan. Maka bagi seseorang dengan weton ini, hendaknya ia memiliki kemampuan mengendalikan diri yang sangat kuat dan selalu berusaha agar tidak emosional dalam menghadapi berbagai persoalan supaya hidupnya tetap selamat dan sejahtera, meskipun mungkin tidak selalu berlebihan.\n' +
    '\n' +
    'Fluktuasi Rejeki/Hoki Menurut Primbon Pal Srigati',
  statistik: 'https://www.primbon.com/rejeki/08.png'
}

//Kecocokan Nama
KECOCOKAN NAMA DENGAN TANGGAL LAHIR

Tanggal Lahir: 18 Mei 2005
Life Path Number : 3
Nama: Angel
Destiny Number : 3
Heart's Desire Number : 6
Personality Number : 6
PERSENTASE KECOCOKAN
Life Path & Destiny 100%
Life Path & Heart's Desire 40%
Life Path & Personality 40%
RATA-RATA* 60.00%
*Sebuah nama dianggap cocok atau selaras, jika persentase kecocokan rata-rata diatas 55%.

//Hari Baik
PETUNG HARI BAIK (KAMAROKAM)

Watak Hari Menurut Kamarokam
Sabtu Legi, Tgl. 1 Januari 2000
Mantri Sinaroja: BAIK, Pangkat Berwibawa, Tercapai Tujuan, Bahagia.

//Hari Larangan
Primbon Hari Larangan (Tanggal Sangar, Bangas Padewan, Taliwangke)

1 Januari 2000 = Sabtu Legi, 24 Pasa 1932 (Ehe)
Termasuk TANGGAL SANGAR! Disarankan untuk tidak melakukan perjalanan jauh atau melaksanakan hajat besar pada hari ini.

```