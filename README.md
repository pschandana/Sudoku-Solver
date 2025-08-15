# 🧩 Sudoku Solver (Java Swing)

A **Java-based Sudoku solver** with a graphical user interface built using **Swing**.  
This program allows you to:
- View a Sudoku puzzle in a 9×9 grid.
- Fill in missing numbers manually.
- Automatically solve the puzzle using a **backtracking algorithm**.
- See the solution directly on the board with colored 3×3 blocks.

---


## 🚀 Features
- **GUI Interface** built with Java Swing.
- **Backtracking Algorithm** to solve puzzles.
- **Editable cells** for custom input.
- **Color-coded 3×3 blocks** for better readability.
- Displays **number of backtracking steps** in the console.

---

## 🛠️ Technologies Used
- **Java** (JDK 8+)
- **Swing** (for GUI)
- **AWT** (for layout & event handling)




---

## 📖 How It Works
1. **Initial Puzzle** is pre-filled in a 2D array.
2. **GUI** is created using a 9×9 grid of `JTextField` components.
3. **Solve Button** triggers:
   - Reading input values from the grid.
   - Running the `solveSudoku()` method (recursive backtracking).
4. **Solution** is displayed in the GUI.

---

## ▶️ How to Run


### **1. Clone this repository**

     git clone https://github.com/pschandana/Sudoko_Solver.git
     cd Sudoko_Solver

### **2.Compile**

     javac ProjectSudoku.java
     
### **3. Run**

     java ProjectSudoku

### **Example Output**

     Number of Backtrackings: 142




