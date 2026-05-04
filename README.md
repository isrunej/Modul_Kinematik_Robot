# Modul Kinematik Robot — Teknik Robotika Agroindustri

**Studi Kasus:** Robot Pemetik Stroberi di Greenhouse  
**Level:** Sarjana Teknik Elektro  
**Prasyarat Python:** numpy, matplotlib — tidak perlu install tambahan

---

## Buka Langsung di Google Colab (Tanpa Install Apapun!)

| Modul | Topik | Buka di Colab |
|-------|-------|---------------|
| Modul 1 | Forward Kinematics 2-DOF | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/isrunej/Modul_Kinematik_Robot/blob/main/Modul_01_FK_2DOF.ipynb) |
| Modul 2 | Inverse Kinematics 2-DOF | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/isrunej/Modul_Kinematik_Robot/blob/main/Modul_02_IK_2DOF.ipynb) |
| Modul 3 | FK & IK 3-DOF Spatial | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/isrunej/Modul_Kinematik_Robot/blob/main/Modul_03_FK_IK_3DOF.ipynb) |
| Tugas 1 | Latihan FK (dikumpulkan) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/isrunej/Modul_Kinematik_Robot/blob/main/tugas/Tugas_01_FK_2DOF.ipynb) |
| Tugas 2 | Proyek Robot Greenhouse | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/isrunej/Modul_Kinematik_Robot/blob/main/tugas/Tugas_02_IK_Proyek.ipynb) |

---

## 🎮 Simulasi Interaktif (Langsung di Browser)

Tidak perlu install apapun — klik langsung dan coba gerakkan robot!

| Simulasi | Keterangan | Link |
|----------|------------|------|
| Simulasi 2D | FK Robot 2-DOF Planar berbasis JavaScript | [▶ Buka Simulasi 2D](https://isrunej.github.io/Modul_Kinematik_Robot/FK_DH_2DOF_Contoh1.html) |
| Simulasi 3D | FK Robot 6-DOF Spatial interaktif | [▶ Buka Simulasi 3D](https://isrunej.github.io/Modul_Kinematik_Robot/FK_DH_6DOF_Contoh3_v2.html) |

---

## Cara Mengerjakan Tugas (untuk Mahasiswa)

1. Klik tombol **Open in Colab** di tabel atas
2. Klik **File → Save a copy in Drive** agar bisa diedit dan disimpan
3. Kerjakan semua sel
4. Kumpulkan link Google Colab Anda ke dosen

---

## Urutan Belajar

```
Modul 1 (FK 2D) → Modul 2 (IK 2D) → Modul 3 (FK & IK 3D)
                                              ↓
                                    Tugas 1 → Tugas 2 (Proyek)
```

| Urutan | Topik | Prasyarat |
|--------|-------|-----------|
| 1 | FK 2-DOF: posisi end-effector, workspace, matriks homogen 2D | — |
| 2 | IK 2-DOF: dua solusi (elbow-up/down), pemilihan konfigurasi | Modul 1 |
| 3 | FK & IK 3-DOF: parameter DH, matriks 4×4, visualisasi 3D | Modul 1 & 2 |
| 4 | Tugas 1: latihan FK terstruktur | Modul 1 |
| 5 | Tugas 2: proyek greenhouse lengkap | Semua modul |

---

## Library yang Digunakan

- `numpy` — operasi matriks dan trigonometri
- `matplotlib` — visualisasi 2D dan 3D
- Tidak perlu `roboticstoolbox` (opsional untuk eksplorasi lanjutan)
