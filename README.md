# EAS Analitika Bisnis

## Tentang

EAS mata kuliah analitika bisnis. Mengimplementasikan Genetic Algorithm dan Google OR-tools untuk traveling salesman problem pada 15 dataset TSPLIB. Membandingkan hasilnya dengan hasil algoritma SOS dan DSOS pada paper _"Discrete symbiotic organisms search algorithm for travelling salesman problem"_ (https://doi.org/10.1016/j.eswa.2017.06.007).

## Buka Instan

**Kode tidak akan bisa dijalankan tanpa dataset.py**

Buka di [Google Colab](https://colab.research.google.com/github/rochimfn/eas-analitika-bisnis/blob/main/EAS.ipynb)

## Pemasangan

Paket `ortools` tidak tersedia pada lingkungan anaconda maupun conda. Google `ortools` [hanya tersedia](https://github.com/google/or-tools/issues/92#issuecomment-518730316) pada lingkungan official python (pypi). Sehingga untuk memasang dependensi dan menjalankan kode diperlukan `pip`. Secara bawaan `pip` akan turut dipasang saat `python` dipasang.

Pertama buka console atau terminal pada folder program(eas-analitika-bisnis-main). Pada windows cara paling mudah adalah dengan membuka folder program pada windows explorer lalu menekan tombol `shift` dan klik kanan mouse secara bersamaaan. Akan muncul pilihan _Open PowerShell window here_ / _Open Command prompt window here_. Pilih pada pilihan tersebut untuk membuka folder pada console.

### Menggunakan Virtualenv (Disarankan)

Jika ingin memasang program pada lingkungan virtualenv(terisolasi) silahkan jalankan perintah berikut pada console.

```bash
python3 -m venv venv
# atau
python -m venv venv
# atau
virtualenv3 venv
# atau
python3 -m virtualenv venv
```

Masuk ke virtual environments

```bash
venv\Scripts\activate # pada Windows
source venv/bin/activate # pada *nix os
```

Memasang dependensi dengan `pip`

```bash
pip install -r requirements.txt
```

### Pemasangan Langsung

Jika ingin memasang program pada lingkungan global silahkan jalankan perintah berikut pada console.

Memasang dependensi dengan `pip`

```bash
pip install -r requirements.txt
```

## Penggunaan

Terdapat dua jenis program, yang ditulis dalam format jupyter notebook (`EAS.ipynb`) dan dalam format python pada umumnya (`eas.py`). Notebook dapat dibuka dengan aplikasi Jupyter lab atau notebook. Sedangkan `eas.py` dapat dibuka pada aplikasi yang mendukung lingkungan IPython, kami telah menyertakan IDE dengan nama `spyder`.

### Menggunakan Jupyter lab atau notebook

Buka Jupyter lab atau notebook dengan menjalankan perintah berikut pada console yang digunakan saat pemasangan.

```bash
jupyter lab EAS.ipynb # Jika menggunakan Jupyter-lab
jupyter notebook EAS.ipynb # Jika menggunakan Jupyter-notebook
```

Tunggu sebentar dan browser akan membuka notebook `EAS.ipynb`

### Menggunakan Sypder

Buka Sypder IDE dengan menjalankan perintah berikut pada console yang digunakan saat pemasangan.

```bash
spyder -p "."
```

Tunggu sebentar dan sypder akan terbuka.
