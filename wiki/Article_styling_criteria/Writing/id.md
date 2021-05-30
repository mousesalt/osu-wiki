# Penulisan

*Untuk standar-standar Pemformatan, kunjungi: [Kriteria gaya artikel/Pemformatan](../formatting)*

*Perhatian: Artikel di bawah ini menggunakan format [RFC 2119](https://tools.ietf.org/html/rfc2119 "IETF Tools") untuk menggambarkan tingkat persyaratan.*

Semua artikel berbahasa Inggris, wajib menggunakan bahasa Inggris umum.

## Daftar bahasa

Ada dua daftar bahasa di wiki: netral dan informal.

Daftar netral adalah bentuk umum di wiki.

Daftar informal bersifat khusus dan diberikan untuk sejumlah kecil artikel. [FAQ](/wiki/FAQ) dan [Help Centre](/wiki/Help_Centre) tergabung sebagai contoh ke dalam daftar ini.

Untuk kedua daftar, semua aturan di bagian kriteria gaya artikel ini wajib diikuti. Pengecualian untuk salah satu daftar akan dicatat.

## Inggris British

Inggris British memiliki varian ejaan yang wajib digunakan jika ada ejaan kata-kata bahasa Inggris yang bertentangan. Misalnya, penggunaan:

- `colour` daripada `color`
- `centre` daripada `center`
- `skilful` daripada `skillful`
- `analyse` daripada `analyze`

## Kapitalisasi

### Nama artikel

Nama artikel, ketika ditulis dalam paragraf, tidak boleh menggunakan kapitalisasi atau huruf besar, kecuali jika itu adalah tautan yang mengarah ke artikel atau itu adalah kata benda yang tepat (misalnya BanchoBot). Berikut ini contohnya:

```markdown
Jika Anda ingin tahu lebih banyak tentang chat, kunjungi [Chat Console](/wiki/Chat_Console).
```

### Game modifier

Game modifier wajib menggunakan kata `mod` setelah nama mod untuk mengurangi ambiguitas. Ini wajib dieja seperti yang terlihat di bawah ini (huruf besar dan spasi wajib cocok):

- `Easy` atau `EZ`
- `No Fail` atau `NF`
- `Half Time` atau `HT`
- `Daycore` atau `DC`
- `Hard Rock` atau `HR`
- `Sudden Death` atau `SD`
- `Perfect` atau `PF`
- `Double Time` atau `DT`
- `Nightcataue` atau `NC`
- `Fade In` atau `FI`
- `Hidden` atau `HD`
- `Flashlight` atau `FL`
- `Relax` atau `RL`
- `Autopilot` atau `AP`
- `Target Practice` atau `TP`
- `Spun Out` atau `SO`
- `1K`, `2K`, `3K`, `4K`, `5K`, `6K`, `7K`, `8K`, and `9K`
  - Jika mengacu pada mod key secara kolektif, gunakan `xK`.
- `Co-op` atau `CO`
- `Random` atau `RD`
- `Mirratau` atau `MR`
- `Auto` atau `AT`
- `Cinema` atau `CM`
- `Touch Device` atau `TD`
- `ScoreV2`

---

Game modifier ini tidak lagi digunakan oleh osu!; namun, jika diperlukan, wajib dieja seperti yang terlihat di bawah ini (huruf besar dan spasi wajib cocok):

- `Fade Out`
- `No Video`
- `10K`
- `Taiko`

---

Saat menulis game modifier untuk artikel turnamen, mereka wajib menggunakan casing camel atas (hilangkan spasi dan simpan casing huruf seperti yang terlihat di atas).

### Elemen gameplay

Elemen gameplay tidak boleh menggunakan huruf besar, kecuali jika berfungsi sebagai judul untuk tautan yang mengarah ke artikel. Berikut ini contohnya:

```markdown
Di mode permainan osu!, beatmap terdiri dari tiga elemen gameplay yang berbeda: hit circle, slider, dan spinner.
```

### Nama bahasa

Nama bahasa wajib menggunakan huruf besar. Berikut ini contohnya:

```markdown
Kanal chat `#spanish` peruntukkan bagi yang berbicara bahasa Spanyol.
```

### Kata benda yang tepat

Kata benda yang tepat wajib menggunakan huruf besar. Berikut ini contohnya:

```markdown
Dean Herbert (juga dikenal sebagai peppy) menciptakan osu! pada tahun 2007.
```

### Merek Dagang

*untuk aturan tentang osu!, kunjungi: [osu!](#osu!)*

Merek dagang berikut harus dieja sebagai berikut (huruf besar atau huruf kecil harus sesuai):

- `Discord`
- `Facebook`
- `GitHub`
- `Google`
- `Reddit`
- `Skype`
- `Twitch`
- `Twitter`
- `YouTube`

Merek dagang tidak boleh diikuti oleh merek dagang atau simbol merek dagang terdaftar.

## Tanggal dan waktu

### Pemformatan tanggal

Format bisa ditemukan di dalam [Wikipedia:Manual of Style/Dates and numbers § formats](https://en.wikipedia.org/wiki/Wikipedia:Manual_of_Style/Dates_and_numbers#formats "Wikipedia") adalah semua format tanggal yang diterima. Format tanggal harus konsisten di seluruh artikel.

Hanya format tanggal `YYYY-MM-DD` yang harus digunakan di dalam tabel.

### Pemformatan waktu

Pemformatan waktu harus dilakukan dengan format berikut:

```markdown
HH:MM ZONAWAKTU
```

Waktu ditulis dalam format 24 jam dan setiap angka harus diawali dengan nol. Zona waktu harus ditulis segera setelah waktu dan harus dalam UTC+0 untuk acara global. Gunakan `UTC` daripada `GMT` atau di zona waktu acara untuk yang lebih kecil.

Contoh yang buruk:

```markdown
3:30 PM UTC
22:30 (UTC+7)
11:30
```

Contoh yang bagus:

```markdown
15:30 UTC
22:30 UTC+7
11:30 UTC-4
```

`UTC` (tanpa offset) tersirat `UTC+0`. Salah satu dapat digunakan, tetapi penggunaan harus konsisten. UTC dengan offset 0 eksplisit harus menggunakan simbol plus (`+`).

### Pemformatan tanggal dan waktu

Jika tanggal dan waktu digunakan bersamaan, tanggal wajib ditulis terlebih dahulu, diikuti oleh waktu. Waktu wajib diapit di antara tanda kurung (`(` dan `)`).

Contoh yang buruk:

```markdown
October 25, 2016 at 11:45 UTC
October 25, 2016 11:45 UTC
```

Contoh yang bagus:

```markdown
October 25, 2016 (11:45 UTC)
```

## Mode permainan

Mode permainan wajib ditulis sebagai berikut:

- `osu!`
- `osu!taiko`
- `osu!catch`
- `osu!mania`

Mengacu pada nama mode permainan lama (yaitu `Catch the Beat`, `Taiko`, dan `Mania`) mungkin bisa dilakukan jika membahas nama mode permainan sebelumnya.

## osu!

Nama permainan, osu!, tidak boleh menggunakan huruf besar atau miring. Pencitraan merek resmi osu! tidak boleh menggunakan spasi apa pun. Contohnya termasuk:

- `osu!academy`
- `osu!api`
- `osu!catch`
- `osu!direct`
- `osu!keyboard`
- `osu!mania`
- `osu!store`
- `osu!stream`
- `osu!supporter`
- `osu!tablet`
- `osu!taiko`
- `osu!talk`
- `osu!tourney`

Judul pengguna yang menyertakan `osu!` sebagai bagian dari nama judul wajib menggunakan huruf besar. Contohnya termasuk:

- `osu! Alumni`
- `osu! Champion`

untuk semua istilah lainnya, osu! harus diperlakukan sebagai [qualifying noun](https://en.wikipedia.org/wiki/Noun_adjunct "Wikipedia"). Ini berarti menambahkan spasi di antara osu! dan kata benda yang dimodifikasi. Contohnya termasuk:

- `osu! tournaments`
- `osu! community`
- `osu! chat`
- `osu! client`
- `osu! wiki`

---

`osu!` seharusnya tidak mengakhiri kalimat. Jika ya, gunakan tanda titik (`.`) atau tanda tanya untuk mendapatkan `osu!.` atau `osu!?`.

`osu!` tidak boleh diikuti dengan tanda seru (misalnya `osu!!`). Kalimat tersebut wajib ditulis ulang untuk memastikan bahwa ini tidak akan terjadi.

## Terminologi

Kata-kata ini wajib dieja sebagai berikut (spasi wajib sama):

- `approach circle`
- `game mode` (atau `mode`)
- `game mod` (atau `mod`)
- `gameplay`
- `hit burst`
- `hit circle`
- `hitsound`
- `in-game`
- `playstyle`
- `slider tick`
- `slider ball`
- `slider path`
- `Kudosu` (untuk diperlakukan sebagai kata benda yang tepat)

---

Beberapa kata memiliki varian. Ejaan pilihan mereka harus digunakan dan sebagai berikut:

- `beatmap` daripada `map`.
- `creator` daripada `beatmapper` atau `mapper`.
- `mapped` daripada `beatmapped`.
- `BN` atau `Beatmap Nominator` saat mengacu pada *Beatmap Nominator*.
- `sign in` daripada `log in`, kecuali nama tombol atau tautan menyatakan sebaliknya.
- `sign out` daripada `log out`, kecuali nama tombol atau tautan menyatakan sebaliknya.
- `register` daripada `sign up`, kecuali nama tombol atau tautan menyatakan sebaliknya.

### Artikel turnamen

Kata-kata ini wajib dieja sebagai berikut (spasi wajib sama):

- `NoMods`, `NoMod`, atau `NM`
- `FreeMods`, `FreeMod`, atau `FM`
- `Tiebreaker`

## Singkatan, akronim, dan inisialisme

Singkatan, akronim, dan inisialisme wajib memiliki makna tertulis pada kejadian pertama mereka. Kejadian lain bersifat opsional, tetapi dilakukan hanya jika diperlukan. Berikut ini contohnya:

```markdown
Mod NC (Nightcore) mirip dengan mod DT (Double Time) karena NC dan DT meningkatkan kecepatan musik hingga 50%. Namun, NC akan mengubah nada musik dan menambahkan tepuk serta menyelesaikan beat.
```

Singkatan, akronim, dan inisialisme wajib memiliki huruf besar, dengan pengecualian. Berikut ini adalah contohnya:

- `CS` untuk `Circle Size`
- `AR` untuk `Approach Rate`
- `DT` untuk `Double Time`
- `SBS` untuk `Storyboard Scripting`

---

Gunakan `misalnya` untuk "sebagai contoh" dan `yaitu` untuk "itu adalah".

---

Singkatan, akronim, dan inisialisme tidak boleh dijadikan jamak. Berikut ini adalah contohnya:

```markdown
Hindari: BN dapat menominasikan beatmap Anda.

Seharusnya: Beatmap Nominator dapat menominasikan beatmap Anda.
```

## Perspektif

`player`, `user`, `skinner`, `storyboarder`, dan `creator` harus digunakan ketika merujuk pada pembaca atau orang lain. `mereka`, `milik mereka` dapat digunakan saat dibutuhkan.

`kamu` dan `milikmu` harus dihindari. `Saya` tidak boleh digunakan. `kami`, `dia` atau `milik dia` tidak boleh digunakan (lihat di atas untuk istilah lain).

---

[Artikel dengan daftar informal](#daftar-bahasa) boleh mengabaikan bagian ini; namun, penggunaan kata `Saya` dalam paragraf wajib dihindari.

## Tata bahasa dan sintaks

Artikel sebaiknya lebih baik menggunakan yang lebih sederhana [American grammar and syntax](https://www.thepunctuationguide.com/british-versus-american-style.html "The Punctuation Guide").

### Kontraksi

Kontraksi tidak boleh digunakan.

[Artikel dengan daftar informal](#daftar-bahasa) mungkin menggunakan kontraksi; namun, penggunaan harus tetap konsisten di seluruh artikel.

### Angka

*untuk pemformatan angka, kunjungi [Wikipedia's Manual of Style on Number formatting](https://en.wikipedia.org/wiki/Wikipedia:Manual_of_Style#Numbers)*

[Artikel dengan daftar informal](#daftar-bahasa)  boleh mengabaikan bagian ini; namun, penggunaan harus tetap konsisten di seluruh artikel.

### Titik koma

[Artikel dengan daftar informal](#daftar-bahasa) harus menghindari penggunaan titik koma (`;`).

### Koma serial

Koma serial, dikenal juga sebagai koma Oxford atau koma Harvard, wajib digunakan.

### Kutipan logis

Merujuk ke [Wikipedia's Manual of Style for logical quotations](https://en.wikipedia.org/wiki/Wikipedia:Manual_of_Style#Punctuation_inside_or_outside "Wikipedia").

Dari Gay Manual Wikipedia:

> Sertakan tanda baca terminal hanya di dalam tanda kutip jika terdapat di dalam materi asli, dan jika tidak, tempatkan setelah tanda kutip penutup. Untuk sebagian besar, ini berarti memperlakukan titik dan koma dengan cara yang sama seperti tanda tanya: Simpan di dalam tanda petik jika hanya berlaku untuk materi yang dikutip, dan di luar jika berlaku untuk keseluruhan kalimat.

## Pengucapan

Pengucapan tertulis harus menggunakan [International Phonetic Alphabet](https://en.wikipedia.org/wiki/Help:IPA/English "Wikipedia").
