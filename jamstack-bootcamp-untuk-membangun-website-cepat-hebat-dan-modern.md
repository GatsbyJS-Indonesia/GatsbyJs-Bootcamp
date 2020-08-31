---
title: JAMStack Bootcamp untuk membangun website Cepat Hebat dan Modern
date: 2020-08-30
---

# Creating a Gatsby Site

## Instalasi nodejs

* Download file instalasinya di https://nodejs.org/eng
![Download Node.Js](https://i.ibb.co/WtRvzN0/download-nodejs.png)
* Pilih paket sesuai dengan sistem operasi yang anda gunakan, sebagai contoh saya menggunakan linux maka saya pilih paket yang support untuk Linux. Seperti gambar di bawah.
[![download-nodejs-linux.png](https://i.postimg.cc/y8KdDPvq/download-nodejs-linux.png)](https://postimg.cc/kBj9ZW0w) 
* Klik kanan file pada mouse untuk ekstrak file, Pilih Extract Here.
[![extraks-nodejs.png](https://i.postimg.cc/rmx3RSfb/extraks-nodejs.png)](https://postimg.cc/dkQ4zTPm)
* Saya berinama folder misalnya menjadi nodejs seperti gambar berikut:

## Instalasi Gatsby JS

* Buka terminal atau konsole ketikkan perintah untuk masuk ke folder Desktop/nodejs.

```
$ cd Desktop/nodejs/bin/
```

* Install gatsby-cli dengan perintah npm:

```
$ sudo ./npm i g gatsby-cli 
```

* Jika berhasil, akan tampil pesan sebagai berikut:
* Install repository gatsby dengan cara masuk ke folder Desktop dengan perintah:

```
$ cd Desktop
```

* Install repository gatsby-starter-hello-world

```
$ gatsby new gatsby-bootcamp https://github.com/gatsbyjs/gatsby-starter-hello-world
```

* Jika sukses akan ada informasi berikut:

```
Your new Gatsby site has been successfully bootstrapped. Start developing it by
running:
cd gatsby-bootcamp
gatsby develop
```

* Masuk ke folder gatsby-bootcamp dengan perintah:

```
$ cd gatsby-bootcamp
```

* Untuk menguji coba repository gatsbyjs jalankan perintah:

```
$ npm run develop
```
atau
```
$ gatsby develop
```
* Jika sukses akan ada informasi seperti berikut:
* Buka aplikasi browser, jalankan dengan mengetikkan alamat url: localhost:8000
* Jika berhasil akan tampil halaman di browser seperti berikut:

## Mulai Project GatsbyJs

* Pada terminal masuk ke folder src/pages

```
$ cd src/pages
```

* Anda dapat memulai dengan mengetikkan file index.js. Gunakan text editor untuk mengedit/menuliskan script program. Sebagai contoh saya menggunakan text editor vi/vim.
```
$ vi index.js
```

* Isi file index.js seperti berikut:

```
import React from "react"

export default function Home() {
  return <div>Hello world!</div>
}
```

* Anda coba ganti file "Hello world!" dengan "The Greate Gatbsby Bootcamp"
* Coba buka browser anda, otomatis hasilnya akan menampilkan seperti gambar berikut:

## Working wih Gatsby Pages

* Modifikasi file index.js di folder src/pages
* Edit file dengan text editor anda dengan perintah:

```
$ vi index.js
import React from 'react'

const IndexPage = () => {
  return (
    <div>
      <h1>Halo.</h1>
<h2>Saya Muhammad Syukri, seorang web developer gatsby di Indonesia.</h2>
    </div>
  )
}

export default IndexPage
```

* Hasilnya akan terlihat seperti gambar berikut:
* Buat file blog.js di folder src/pages dengan perintah:

```
$ vi blog.js
import React from 'react'

const BlogPage = () => {
   return(
	<div>
	<h1>Blog</h1>
	<p>Halaman Posting Blog anda di sini.</p>
	</div>
    )
}

export default BlogPage
```

* Akses alamat localhost:800/blog di browser anda hasilnya akan terlihat seperti berikut:
* Buat file about.js di folder src/pages perintahnya:

```
$ vi about.js
import React from 'react'

const AboutPage = () => {
   return(
     <div>
	<h1>About Me</h1>
 	<p>Saya bekerja di Areta Informatics College</p>
     </div>
  )
}

export default AboutPage
```

* Hasilnya terlihat seperti gambar berikut:
* Buat file contact.js di folder src/pages perintahnya:

```
$ vi contact.js
import React from 'react'

const ContactPage = () => {
  return(
	<div>
	   <h1>Contact</h1>
	   <p>Saya bisa dihubungi via @syukrie di Twitter!</p>
	</div>
  )
}

export default ContactPage
```

* Hasilnya terlihat seperti gambar berikut:

