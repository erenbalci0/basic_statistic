# basic_statistic

###Soru1

### Veriler:
- Sınıf Aralıkları ve Frekanslar:
  - 0-2: 210
  - 2-4: 190
  - 4-6: 50
  - 6-8: 30
  - 8-10: 20

### Adım 1: Sınıf Orta Noktaları Hesaplama
Formül: 
\[
\text{Orta Nokta} = \frac{\text{Alt Sınır} + \text{Üst Sınır}}{2}
\]

Sonuçlar:
- 0-2: 1.0
- 2-4: 3.0
- 4-6: 5.0
- 6-8: 7.0
- 8-10: 9.0

### Adım 2: Göreli Frekans Hesaplama
Formül:
\[
\text{Göreli Frekans} = \frac{\text{Frekans}}{\text{Toplam Frekans}}
\]

**Toplam Frekans:**
\[
210 + 190 + 50 + 30 + 20 = 500
\]

Sonuçlar:
- 0-2: 0.42
- 2-4: 0.38
- 4-6: 0.10
- 6-8: 0.06
- 8-10: 0.04

### Adım 3: Kümülatif Frekans Hesaplama
Kümülatif frekans, her sınıfın frekansını kendisinden önceki frekanslarla toplayarak hesaplanır.

Sonuçlar:
- 0-2: 210
- 2-4: 400
- 4-6: 450
- 6-8: 480
- 8-10: 500

### Adım 4: Merkezi Eğilim Ölçütleri

#### Aritmetik Ortalama:
\[
\bar{x} = \frac{\sum f \cdot x}{\sum f}
\]
- \( \sum f \cdot x = (210 \cdot 1) + (190 \cdot 3) + (50 \cdot 5) + (30 \cdot 7) + (20 \cdot 9) = 1420 \)
- \( \sum f = 500 \)

\[
\bar{x} = \frac{1420}{500} = 2.84
\]

#### Mod:
En yüksek frekans 210 olup, mod bu sınıfın orta noktalarıdır:
\[
\text{Mod} = 1.0
\]

#### Medyan:
Medyan, toplam frekansın yarısına denk gelen kümülatif frekanstaki sınıfta bulunur. Yırı frekans:
\[
\frac{500}{2} = 250
\]
250, \( 0-2 \) sınıfının kümülatif frekansı içindedir. Bu sınıfın orta noktaları medyandır:
\[
\text{Medyan} = 1.0
\]

### Adım 5: Histogram
Sınıf aralıklarına göre frekansların görselleştirilmesi histogram ile yapılmıştır.

### Özet:
- Sınıf Orta Noktaları: 1.0, 3.0, 5.0, 7.0, 9.0
- Göreli Frekanslar: 0.42, 0.38, 0.10, 0.06, 0.04
- Kümülatif Frekanslar: 210, 400, 450, 480, 500
- Aritmetik Ortalama: 2.84
- Mod: 1.0
- Medyan: 1.0

###Soru2

### Veriler:
- \( P(A) = 0.10 \)
- \( P(B) = 0.12 \)
- \( P(C) = 0.21 \)
- \( P(A \cap C) = 0.05 \)
- \( P(B \cap C) = 0.03 \)

### Adım 1: Birleşim Olasılığı Formülü
Birleşim olasılığı genel formülü şu şekildedir:
\[
P(X \cup Y) = P(X) + P(Y) - P(X \cap Y)
\]

### **1. \( P(A \cup C) \) Hesaplama**
Formülü uygulayalım:
\[
P(A \cup C) = P(A) + P(C) - P(A \cap C)
\]

Verileri yerine koyalım:
\[
P(A \cup C) = 0.10 + 0.21 - 0.05 = 0.26
\]

**Sonuç:**
\[
P(A \cup C) = 0.26
\]

---

### **2. \( P(B \cup C) \) Hesaplama**
Formülü uygulayalım:
\[
P(B \cup C) = P(B) + P(C) - P(B \cap C)
\]

Verileri yerine koyalım:
\[
P(B \cup C) = 0.12 + 0.21 - 0.03 = 0.30
\]

**Sonuç:**
\[
P(B \cup C) = 0.30
\]

---

### **3. \( P(A \cup B) \) Hesaplama (A ve B Birbirini Dışlayan Olaylar)**
Birbirini dışlayan olaylar için kesişim olasılığı sıfırdır, yani:
\[
P(A \cap B) = 0
\]

Bu durumda birleşim olasılığı şu şekilde hesaplanır:
\[
P(A \cup B) = P(A) + P(B)
\]

Verileri yerine koyalım:
\[
P(A \cup B) = 0.10 + 0.12 = 0.22
\]

**Sonuç:**
\[
P(A \cup B) = 0.22
\]

---

### Özet Sonuçlar:
1. \( P(A \cup C) = 0.26 \)
2. \( P(B \cup C) = 0.30 \)
3. \( P(A \cup B) = 0.22 \) (A ve B birbirini dışlayan olaylardır)

###Soru3

