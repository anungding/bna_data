# BNA DATA
- Dashboard
- Dataset

#### Install App
- Clone repository ke lokal
- Install Dependencies
- Run python -m streamlit run app.py

#### Notes
- Semua data .csv ada di folder dataset
- Semua data diambil dari BPS Kabupaten Banjarnegara, Banajarnegara Satu Datu, dan Sumber data resmi lainya milik pemerintah/lembaga/organsiasi resmi.
##### DATA BNA UNTUK SEMUA

# DOC
### Format .csv file untuk data GIS
| kecamatan  | x          | y          | total  |
|------------|------------|------------|--------|
| Mandiraja  | bla        | bli        | 28000  |
| Sigaluh    | bla        | bli        | 34000  |
| dst.       | dst.       | dst        | dst    |

##### Harus ada kolom kecamatan dan kolom total.
##### Dataset harus dari sumber resmi (BPS atau website milik pemerintah)

### Struktur Konten (Pages)
#### example:
- Judul (DATA KESEHATAN BNA)
    - Sub Judul 1 (DATA TENAGA KESEHATAN BNA)
        - Filter
        - Card
        - Chart
        - Map (Opsional)
        - Dataset
    - Sub Judul 2 (DATA FASILITAS KESEHATAN BNA)
        - Filter
        - Card
        - Chart
        - Dataset
