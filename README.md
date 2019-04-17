ZakatCalc
=========
(c) 2009-2015 Al Farisi & Indokreatif Teknologi.
All rights reserved.

### Docker

Untuk menjalankan aplikasi `zakatcalc` dengan menggunakan docker, anda perlu melakukan instalasi software berikut:

* [Docker](https://docs.docker.com/install/)
* [Docker Compose](https://docs.docker.com/compose/install/)

Berikut ini langkah-langkah untuk menjalankan aplikasi `zakatcalc` dengan menggunakan docker:

```bash
git clone https://github.com/muhammadhanif/zakatcalc.git
```
```bash
cd zakatcalc
```
```bash
docker-compose up -d
```
```bash
docker-compose ps
```

Dengan menggunakan browser akses alamat http://localhost:8080/.

Untuk menghapus kontainer aplikasi `zakatcalc`, gunakan perintah berikut:

```bash
docker-compose down --rmi all
```
