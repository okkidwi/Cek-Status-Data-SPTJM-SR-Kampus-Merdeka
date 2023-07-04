![image](https://github.com/okkidwi/Cek-Status-Data-SPTJM-SR-Kampus-Merdeka/assets/64502893/bcb0b5ff-801b-4c7b-989d-cc84b04c2d65)

<h1 align="center">Cek Status Surat Rekomendasi (SR) SPTJM & SR Kampus Merdeka</h1>

<div align="center">

### Sebuah Userscript Untuk Mengecek Status Data SPTJM & Surat Rekomendasi (SR) Kampus Merdeka Batch 5 Tahun 2023

[![](https://img.shields.io/badge/Author-okkidwi-green.svg)](https://github.com/okkdwi)
[![](https://img.shields.io/github/license/okkidwi/chathub?Cek-Status-Data-SPTJM-SR-Kampus-Merdeka=green)](../LICENSE.md)
[![](https://img.shields.io/badge/Support-Chrome/Firefox/Edge/Opera/Brave/Vivaldi/Safari-989898.svg)](#compatibility)
[![](https://img.shields.io/github/commit-activity/m/okkidwi/Cek-Status-Data-SPTJM-SR-Kampus-Merdeka?label=Commits)](https://github.com/okkidwi/Cek-Status-Data-SPTJM-SR-Kampus-Merdeka/commits/main)
[![](https://img.shields.io/static/v1?label=%20&message=https%3A%2F%2Flinktr.ee/okkidwi&labelColor=464747&color=black&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABUAAAAVCAYAAACpF6WWAAAAAXNSR0IB2cksfwAAAAlwSFlzAAALEwAACxMBAJqcGAAAAz9JREFUeJyNVUtIW1EQff4WggvRhfjbmEUjNo2LBIrQggsRWl0JIliKIC4E3YikSIWKEEQQwYXQgKCt4EIFUVF3ytMadCWklOIPUQRBE83PXz5veubhveTFRDpwue+9zD1z5szMjaKkse7u7nfb29s/jo6O/pycnATPzs4ip6en/uPjY8/W1tbE4eGhLd3ZZ9bT0/Nmf39ffXx81OjJZmdnqbGxkW5vbynRzs/PV/r6+kwvAi4vL38Kh8OGk3t7e5SVlUWdnZ20trZG8KH7+3tyu920tLREQRi+fUgJuLq6+vnh4SHGQEiZpqamqKGhgVpaWgg/G1ZGRoZ87ujoIBCJra+v1xkAh4aGrIgeRtqEdHRmyUCpVl5eHjU1NdHGxgaFQqHg9PR0hQSFNio+/BeQYNfW1kbDw8NSpmg0SijmjA44OTn5Hiw1ZpgOhJlnZ2fre2lpKUUiEYrFYqRpGsXjcQPwwsLCawXt8tPlcuk6DgwMGMAEkNAwNzeXHA4H3dzc0OjoKHV1dTE7PQAbBzk4OPimXF9f/2UwEdVsNkvAxABWq5W8Xq/0Y1a7u7u6BPwuGF9dXf1SAoFAaG5uTqawuLhoYCfSR3Up2VAcqq+vp9raWvL7/fo3dEJQQZNHx8bGpCPaTrJlYGbMOxg8A2XWvDY3N/UATxZXMCWB5uZmgzPrVFZWRpmZmZItZyO0S2UMzgYfn4KG/82Nnmg7OzuUn59vKFhhYSG1t7fT+Pi4BEg0Dsg6A09VkO7E3d2dwaG6ulrXMScnRy5RuPLy8pRMORimkkEdClrJLio3Pz9PBQUFUsfkluJ3DpjMFEBks9lYd+3y8tKsDwCor3D1iouLdQDWMhGMn8Xotra2GgBVVdUHwul0clt9l2N6cXFRwQXjXhRpMnAyU959Pp+hOFVVVVRTU8PXohe/lRguFYzqR9wBMXYSwEICXqwrZyJS50Hg/rTb7Zx2FBK8TXn94UAdogX57mSQ5NvKZDLp/ToyMkJFRUXU29vLfe1Fr6cGFAZ9TQCf8Xg81N/fT5WVlbJfebdYLDQ4OEj4W4Gb5sIElbwImGjI0IJDX7G7kZofl4iG2ymAbyoK8gXPr9Kd/Qdrlspm3F/gPAAAAABJRU5ErkJggg==)](https://linktr.ee/okkidwi)

### Instal

<a href="https://chatgptwidescreen.com/greasyfork" target="_blank"><img height="44px" src="https://raw.githubusercontent.com/adamlui/chatgpt-widescreen/main/media/images/badges/greasy-fork/available-on-greasy-fork-gold-square-border-light-816x262.png" alt="Instal Melalui Greasyfork"></a>

</div>

## ✨ Fitur

- Menampilkan status data SPTJM & Surat Rekomendasi (SR) Kampus Merdeka yang telah anda upload di https://kampusmerdeka.kemdikbud.go.id seperti:
  
  * Status `KESALAHAN, SKRIP GAGAL MENGURAI DATA ANDA`: Skrip tidak berjalan dengan sempurna, instal kembali skrip diatas
  * Status `Data SPTJM atau SURAT REKOMENDASI tidak ditemukan`: Data SPTJM & Surat Rekomendasi (SR) belum anda upload
  * `(Hari, Tanggal Bulan Tahun pukul [Jam.Menit] Zona Waktu)` Status SPTJM anda adalah `(Status Data)`
  * `(Hari, Tanggal Bulan Tahun pukul [Jam.Menit] Zona Waktu)` Status Surat Rekomendasi anda adalah `(Status Data)`

| `(Hari, Tanggal Bulan Tahun pukul [Jam & Menit]`                           | `(Status Data)`                                                                                        |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| `Hari`: Numeric, contoh: Senin                 | `ON_REVIEW`: Data SPTJM & Surat Rekomendasi (SR) anda sedang dalam proses review                      |
| `Tanggal`: Numeric, contoh: 15                  | `VERIFIED`: Data SPTJM & Surat Rekomendasi (SR) anda telah terverifikasi                             |
| `Bulan`: Long, contoh: Januari                 | `REJECTED`: Data SPTJM & Surat Rekomendasi (SR) anda ditolak                                        |
| `Tahun`: Numerik, contoh: 2023                 |                                                                                                    |
| `Jam.Menit`: Numerik, 14.00                  |                                                                                                    |
| `Zona Waktu`: Indonesia/Asia/Jakarta (WIB) |                                                                                                    |

## Instalasi

### <img style="margin: 0 2px -1px 0" height=16 src="https://favicon-generator.org/favicon-generator/htdocs/favicons/2023-07-04/50a84d541c2f7c791c9c3f9faeafe352.ico.png"> <img style="margin: 0 2px -1px 0" height=16 src="https://favicon-generator.org/favicon-generator/htdocs/favicons/2023-07-04/afdcf7209fcd4b14fb521ee04f24e676.ico.png"> Console Browser:

1. Buka website https://kampusmerdeka.kemdikbud.go.id menggunakan desktop PC / Laptop | Windows / macOS
2. Pastikan anda telah login
3. Buka devtools pada browser anda dengan cara:
  * <img style="margin: 0 2px -1px 0" height=16 src="https://favicon-generator.org/favicon-generator/htdocs/favicons/2023-07-04/50a84d541c2f7c791c9c3f9faeafe352.ico.png"> `Windows` | Chrome / Firefox / Microsoft Edge / Opera / Brave / Vivaldi , gunakan shortcut keyboard `CTRL + SHIFT + J` / `Klik Kanan > Inspect > Console`
  * <img style="margin: 0 2px -1px 0" height=16 src="https://favicon-generator.org/favicon-generator/htdocs/favicons/2023-07-04/afdcf7209fcd4b14fb521ee04f24e676.ico.png"> `macOS` | Safari, gunakan shortcut keyboard `CMD + OPTION + J`
![Screenshot 2023-07-05 043823](https://github.com/okkidwi/Cek-Status-Data-SPTJM-SR-Kampus-Merdeka/assets/64502893/9e9ab4e6-b951-41df-ab3a-4a57dafe67af)
4. Copy & paste kode yang dilampirkan dibawah, kemudian tekan Enter
```
  const printErrorShouldLoginBefore = () => {
    console.log(
      '%cKESALAHAN, SKRIP GAGAL MENGURAI DATA ANDA',
      'font-size: 18px; color: #f00; background: #000;'
    );
    throw new Error('NOT_LOGGED_IN');
  };

  const printGenericError = (err) => {
    console.log(
      `%cError: ${err}`,
      'font-size: 18px; color: #f00; background: #000;'
    );
    throw err;
  };

  const currentCycle = 5;

  const userLocalKey = `@mkbm/manager/user`;
  const storageData = localStorage.getItem(userLocalKey);
  if (!storageData) {
    printErrorShouldLoginBefore();
  }
  const storageDataParsed = JSON.parse(storageData);
  if (!storageDataParsed) {
    printErrorShouldLoginBefore();
  }
  const token = storageDataParsed?.value?.token;
  if (!token) {
    printErrorShouldLoginBefore();
  }

  const abortController = new AbortController();

  const getActiveDocuments = async () => {
    const resp = await fetch(
      'https://api.kampusmerdeka.kemdikbud.go.id/v1alpha1/documents?type=SPTJM,SURAT_REKOMENDASI&programs=Magang',
      {
        signal: abortController.signal,
        headers: {
          Authorization: `Bearer ${token}`,
        },
      }
    ).then((resp) => resp.json());
    const docs = resp.data;
    const mapDocumentByType = {};
    docs.forEach((doc) => {
      if (!(doc.type in mapDocumentByType)) {
        mapDocumentByType[doc.type] = [];
      }

      doc.cycle_int = Number.parseInt(doc.cycle);
      mapDocumentByType[doc.type].push(doc);
    });

    return mapDocumentByType;
  };

  const getDocumentLatestCycle = (currentCycle, data) => {
    const sortedData = [...data].sort(
      (docA, docB) => docB.cycle_int - docA.cycle_int
    );
    return sortedData.find((doc) => doc.cycle_int <= currentCycle);
  };

  const getUserDocumentStatus = async (docId, docType) => {
    const resp = await fetch(
      `https://api.kampusmerdeka.kemdikbud.go.id/v1alpha1/documents/${docId}/users`,
      {
        headers: {
          Authorization: `Bearer ${token}`,
        },
      }
    ).then((resp) => resp.json());

    const status = resp?.data?.status;
    if (!status) {
      return `DATA ${docType} TIDAK DAPAT DITEMUKAN`;
    }

    return status;
  };

  const getCurrentDateTimeWIB = () => {
    const date = new Date();
    const options = {
      weekday: 'long',
      year: 'numeric',
      month: 'long',
      day: 'numeric',
      hour: 'numeric',
      minute: 'numeric',
      timeZone: 'Asia/Jakarta',
    };
    return date.toLocaleString('id-ID', options);
  };

  const main = async () => {
    try {
      const documentMapped = await getActiveDocuments();
      const docsSPTJM = documentMapped['SPTJM'];
      const docsSR = documentMapped['SURAT_REKOMENDASI'];

      if (!docsSPTJM || !docsSR) {
        throw 'Data SPTJM atau SURAT REKOMENDASI tidak ditemukan';
      }

      const validDocSPTJM = getDocumentLatestCycle(currentCycle, docsSPTJM);
      const validDocsSR = getDocumentLatestCycle(currentCycle, docsSR);

      if (!validDocSPTJM || !validDocsSR) {
        throw 'Data SPTJM atau SURAT REKOMENDASI tidak ditemukan';
      }

      const sptjmId = validDocSPTJM.id;
      const srId = validDocsSR.id;
      const statusUserSptjm = await getUserDocumentStatus(sptjmId, 'SPTJM');
      const statusUserSr = await getUserDocumentStatus(srId, 'SURAT REKOMENDASI');

      const dateTimeWIB = getCurrentDateTimeWIB();

      console.log(
        `%c[${dateTimeWIB} WIB] Status SPTJM anda adalah %c${statusUserSptjm}`,
        'font-size: 24px; color: black; background: white;',
        `font-size: 30px; background: ${
          statusUserSptjm === 'VERIFIED'
            ? 'green'
            : statusUserSptjm === 'REJECTED'
            ? 'red'
            : 'blue'
        }; color: white;`
      );
      console.log(
        `%c[${dateTimeWIB} WIB] Status SURAT REKOMENDASI anda adalah %c${statusUserSr}`,
        'font-size: 24px; color: black; background: white;',
        `font-size: 30px; background: ${
          statusUserSr === 'VERIFIED'
            ? 'green'
            : statusUserSr === 'REJECTED'
            ? 'red'
            : 'blue'
        }; color: white;`
      );
    } catch (err) {
      printGenericError(err);
    }
  };

main();
```
5. Silahkan tunggu sebentar, dan baca status data yang ditampilkan pada console tersebut
