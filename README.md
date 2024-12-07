# Movie Recommendation System Documentation

This project implements a movie recommendation system using machine learning techniques like collaborative filtering, matrix factorization, and autoencoders. It uses the MovieLens 20M dataset.

## File Structure

- **data/**: Contains the dataset files (`ratings.csv`, `movies.csv`).
- **src/**: Contains the Python scripts:
  - `preprocessing.py`: Preprocessing the dataset.
  - `collaborative_filtering.py`: Implements the collaborative filtering model (SVD).
  - `autoencoder.py`: Implements an autoencoder model for recommendations.
  - `evaluation.py`: Evaluation metrics for the models.
  - `main.py`: Main script to run the entire project.
- **requirements.txt**: List of dependencies to install.

## How to Run

1. Clone this repository.
2. Install the dependencies using: `pip install -r requirements.txt`.
3. Place the dataset files (`ratings.csv`, `movies.csv`) in the `data/` folder.
4. Run the project using: `python src/main.py`.

## 1. pandas

**Versi**: Terbaru (secara umum)
**Deskripsi**: pandas adalah library Python yang menyediakan struktur data dan analisis data yang sangat cepat, fleksibel, dan mudah digunakan. Pada proyek ini, pandas digunakan untuk memuat dan memanipulasi dataset dalam bentuk DataFrame. Ini memungkinkan kita untuk melakukan operasi seperti filtering, agregasi, dan transformasi data.
**Instalasi**:
    ```bash
    pip install pandas
    ```

## 2. numpy

- **Versi**: Terbaru (secara umum)
- **Deskripsi**: numpy adalah library untuk pemrograman numerik di Python. Ia menyediakan objek array multidimensi dan berbagai fungsi untuk melakukan operasi matematika dan statistik pada array. Di proyek ini, numpy digunakan untuk menangani operasi numerik dalam model autoencoder, terutama saat membuat matriks user-item.
- **Instalasi**:

    ```bash
    pip install numpy
    ```

## 3. scikit-surprise

- **Versi**: Terbaru (secara umum)
- **Deskripsi**: scikit-surprise adalah library untuk membangun dan menganalisis sistem rekomendasi berbasis collaborative filtering. Dalam proyek ini, library ini digunakan untuk mengimplementasikan model SVD (Singular Value Decomposition) yang merupakan metode dalam Collaborative Filtering untuk rekomendasi film.
- **Instalasi**:
  
    ```bash
    pip install scikit-surprise
    ```

## 4. matplotlib

- **Versi**: Terbaru (secara umum)
- **Deskripsi**: matplotlib adalah library visualisasi data yang digunakan untuk membuat grafik 2D. Di proyek ini, matplotlib digunakan untuk memvisualisasikan performa model dan membandingkan hasil evaluasi model menggunakan grafik seperti kurva loss dan metrik lainnya.
- **Instalasi**:
  
    ```bash
    pip install matplotlib
    ```

## 5. joblib

- **Versi**: Terbaru (secara umum)
- **Deskripsi**: joblib adalah library yang digunakan untuk serialisasi objek Python, seperti model yang telah dilatih. Library ini digunakan dalam proyek ini untuk menyimpan model yang sudah dilatih agar dapat digunakan kembali tanpa perlu pelatihan ulang. Model yang disimpan bisa berupa model SVD atau model autoencoder.
- **Instalasi**:
  
    ```bash
    pip install joblib
    ```

## 6. tensorflow

- **Versi**: Terbaru (secara umum)
- **Deskripsi**: tensorflow adalah library open-source untuk komputasi numerik yang memungkinkan pengembangan dan pelatihan model machine learning, termasuk neural network. Pada proyek ini, tensorflow digunakan untuk membangun dan melatih autoencoder, sebuah jenis neural network untuk pemodelan rekomendasi.
- **Instalasi**:
  
    ```bash
    pip install tensorflow
    ```

## 7. keras

- **Versi**: Terbaru (secara umum)
- **Deskripsi**: keras adalah API tingkat tinggi untuk membangun dan melatih model deep learning. keras berjalan di atas tensorflow dan mempermudah pembuatan model neural network. Di proyek ini, keras digunakan untuk membangun arsitektur autoencoder dan melakukan training untuk sistem rekomendasi berbasis neural network.
- **Instalasi**:
  
    ```bash
    pip install keras
    ```

## Cara Menggunakan `requirements.txt`

### Menginstal Semua Dependensi

Untuk menginstal semua dependensi yang tercantum dalam file `requirements.txt`, jalankan perintah berikut di terminal atau command prompt:

```bash
pip install -r requirements.txt
