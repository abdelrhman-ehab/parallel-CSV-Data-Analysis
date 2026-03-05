# Parallel CSV Data Analyzer

A Java-based project that analyzes large CSV datasets using **Parallel Programming** and **MultiThreading** techniques.
The system processes large files efficiently by distributing the workload across multiple threads.

## 📌 Project Overview

Processing large datasets using a single thread can be slow and inefficient.
This project demonstrates how **Parallel Processing** can significantly improve performance when working with large CSV files.

The application reads a CSV file containing sales data, processes it in parallel using a **Thread Pool**, and generates statistical insights such as total sales, average price, top-selling product, and sales per region.

## ⚙️ Technologies Used

* **Java**
* **MultiThreading**
* **Thread Pool (ExecutorService)**
* **BlockingQueue**
* **Producer–Consumer Pattern**
* **Concurrent Collections**
* **VS Code**

## 🏗️ System Architecture

CSV File
⬇
CSVReader (Producer Thread)
⬇
BlockingQueue
⬇
Worker Threads (Thread Pool)
⬇
Statistics Engine
⬇
Final Analysis Report

## 📊 Features

* Process large CSV files efficiently
* Parallel data processing using multiple threads
* Real-time progress tracking during analysis
* Statistical analysis including:

  * Total number of records
  * Total sales
  * Average price
  * Top-selling product
  * Sales per region
* Performance comparison between:

  * **Single Thread Processing**
  * **MultiThread Processing**

## 📂 Project Structure

ParallelCSVAnalyzer
│
├── src
│   ├── MainApp.java
│   ├── Worker.java
│   ├── CSVReader.java
│   ├── Statistics.java
│   ├── CSVGenerator.java
│   └── SingleThreadAnalyzer.java
│
└── data
    └── sales.csv

## 🚀 How to Run

1. Clone the repository
2. Open the project in **VS Code**
3. Generate the dataset (optional):

Run `CSVGenerator.java`

4. Run the main application:

Run `MainApp.java`

The program will execute both:

* Single-thread analysis
* Multi-thread analysis

and display the performance comparison.

## 📈 Example Output

Single Thread Execution Time: 3200 ms
MultiThread Execution Time: 900 ms

This demonstrates how **Parallel Processing significantly improves performance** when handling large datasets.

## 🎓 Academic Purpose

This project was developed as part of a **Parallel Programming course** to demonstrate practical implementation of multithreading and parallel data processing in Java.

## 👨‍💻 Author

Developed by a Computer Science student as a demonstration of **parallel data processing techniques in Java**.
