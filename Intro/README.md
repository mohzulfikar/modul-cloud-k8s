# Intro K8s

## Kubernetes & Container Orchestration

Kubernetes mengoordinasikan klaster komputer ketersediaan tinggi (_highly available_) yang saling terhubung sebagai unit tunggal. Abstraksi pada Kubernetes mengizinkan kamu untuk men-_deploy_ aplikasi terkemas (_containerized_) ke sebuah klaster tanpa perlu membalutnya secara spesifik pada setiap mesin. Untuk menggunakan model baru _deployment_ ini, aplikasi perlu dikemas dengan cara memisahkan mereka dari hos individu: mereka perlu dikemas. Aplikasi terkemas lebih fleksibel dan tersedia dibanding model _deployment_ lama, dimana aplikasi dipasang secara langsung didalam mesin spesifik sebagai paket yang sangat terintegrasi dengan hos. Kubernetes mengotomasisasikan distribusi dan penjadwalan kontainer aplikasi sebuah klaster secara menyeluruh dengan cara yang lebih efisien. Kubernetes merupakan platform _open-source_ dan siap produksi.

Klaster Kubernetes terdiri dari 2 tipe sumber daya:

- **Master** mengoordinasikan klaster
- **Node** adalah pekerja (_worker_) yang menjalankan aplikasi

### Diagram Klaster

![Diagram](img/diagram.png)

Pada gambar diatas, terdapat beberapa bagian yang dapat diperhatikan.
