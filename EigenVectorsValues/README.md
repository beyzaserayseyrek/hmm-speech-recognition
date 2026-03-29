# Eigenvalues and Eigenvectors

Bu klasör, Makine Öğrenmesi dersi kapsamında gerçekleştirilen 3. laboratuvar çalışmasını içermektedir.

## İçerik

Bu çalışmada aşağıdaki konular ele alınmıştır:

* Matris kavramı
* Özdeğer (eigenvalue) ve özvektör (eigenvector) tanımları
* Bu kavramların makine öğrenmesi ile ilişkisi
* NumPy kütüphanesinin `eig` fonksiyonu ile hesaplama
* Manuel yöntem ile NumPy sonuçlarının karşılaştırılması

## Kullanılan Yöntemler

Özdeğer ve özvektör hesaplaması iki farklı şekilde incelenmiştir:

1. **Manuel yaklaşım (referans repo mantığı)**
   Karakteristik denklem kullanılmıştır:
   det(A − λI) = 0

2. **NumPy yöntemi**
   `numpy.linalg.eig` fonksiyonu kullanılmıştır.

Her iki yöntemde de aynı sonuçlar elde edilmiştir.

## Dosyalar

* `eig_numpy.ipynb` → NumPy eig fonksiyonu kullanımı
* `comparison.ipynb` → Manuel ve NumPy yöntemlerinin karşılaştırılması
* `report.pdf` → Detaylı rapor

## Sonuç

Bu çalışma sonucunda, özdeğer ve özvektör kavramlarının makine öğrenmesinde önemli bir yere sahip olduğu görülmüştür.
Ayrıca NumPy kütüphanesinin bu hesaplamaları hızlı ve pratik bir şekilde gerçekleştirdiği gözlemlenmiştir.
