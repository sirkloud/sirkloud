---
title: "Memasang Banyak Font Sekaligus di Linux Mint"
meta_title: ""
description: "this is meta description"
date: 2020-06-22
image: "/images/post-banner/post1-banner.png"
categories: ["Linux"]
author: "Krisna Amarta"
tags: ["Font"]
draft: false
---

Salah satu hal utama bagi para desainer grafis adalah memilih font secara tepat. Namun pada distro Linux Mint Mate saya mengalami beberapa kendala saat memasang / menginstall font.

Beberapa kendala yang saya alami saat memasang font dengan yaitu proses pemasangan yang agak lama, Mate Font Viewer tidak memberikan alert ketika font sudah terpasang, tidak bisa memasang font lebih dari 1 secara langsung.

Tapi setelah 5 menit saya mencoba mencari-cari letak folder font, akhirnya saya menemukan solusi dari semua masalah tersebut.

#### Memasang Font Secara Manual
Maksud dari memasang font secara manual adalah memasang font tanpa menggunakan bantuan font viewer seperti Mate Font Viewer
Bagaimana caranya? Simak dibawah ini.

Pertama - tama siapkan font yang akan dipasang, lalu buka file manajer kalian. Lalu arahkan direktori file manajer ke /home/user seperti gambar dibawah. User adalah nama user komputer kalian.

{{< image src="images/post/gambar1.png" caption="/home/user" alt="gambar" height="" width="" position="center" command="fill" option="q100" class="img-fluid" title=""  webp="true" >}}

Lalu setelah itu, buka folder .local, pastikan opsi show hidden folders aktif, jika tidak maka folder .local tidak akan muncul.

Di dalam .local terdapat folder share, kalian buka saja, kemudian pilih folder fonts. Jadi nantinya seperti ini 
**_/home/user/.local/share/fonts._**

{{< image src="images/post/gambar2.png" caption="/home/user/.local/share/fonts." alt="gambar" height="" width="" position="center" command="fill" option="q100" class="img-fluid" title=""  webp="true" >}}

Setelah itu kalian tinggal copy font yang akan di install lalu paste pada folder tersebut.
Kalian juga bisa memasang banyak font dengan cara ini, cukup pilih font mana yang akan dipasang, lalu salin di folder tersebut.

{{< notice "note" >}}
Cara ini bisa kalian lakukan di ubuntu, dan beberapa distro turunan debian lainnya.
{{< /notice >}}