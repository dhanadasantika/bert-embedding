# Analisis Eksperimen BERT Embedding
Di era NLP modern, model pralatih seperti BERT sangat populer karena kemampuannya memahami konteks kata. Salah satu aspek krusial adalah strategi ekstraksi embedding atau memilih bagian mana dari BERT yang diambil sebagai representasi vektor teks.

Eksperimen ini menganalisis pengaruh enam strategi ekstraksi embedding BERT:

1. First Layer
2. Last Hidden Layer
3. Sum All 12 Layers
4. Second-to-Last Hidden Layer
5. Sum Last Four Hidden Layers
6. Concat Last Four Hidden Layers

Model dievaluasi pada dua tugas berbeda:
* Klasifikasi sentimen (menggunakan dataset IMDB)
* Inferensi logis antar kalimat (menggunakan dataset SNLI)

Tujuannya adalah mendapatkan *insight* tentang strategi embedding mana yang paling efektif berdasarkan jenis tugas dan kompleksitas semantik.
