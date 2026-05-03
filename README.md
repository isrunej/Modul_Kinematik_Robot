# Modul Kinematik Robot — Teknik Robotika Agroindustri

**Studi Kasus:** Robot Pemetik Stroberi di Greenhouse  
**Level:** Sarjana Teknik Elektro  
**Prasyarat Python:** numpy, matplotlib (standar — tidak perlu install tambahan)

---

## Struktur Modul

```
Modul_Kinematik_Robot/
│
├── Modul_01_FK_2DOF.ipynb       ← Mulai dari sini
├── Modul_02_IK_2DOF.ipynb
├── Modul_03_FK_IK_3DOF.ipynb
│
└── tugas/
    ├── Tugas_01_FK_2DOF.ipynb   ← Tugas individu (FK)
    └── Tugas_02_IK_Proyek.ipynb ← Tugas proyek (IK + jalur)
```

## Urutan Belajar

| Urutan | File | Topik | Prasyarat |
|--------|------|-------|-----------|
| 1 | Modul_01 | FK 2-DOF, workspace, transformasi homogen 2D | - |
| 2 | Modul_02 | IK 2-DOF, dua solusi, pemilihan konfigurasi | Modul 1 |
| 3 | Modul_03 | FK & IK 3-DOF, matriks DH, visualisasi 3D | Modul 1 & 2 |
| 4 | Tugas_01 | Latihan terstruktur FK | Modul 1 |
| 5 | Tugas_02 | Proyek greenhouse lengkap | Semua modul |

## Cara Menjalankan

```bash
# Pastikan jupyter terinstal
pip install jupyter numpy matplotlib

# Buka Jupyter
jupyter notebook
```

## Library yang Digunakan

- `numpy` — operasi matriks dan trigonometri
- `matplotlib` — visualisasi 2D dan 3D
- Tidak perlu `roboticstoolbox` (opsional untuk eksplorasi lanjutan)
