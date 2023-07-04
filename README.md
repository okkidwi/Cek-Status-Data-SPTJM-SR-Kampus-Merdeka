![image](https://github.com/okkidwi/Cek-Status-Data-SPTJM-SR-Kampus-Merdeka/assets/64502893/bcb0b5ff-801b-4c7b-989d-cc84b04c2d65)

<h1 align="center">Cek Status Data SPTJM & SR Kampus Merdeka</h1>

<div align="center">

### Sebuah Userscript Untuk Mengecek Status Data SPTJM & Surat Rekomendasi (SR) Kampus Merdeka Batch 5 Tahun 2023

[![](https://img.shields.io/badge/Author-okkidwi-green.svg)](https://github.com/okkdwi)
[![](https://img.shields.io/github/license/okkidwi/chathub?Cek-Status-Data-SPTJM-SR-Kampus-Merdeka=green)](../LICENSE.md)
[![](https://img.shields.io/badge/Support-Chrome/Firefox/Edge/Opera/Brave/Vivaldi/Safari-989898.svg)](#compatibility)
[![](https://img.shields.io/github/commit-activity/m/okkidwi/Cek-Status-Data-SPTJM-SR-Kampus-Merdeka?label=Commits)](https://github.com/okkidwi/Cek-Status-Data-SPTJM-SR-Kampus-Merdeka/commits/main)
[![](https://img.shields.io/static/v1?label=%20&message=https%3A%2F%2Flinktr.ee/okkidwi&labelColor=464747&color=black&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABUAAAAVCAYAAACpF6WWAAAAAXNSR0IB2cksfwAAAAlwSFlzAAALEwAACxMBAJqcGAAAAz9JREFUeJyNVUtIW1EQff4WggvRhfjbmEUjNo2LBIrQggsRWl0JIliKIC4E3YikSIWKEEQQwYXQgKCt4EIFUVF3ytMadCWklOIPUQRBE83PXz5veubhveTFRDpwue+9zD1z5szMjaKkse7u7nfb29s/jo6O/pycnATPzs4ip6en/uPjY8/W1tbE4eGhLd3ZZ9bT0/Nmf39ffXx81OjJZmdnqbGxkW5vbynRzs/PV/r6+kwvAi4vL38Kh8OGk3t7e5SVlUWdnZ20trZG8KH7+3tyu920tLREQRi+fUgJuLq6+vnh4SHGQEiZpqamqKGhgVpaWgg/G1ZGRoZ87ujoIBCJra+v1xkAh4aGrIgeRtqEdHRmyUCpVl5eHjU1NdHGxgaFQqHg9PR0hQSFNio+/BeQYNfW1kbDw8NSpmg0SijmjA44OTn5Hiw1ZpgOhJlnZ2fre2lpKUUiEYrFYqRpGsXjcQPwwsLCawXt8tPlcuk6DgwMGMAEkNAwNzeXHA4H3dzc0OjoKHV1dTE7PQAbBzk4OPimXF9f/2UwEdVsNkvAxABWq5W8Xq/0Y1a7u7u6BPwuGF9dXf1SAoFAaG5uTqawuLhoYCfSR3Up2VAcqq+vp9raWvL7/fo3dEJQQZNHx8bGpCPaTrJlYGbMOxg8A2XWvDY3N/UATxZXMCWB5uZmgzPrVFZWRpmZmZItZyO0S2UMzgYfn4KG/82Nnmg7OzuUn59vKFhhYSG1t7fT+Pi4BEg0Dsg6A09VkO7E3d2dwaG6ulrXMScnRy5RuPLy8pRMORimkkEdClrJLio3Pz9PBQUFUsfkluJ3DpjMFEBks9lYd+3y8tKsDwCor3D1iouLdQDWMhGMn8Xotra2GgBVVdUHwul0clt9l2N6cXFRwQXjXhRpMnAyU959Pp+hOFVVVVRTU8PXohe/lRguFYzqR9wBMXYSwEICXqwrZyJS50Hg/rTb7Zx2FBK8TXn94UAdogX57mSQ5NvKZDLp/ToyMkJFRUXU29vLfe1Fr6cGFAZ9TQCf8Xg81N/fT5WVlbJfebdYLDQ4OEj4W4Gb5sIElbwImGjI0IJDX7G7kZofl4iG2ymAbyoK8gXPr9Kd/Qdrlspm3F/gPAAAAABJRU5ErkJggg==)](https://linktr.ee/okkidwi)

### Install

<a href="https://chatgptwidescreen.com/greasyfork" target="_blank"><img height="44px" src="https://raw.githubusercontent.com/adamlui/chatgpt-widescreen/main/media/images/badges/greasy-fork/available-on-greasy-fork-gold-square-border-light-816x262.png" alt="Install Melalui Greasyfork"></a>

</div>

##

## ✨ Fitur

- Menampilkan status data SPTJM & Surat Rekomendasi (SR) Kampus Merdeka yang telah anda upload di https://kampusmerdeka.kemdikbud.go.id seperti:
  * Status KESALAHAN, SKRIP GAGAL MENGURAI DATA ANDA: skrip tidak berjalan dengan sempurna, install kembali skrip diatas
  * Status Data SPTJM atau SURAT REKOMENDASI tidak ditemukan: data SPTJM & Surat Rekomendasi (SR) belum anda upload
  * %c[${dateTimeWIB} WIB] Status SPTJM anda adalah %c${statusUserSptjm}

| %c[${dateTimeWIB} WIB]                           | %c${statusUserSptjm}                                                                                        |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| Hari: Numeric, contoh: Senin                 | ON_REVIEW: Data SPTJM & Surat Rekomendasi (SR) anda sedang dalam proses review                      |
| Tanggal: Numeric, contoh: 15                  | VERIFIED: Data SPTJM & Surat Rekomendasi (SR) anda telah terverifikasi                             |
| Bulan: Long, contoh: Januari                 | REJECTED: Data SPTJM & Surat Rekomendasi (SR) anda ditolak                                        |
| Tahun: Numerik, contoh: 2023                 |                                                                                                    |
| Jam & Menit: Numerik, 14.00                  |                                                                                                    |
| Zona Waktu: Indonesia/Asia/Jakarta (WIB) |                                                                                                    |
