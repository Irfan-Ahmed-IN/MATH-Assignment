🔰 Topics Covered

This project implements the following matrix operations:

Transpose of a Rectangular Matrix (Using another matrix)

Transpose of a Square Matrix (In-place transpose)

Check whether a Matrix is Symmetric

Check whether a Matrix is Skew-Symmetric

Matrix Addition

Matrix Subtraction

Matrix Multiplication

🧪 Task 1A: Transpose of a Rectangular Matrix
✅ What it does:

Calculates the transpose of a rectangular matrix by storing the result in another matrix.

🔎 Logic:

If the original matrix is A[r][c], then its transpose is T[c][r].

Each element is swapped as:

T[j][i] = A[i][j]

🧠 Output:

The program displays the transposed matrix after processing all elements.

🧪 Task 1B: In-Place Transpose of a Square Matrix
✅ What it does:

Transposes a square matrix without using another matrix.

🔎 Logic:

Only elements above the main diagonal are swapped with the corresponding symmetric elements.

swap(A[i][j], A[j][i])


Condition:

j > i

🧪 Task 2: Check Symmetric Matrix
✅ What it does:

Checks whether a matrix is symmetric.

📌 Definition:

A square matrix is symmetric if:

A[i][j] == A[j][i]

🔎 Logic:

First checks if the matrix is square.

Then compares each element with its transpose.

🧪 Task 3: Check Skew-Symmetric Matrix
✅ What it does:

Checks whether a matrix is skew-symmetric.

📌 Definition:

A skew-symmetric matrix satisfies:

A[i][j] = -A[j][i]


and

Diagonal elements must be 0

🔎 Logic:

Check if matrix is square.

Check all diagonal elements = 0.

Check opposite elements are negative of each other.

🧮 Matrix Arithmetic Operations

These operations are implemented using separate functions.

➕ Matrix Addition
✅ Requirement:

Both matrices must have the same dimensions.

🧠 Formula:
result[i][j] = A[i][j] + B[i][j]

➖ Matrix Subtraction
✅ Requirement:

Both matrices must have the same dimensions.

🧠 Formula:
result[i][j] = A[i][j] - B[i][j]

✖ Matrix Multiplication
✅ Requirement:

Number of columns of Matrix A must equal number of rows of Matrix B.

🧠 Formula:
result[i][j] = Σ (A[i][k] × B[k][j])

🛠 How to Run the Code
✅ Requirements:

C++ Compiler (e.g. g++)

C++17 or above

▶ Compile:
g++ matrix.cpp -o matrix

▶ Run:
./matrix

📥 Input / 📤 Output

User is prompted to:

Enter matrix row and column sizes

Enter matrix values

Program prints results based on selected operation

Example:

Input:

2 2
1 2
3 4


Output (Transpose):

1 3
2 4
