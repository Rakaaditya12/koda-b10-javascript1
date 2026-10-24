# Membuat program hitung luas dan keliling lingkaran

## Alur kerja program

- Membuat 2 function (hitungAwal dan hitungKedua).
- Menjalankan function hitungAwal dengan parameter r & kondisi, dan menjalankan function hitungKedua dengan tanpa parameter.

## Flowchart

```mermaid
    flowchart TD
    A([Start]) --> B[/Jari Jari/]
    B --> C{Pilih Kondisi}
    C --> |Luas| D[3.14 * r * r]
    C --> |Keliling| E[2 * 3.14 * r]
    C --> |ELSE| F[/Input Salah/]
    D --> G[/Cetak Luas/]
    E --> H[/Cetak Keliling/]
    H --> X[/Hasil/]
    G --> X
    F --> Z
    X --> Z[(Selesai)]
```
