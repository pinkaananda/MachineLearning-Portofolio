"Machine Learning Portofolio"

Terdapat 3 file tugas Portofolio
1. melakukan Segmentasi Data dengan metode Clustering
2. melakukan dan membandingkan beberapa model Supervised Learning
3. mendesain dan buat neural network sederhana (bukan CNN, namun dengan perceptron model) untuk MNIST Handwritten Digit Dataset

Segmentasi Data dengan Metode Clustering
Hal-hal yang dilakukan
1. Preparing
2. Import Library
3. Input Dataset
4. Preprocessing
5. Train-Test Split
6. Modeling
7. Membuat Kesimpulan

Membandingkan Model Supervised Learning

Membuat Desain Neural Network Sederhana MNIST Handwritten Digit Dataset

### Deteksi Digit Tulisan Tangan dengan Model Neural Network

#### Langkah 1: Memuat dan Persiapkan Dataset MNIST
Langkah pertama melibatkan pemuatan dataset MNIST, yang merupakan kumpulan gambar digit tulisan tangan dari 0 hingga 9. Dataset ini dibagi menjadi data pelatihan dan pengujian untuk melatih dan menguji model.

#### Langkah 2: Visualisasi Data MNIST
Setelah dataset dimuat, dilakukan visualisasi beberapa gambar dari dataset untuk memberikan gambaran tentang bentuk dan variasi digit tulisan tangan yang ada.

#### Langkah 3: Desain Model Neural Network
Model Neural Network sederhana dibangun dengan lapisan-lapisan linear (fully connected) untuk mengenali pola dalam gambar. Model ini dirancang untuk menerima gambar dengan ukuran 28x28 piksel.

#### Langkah 4: Setup Hyperparameter
Parameter-model seperti fungsi kerugian (loss) dan optimizer diatur untuk melatih model dengan efisien. Dalam hal ini, CrossEntropyLoss digunakan sebagai fungsi kerugian dan Stochastic Gradient Descent (SGD) sebagai optimizer.

#### Langkah 5: Training Loop
Model dilatih dengan data pelatihan menggunakan loop pelatihan. Proses ini berlangsung selama beberapa epoch, dengan hasil kerugian yang dicetak untuk setiap batch dari data pelatihan.

#### Langkah 6: Evaluasi Model
Model dievaluasi menggunakan data pengujian untuk mengukur akurasi dan kinerja keseluruhan. Hasil akhir termasuk akurasi, F1 Score, Precision, Recall, dan Confusion Matrix, yang memberikan gambaran tentang seberapa baik model dapat mengenali digit tulisan tangan.

#### Hasil dan Kesimpulan
Model berhasil dilatih dan dievaluasi dengan baik, menunjukkan akurasi sekitar 92.72%. Hasil evaluasi menunjukkan kemampuan model dalam mengklasifikasikan digit tulisan tangan dengan presisi dan recall yang tinggi. Informasi ini dapat membantu untuk memahami sejauh mana model dapat digunakan dalam mendeteksi digit tulisan tangan pada dataset MNIST.