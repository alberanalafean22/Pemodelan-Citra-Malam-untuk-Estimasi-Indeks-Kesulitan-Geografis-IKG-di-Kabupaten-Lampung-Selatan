
# Pemodelan-Citra-Malam-untuk-Estimasi-Indeks-Kesulitan-Geografis-IKG-di-Kabupaten-Lampung-Selatan


Tujuan: Memodelkan Nilai Estimasi Indeks Kesulitan Geografis (IKG) desa di Lampung Selatan tahun 2021

Metode: Machine Learning (Support Vector Machine)

Tools: Python (Google Collab) integration Google Earth Engine(GEE)

Sumber Data : 

*   Data Citra VIIRS tahun 2021 : https://eogdata.mines.edu
*   Data Citra Copernicus(GEE) tahun 2021
*   Data DEM : http://tanahair.indonesia.go.id/demnas
*   Data Shapefile Desa di Lampung Selatan : www.indonesia-geospasial.com
*   Data IKG Desa Lampung Selatan tahun 2021 : BPS Provinsi Lampung

Tahapan
*   Preprocessing Data
      *   Clip Raster
      *   Kalkulasi Intensitas raster VIIRS
      *   Kalkulasi Jumlah Bangunan desa
      *   Kalkulasi Ketinggian Desa
      *   Peta Klasifikasi
      *   Transformasi Data
      *   Normalisasi Data
*   Uji Hipotesis
*   Model Support Vector Machine
*   Evaluasi Model
      *   MSE
      *   MAE
      *   RMSE
      *   R-Squared
*   Korelasi Pearson actual dan predicted dari model
*   analisis model
