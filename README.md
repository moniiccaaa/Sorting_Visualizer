# Java Sorting Visualizer

A desktop GUI-based application for visualizing classic sorting algorithms built using Java Swing. The app allows users to see how different algorithms work in real time with customizable settings like speed, size, and step-wise data.

## 🎯 Features

- **Sorting Algorithms**:
  - Bubble Sort (normal & fast)
  - Selection Sort (normal & fast)
  - Insertion Sort (normal & fast)
  - Merge Sort
  - Quick Sort (normal & fast)

- **Interactive Controls**:
  - Select algorithm from dropdown
  - Control sorting **speed** (1ms to 1000ms)
  - Adjust **array size** (5 to 500 elements)
  - Toggle **stepped (incremental)** or **random values**

- **Real-Time Visualization**:
  - Animated bars representing the array
  - Color-coded comparisons: 
    - Green: working index
    - Red: comparing
    - Yellow: currently being read
    - Blue: default

- **Responsive GUI**:
  - Java Swing-based layout
  - Dynamically resizes based on window dimensions

## 📦 Tech Stack

- **Language**: Java
- **UI Toolkit**: Java Swing
- **Architecture**: OOP + Multithreading (each sort runs in its own thread)

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/moniiccaaa/Sorting_Visualizer.git
   cd Sorting_Visualizer

2. Compile and run:
   ```bash
    javac Visualizer/SortingVisualizer.java
    java Visualizer.SortingVisualizer
   
    Make sure all .java files in Visualizer/ and Visualizer/Sorts/ are compiled.

## 📂 Project Structure
  ```graphql
    Visualizer/
    ├── SortingVisualizer.java      # Main controller class
    ├── VisualizerFrame.java        # GUI frame and components
    └── Sorts/
        ├── BubbleSort.java
        ├── SelectionSort.java
        ├── InsertionSort.java
        ├── MergeSort.java
        └── QuickSort.java
