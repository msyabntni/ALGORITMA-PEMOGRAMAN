# Masya Bantani_Algoritma_Pemograman
Tugas Algoritma Pemograman

## Menentukan Jenis Sudut

## A. Deskripsi Masalah

Dalam pembelajaran matematika, khususnya materi geometri, sudut dapat dibedakan berdasarkan besar ukurannya. Salah satunya adalah sudut lancip dan bukan sudut lancip.

Sudut yang memiliki besar kurang dari 90° termasuk sudut lancip. Sedangkan sudut yang memiliki besar 90° atau lebih bukan merupakan sudut lancip.

Program ini menerapkan logika matematika untuk menentukan jenis sudut berdasarkan kondisi yang diberikan. Program akan menerima besar sudut sebagai input, kemudian mengevaluasi apakah besar sudut tersebut kurang dari 90° atau tidak.

Berdasarkan hasil evaluasi tersebut, program akan menentukan apakah sudut tersebut merupakan sudut lancip atau bukan sudut lancip.

---

## B. Identifikasi Input-Proses-Output



| **Komponen** | **Keterangan** |
|---|---|
| **Input** | • Besar sudut dalam satuan derajat (°). |
| **Proses** | Program membandingkan besar sudut dengan **90°** menggunakan kondisi logika:<br><br>• Jika sudut **kurang dari 90°**, maka sudut merupakan **sudut lancip**.<br>• Jika sudut **90° atau lebih**, maka sudut merupakan **bukan sudut lancip**. |
| **Output** | Jenis sudut berdasarkan besar sudut yang dimasukkan, yaitu **sudut lancip** atau **bukan sudut lancip**. |
---

## C. Pseudocode


```text
INPUT sudut

IF sudut < 90 THEN
    OUTPUT "Sudut merupakan sudut lancip"
ELSE
    OUTPUT "Sudut bukan merupakan sudut lancip"
END IF


## D.Flowchart

```mermaid
flowchart TD
    A([START]) --> B[/INPUT sudut/]
    B --> C{Apakah sudut < 90°?}

    C -->|Ya| D[/OUTPUT: Sudut lancip/]
    C -->|Tidak| E[/OUTPUT: Bukan sudut lancip/]

    D --> F([END])
    E --> F

##E. Test Case

| Test Case | Input Sudut | Kondisi | Hasil yang Diharapkan |
|---|---|---|---|
| 1 | 45° | Sudut < 90° | Sudut lancip |
| 2 | 120° | Sudut ≥ 90° | Bukan sudut lancip |

## F. Implementasi Python

Implementasi program dibuat menggunakan bahasa pemrograman **Python** dan dapat dijalankan melalui **Visual Studio Code**.

Source code disimpan dalam file `main.py`.

```python
# Program Menentukan Jenis Sudut

sudut = float(input("Masukkan besar sudut: "))

if sudut < 90:
    print("Sudut lancip")
else:
    print("Bukan sudut lancip")
```

## G. Hasil Pengujian

Program telah diuji menggunakan dua test case untuk memastikan program dapat menentukan jenis sudut dengan benar.

###  Test Case 1

**Input:**

```text
Masukkan besar sudut: 45
```

**Output:**

```text
Sudut lancip
```

**Keterangan:**  
Karena besar sudut **45° < 90°**, maka program menampilkan **"Sudut lancip"**.

---

###  Test Case 2

**Input:**

```text
Masukkan besar sudut: 120
```

**Output:**

```text
Bukan sudut lancip
```

**Keterangan:**  
Karena besar sudut **120° ≥ 90°**, maka program menampilkan **"Bukan sudut lancip"**.

---
## H. Tabel Pengujian

| Test Case | Input Sudut | Kondisi | Output yang Diharapkan | Hasil Pengujian |
|---|---|---|---|---|
| 1 | 45° | Sudut < 90° | Sudut lancip | Berhasil |
| 2 | 120° | Sudut ≥ 90° | Bukan sudut lancip | Berhasil |

<img width="960" height="504" alt="Screenshot 2026-09-02 213148" src="https://github.com/user-attachments/assets/e5279c8e-46be-47bb-bb05-6c7bf6cf70d8" />


## ✅ Kesimpulan Pengujian

Berdasarkan dua test case yang telah dilakukan, program berhasil menentukan jenis sudut sesuai dengan kondisi yang diberikan.

| Test Case | Input | Hasil |
|---|---:|---|
| 1 | 45° | Sudut lancip |
| 2 | 120° | Bukan sudut lancip |

Program menghasilkan output yang sesuai dengan hasil yang diharapkan.



