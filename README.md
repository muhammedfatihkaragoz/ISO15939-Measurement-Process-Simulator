# ISO/IEC 15939 Measurement Process Simulator

## Student Information

Name: Muhammed Fatih Karagöz
Student ID: 202328035
Course: Software Project II
Department: Software Engineering
University: Çankaya University

GitHub Repository:
https://github.com/muhammedfatihkaragoz/ISO15939-Measurement-Process-Simulator

---

## Project Overview

This project is a Java Swing desktop application developed to simulate the ISO/IEC 15939 Software Measurement Process.

The system follows five main steps:

1. Profile
2. Define
3. Plan
4. Collect
5. Analyse

The application allows users to define scenarios, evaluate metrics, calculate scores, and perform gap analysis.

---

## Implemented Features

* Wizard navigation using CardLayout
* Step indicator for progress tracking
* Automatic metric score calculation (1–5 scale)
* Weighted dimension and scenario scoring
* Gap analysis for weakest dimension
* Back and Next navigation
* Custom scenario support (bonus)
* Use of HashMap and ArrayList

---

## Technologies Used

* Java SE 17+
* Java Swing
* Java Collections Framework
* Object-Oriented Programming
* No external libraries used

---

## Project Structure

src/
├── main/
├── gui/
├── model/
└── service/

---

## Compilation

Compile the project from the src directory.

### Windows

```text
dir /s /B *.java > sources.txt
javac @sources.txt
```

### Linux / Mac

```text
javac -d . $(find . -name "*.java")
```

---

## Run

Run the project:

```text
java main.Main
```

The project does not require any IDE and can be compiled and run using only javac and java.

---

## Screenshots

### Profile Step
<img width="800" alt="Ekran görüntüsü 2026-04-23 214218" src="https://github.com/user-attachments/assets/efca238c-7a6d-484a-8329-9f8b9dd3f179" />

### Define Step
<img width="800" alt="Ekran görüntüsü 2026-04-23 214246" src="https://github.com/user-attachments/assets/401a475e-3aa3-424e-87cb-ab21f65f1698" />

### Plan Step
<img width="800" alt="Ekran görüntüsü 2026-04-23 214309" src="https://github.com/user-attachments/assets/12fc7a72-8103-447f-9b65-e6091c960c7a" />

### Collect Step
<img width="800" alt="Ekran görüntüsü 2026-04-23 214328" src="https://github.com/user-attachments/assets/8455f7ab-3495-4d22-9927-766e2bc27341" />

### Analyse Step
<img width="800" alt="Ekran görüntüsü 2026-04-23 214343" src="https://github.com/user-attachments/assets/31e8dc8a-2cf6-4a7f-bb09-b453935a8949" />
