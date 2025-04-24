# Penjelasan Struktur Folder
## Struktur Folder<br>
├───data <br>
│   └───results <br>
└───notebooks <br>
............├───EDA <br>
............├───Modeling <br> 
............└───temp <br>

__Folder:__
1. "data" Pada folder data adalah tempat untuk menyimpan dataset-datasets.
2. "result" adalah hasil datasets yang sudah di preprocessing.
3. "notebooks" adalah folder berisikan kumpulan-kumpulan process kode EDA dan modeling.
4. "EDA" adalah folder berisi kode untuk insight datasets dan mengelola datasets
5. "Modeling" adalah folder berisi kode untuk pembuatan model dan evaluasi model sampai mendapatkan model yang terbaik.
6. "temp" adalah folder berisi kode untuk melakukan tes kode python.

**File:**
1. "Datafull terakhir test.csv" dan "Datafull train.csv" adalah file datasets yang masih mentah yang di berikan juri.
2. "Clean_DataFull_Terakhir_Test.csv" dan "Clean_Datafull_Train.csv" adalah versi datasets yang sudah melalui proses cleaning.
3. "EDA_and_PreProcessing_train_dataset.ipynb" adalah kode untuk melakukan Exploratory Data Analysis(EDA) dan melakukan pre-processing data pada __datasets mentah__.
4. "PreProcessing_testing_dataset.ipynb" adalah kode untuk melakukan Exploratory Data Analysis(EDA) dan melakukan pre-processing data pada __datasets matang__.
5. "prototyping_model.ipynb" adalah file untuk melakukan penulisan kode modeling dan evaluasi pada __datasets kotor__, bisa di bilang seadanya dulu.
6. "implements_model.ipynb" adalah file untuk melakukan penulisan kode modeling dan evaluasi pada __datasets yang sudah matang__ dan melakukan testing features manual.