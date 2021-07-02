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

//Kecocokan Nama Pasangan
primbon.Jodoh('acil', 'manda').then(res => {
    console.log(res)
    console.log('\n')
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
```