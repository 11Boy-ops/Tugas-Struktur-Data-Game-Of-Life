
---

# 📄 README.md

```markdown
# Game of Life dengan ADT Array

## 📋 Deskripsi Proyek

Proyek ini mengimplementasikan dua tugas utama dalam pemrograman dasar:

### Tugas 1: Abstract Data Type (ADT) Array
Implementasi ADT Array sebagai struktur data fundamental dengan operasi-operasi dasar:
- Inisialisasi array dengan ukuran tertentu
- Insert nilai pada indeks tertentu
- Access nilai berdasarkan indeks
- Update nilai pada indeks tertentu
- Menghitung jumlah elemen terisi
- Reset seluruh elemen

Analogi: ADT Array dapat dianalogikan sebagai rak penyimpanan dengan slot-slot bernomor yang masing-masing dapat menyimpan sebuah nilai.

### Tugas 2: Game of Life (Cellular Automata)
Implementasi Conway's Game of Life sebagai studi kasus penggunaan array 2 dimensi dengan aturan:

Keadaan Sel:
- Hidup (1) - Sel aktif/berisi organisme
- Mati (0) - Sel tidak aktif/kosong

Aturan Transisi:
1. Underpopulation: Sel hidup dengan < 2 tetangga hidup → mati
2. Survival: Sel hidup dengan 2-3 tetangga hidup → tetap hidup
3. Overpopulation: Sel hidup dengan > 3 tetangga hidup → mati
4. Reproduction: Sel mati dengan tepat 3 tetangga hidup → hidup

---

## 🚀 Instalasi dan Eksekusi

### Prasyarat
- Python 3.x (tidak memerlukan library tambahan)

### Cara Menjalankan

Clone repository:
```bash
git clone https://github.com/username/game-of-life-adt.git
cd game-of-life-adt