ISO/IEC 15939 Measurement Process Simulator

Student Information
Name: Muhammed Fatih Karagöz
Student ID: 202328035
Course: Software Project II
Department: Software Engineering
University: Çankaya University

GitHub Repository:
https://github.com/muhammedfatihkaragoz/ISO15939-Measurement-Process-Simulator

--------------------------------------------------

Project Overview
This project is a Java Swing desktop application developed to simulate the ISO/IEC 15939 Software Measurement Process.

The system follows five main steps:
Profile, Define, Plan, Collect, Analyse

The application allows users to define scenarios, evaluate metrics, calculate scores, and perform gap analysis.

--------------------------------------------------

Implemented Features
Wizard navigation using CardLayout
Step indicator for progress tracking
Automatic metric score calculation (1-5 scale)
Weighted dimension and scenario scoring
Gap analysis for weakest dimension
Back and Next navigation
Custom scenario support (bonus)
Use of HashMap and ArrayList

--------------------------------------------------

Technologies Used
Java SE 17+
Java Swing
Java Collections Framework
Object-Oriented Programming
No external libraries used

--------------------------------------------------

Project Structure
src/
  main/
  gui/
  model/
  service/

--------------------------------------------------

Compilation (from src directory)

Windows:
dir /s /B *.java > sources.txt
javac -d . @sources.txt

Linux / Mac:
javac -d . $(find . -name "*.java")

--------------------------------------------------

Run (from src directory)
java main.Main

The project does not require any IDE and can be compiled and run using only javac and java.

--------------------------------------------------

Screenshots

Profile Step: https://raw.githubusercontent.com/muhammedfatihkaragoz/ISO15939-Measurement-Process-Simulator/a228224003080baba697beb288fb4ef699479d63/screenshots/profile-step.png

Define Step: https://raw.githubusercontent.com/muhammedfatihkaragoz/ISO15939-Measurement-Process-Simulator/a228224003080baba697beb288fb4ef699479d63/screenshots/define-step.png

Plan Step: https://raw.githubusercontent.com/muhammedfatihkaragoz/ISO15939-Measurement-Process-Simulator/a228224003080baba697beb288fb4ef699479d63/screenshots/plan-step.png

Collect Step: https://raw.githubusercontent.com/muhammedfatihkaragoz/ISO15939-Measurement-Process-Simulator/a228224003080baba697beb288fb4ef699479d63/screenshots/collect-step.png

Analyse Step: https://raw.githubusercontent.com/muhammedfatihkaragoz/ISO15939-Measurement-Process-Simulator/a228224003080baba697beb288fb4ef699479d63/screenshots/analyse-step.png
