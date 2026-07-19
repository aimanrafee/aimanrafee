🌐 **Bahasa:** [English](README.md) | [Bahasa Melayu](README.ms.md) | [中文](README.zh.md)

---

# UCAS

## Piawaian Seni Bina Boleh Gubah Sejagat (Universal Composable Architecture Standard)

> **Asas terbuka, neutral vendor, dan neutral pelaksanaan untuk mereka bentuk sistem, spesifikasi, seni bina, protokol, dan pelaksanaan yang boleh saling beroperasi dalam jangka masa panjang.**

> **Status:** Penyelidikan & Pembangunan (Pra-Yayasan)
> **Status Repositori:** Penyelidikan Aktif
> **Lesen:** Apache-2.0 (Tertakluk kepada semakan pada masa hadapan)
> **Kestabilan:** Eksperimen

---

# Visi

Untuk membina asas sejagat yang berkekalan bagi mereka bentuk sistem yang kekal mudah difahami, boleh digubah, boleh berkembang, dan boleh saling beroperasi merentasi generasi teknologi.

UCAS bukan satu rangka kerja (framework).

UCAS bukan satu bahasa pengaturcaraan.

UCAS bukan satu sistem pengendalian.

UCAS bukan satu platform ejen AI.

UCAS ialah **piawaian asas** yang bertujuan untuk menerangkan **bagaimana sistem harus dispesifikasikan**, bukannya menetapkan **bagaimana ia mesti dilaksanakan**.

---

# Misi

Membangunkan spesifikasi terbuka yang membolehkan individu, organisasi, penyelidik, kerajaan, perniagaan, dan teknologi masa hadapan membina sistem di atas asas seni bina yang dikongsi bersama, tanpa bergantung kepada mana-mana:

* Bahasa pengaturcaraan
* Masa jalan (runtime)
* Rangka kerja
* Model AI
* Sistem pengendalian
* Vendor
* Penyedia awan
* Metodologi pembangunan

---

# Status Semasa

UCAS kini berada dalam **Fasa Penyelidikan Asas**.

Pada peringkat ini, projek ini memberi tumpuan kepada penemuan, pengesahan, dan pendokumenan set prinsip minimum yang diperlukan bagi sesuatu piawaian seni bina yang berkekalan.

Tiada apa-apa yang dianggap kekal sehingga ia telah diselidik, dicabar, disemak, dan dijustifikasikan.

---

# Falsafah Teras

UCAS dibina berasaskan beberapa kepercayaan panduan:

* Asas harus berubah secara perlahan.
* Pelaksanaan harus berkembang dengan pantas.
* Seni bina harus mendahului pelaksanaan.
* Spesifikasi harus lebih berkekalan daripada pelaksanaan.
* Prinsip harus lebih berkekalan daripada teknologi.
* Pengetahuan harus boleh dikesan asal-usulnya (traceable).
* Keputusan harus dijustifikasikan.
* Piawaian harus kekal neutral vendor.
* Evolusi tidak sepatutnya menjejaskan integriti asas.

---

# Objektif Reka Bentuk

UCAS bertujuan untuk menjadi:

* Neutral Vendor
* Neutral Teknologi
* Neutral Masa Jalan (Runtime)
* Neutral Platform
* Neutral Bahasa
* Pilihan Awan (Cloud Optional)
* Mesra Luar Talian (Offline)
* Boleh Dibaca Manusia
* Boleh Dibaca Mesin
* Boleh Dibaca AI
* Boleh Diperluas (Extensible)
* Boleh Digubah (Composable)
* Boleh Diselenggara Jangka Panjang

---

# Matlamat Penyelidikan Jangka Panjang

UCAS meneroka bagaimana sesuatu spesifikasi boleh kekal relevan selama berdekad-dekad—atau lebih lama—dengan mengasaskan dirinya kepada prinsip yang berkekalan berbanding teknologi yang bersifat sementara.

Bidang penyelidikan termasuk:

* Seni bina asas
* Kejuruteraan spesifikasi
* Metodologi sistem
* Kontrak antara muka (interface)
* Pemodelan kebergantungan
* Kebolehselenggaraan jangka panjang
* Tadbir urus evolusi
* Kesalinghubungan (interoperability)
* Kejuruteraan berbantukan AI
* Metodologi pematuhan (conformance)

---

# Struktur Repositori

```text
UCAS/
│
├── foundation/
│
├── governance/
│
├── architecture/
│
├── specification/
│
├── profiles/
│
├── research/
│
├── adr/
│
├── templates/
│
├── examples/
│
├── tooling/
│
├── references/
│
├── assets/
│
├── quality/
│
├── documentation/
│
├── lifecycle/
│
├── risk/
```

Setiap direktori mempunyai tujuan yang berbeza dan dijangka akan berkembang secara berasingan sambil kekal boleh dikesan kepada prinsip asas projek.

---

# Falsafah Pembangunan

UCAS mengikuti pendekatan "Asas Dahulu" (Foundation First).

Susunan perkembangan yang dijangka adalah:

```text
Visi
    ↓
Penyelidikan
    ↓
Prinsip Asas
    ↓
Tadbir Urus
    ↓
Spesifikasi
    ↓
Profil
    ↓
Pelaksanaan Rujukan
    ↓
Alatan (Tooling)
    ↓
Ekosistem
```

Pelaksanaan tidak sekali-kali mendahului seni bina.

Seni bina tidak sekali-kali mendahului prinsip.

Prinsip tidak sekali-kali mendahului penyelidikan.

---

# Prinsip Projek

Setiap cadangan seharusnya berusaha untuk menjadi:

* Perlu (Necessary)
* Bebas (Independent)
* Boleh Disahkan (Verifiable)
* Boleh Digubah (Composable)
* Boleh Diselenggara (Maintainable)
* Boleh Berkembang (Evolvable)
* Neutral teknologi
* Dispesifikasikan dengan jelas
* Boleh Disemak (Reviewable)
* Boleh Dikesan (Traceable)

---

# Falsafah Sumbangan

UCAS mengutamakan bukti berbanding pendapat.

Penyumbang digalakkan untuk:

* mempersoalkan andaian,
* memberikan kes bertentangan (counterexamples),
* mendokumenkan pertukaran (trade-offs),
* menjustifikasikan keputusan seni bina,
* memperbaiki kejelasan,
* mengekalkan konsistensi jangka panjang.

Perbincangan penyelidikan digalakkan.

Dakwaan tanpa sokongan tidak digalakkan.

---

# Pelan Tindakan Projek (Roadmap)

Fokus semasa:

* Asas
* Prinsip Teras
* Penyelidikan Aksiom
* Model Tadbir Urus
* Metodologi Spesifikasi

Fasa akan datang:

* Spesifikasi Rujukan
* Profil
* Ujian Pematuhan (Conformance Testing)
* SDK
* Alatan
* Pensijilan
* Pelaksanaan Rujukan

---

# Apa yang UCAS Bukan

UCAS **tidak** bertujuan untuk menjadi:

* satu lagi bahasa pengaturcaraan
* satu lagi rangka kerja web
* satu lagi rangka kerja AI
* satu lagi sistem pengendalian
* satu lagi platform DevOps
* satu lagi platform awan

Sebaliknya, UCAS berusaha untuk mentakrifkan prinsip yang kekal berguna tanpa mengira teknologi mana yang akan menjadi dominan.

---

# Tadbir Urus

Tadbir urus kini sedang diselidik secara aktif.

Projek ini berhasrat untuk berkembang ke arah proses membuat keputusan yang terbuka, telus, dan berasaskan bukti, di mana perubahan seni bina dijustifikasikan melalui pemikiran yang didokumenkan dan semakan, bukannya melalui autoriti semata-mata.

---

# Penafian

UCAS ialah satu inisiatif penyelidikan bebas.

Ia **tidak** bergabung dengan mana-mana kerajaan, badan piawaian, institusi akademik, syarikat, atau mana-mana organisasi penyeragaman antarabangsa yang sedia ada.

Tiada apa-apa dalam repositori ini yang sepatutnya ditafsirkan sebagai piawaian rasmi melainkan disahkan secara jelas melalui proses piawaian yang sesuai.

---

# Penghargaan

UCAS mendapat inspirasi daripada beberapa dekad kerja dalam kejuruteraan sistem, seni bina perisian, piawaian terbuka, reka bentuk protokol, dan pembangunan sumber terbuka secara kolaboratif.

Projek ini bertujuan untuk belajar daripada amalan kejuruteraan yang telah mantap sambil kekal bebas daripada mana-mana teknologi atau ekosistem tunggal.

---

# Peranan Penyelenggara

Peranan projek semasa:

**Penyelidik Sistem Asas UCAS (UCAS Foundational Systems Researcher)**

Tanggungjawab termasuk:

* Penyelidikan asas
* Penerbitan prinsip (principle derivation)
* Konsistensi seni bina
* Strategi spesifikasi jangka panjang
* Pembangunan metodologi
* Penyelarasan penyelidikan

Peranan ini mewakili fungsi projek, bukan jawatan atau pangkat.

---

# Menyumbang

Sumbangan adalah dialu-alukan.

Sebelum mencadangkan perubahan besar, sila:

1. Baca dokumentasi sedia ada.
2. Semak keputusan seni bina yang terdahulu.
3. Berikan penjelasan dan bukti.
4. Terangkan pertukaran (trade-offs).
5. Jelaskan implikasi jangka panjang.

UCAS mengutamakan perbincangan yang bijaksana berbanding perubahan yang tergesa-gesa.

---

# Moto

> **Bina asas yang kekal lebih lama daripada pelaksanaannya.**
